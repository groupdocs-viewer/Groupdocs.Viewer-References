---
title: "Свойство vertical_resolution"
second_title: "Справочник API GroupDocs.Viewer для Python через .NET"
description: "Вертикальное разрешение генерируемых изображений в точках на дюйм."
type: docs
url: /ru/python-net/groupdocs.viewer.options/spreadsheetoptions/vertical_resolution/
is_root: false
weight: 2160
---


## vertical_resolution property

Вертикальное разрешение генерируемых изображений в точках на дюйм. Этот параметр используется только при отображении электронных таблиц в форматах PNG или JPEG.

Значение по умолчанию — 96 DPI. Минимальное возможное значение — 72 DPI; максимальное возможное значение — 600 DPI. Если пользователь задает значение за пределами этих границ, будет применено ближайшее допустимое значение.

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
* class [`SpreadsheetOptions`](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/)
