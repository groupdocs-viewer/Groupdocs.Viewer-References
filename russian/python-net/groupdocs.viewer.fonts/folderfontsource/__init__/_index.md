---
title: "__init__ конструктор"
second_title: "Справочник API GroupDocs.Viewer для Python через .NET"
description: "Инициализирует новый экземпляр FolderFontSource."
type: docs
url: /ru/python-net/groupdocs.viewer.fonts/folderfontsource/__init__/
is_root: false
weight: 10
---


## __init__ {#folder_path-search_option}

Инициализирует новый экземпляр [`FolderFontSource`](/viewer/python-net/groupdocs.viewer.fonts/folderfontsource/).

```python
def __init__(self, folder_path, search_option):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| folder_path | `str` | Путь к папке, содержащей шрифты TrueType. |
| search_option | `SearchOption` | Указывает, искать только в текущей папке или в текущей папке и всех вложенных подпапках. |

| Исключения | Описание |
| :- | :- |
| `ValueError` | Если `folder_path` равно None. |
| `FileNotFoundError` | Если указанный в `folder_path` путь не может быть найден. |

### Пример

```python
from groupdocs.viewer.fonts import FolderFontSource, SearchOption, FontSettings

src1 = FolderFontSource("C:/fonts/primary", SearchOption.ALL_FOLDERS)
src2 = FolderFontSource("C:/fonts/backup", SearchOption.TOP_FOLDER_ONLY)

# Зарегистрировать источники шрифтов для рендеринга
FontSettings.set_font_sources(src1, src2)

# После завершения сбросьте, чтобы избежать утечки источников
FontSettings.reset_font_sources()
```

### См. также
* class [`FolderFontSource`](/viewer/python-net/groupdocs.viewer.fonts/folderfontsource/)
