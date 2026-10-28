---
title: "Класс ArchiveViewInfo"
second_title: "Справочник API GroupDocs.Viewer для Python через .NET"
description: "Представляет информацию о представлении архивного файла."
type: docs
url: /ru/python-net/groupdocs.viewer.results/archiveviewinfo/
is_root: false
weight: 10
---


## ArchiveViewInfo class

Представляет информацию о представлении архивного файла.

Тип ArchiveViewInfo раскрывает следующие члены:

### Конструкторы
| Конструктор | Описание |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.results/archiveviewinfo/__init__/) | Инициализирует новый экземпляр [`ArchiveViewInfo`](/viewer/python-net/groupdocs.viewer.results/archiveviewinfo/). |
| [__init__](/viewer/python-net/groupdocs.viewer.results/archiveviewinfo/__init__/#file_type-pages-folders) | Инициализирует новый экземпляр ArchiveViewInfo. |

### Методы
| Метод | Описание |
| :- | :- |
| [to_string](/viewer/python-net/groupdocs.viewer.results/viewinfo/to_string/) | Возвращает строку, представляющую текущий объект. (унаследовано от [`ViewInfo`](/viewer/python-net/groupdocs.viewer.results/viewinfo/)) |

### Свойства
| Свойство | Описание |
| :- | :- |
| [folders](/viewer/python-net/groupdocs.viewer.results/archiveviewinfo/folders/) | Папки, содержащиеся в архивном файле. |
| [file_type](/viewer/python-net/groupdocs.viewer.results/viewinfo/file_type/) | Тип файла. (унаследовано от [`ViewInfo`](/viewer/python-net/groupdocs.viewer.results/viewinfo/)) |
| [pages](/viewer/python-net/groupdocs.viewer.results/viewinfo/pages/) | Список страниц для просмотра. (унаследовано от [`ViewInfo`](/viewer/python-net/groupdocs.viewer.results/viewinfo/)) |

### Пример

```python
from typing import cast
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import ViewInfoOptions
from groupdocs.viewer.results import ArchiveViewInfo

def get_archive_info():
    with Viewer("documents.zip") as viewer:
        info = viewer.get_view_info(ViewInfoOptions.for_html_view())
        archive_info = cast(ArchiveViewInfo, info)

        print("File type:", archive_info.file_type)
        print("Pages count:", len(archive_info.pages))
        print("Folders:")
        for folder in archive_info.folders:
            print(f"  {folder}")

if __name__ == "__main__":
    get_archive_info()
```

### Guides
Руководства задач, использующие `ArchiveViewInfo`:

* [Get Document Information](/viewer/python-net/guides/get-document-info/)

### См. также
* module [`groupdocs.viewer.results`](/viewer/python-net/groupdocs.viewer.results/)
