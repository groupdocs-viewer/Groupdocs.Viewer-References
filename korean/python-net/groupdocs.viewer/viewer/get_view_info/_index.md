---
title: "get_view_info 메서드"
second_title: "GroupDocs.Viewer 용 Python via .NET API 참조"
description: "뷰 및 문서별 정보를 반환합니다."
type: docs
url: /ko/python-net/groupdocs.viewer/viewer/get_view_info/
is_root: false
weight: 1050
---


## get_view_info {#options}

뷰 및 문서별 정보를 반환합니다.

문서에 대해 자세히 알아보기 - 파일 유형, 페이지 수 및 기타 형식별 속성:
- [How to get file information using GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Get+file+information)

```python
def get_view_info(self, options):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| options | `ViewInfoOptions` | 뷰 정보 옵션. |

**Returns:** Information about view and document specific information.

| 예외 발생 | 설명 |
| :- | :- |
| `ValueError` | 옵션이 `None`인 경우. |
| `PasswordRequiredException` | 문서를 열기 위해 비밀번호가 필요한 경우. |
| `IncorrectPasswordException` | 지정된 비밀번호가 올바르지 않을 때. |

### 예시

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import ViewInfoOptions

with Viewer("document.pdf") as viewer:
    info = viewer.get_view_info(ViewInfoOptions.for_html_view())
    print(f"Pages: {len(info.pages)}")
    for page in info.pages:
        print(f"  Page {page.number}: {page.width}x{page.height}")
```

### 참고
* class [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/)
