---
title: "Свойство vertical_resolution"
second_title: "Справочник API GroupDocs.Viewer для Python через .NET"
description: "Вертикальное разрешение генерируемых изображений в точках на дюйм, используется только при рендеринге документов WordProcessing в форматы PNG или JPEG."
type: docs
url: /ru/python-net/groupdocs.viewer.options/wordprocessingoptions/vertical_resolution/
is_root: false
weight: 2120
---


## vertical_resolution property

Вертикальное разрешение генерируемых изображений в точках на дюйм, используется только при рендеринге документов WordProcessing в форматы PNG или JPEG.

Значение по умолчанию — 96 DPI.

Минимально возможное значение — 72 DPI, а максимально возможное значение — 600 DPI. Если указанное пользователем значение выходит за эти пределы, будет применено ближайшее ограничение.

### Definition:
```python
@property
def vertical_resolution(self):
    ...
@vertical_resolution.setter
def vertical_resolution(self, value):
    ...
```

### См. также
* class [`WordProcessingOptions`](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/)
