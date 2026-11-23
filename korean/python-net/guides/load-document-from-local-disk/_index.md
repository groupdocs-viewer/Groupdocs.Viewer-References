---
title: "로컬 디스크에서 문서 로드"
linkTitle: "Load from local disk"
second_title: "GroupDocs.Viewer 용 Python via .NET API 참조"
description: ".NET을 통해 Python용 GroupDocs.Viewer를 사용하여 파일 경로로 로컬 디스크에서 문서를 로드합니다."
type: docs
url: /ko/python-net/guides/load-document-from-local-disk/
is_root: false
weight: 50
---


파일 경로를 사용하여 로컬 디스크에서 문서를 로드할 수 있습니다. GroupDocs.Viewer는 파일을 읽기 전용 모드로 엽니다.

다음 코드 스니펫은 로컬 경로 문자열을 사용하여 문서를 로드하는 방법을 보여줍니다:

{{< tabs \"example1\">}}
{{< tab "Python" >}}
```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

def load_document_from_local_disk():
    # 로컬 디스크에서 문서 로드
    with Viewer("sample.docx") as viewer:
        html_options = HtmlViewOptions.for_embedded_resources("load_document_from_local_disk/document_from_local_disk_{0}.html")
        viewer.view(html_options)

if __name__ == "__main__":
    load_document_from_local_disk()
```
{{< /tab >}}
{{< tab \"sample.docx\" >}}

`sample.docx`은 이 예제에서 사용되는 샘플 파일입니다. 다운로드하려면 [here](https://docs.groupdocs.com/viewer/python-net/_sample_files/developer-guide/loading-documents/load-document-from-local-disk/sample.docx)를 클릭하십시오.

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
