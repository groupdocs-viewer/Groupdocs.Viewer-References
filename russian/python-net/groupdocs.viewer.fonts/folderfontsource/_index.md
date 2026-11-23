---
title: "FolderFontSource класс"
second_title: "Справочник API GroupDocs.Viewer для Python через .NET"
description: "Представляет папку, содержащую TrueType‑шрифты."
type: docs
url: /ru/python-net/groupdocs.viewer.fonts/folderfontsource/
is_root: false
weight: 10
---


## FolderFontSource class

Представляет папку, содержащую TrueType‑шрифты.

Тип FolderFontSource раскрывает следующие члены:

### Конструкторы
| Конструктор | Описание |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.fonts/folderfontsource/__init__/#folder_path-search_option) | Инициализирует новый экземпляр [`FolderFontSource`](/viewer/python-net/groupdocs.viewer.fonts/folderfontsource/). |

### Методы
| Метод | Описание |
| :- | :- |
| [equals](/viewer/python-net/groupdocs.viewer.fonts/folderfontsource/equals/#other) | Определяет, является ли текущий FolderFontSource тем же, что и указанный объект FolderFontSource. |
| [equals](/viewer/python-net/groupdocs.viewer.fonts/folderfontsource/equals/#obj) | Определяет, является ли текущий FolderFontSource тем же, что и указанный объект. |
| [equals_folder_font_source](/viewer/python-net/groupdocs.viewer.fonts/folderfontsource/equals_folder_font_source/) |  |
| [equals_object](/viewer/python-net/groupdocs.viewer.fonts/folderfontsource/equals_object/) |  |
| [get_hash_code](/viewer/python-net/groupdocs.viewer.fonts/folderfontsource/get_hash_code/) | Возвращает хеш-код текущего объекта [`FolderFontSource`](/viewer/python-net/groupdocs.viewer.fonts/folderfontsource/). |
| [to_string](/viewer/python-net/groupdocs.viewer.fonts/folderfontsource/to_string/) | Возвращает строку, представляющую текущий объект. |

### Свойства
| Свойство | Описание |
| :- | :- |
| [folder_path](/viewer/python-net/groupdocs.viewer.fonts/folderfontsource/folder_path/) | Путь к папке, содержащей шрифты TrueType. |
| [search_option](/viewer/python-net/groupdocs.viewer.fonts/folderfontsource/search_option/) | Параметр поиска, указывающий, искать ли только в текущей папке или в текущей папке и всех подпапках. |

### Пример

```python
from groupdocs.viewer.fonts import FolderFontSource, SearchOption

# Создайте источник шрифтов, который ищет во всех подпапках.
src = FolderFontSource("C:/fonts/primary", SearchOption.ALL_FOLDERS)
```

### См. также
* module [`groupdocs.viewer.fonts`](/viewer/python-net/groupdocs.viewer.fonts/)
