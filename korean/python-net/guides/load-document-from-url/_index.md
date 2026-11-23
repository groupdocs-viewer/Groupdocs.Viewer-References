---
title: "URL에서 문서 로드"
linkTitle: "Load from URL"
second_title: "GroupDocs.Viewer 용 Python via .NET API 참조"
description: "requests 라이브러리를 사용해 HTTP를 통해 문서를 가져오고, GroupDocs.Viewer for Python via .NET를 사용하여 메모리 스트림에서 렌더링합니다."
type: docs
url: /ko/python-net/guides/load-document-from-url/
is_root: false
weight: 70
---


다음 코드 조각은 URL에서 문서를 로드하는 방법을 보여줍니다:

{{< tabs \"demo_app_load_document_from_url\">}}
{{< tab \"load_document_from_url.py\" >}}
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
{{< tab \"load-document-from-url-outputs.zip\" >}}
```text
load_document_from_url/page_1.html (317 KB)
load_document_from_url/page_2.html (149 KB)
load_document_from_url/page_3.html (113 KB)
```
[Download full output](https://docs.groupdocs.com/viewer/python-net/_output_files/developer-guide/loading-documents/load-document-from-url/load_document_from_url/load-document-from-url-outputs.zip)
{{< /tab >}}
{{< /tabs >}}
