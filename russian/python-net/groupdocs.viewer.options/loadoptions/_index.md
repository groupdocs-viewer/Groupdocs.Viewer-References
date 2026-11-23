---
title: "Класс LoadOptions"
second_title: "Справочник API GroupDocs.Viewer для Python через .NET"
description: "Опции, используемые для открытия файла."
type: docs
url: /ru/python-net/groupdocs.viewer.options/loadoptions/
is_root: false
weight: 110
---


## LoadOptions class

Опции, используемые для открытия файла.

Тип LoadOptions раскрывает следующие члены:

### Конструкторы
| Конструктор | Описание |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.options/loadoptions/__init__/) | Инициализирует экземпляр класса [`LoadOptions`](/viewer/python-net/groupdocs.viewer.options/loadoptions/). |
| [__init__](/viewer/python-net/groupdocs.viewer.options/loadoptions/__init__/#file_type) | Инициализирует новый экземпляр LoadOptions. |

### Свойства
| Свойство | Описание |
| :- | :- |
| [detect_encoding](/viewer/python-net/groupdocs.viewer.options/loadoptions/detect_encoding/) | Свойство включает обнаружение кодировки для файлов [`FileType.txt`](/viewer/python-net/groupdocs.viewer/filetype/txt/), [`FileType.csv`](/viewer/python-net/groupdocs.viewer.filetype/csv/), и [`FileType.tsv`](/viewer/python-net/groupdocs.viewer.filetype/tsv/). |
| [encoding](/viewer/python-net/groupdocs.viewer.options/loadoptions/encoding/) | Кодировка, используемая при открытии текстовых файлов или электронных сообщений, таких как [`FileType.csv`](/viewer/python-net/groupdocs.viewer/filetype/csv/), [`FileType.txt`](/viewer/python-net/groupdocs.viewer/filetype/txt/), и [`FileType.msg`](/viewer/python-net/groupdocs.viewer/filetype/msg/). Значение по умолчанию — `utf-8`. |
| [file_type](/viewer/python-net/groupdocs.viewer.options/loadoptions/file_type/) | Тип открываемого файла. |
| [password](/viewer/python-net/groupdocs.viewer.options/loadoptions/password/) | Пароль для открытия зашифрованного файла. |
| [resource_loading_timeout](/viewer/python-net/groupdocs.viewer.options/loadoptions/resource_loading_timeout/) | Тайм‑аут для загрузки внешних ресурсов. |
| [skip_external_resources](/viewer/python-net/groupdocs.viewer.options/loadoptions/skip_external_resources/) | Свойство отключает загрузку всех внешних ресурсов, таких как изображения, кроме тех, которые перечислены в [`LoadOptions.whitelisted_resources`](/viewer/python-net/groupdocs.viewer.options/loadoptions/whitelisted_resources/). |
| [try_repair](/viewer/python-net/groupdocs.viewer.options/loadoptions/try_repair/) | Свойство позволяет GroupDocs.Viewer попытаться восстановить структурные повреждения в PDF‑документах. По умолчанию — False. |
| [whitelisted_resources](/viewer/python-net/groupdocs.viewer.options/loadoptions/whitelisted_resources/) | Список фрагментов URL, соответствующих внешним ресурсам, которые должны быть загружены, когда [`LoadOptions.skip_external_resources`](/viewer/python-net/groupdocs.viewer.options/loadoptions/skip_external_resources/) установлен в `True`. |

### Пример

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions, LoadOptions

load_options = LoadOptions()
load_options.password = "12345"

with Viewer("protected.docx", load_options) as viewer:
    viewer.view(HtmlViewOptions.for_embedded_resources("page_{0}.html"))
```

### См. также
* module [`groupdocs.viewer.options`](/viewer/python-net/groupdocs.viewer.options/)
