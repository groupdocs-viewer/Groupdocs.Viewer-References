---
title: "Метод from_html_view_options"
second_title: "Справочник API GroupDocs.Viewer для Python через .NET"
description: "Инициализирует экземпляр класса ViewInfoOptions на основе объекта HtmlViewOptions."
type: docs
url: /ru/python-net/groupdocs.viewer.options/viewinfooptions/from_html_view_options/
is_root: false
weight: 1080
---


## from_html_view_options {#options}

Инициализирует экземпляр класса ViewInfoOptions на основе объекта HtmlViewOptions.

```python
def from_html_view_options(cls, options):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| options | `HtmlViewOptions` | Параметры просмотра HTML. |

**Returns:** A new ViewInfoOptions instance.

| Исключения | Описание |
| :- | :- |
| `ValueError` | Если `options` равно None. |

### Пример

```python
from groupdocs.viewer.options import ViewInfoOptions, HtmlViewOptions

html_opts = HtmlViewOptions()
view_info_opts = ViewInfoOptions.from_html_view_options(html_opts)
```

### См. также
* class [`ViewInfoOptions`](/viewer/python-net/groupdocs.viewer.options/viewinfooptions/)
