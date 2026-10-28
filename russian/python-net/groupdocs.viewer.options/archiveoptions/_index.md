---
title: "Класс ArchiveOptions"
second_title: "Справочник API GroupDocs.Viewer для Python через .NET"
description: "Содержит параметры для рендеринга архивных файлов."
type: docs
url: /ru/python-net/groupdocs.viewer.options/archiveoptions/
is_root: false
weight: 10
---


## ArchiveOptions class

Содержит параметры для рендеринга архивных файлов.

Тип ArchiveOptions раскрывает следующие члены:

### Конструкторы
| Конструктор | Описание |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.options/archiveoptions/__init__/) | Инициализирует экземпляр класса [`ArchiveOptions`](/viewer/python-net/groupdocs.viewer.options/archiveoptions/). |

### Свойства
| Свойство | Описание |
| :- | :- |
| [file_name](/viewer/python-net/groupdocs.viewer.options/archiveoptions/file_name/) | Отображаемое имя файла архива. |
| [folder](/viewer/python-net/groupdocs.viewer.options/archiveoptions/folder/) | Папка для отображения. |

### Пример

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("documents.zip") as viewer:
    view_options = HtmlViewOptions.for_embedded_resources(
        "render_specific_archive_folder/specific_archive_folder.html"
    )
    view_options.archive_options.folder = "first_folder"
    viewer.view(view_options)
```

### См. также
* module [`groupdocs.viewer.options`](/viewer/python-net/groupdocs.viewer.options/)
