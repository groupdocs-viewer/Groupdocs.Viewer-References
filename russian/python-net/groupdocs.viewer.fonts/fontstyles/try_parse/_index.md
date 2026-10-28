---
title: "метод try_parse"
second_title: "Справочник API GroupDocs.Viewer для Python через .NET"
description: "Пытается разобрать указанную строку как имя стиля шрифта."
type: docs
url: /ru/python-net/groupdocs.viewer.fonts/fontstyles/try_parse/
is_root: false
weight: 1060
---


## try_parse {#style-parsed}

Пытается разобрать указанную строку как имя стиля шрифта.

```python
def try_parse(cls, style, parsed):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| style | `str` | Строка, которую следует разобрать как стиль шрифта. |
| parsed | `FontStyles` | Разобранный стиль шрифта при успехе или `FontStyles.Regular` при неудаче. |

**Returns:** bool: True if string was successfully parsed as a correct font style; False otherwise.

### См. также
* class [`FontStyles`](/viewer/python-net/groupdocs.viewer.fonts/fontstyles/)
