---
title: "ViewInfo 클래스"
second_title: "GroupDocs.Viewer 용 Python via .NET API 참조"
description: "일반 문서에 대한 보기 정보를 나타냅니다."
type: docs
url: /ko/python-net/groupdocs.viewer.results/viewinfo/
is_root: false
weight: 180
---


## ViewInfo class

일반 문서에 대한 보기 정보를 나타냅니다.

ViewInfo 유형은 다음 멤버를 노출합니다:

### 생성자
| 생성자 | 설명 |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.results/viewinfo/__init__/) | 새 인스턴스를 초기화합니다 [`ViewInfo`](/viewer/python-net/groupdocs.viewer.results/viewinfo/). |
| [__init__](/viewer/python-net/groupdocs.viewer.results/viewinfo/__init__/#file_type-pages) | 새 ViewInfo 인스턴스를 초기화합니다. |

### 메서드
| 메서드 | 설명 |
| :- | :- |
| [to_string](/viewer/python-net/groupdocs.viewer.results/viewinfo/to_string/) | 현재 객체를 나타내는 문자열을 반환합니다. |

### 속성
| 속성 | 설명 |
| :- | :- |
| [file_type](/viewer/python-net/groupdocs.viewer.results/viewinfo/file_type/) | 파일의 유형입니다. |
| [pages](/viewer/python-net/groupdocs.viewer.results/viewinfo/pages/) | 볼 페이지 목록입니다. |

### 예시

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import ViewInfoOptions

with Viewer("sample.docx") as viewer:
    options = ViewInfoOptions.for_html_view()
    view_info = viewer.get_view_info(options)
    for page in view_info.pages:
        print(f"Page {page.number}: {page.name}")
```

### 참고
* module [`groupdocs.viewer.results`](/viewer/python-net/groupdocs.viewer.results/)
