---
title: "__init__ 생성자"
second_title: "GroupDocs.Viewer 용 Python via .NET API 참조"
description: "Layout의 새 인스턴스를 초기화합니다."
type: docs
url: /ko/python-net/groupdocs.viewer.results/layout/__init__/
is_root: false
weight: 10
---


## __init__

Layout의 새 인스턴스를 초기화합니다.

```python
def __init__(self):
    ...
```

## __init__ {#name-width-height}

[`Layout`](/viewer/python-net/groupdocs.viewer.results/layout/)의 새 인스턴스를 초기화합니다.

```python
def __init__(self, name, width, height):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| name | `str` | 레이아웃의 이름입니다. |
| width | `float` | 레이아웃의 너비(픽셀). |
| height | `float` | 레이아웃의 높이(픽셀). |

| 예외 발생 | 설명 |
| :- | :- |
| `ValueError` | `name`이 None이거나 비어 있을 때. |

### 참고
* class [`Layout`](/viewer/python-net/groupdocs.viewer.results/layout/)
