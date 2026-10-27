---
title: "__init__ 생성자"
second_title: "GroupDocs.Viewer 용 Python via .NET API 참조"
description: "Line의 새 인스턴스를 초기화합니다."
type: docs
url: /ko/python-net/groupdocs.viewer.results/line/__init__/
is_root: false
weight: 10
---


## __init__

새로운 [`Line`](/viewer/python-net/groupdocs.viewer.results/line/) 인스턴스를 초기화합니다.

```python
def __init__(self):
    ...
```

## __init__ {#line-x-y-width-height-words}

새로운 [`Line`](/viewer/python-net/groupdocs.viewer.results/line/) 클래스 인스턴스를 초기화합니다.

```python
def __init__(self, line, x, y, width, height, words):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| line | `str` | 줄입니다. |
| x | `float` | 줄을 포함하는 사각형이 시작되는 페이지 레이아웃의 가장 왼쪽 상단 지점의 X 좌표입니다. |
| y | `float` | 줄을 포함하는 사각형이 시작되는 페이지 레이아웃의 가장 왼쪽 상단 지점의 Y 좌표입니다. |
| width | `float` | 줄을 포함하는 사각형의 너비(픽셀 단위)입니다. |
| height | `float` | 라인을 포함하는 사각형의 높이 (픽셀). |
| words | `List[Word]` | 라인에 포함된 단어들. |

| 예외 발생 | 설명 |
| :- | :- |
| `ValueError` | `line`이 null이거나 비어 있을 때, 또는 `words`가 null일 때 발생합니다. |

### 참고
* class [`Line`](/viewer/python-net/groupdocs.viewer.results/line/)
