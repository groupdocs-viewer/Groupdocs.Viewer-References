---
title: "Класс FontSettings"
second_title: "Справочник API GroupDocs.Viewer для Python через .NET"
description: "Предоставляет методы для работы с источниками при поиске TrueType‑шрифтов."
type: docs
url: /ru/python-net/groupdocs.viewer.fonts/fontsettings/
is_root: false
weight: 30
---


## FontSettings class

Предоставляет методы для работы с источниками при поиске TrueType‑шрифтов.

Тип FontSettings раскрывает следующие члены:

### Методы
| Метод | Описание |
| :- | :- |
| [reset_font_sources](/viewer/python-net/groupdocs.viewer.fonts/fontsettings/reset_font_sources/) | Сбрасывает ранее установленные источники шрифтов. |
| [set_font_sources](/viewer/python-net/groupdocs.viewer.fonts/fontsettings/set_font_sources/#font_sources) | Устанавливает источники для поиска TrueType‑шрифтов при рендеринге документов. |

### Пример

```python
from groupdocs.viewer.fonts import FontSettings, FolderFontSource, SearchOption

src1 = FolderFontSource("C:/fonts/primary", SearchOption.ALL_FOLDERS)
src2 = FolderFontSource("C:/fonts/backup", SearchOption.TOP_FOLDER_ONLY)

# Устанавливает источники шрифтов с использованием различных форм аргументов (внутри уплощаются).
FontSettings.set_font_sources(src1, src2)          # varargs
FontSettings.set_font_sources([src1, src2])        # single list
FontSettings.set_font_sources([src1], [src2])      # multiple lists (flattened)
FontSettings.set_font_sources([src1, src2], src2)  # mixed — also flattened

# Очистить все зарегистрированные источники шрифтов.
FontSettings.reset_font_sources()
```

### См. также
* module [`groupdocs.viewer.fonts`](/viewer/python-net/groupdocs.viewer.fonts/)
