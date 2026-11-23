---
title: "Класс OutlookViewInfo"
second_title: "Справочник API GroupDocs.Viewer для Python через .NET"
description: "Представляет информацию представления для файла данных Outlook."
type: docs
url: /ru/python-net/groupdocs.viewer.results/outlookviewinfo/
is_root: false
weight: 120
---


## OutlookViewInfo class

Представляет информацию представления для файла данных Outlook.

Тип OutlookViewInfo раскрывает следующие члены:

### Конструкторы
| Конструктор | Описание |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.results/outlookviewinfo/__init__/) | Инициализирует новый экземпляр [`OutlookViewInfo`](/viewer/python-net/groupdocs.viewer.results/outlookviewinfo/). |
| [__init__](/viewer/python-net/groupdocs.viewer.results/outlookviewinfo/__init__/#file_type-pages-folders) | Инициализирует новый экземпляр OutlookViewInfo. |

### Методы
| Метод | Описание |
| :- | :- |
| [to_string](/viewer/python-net/groupdocs.viewer.results/viewinfo/to_string/) | Возвращает строку, представляющую текущий объект. (унаследовано от [`ViewInfo`](/viewer/python-net/groupdocs.viewer.results/viewinfo/)) |

### Свойства
| Свойство | Описание |
| :- | :- |
| [folders](/viewer/python-net/groupdocs.viewer.results/outlookviewinfo/folders/) | Список папок, содержащихся в файле данных Outlook. |
| [file_type](/viewer/python-net/groupdocs.viewer.results/viewinfo/file_type/) | Тип файла. (унаследовано от [`ViewInfo`](/viewer/python-net/groupdocs.viewer.results/viewinfo/)) |
| [pages](/viewer/python-net/groupdocs.viewer.results/viewinfo/pages/) | Список страниц для просмотра. (унаследовано от [`ViewInfo`](/viewer/python-net/groupdocs.viewer.results/viewinfo/)) |

### Пример

```python
from typing import cast
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import ViewInfoOptions
from groupdocs.viewer.results import OutlookViewInfo

def get_outlook_info():
    with Viewer("sample.pst") as viewer:
        info = viewer.get_view_info(ViewInfoOptions.for_html_view())
        outlook_info = cast(OutlookViewInfo, info)

        print("File type:", outlook_info.file_type)
        print("Pages count:", len(outlook_info.pages))
        print("Folders:")
        for folder in outlook_info.folders:
            print(f"  {folder}")

if __name__ == "__main__":
    get_outlook_info()
```

### Guides
Руководства по задачам, использующие `OutlookViewInfo`:

* [Get Document Information](/viewer/python-net/guides/get-document-info/)

### См. также
* module [`groupdocs.viewer.results`](/viewer/python-net/groupdocs.viewer.results/)
