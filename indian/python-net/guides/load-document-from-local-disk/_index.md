---
title: "स्थानीय डिस्क से दस्तावेज़ लोड करें"
linkTitle: "Load from local disk"
second_title: "GroupDocs.Viewer Python के लिए .NET के माध्यम से API संदर्भ"
description: "GroupDocs.Viewer for Python via .NET के साथ फ़ाइल पथ का उपयोग करके अपने स्थानीय डिस्क से दस्तावेज़ लोड करें।"
type: docs
url: /hi/python-net/guides/load-document-from-local-disk/
is_root: false
weight: 50
---


आप फ़ाइल के पथ का उपयोग करके स्थानीय डिस्क से दस्तावेज़ लोड कर सकते हैं। GroupDocs.Viewer फ़ाइल को केवल-पढ़ने वाले मोड में खोलता है।

निम्नलिखित कोड स्निपेट दर्शाता है कि स्थानीय पथ स्ट्रिंग का उपयोग करके दस्तावेज़ कैसे लोड किया जाए:

{{< tabs "example1">}}
{{< tab "Python" >}}
```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

def load_document_from_local_disk():
    # स्थानीय डिस्क से दस्तावेज़ लोड करें
    with Viewer("sample.docx") as viewer:
        html_options = HtmlViewOptions.for_embedded_resources("load_document_from_local_disk/document_from_local_disk_{0}.html")
        viewer.view(html_options)

if __name__ == "__main__":
    load_document_from_local_disk()
```
{{< /tab >}}
{{< tab "sample.docx" >}}

`sample.docx` इस उदाहरण में उपयोग की गई नमूना फ़ाइल है। इसे डाउनलोड करने के लिए [यहाँ](https://docs.groupdocs.com/viewer/python-net/_sample_files/developer-guide/loading-documents/load-document-from-local-disk/sample.docx) क्लिक करें।

{{< /tab >}}
{{< tab "load-document-from-local-disk-outputs.zip" >}}
```text
load_document_from_local_disk/document_from_local_disk_1.html (317 KB)
load_document_from_local_disk/document_from_local_disk_2.html (149 KB)
load_document_from_local_disk/document_from_local_disk_3.html (113 KB)
```
[Download full output](https://docs.groupdocs.com/viewer/python-net/_output_files/developer-guide/loading-documents/load-document-from-local-disk/load_document_from_local_disk/load-document-from-local-disk-outputs.zip)
{{< /tab >}}
{{< /tabs >}}
