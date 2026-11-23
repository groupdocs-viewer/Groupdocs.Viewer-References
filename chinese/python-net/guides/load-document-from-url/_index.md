---
title: "从 URL 加载文档"
linkTitle: "Load from URL"
second_title: "GroupDocs.Viewer 用于 Python，通过 .NET API 参考"
description: "使用 requests 库通过 HTTP 获取文档，并使用 GroupDocs.Viewer for Python via .NET 从内存流渲染它。"
type: docs
url: /zh/python-net/guides/load-document-from-url/
is_root: false
weight: 70
---


以下代码片段展示了如何从 URL 加载文档：

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
