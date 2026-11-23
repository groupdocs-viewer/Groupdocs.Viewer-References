---
title: "__init__ конструктор"
second_title: "Справочник API GroupDocs.Viewer для Python через .NET"
description: "Инициализирует новый экземпляр класса Layer."
type: docs
url: /ru/python-net/groupdocs.viewer.results/layer/__init__/
is_root: false
weight: 10
---


## __init__

Инициализирует новый экземпляр класса [`Layer`](/viewer/python-net/groupdocs.viewer.results/layer/).

```python
def __init__(self):
    ...
```

### Пример

```python
from groupdocs.viewer.results import Layer

# Создайте слой с указанным именем.
layer = Layer("QUADRANT")
```

## __init__ {#name}

Инициализирует новый экземпляр Layer.

```python
def __init__(self, name):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| name | `str` | Имя слоя. |

| Исключения | Описание |
| :- | :- |
| `ValueError` | Возникает, когда `name` равно None или пусто. |

### Пример

```python
from groupdocs.viewer.results import Layer

# Создайте слой с указанным именем
layer = Layer("QUADRANT")
```

## __init__ {#name-visible}

Инициализирует новый экземпляр Layer.

```python
def __init__(self, name, visible):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| name | `str` | Имя слоя. |
| visible | `bool` | Индикатор видимости слоя. |

| Исключения | Описание |
| :- | :- |
| `ValueError` | Когда `name` равно None или пустой. |

### Пример

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions
from groupdocs.viewer.results import Layer

with Viewer("sample.dwg") as viewer:
    options = PdfViewOptions("render_specific_layers/specific_layers.pdf")
    options.cad_options.layers = [Layer("QUADRANT")]
    viewer.view(options)
```

### См. также
* class [`Layer`](/viewer/python-net/groupdocs.viewer.results/layer/)
