---
title: "Класс OutlookOptions"
second_title: "Справочник API GroupDocs.Viewer для Python через .NET"
description: "Содержит опции для рендеринга файлов данных Outlook."
type: docs
url: /ru/python-net/groupdocs.viewer.options/outlookoptions/
is_root: false
weight: 130
---


## OutlookOptions class

Содержит опции для рендеринга файлов данных Outlook.

Подробности см. в документации GroupDocs.

Тип OutlookOptions раскрывает следующие члены:

### Конструкторы
| Конструктор | Описание |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.options/outlookoptions/__init__/) |  |

### Свойства
| Свойство | Описание |
| :- | :- |
| [address_filter](/viewer/python-net/groupdocs.viewer.options/outlookoptions/address_filter/) | Электронный адрес, используемый для фильтрации сообщений по отправителю или получателю. |
| [folder](/viewer/python-net/groupdocs.viewer.options/outlookoptions/folder/) | Имя папки (например, Inbox, Sent Item или Deleted Items), которую нужно отобразить. |
| [max_items_in_folder](/viewer/python-net/groupdocs.viewer.options/outlookoptions/max_items_in_folder/) | Максимальное количество сообщений или элементов, которые могут быть отображены из одной папки. |
| [text_filter](/viewer/python-net/groupdocs.viewer.options/outlookoptions/text_filter/) | Ключевые слова, используемые для фильтрации сообщений. |

### Пример

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

def render_outlook():
    with Viewer("sample.pst") as viewer:
        view_options = HtmlViewOptions.for_embedded_resources(
            "outlook.html"
        )
        # Ограничьте количество элементов, отображаемых в каждой папке.
        view_options.outlook_options.max_items_in_folder = 30
        viewer.view(view_options)
```

### См. также
* module [`groupdocs.viewer.options`](/viewer/python-net/groupdocs.viewer.options/)
