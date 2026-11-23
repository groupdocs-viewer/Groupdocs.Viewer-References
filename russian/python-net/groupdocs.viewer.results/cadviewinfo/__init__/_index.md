---
title: "__init__ конструктор"
second_title: "Справочник API GroupDocs.Viewer для Python через .NET"
description: "Инициализирует новый экземпляр CadViewInfo."
type: docs
url: /ru/python-net/groupdocs.viewer.results/cadviewinfo/__init__/
is_root: false
weight: 10
---


## __init__ {#file_type-pages-layers-layouts}

Инициализирует новый экземпляр CadViewInfo.

```python
def __init__(self, file_type, pages, layers, layouts):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| file_type | `FileType` | Тип файла. |
| pages | `List[Page]` | Список страниц для просмотра. |
| layers | `List[Layer]` | Список слоёв, содержащихся в CAD‑чертежe. |
| layouts | `List[Layout]` | Список слоёв, содержащихся в CAD‑чертежe. |

| Исключения | Описание |
| :- | :- |
| `ValueError` | Вызывается, когда `layouts` равно None. |

### См. также
* class [`CadViewInfo`](/viewer/python-net/groupdocs.viewer.results/cadviewinfo/)
