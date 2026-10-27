---
title: "Muat dokumen dari URL"
linkTitle: "Load from URL"
second_title: "Referensi API GroupDocs.Viewer untuk Python via .NET"
description: "Ambil dokumen melalui HTTP dengan pustaka requests dan render dari aliran memori menggunakan GroupDocs.Viewer untuk Python via .NET."
type: docs
url: /id/python-net/guides/load-document-from-url/
is_root: false
weight: 70
---


Potongan kode berikut menunjukkan cara memuat dokumen dari URL:

{{< tabs "demo_app_load_document_from_url">}}
{{< tab "load_document_from_url.py" >}}
```python
import requests
import io
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

def download_file(url):
    response = requests.get(url, stream=True, timeout=10)
    response.raise_for_status()
    return io.BytesIO(response.content)

def load_document_from_url():
    url = "https://github.com/groupdocs-viewer/GroupDocs.Viewer-for-.NET/blob/master/Examples/GroupDocs.Viewer.Examples.CSharp/Resources/SampleFiles/sample.docx?raw=true"

    stream = download_file(url)

    with Viewer(stream) as viewer:
        options = HtmlViewOptions.for_embedded_resources("load_document_from_url/page_{0}.html")
        viewer.view(options)

if __name__ == "__main__":
    load_document_from_url()
```
{{< /tab >}}
{{< tab "load-document-from-url-outputs.zip" >}}
```text
load_document_from_url/page_1.html (317 KB)
load_document_from_url/page_2.html (149 KB)
load_document_from_url/page_3.html (113 KB)
```
[Download full output](https://docs.groupdocs.com/viewer/python-net/_output_files/developer-guide/loading-documents/load-document-from-url/load_document_from_url/load-document-from-url-outputs.zip)
{{< /tab >}}
{{< /tabs >}}
