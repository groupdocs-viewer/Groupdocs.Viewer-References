---
title: "__init__ 생성자"
second_title: "GroupDocs.Viewer 용 Python via .NET API 참조"
description: "Word의 새 인스턴스를 초기화합니다."
type: docs
url: /ko/python-net/groupdocs.viewer.results/word/__init__/
is_root: false
weight: 10
---


## __init__

새로운 [`Word`](/viewer/python-net/groupdocs.viewer.results/word/) 인스턴스를 초기화합니다.

```python
def __init__(self):
    ...
```

## __init__ {#word-x-y-width-height-characters}

새로운 [`Word`](/viewer/python-net/groupdocs.viewer.results/word/) 인스턴스를 초기화합니다.

```python
def __init__(self, word, x, y, width, height, characters):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| word | `str` | 단어입니다. |
| x | `float` | 단어를 포함하는 사각형이 시작되는 페이지 레이아웃의 가장 왼쪽 상단 지점의 X 좌표입니다. |
| y | `float` | 단어를 포함하는 사각형이 시작되는 페이지 레이아웃의 가장 왼쪽 상단 지점의 Y 좌표입니다. |
| width | `float` | 단어를 포함하는 사각형의 너비입니다. |
| height | `float` | 단어를 포함하는 사각형의 높이입니다. |
| characters | `List[Character]` | 단어에 포함된 문자들. |

| 예외 발생 | 설명 |
| :- | :- |
| `ValueError` | `characters`가 null인 경우. |

### 참고
* class [`Word`](/viewer/python-net/groupdocs.viewer.results/word/)
