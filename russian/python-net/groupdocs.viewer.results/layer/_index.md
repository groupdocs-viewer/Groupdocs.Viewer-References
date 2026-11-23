---
title: "Класс Layer"
second_title: "Справочник API GroupDocs.Viewer для Python через .NET"
description: "Представляет слой, содержащийся в чертеже CAD."
type: docs
url: /ru/python-net/groupdocs.viewer.results/layer/
is_root: false
weight: 60
---


## Layer class

Представляет слой, содержащийся в чертеже CAD.

The тип Layer раскрывает следующие члены:

### Конструкторы
| Конструктор | Описание |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.results/layer/__init__/) | Инициализирует новый экземпляр класса [`Layer`](/viewer/python-net/groupdocs.viewer.results/layer/). |
| [__init__](/viewer/python-net/groupdocs.viewer.results/layer/__init__/#name) | Инициализирует новый экземпляр Layer. |
| [__init__](/viewer/python-net/groupdocs.viewer.results/layer/__init__/#name-visible) | Инициализирует новый экземпляр Layer. |

### Методы
| Метод | Описание |
| :- | :- |
| [equals](/viewer/python-net/groupdocs.viewer.results/layer/equals/#other) | Определяет, является ли текущий Layer тем же, что и указанный объект Layer. |
| [equals](/viewer/python-net/groupdocs.viewer.results/layer/equals/#obj) | Проверяет, равен ли текущий [`Layer`](/viewer/python-net/groupdocs.viewer.results/layer/) указанному объекту. |
| [equals_layer](/viewer/python-net/groupdocs.viewer.results/layer/equals_layer/) |  |
| [equals_object](/viewer/python-net/groupdocs.viewer.results/layer/equals_object/) |  |
| [get_hash_code](/viewer/python-net/groupdocs.viewer.results/layer/get_hash_code/) | Возвращает код хэша для текущего объекта Layer. |
| [to_string](/viewer/python-net/groupdocs.viewer.results/layer/to_string/) | Возвращает строку, представляющую текущий объект. |

### Свойства
| Свойство | Описание |
| :- | :- |
| [name](/viewer/python-net/groupdocs.viewer.results/layer/name/) | Имя слоя. |
| [visible](/viewer/python-net/groupdocs.viewer.results/layer/visible/) | Индикатор видимости слоя. |

### Пример

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions
from groupdocs.viewer.results import Layer

with Viewer("sample.dwg") as viewer:
    options = PdfViewOptions("output.pdf")
    options.cad_options.layers = [Layer("QUADRANT")]
    viewer.view(options)
```

### См. также
* module [`groupdocs.viewer.results`](/viewer/python-net/groupdocs.viewer.results/)
