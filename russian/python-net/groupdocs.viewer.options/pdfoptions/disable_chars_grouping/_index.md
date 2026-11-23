---
title: "свойство disable_chars_grouping"
second_title: "Справочник API GroupDocs.Viewer для Python через .NET"
description: "Свойство отключает группировку символов для точного позиционирования символов во время рендеринга страницы."
type: docs
url: /ru/python-net/groupdocs.viewer.options/pdfoptions/disable_chars_grouping/
is_root: false
weight: 2010
---


## disable_chars_grouping property

Свойство отключает группировку символов для точного позиционирования символов во время рендеринга страницы.

При конвертации PDF‑файлов GroupDocs.Viewer объединяет отдельные символы в слова для повышения производительности рендеринга. Если ваш документ содержит иероглифы или специальные символы, вы можете запретить группировку символов, чтобы обеспечить более точный макет. Значение по умолчанию — False.

Для примера кода см. документацию.

### Definition:
```python
@property
def disable_chars_grouping(self):
    ...
@disable_chars_grouping.setter
def disable_chars_grouping(self, value):
    ...
```

### См. также
* class [`PdfOptions`](/viewer/python-net/groupdocs.viewer.options/pdfoptions/)
