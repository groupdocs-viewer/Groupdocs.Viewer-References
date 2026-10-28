---
title: "__init__ конструктор"
second_title: "Справочник API GroupDocs.Viewer для Python через .NET"
description: "Инициализирует новый экземпляр Line."
type: docs
url: /ru/python-net/groupdocs.viewer.results/line/__init__/
is_root: false
weight: 10
---


## __init__

Инициализирует новый экземпляр [`Line`](/viewer/python-net/groupdocs.viewer.results/line/).

```python
def __init__(self):
    ...
```

## __init__ {#line-x-y-width-height-words}

Инициализирует новый экземпляр класса [`Line`](/viewer/python-net/groupdocs.viewer.results/line/) .

```python
def __init__(self, line, x, y, width, height, words):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| line | `str` | Линия. |
| x | `float` | Координата X самой верхней левой точки на макете страницы, где начинается прямоугольник, содержащий линию. |
| y | `float` | Координата Y самой верхней левой точки на макете страницы, где начинается прямоугольник, содержащий линию. |
| width | `float` | Ширина прямоугольника, содержащего линию (в пикселях). |
| height | `float` | Высота прямоугольника, содержащего линию (в пикселях). |
| words | `List[Word]` | Слова, содержащиеся в строке. |

| Исключения | Описание |
| :- | :- |
| `ValueError` | Возникает, когда `line` равно null или пусто, либо когда `words` равно null. |

### См. также
* class [`Line`](/viewer/python-net/groupdocs.viewer.results/line/)
