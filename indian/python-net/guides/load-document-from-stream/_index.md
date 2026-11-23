---
title: "स्ट्रीम से दस्तावेज़ लोड करें"
linkTitle: "Load from stream"
second_title: "GroupDocs.Viewer Python के लिए .NET के माध्यम से API संदर्भ"
description: "GroupDocs.Viewer for Python via .NET के साथ फ़ाइल-समरूप ऑब्जेक्ट — खुला फ़ाइल हैंडल, BytesIO, या कोई भी स्ट्रीम — से सीधे दस्तावेज़ लोड करें।"
type: docs
url: /hi/python-net/guides/load-document-from-stream/
is_root: false
weight: 60
---


आप एक दस्तावेज़ को स्ट्रीम से बिना डिस्क पर फ़ाइल के रूप में सहेजे लोड कर सकते हैं। आप इस सुविधा का उपयोग विभिन्न स्रोतों जैसे URL, FTP आदि से दस्तावेज़ लोड करने के लिए कर सकते हैं।

स्ट्रीम से दस्तावेज़ लोड करने के लिए, इन चरणों का पालन करें:

1. दस्तावेज़ स्ट्रीम प्राप्त करने के लिए एक मेथड लागू करें।
2. [Viewer](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer/viewer) क्लास कंस्ट्रक्टर को कॉल करें। पिछले चरण में लागू किए गए मेथड को निर्दिष्ट करें।

निम्नलिखित कोड स्निपेट दिखाता है कि स्ट्रीम से दस्तावेज़ कैसे लोड किया जाए:

{{< tabs "example1">}}
{{< tab "Python" >}}
```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

def load_document_from_stream():
    # दस्तावेज़ स्ट्रीम खोलें
    stream = open("sample.docx", "rb")

    # स्ट्रीम से दस्तावेज़ रेंडर करें।
    with Viewer(stream) as viewer:
        options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
        viewer.view(options)

if __name__ == "__main__":
    load_document_from_stream()
```
{{< /tab >}}
{{< tab "sample.docx" >}}

`sample.docx` इस उदाहरण में उपयोग की गई नमूना फ़ाइल है। इसे डाउनलोड करने के लिए [यहाँ](https://docs.groupdocs.com/viewer/python-net/_sample_files/developer-guide/loading-documents/load-document-from-stream/sample.docx) क्लिक करें।

{{< /tab >}}
{{< tab "load-document-from-stream-outputs.zip" >}}
```text
page_1.html (317 KB)
page_2.html (149 KB)
page_3.html (113 KB)
```
[Download full output](https://docs.groupdocs.com/viewer/python-net/_output_files/developer-guide/loading-documents/load-document-from-stream/load_document_from_stream/load-document-from-stream-outputs.zip)
{{< /tab >}}
{{< /tabs >}}

एक ठोस उदाहरण के लिए देखें [Load document from URL](), जिसमें दस्तावेज़ को `BytesIO` स्ट्रीम में डाउनलोड करके डिस्क पर कभी नहीं लिखे रेंडर किया जाता है।
