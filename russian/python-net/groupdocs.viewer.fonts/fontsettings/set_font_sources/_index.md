---
title: "метод set_font_sources"
second_title: "Справочник API GroupDocs.Viewer для Python через .NET"
description: "Устанавливает источники для поиска TrueType‑шрифтов при рендеринге документов."
type: docs
url: /ru/python-net/groupdocs.viewer.fonts/fontsettings/set_font_sources/
is_root: false
weight: 1020
---


## set_font_sources {#font_sources}

Устанавливает источники для поиска TrueType‑шрифтов при рендеринге документов.

Метод принимает любую комбинацию отдельных объектов [`IFontSource`](/viewer/python-net/groupdocs.viewer.fonts/ifontsource/), списков этих объектов или их смеси; все входные данные преобразуются в один список перед применением. Строковые пути передаются как есть и не разбиваются на символы.

```python
def set_font_sources(cls, font_sources):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| font_sources | `list[IFontSource]` | Источники шрифтов. |

| Исключения | Описание |
| :- | :- |
| `ValueError` | Когда `font_sources` равно None. |

### Пример

```python
from groupdocs.viewer.fonts import FontSettings, FolderFontSource, SearchOption

src1 = FolderFontSource("C:/fonts/primary", SearchOption.ALL_FOLDERS)
src2 = FolderFontSource("C:/fonts/backup", SearchOption.TOP_FOLDER_ONLY)

# varargs
FontSettings.set_font_sources(src1, src2)
# один список
FontSettings.set_font_sources([src1, src2])
# несколько списков (уплощённые)
FontSettings.set_font_sources([src1], [src2])
# смешанные — также уплощённые
FontSettings.set_font_sources([src1, src2], src2)
```

### См. также
* class [`FontSettings`](/viewer/python-net/groupdocs.viewer.fonts/fontsettings/)
