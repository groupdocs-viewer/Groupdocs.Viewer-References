---
title: "PdfViewInfo 클래스"
second_title: "GroupDocs.Viewer 용 Python via .NET API 참조"
description: "PDF 문서에 대한 보기 정보를 나타냅니다."
type: docs
url: /ko/python-net/groupdocs.viewer.results/pdfviewinfo/
is_root: false
weight: 140
---


## PdfViewInfo class

PDF 문서에 대한 보기 정보를 나타냅니다.

PdfViewInfo 형식은 다음 멤버를 노출합니다:

### 생성자
| 생성자 | 설명 |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.results/pdfviewinfo/__init__/) | 새 PdfViewInfo 인스턴스를 초기화합니다. |
| [__init__](/viewer/python-net/groupdocs.viewer.results/pdfviewinfo/__init__/#file_type-pages-printing_allowed) | 새 PdfViewInfo 인스턴스를 초기화합니다. |

### 메서드
| 메서드 | 설명 |
| :- | :- |
| [to_string](/viewer/python-net/groupdocs.viewer.results/viewinfo/to_string/) | 현재 객체를 나타내는 문자열을 반환합니다. ([`ViewInfo`](/viewer/python-net/groupdocs.viewer.results/viewinfo/)에서 상속됨) |

### 속성
| 속성 | 설명 |
| :- | :- |
| [printing_allowed](/viewer/python-net/groupdocs.viewer.results/pdfviewinfo/printing_allowed/) | printing_allowed 속성은 문서 인쇄가 허용되는지 여부를 나타냅니다. |
| [file_type](/viewer/python-net/groupdocs.viewer.results/viewinfo/file_type/) | 파일의 유형입니다. ([`ViewInfo`](/viewer/python-net/groupdocs.viewer.results/viewinfo/)에서 상속됨) |
| [pages](/viewer/python-net/groupdocs.viewer.results/viewinfo/pages/) | 볼 페이지 목록입니다. ([`ViewInfo`](/viewer/python-net/groupdocs.viewer.results/viewinfo/)에서 상속됨) |

### 예시

```python
from typing import cast
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import ViewInfoOptions
from groupdocs.viewer.results import PdfViewInfo

def get_pdf_info():
    with Viewer("sample.pdf") as viewer:
        info = viewer.get_view_info(ViewInfoOptions.for_html_view())
        pdf_info = cast(PdfViewInfo, info)

        print("File type:", pdf_info.file_type)
        print("Pages count:", len(pdf_info.pages))
        print("Printing allowed:", pdf_info.printing_allowed)

if __name__ == "__main__":
    get_pdf_info()
```

### Guides
`PdfViewInfo`를 사용하는 작업 가이드:

* [Get Document Information](/viewer/python-net/guides/get-document-info/)

### 참고
* module [`groupdocs.viewer.results`](/viewer/python-net/groupdocs.viewer.results/)
