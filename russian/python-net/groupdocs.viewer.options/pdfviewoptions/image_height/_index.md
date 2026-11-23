---
title: "Свойство image_height"
second_title: "Справочник API GroupDocs.Viewer для Python через .NET"
description: "Высота выходного изображения в пикселях."
type: docs
url: /ru/python-net/groupdocs.viewer.options/pdfviewoptions/image_height/
is_root: false
weight: 2010
---


## image_height property

Высота выходного изображения в пикселях.

Используйте это свойство, чтобы задать высоту выходного изображения (в пикселях). GroupDocs.Viewer применяет это свойство только при рендеринге отдельного изображения в HTML. Подробности см. в документации по адресу https://docs.groupdocs.com/viewer/net/set-image-size-limits-when-rendering-to-pdf/.

Если вы задаете это свойство, свойство [`PdfViewOptions.ImageMaxHeight`](/viewer/python-net/groupdocs.viewer.options/pdfviewoptions/image_max_height/) игнорируется.

### Definition:
```python
@property
def image_height(self):
    ...
@image_height.setter
def image_height(self, value):
    ...
```

### См. также
* class [`PdfViewOptions`](/viewer/python-net/groupdocs.viewer.options/pdfviewoptions/)
