---
title: "__init__ 생성자"
second_title: "GroupDocs.Viewer 용 Python via .NET API 참조"
description: "Layer 클래스의 새 인스턴스를 초기화합니다."
type: docs
url: /ko/python-net/groupdocs.viewer.results/layer/__init__/
is_root: false
weight: 10
---


## __init__

새로운 [`Layer`](/viewer/python-net/groupdocs.viewer.results/layer/) 클래스 인스턴스를 초기화합니다.

```python
def __init__(self):
    ...
```

### 예시

```python
from groupdocs.viewer.results import Layer

# 지정된 이름으로 레이어를 생성합니다.
layer = Layer("QUADRANT")
```

## __init__ {#name}

새로운 Layer 인스턴스를 초기화합니다.

```python
def __init__(self, name):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| name | `str` | 레이어의 이름. |

| 예외 발생 | 설명 |
| :- | :- |
| `ValueError` | `name`이 None이거나 비어 있을 때 발생합니다. |

### 예시

```python
from groupdocs.viewer.results import Layer

# 지정된 이름으로 레이어를 생성합니다
layer = Layer("QUADRANT")
```

## __init__ {#name-visible}

새로운 Layer 인스턴스를 초기화합니다.

```python
def __init__(self, name, visible):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| name | `str` | 레이어의 이름. |
| visible | `bool` | 레이어 가시성 표시기. |

| 예외 발생 | 설명 |
| :- | :- |
| `ValueError` | `name`이 None이거나 비어 있을 때. |

### 예시

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions
from groupdocs.viewer.results import Layer

with Viewer("sample.dwg") as viewer:
    options = PdfViewOptions("render_specific_layers/specific_layers.pdf")
    options.cad_options.layers = [Layer("QUADRANT")]
    viewer.view(options)
```

### 참고
* class [`Layer`](/viewer/python-net/groupdocs.viewer.results/layer/)
