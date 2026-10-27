---
title: "__init__ 생성자"
second_title: "GroupDocs.Viewer 용 Python via .NET API 참조"
description: "ViewInfo의 새 인스턴스를 초기화합니다."
type: docs
url: /ko/python-net/groupdocs.viewer.results/viewinfo/__init__/
is_root: false
weight: 10
---


## __init__

새 인스턴스를 초기화합니다 [`ViewInfo`](/viewer/python-net/groupdocs.viewer.results/viewinfo/).

```python
def __init__(self):
    ...
```

## __init__ {#file_type-pages}

새 ViewInfo 인스턴스를 초기화합니다.

```python
def __init__(self, file_type, pages):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| file_type | `FileType` | 파일의 유형입니다. |
| pages | `List[Page]` | 볼 페이지 목록입니다. |

| 예외 발생 | 설명 |
| :- | :- |
| `ValueError` | 만약 `pages`가 None이면. |

### 참고
* class [`ViewInfo`](/viewer/python-net/groupdocs.viewer.results/viewinfo/)
