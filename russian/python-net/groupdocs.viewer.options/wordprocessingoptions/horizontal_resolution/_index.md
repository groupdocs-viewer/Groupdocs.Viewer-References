---
title: "свойство horizontal_resolution"
second_title: "Справочник API GroupDocs.Viewer для Python через .NET"
description: "Горизонтальное разрешение генерируемых изображений в точках на дюйм."
type: docs
url: /ru/python-net/groupdocs.viewer.options/wordprocessingoptions/horizontal_resolution/
is_root: false
weight: 2030
---


## horizontal_resolution property

Горизонтальное разрешение генерируемых изображений в точках на дюйм. Эта опция используется только при рендеринге документов WordProcessing в форматы PNG или JPEG.

Значение по умолчанию — 96 DPI. Минимально возможное значение — 72 DPI; максимально возможное значение — 600 DPI. Если указанное пользователем значение выходит за эти пределы, будет применено ближайшее ограничение (минимальное или максимальное).

### Definition:
```python
@property
def horizontal_resolution(self):
    ...
@horizontal_resolution.setter
def horizontal_resolution(self, value):
    ...
```

### См. также
* class [`WordProcessingOptions`](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/)
