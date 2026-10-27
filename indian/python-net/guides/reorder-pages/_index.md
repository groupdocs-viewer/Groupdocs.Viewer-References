---
title: "पृष्ठों को पुनः क्रमित करें"
linkTitle: "Reorder pages"
second_title: "GroupDocs.Viewer Python के लिए .NET के माध्यम से API संदर्भ"
description: "GroupDocs.Viewer for Python via .NET के साथ रेंडरिंग के दौरान PDF पृष्ठों को पुनः क्रमित करें। आउटपुट पेज क्रम को नियंत्रित करें।"
type: docs
url: /hi/python-net/guides/reorder-pages/
is_root: false
weight: 100
---


GroupDocs.Viewer स्रोत दस्तावेज़ में पृष्ठ क्रम को बनाए रखता है। इसके बजाय, आप आउटपुट PDF दस्तावेज़ में पृष्ठों को पुनः क्रमित कर सकते हैं।

पृष्ठों को पुन: क्रमबद्ध करने के लिए, इन चरणों का पालन करें:

1. [Viewer](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer/viewer) ऑब्जेक्ट को इंस्टैंसिएट करें।
2. [PdfViewOptions](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer.options/pdfviewoptions) ऑब्जेक्ट बनाएं।
3. [Viewer](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer/viewer) ऑब्जेक्ट की [view](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer/viewer/#methods) मेथड को कॉल करें। अंतिम पैरामीटर में नया पृष्ठ क्रम निर्दिष्ट करें।

निम्नलिखित कोड स्निपेट दिखाता है कि पृष्ठों को कैसे पुन: क्रमबद्ध किया जाए:

{{< tabs "example1">}}
{{< tab "Python">}}
```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions

def reorder_pages():
    # दस्तावेज़ लोड करें
    with Viewer("sample.docx") as viewer:
        # व्यू विकल्प बनाएं।
        viewOptions = PdfViewOptions("reorder_pages/reordered_pages.pdf")

        # पृष्ठ संख्याओं को उस क्रम में पास करें जिसमें आप उन्हें रेंडर करना चाहते हैं।
        viewer.view(viewOptions, [2, 1])

if __name__ == "__main__":
    reorder_pages()
```
{{< /tab >}}
{{< tab "sample.docx" >}}

`sample.docx` इस उदाहरण में उपयोग की गई सैंपल फ़ाइल है। इसे डाउनलोड करने के लिए [here](https://docs.groupdocs.com/viewer/python-net/_sample_files/developer-guide/rendering-documents/rendering-to-pdf/reorder-pages/sample.docx) पर क्लिक करें।

{{< /tab >}}
{{< tab "reordered_pages.pdf" >}}
```text
Binary file (PDF, 176 KB)
```
[Download full output](https://docs.groupdocs.com/viewer/python-net/_output_files/developer-guide/rendering-documents/rendering-to-pdf/reorder-pages/reorder_pages/reordered_pages.pdf)
{{< /tab >}}
{{< /tabs >}}
