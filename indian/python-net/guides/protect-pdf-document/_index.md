---
title: "PDF दस्तावेज़ की सुरक्षा करें"
linkTitle: "Protect PDF document"
second_title: "GroupDocs.Viewer Python के लिए .NET के माध्यम से API संदर्भ"
description: "GroupDocs.Viewer का उपयोग करके दस्तावेज़ रेंडर करते समय पासवर्ड और अनुमतियों के साथ PDF आउटपुट को सुरक्षित करें।"
type: docs
url: /hi/python-net/guides/protect-pdf-document/
is_root: false
weight: 90
---


आप निम्नलिखित पैरामीटर सेट करके PDF दस्तावेज़ की सुरक्षा कर सकते हैं:

* permissions
* password to open document
* password to change permissions

PDF दस्तावेज़ की सुरक्षा करने के लिए, इन चरणों का पालन करें:

1. [Viewer](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer/viewer) क्लास का एक इंस्टेंस बनाएं। स्रोत दस्तावेज़ पथ को कंस्ट्रक्टर पैरामीटर के रूप में निर्दिष्ट करें।
2. [Security](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer.options/security) ऑब्जेक्ट को इंस्टैंशिएट करें।
3. दस्तावेज़ खोलने के लिए पासवर्ड निर्दिष्ट करने हेतु, [DocumentOpenPassword](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer.options/security/#properties) प्रॉपर्टी सेट करें।
4. प्रतिबंध बदलने के लिए पासवर्ड निर्दिष्ट करने हेतु, [PermissionsPassword](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer.options/security/#properties) प्रॉपर्टी सेट करें।
5. दस्तावेज़ की अनुमतियों को निर्दिष्ट करने हेतु, [Permissions](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer.options/permissions) प्रॉपर्टी सेट करें।
6. [PdfViewOptions](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer.options/pdfviewoptions) ऑब्जेक्ट को इंस्टैंशिएट करें। रेंडर किए गए दस्तावेज़ के लिए सहेजने के पथ फ़ॉर्मेट को निर्दिष्ट करें।
7. चरण 2‑5 में बनाए गए ऑब्जेक्ट के साथ [PdfViewOptions](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer.options/pdfviewoptions) ऑब्जेक्ट की [Security](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer.options/pdfviewoptions/#properties) प्रॉपर्टी को इनिशियलाइज़ करें।
8. [Viewer](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer/viewer) ऑब्जेक्ट की [view](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer/viewer/#methods) मेथड को कॉल करें। पैरामीटर के रूप में [PdfViewOptions](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer.options/pdfviewoptions) ऑब्जेक्ट को निर्दिष्ट करें।

निम्नलिखित कोड स्निपेट दिखाता है कि आउटपुट PDF दस्तावेज़ को कैसे सुरक्षित किया जाए:

{{< tabs "example1">}}
{{< tab "Python">}}
```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions, Security, Permissions

def protect_pdf_document():
    # दस्तावेज़ लोड करें
    with Viewer("sample.docx") as viewer:
        # सुरक्षा सेटिंग्स निर्दिष्ट करें।
        security = Security()
        security.document_open_password = "o123"
        security.permissions_password = "p123"
        security.permissions = Permissions.ALLOW_ALL & ~Permissions.DENY_PRINTING

        # एक PDF फ़ाइल बनाएं।
        pdf_options = PdfViewOptions("protect_pdf_document/protected_document.pdf")

        # सुरक्षा सेटिंग्स लागू करें
        pdf_options.security = security
        viewer.view(pdf_options)

if __name__ == "__main__":
    protect_pdf_document()
```
{{< /tab >}}
{{< tab "sample.docx" >}}

`sample.docx` इस उदाहरण में उपयोग की गई सैंपल फ़ाइल है। इसे डाउनलोड करने के लिए [यहाँ](https://docs.groupdocs.com/viewer/python-net/_sample_files/developer-guide/rendering-documents/rendering-to-pdf/protect-pdf-document/sample.docx) पर क्लिक करें।

{{< /tab >}}
{{< tab \"protected_document.pdf\" >}}
```text
Binary file (PDF, 238 KB)
```
[Download full output](https://docs.groupdocs.com/viewer/python-net/_output_files/developer-guide/rendering-documents/rendering-to-pdf/protect-pdf-document/protect_pdf_document/protected_document.pdf)
{{< /tab >}}
{{< /tabs >}}
