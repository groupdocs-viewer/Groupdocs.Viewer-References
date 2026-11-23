---
title: "스트림에서 문서 로드"
linkTitle: "Load from stream"
second_title: "GroupDocs.Viewer 용 Python via .NET API 참조"
description: "GroupDocs.Viewer for Python via .NET를 사용하여 파일과 유사한 객체(열린 파일 핸들, BytesIO 또는 기타 스트림)에서 직접 문서를 로드합니다."
type: docs
url: /ko/python-net/guides/load-document-from-stream/
is_root: false
weight: 60
---


스트림에서 문서를 디스크에 파일로 저장하지 않고 로드할 수 있습니다. 이 기능을 사용하여 URL, FTP 등 다양한 소스에서 문서를 로드할 수 있습니다.

스트림에서 문서를 로드하려면 다음 단계를 따르세요:

1. 문서 스트림을 가져오는 메서드를 구현합니다.
2. [Viewer](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer/viewer) 클래스 생성자를 호출합니다. 이전 단계에서 구현한 메서드를 지정합니다.

다음 코드 스니펫은 스트림에서 문서를 로드하는 방법을 보여줍니다:

{{< tabs \"example1\">}}
{{< tab "Python" >}}
```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

def load_document_from_stream():
    # 문서 스트림 열기
    stream = open("sample.docx", "rb")

    # 스트림에서 문서를 렌더링합니다.
    with Viewer(stream) as viewer:
        options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
        viewer.view(options)

if __name__ == "__main__":
    load_document_from_stream()
```
{{< /tab >}}
{{< tab \"sample.docx\" >}}

`sample.docx`은 이 예제에서 사용되는 샘플 파일입니다. 다운로드하려면 [here](https://docs.groupdocs.com/viewer/python-net/_sample_files/developer-guide/loading-documents/load-document-from-stream/sample.docx)를 클릭하십시오.

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

또한 [Load document from URL]()를 참조하여 문서를 `BytesIO` 스트림에 다운로드하고 디스크에 쓰지 않고 렌더링하는 구체적인 예제를 확인하십시오.
