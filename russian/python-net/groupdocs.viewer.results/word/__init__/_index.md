---
title: "__init__ конструктор"
second_title: "Справочник API GroupDocs.Viewer для Python через .NET"
description: "Инициализирует новый экземпляр Word."
type: docs
url: /ru/python-net/groupdocs.viewer.results/word/__init__/
is_root: false
weight: 10
---


## __init__

Инициализирует новый экземпляр [`Word`](/viewer/python-net/groupdocs.viewer.results/word/).

```python
def __init__(self):
    ...
```

## __init__ {#word-x-y-width-height-characters}

Инициализирует новый экземпляр [`Word`](/viewer/python-net/groupdocs.viewer.results/word/).

```python
def __init__(self, word, x, y, width, height, characters):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| word | `str` | Слово. |
| x | `float` | Координата X самой верхней левой точки на макете страницы, где начинается прямоугольник, содержащий слово. |
| y | `float` | Координата Y самой верхней левой точки на макете страницы, где начинается прямоугольник, содержащий слово. |
| width | `float` | Ширина прямоугольника, содержащего слово. |
| height | `float` | Высота прямоугольника, содержащего слово. |
| characters | `List[Character]` | Символы, содержащиеся в слове. |

| Исключения | Описание |
| :- | :- |
| `ValueError` | Когда `characters` равно null. |

### См. также
* class [`Word`](/viewer/python-net/groupdocs.viewer.results/word/)
