---
title: "Метод serialize_to_css"
second_title: "Справочник API GroupDocs.Viewer для Python через .NET"
description: "Сериализует информацию о шрифте как правило @font-face и записывает её в указанный текстовый писатель."
type: docs
url: /ru/python-net/groupdocs.viewer.fonts/spreadsheetfontinfo/serialize_to_css/
is_root: false
weight: 1010
---


## serialize_to_css {#output}

Сериализует информацию о шрифте как правило @font-face и записывает её в указанный текстовый писатель.

```python
def serialize_to_css(self, output):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| output | `System.IO.TextWriter` | Объект, похожий на файл (например, `io.TextIOBase`), в который должны быть записаны сериализованные текстовые данные. |

**Returns:** None.

| Исключения | Описание |
| :- | :- |
| `ValueError` | Если `output` равно `None`. |

### См. также
* class [`SpreadsheetFontInfo`](/viewer/python-net/groupdocs.viewer.fonts/spreadsheetfontinfo/)
