---
title: "Класс ProjectManagementViewInfo"
second_title: "Справочник API GroupDocs.Viewer для Python через .NET"
description: "Представляет информацию представления для документа MS Project."
type: docs
url: /ru/python-net/groupdocs.viewer.results/projectmanagementviewinfo/
is_root: false
weight: 150
---


## ProjectManagementViewInfo class

Представляет информацию представления для документа MS Project.

Тип ProjectManagementViewInfo раскрывает следующие члены:

### Конструкторы
| Конструктор | Описание |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.results/projectmanagementviewinfo/__init__/) | Инициализирует новый экземпляр [`ProjectManagementViewInfo`](/viewer/python-net/groupdocs.viewer.results/projectmanagementviewinfo/). |
| [__init__](/viewer/python-net/groupdocs.viewer.results/projectmanagementviewinfo/__init__/#file_type-pages-start_date-end_date) | Инициализирует новый экземпляр ProjectManagementViewInfo. |

### Методы
| Метод | Описание |
| :- | :- |
| [to_string](/viewer/python-net/groupdocs.viewer.results/viewinfo/to_string/) | Возвращает строку, представляющую текущий объект. (унаследовано от [`ViewInfo`](/viewer/python-net/groupdocs.viewer.results/viewinfo/)) |

### Свойства
| Свойство | Описание |
| :- | :- |
| [end_date](/viewer/python-net/groupdocs.viewer.results/projectmanagementviewinfo/end_date/) | Дата и время, когда проект должен быть завершён. |
| [start_date](/viewer/python-net/groupdocs.viewer.results/projectmanagementviewinfo/start_date/) | Дата и время, с которых проект начался. |
| [file_type](/viewer/python-net/groupdocs.viewer.results/viewinfo/file_type/) | Тип файла. (унаследовано от [`ViewInfo`](/viewer/python-net/groupdocs.viewer.results/viewinfo/)) |
| [pages](/viewer/python-net/groupdocs.viewer.results/viewinfo/pages/) | Список страниц для просмотра. (унаследовано от [`ViewInfo`](/viewer/python-net/groupdocs.viewer.results/viewinfo/)) |

### Пример

```python
from typing import cast
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import ViewInfoOptions
from groupdocs.viewer.results import ProjectManagementViewInfo

def get_project_info():
    with Viewer("sample.mpp") as viewer:
        info = viewer.get_view_info(ViewInfoOptions.for_html_view())
        project_info = cast(ProjectManagementViewInfo, info)

        print("File type:", project_info.file_type)
        print("Pages count:", len(project_info.pages))
        print("Start date:", project_info.start_date)
        print("End date:", project_info.end_date)

if __name__ == "__main__":
    get_project_info()
```

### Guides
Руководства задач, использующие `ProjectManagementViewInfo`:

* [Get Document Information](/viewer/python-net/guides/get-document-info/)

### См. также
* module [`groupdocs.viewer.results`](/viewer/python-net/groupdocs.viewer.results/)
