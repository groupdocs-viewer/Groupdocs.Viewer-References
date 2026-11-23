---
title: "페이지 순서 재정렬"
linkTitle: "Reorder pages"
second_title: "GroupDocs.Viewer 용 Python via .NET API 참조"
description: "GroupDocs.Viewer for Python via .NET를 사용하여 렌더링 중에 PDF 페이지를 재정렬합니다. 출력 페이지 순서를 제어합니다."
type: docs
url: /ko/python-net/guides/reorder-pages/
is_root: false
weight: 100
---


GroupDocs.Viewer는 원본 문서의 페이지 순서를 유지합니다. 대신, 출력 PDF 문서에서 페이지를 재정렬할 수 있습니다.

페이지를 재정렬하려면 다음 단계를 따르세요:

1. [Viewer](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer/viewer) 객체를 인스턴스화합니다.
2. [PdfViewOptions](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer.options/pdfviewoptions) 객체를 생성합니다.
3. [Viewer](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer/viewer) 객체의 [view](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer/viewer/#methods) 메서드를 호출합니다. 마지막 매개변수에 새 페이지 순서를 지정합니다.

다음 코드 조각은 페이지를 재정렬하는 방법을 보여줍니다:

{{< tabs \"example1\">}}
{{< tab \"Python\">}}
```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions

def reorder_pages():
    # 문서 로드
    with Viewer("sample.docx") as viewer:
        # 뷰 옵션을 생성합니다.
        viewOptions = PdfViewOptions("reorder_pages/reordered_pages.pdf")

        # 렌더링하려는 순서대로 페이지 번호를 전달합니다.
        viewer.view(viewOptions, [2, 1])

if __name__ == "__main__":
    reorder_pages()
```
{{< /tab >}}
{{< tab \"sample.docx\" >}}

`sample.docx`는 이 예제에서 사용된 샘플 파일입니다. 다운로드하려면 [여기](https://docs.groupdocs.com/viewer/python-net/_sample_files/developer-guide/rendering-documents/rendering-to-pdf/reorder-pages/sample.docx)를 클릭하세요.

{{< /tab >}}
{{< tab \"reordered_pages.pdf\" >}}
```text
Binary file (PDF, 176 KB)
```
[Download full output](https://docs.groupdocs.com/viewer/python-net/_output_files/developer-guide/rendering-documents/rendering-to-pdf/reorder-pages/reorder_pages/reordered_pages.pdf)
{{< /tab >}}
{{< /tabs >}}
