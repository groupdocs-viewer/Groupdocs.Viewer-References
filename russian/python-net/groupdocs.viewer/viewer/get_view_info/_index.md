---
title: "get_view_info метод"
second_title: "Справочник API GroupDocs.Viewer для Python через .NET"
description: "Возвращает представление и специфическую информацию о документе."
type: docs
url: /ru/python-net/groupdocs.viewer/viewer/get_view_info/
is_root: false
weight: 1050
---


## get_view_info {#options}

Возвращает представление и специфическую информацию о документе.

Узнайте больше о документе — типе файла, количестве страниц и других свойствах, специфичных для формата:
- [How to get file information using GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Get+file+information)

```python
def get_view_info(self, options):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| options | `ViewInfoOptions` | Опции информации о представлении. |

**Returns:** Information about view and document specific information.

| Исключения | Описание |
| :- | :- |
| `ValueError` | Когда `options` равно None. |
| `PasswordRequiredException` | Когда для открытия документа требуется пароль. |
| `IncorrectPasswordException` | Когда указанный пароль неверен. |

### Пример

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import ViewInfoOptions

with Viewer("document.pdf") as viewer:
    info = viewer.get_view_info(ViewInfoOptions.for_html_view())
    print(f"Pages: {len(info.pages)}")
    for page in info.pages:
        print(f"  Page {page.number}: {page.width}x{page.height}")
```

### См. также
* class [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/)
