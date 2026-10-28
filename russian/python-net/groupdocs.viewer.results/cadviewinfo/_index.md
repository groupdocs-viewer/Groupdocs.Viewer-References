---
title: "Класс CadViewInfo"
second_title: "Справочник API GroupDocs.Viewer для Python через .NET"
description: "Представляет информацию о представлении чертежа CAD."
type: docs
url: /ru/python-net/groupdocs.viewer.results/cadviewinfo/
is_root: false
weight: 30
---


## CadViewInfo class

Представляет информацию о представлении чертежа CAD.

Тип CadViewInfo раскрывает следующие члены:

### Конструкторы
| Конструктор | Описание |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.results/cadviewinfo/__init__/#file_type-pages-layers-layouts) | Инициализирует новый экземпляр CadViewInfo. |

### Методы
| Метод | Описание |
| :- | :- |
| [to_string](/viewer/python-net/groupdocs.viewer.results/viewinfo/to_string/) | Возвращает строку, представляющую текущий объект. (унаследовано от [`ViewInfo`](/viewer/python-net/groupdocs.viewer.results/viewinfo/)) |

### Свойства
| Свойство | Описание |
| :- | :- |
| [layers](/viewer/python-net/groupdocs.viewer.results/cadviewinfo/layers/) | Список слоёв, содержащихся в CAD‑чертежe. |
| [layouts](/viewer/python-net/groupdocs.viewer.results/cadviewinfo/layouts/) | Список макетов, содержащихся в CAD‑чертежe. |
| [file_type](/viewer/python-net/groupdocs.viewer.results/viewinfo/file_type/) | Тип файла. (унаследовано от [`ViewInfo`](/viewer/python-net/groupdocs.viewer.results/viewinfo/)) |
| [pages](/viewer/python-net/groupdocs.viewer.results/viewinfo/pages/) | Список страниц для просмотра. (унаследовано от [`ViewInfo`](/viewer/python-net/groupdocs.viewer.results/viewinfo/)) |

### Пример

```python
from typing import cast
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import ViewInfoOptions
from groupdocs.viewer.results import CadViewInfo

def get_cad_info():
    with Viewer("sample.dwg") as viewer:
        info = viewer.get_view_info(ViewInfoOptions.for_html_view())
        cad_info = cast(CadViewInfo, info)

        print("File type:", cad_info.file_type)
        print("Pages count:", len(cad_info.pages))
        print("Layers:")
        for layer in cad_info.layers:
            print(f"  {layer.name} (visible={layer.visible})")
        print("Layouts:")
        for layout in cad_info.layouts:
            print(f"  {layout.name} ({layout.width}x{layout.height})")

if __name__ == "__main__":
    get_cad_info()
```

### Guides
Руководства задач, использующие `CadViewInfo`:

* [Get Document Information](/viewer/python-net/guides/get-document-info/)

### См. также
* module [`groupdocs.viewer.results`](/viewer/python-net/groupdocs.viewer.results/)
