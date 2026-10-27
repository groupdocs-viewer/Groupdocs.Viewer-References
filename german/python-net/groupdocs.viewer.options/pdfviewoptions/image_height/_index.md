---
title: "image_height Eigenschaft"
second_title: "GroupDocs.Viewer für Python über .NET API-Referenzen"
description: "Die Höhe eines Ausgabebildes in Pixeln."
type: docs
url: /de/python-net/groupdocs.viewer.options/pdfviewoptions/image_height/
is_root: false
weight: 2010
---


## image_height property

Die Höhe eines Ausgabebildes in Pixeln.

Verwenden Sie diese Eigenschaft, um die Ausgabe-Bildhöhe (in Pixeln) festzulegen. GroupDocs.Viewer wendet diese Eigenschaft nur beim Rendern eines einzelnen Bildes zu HTML an. Weitere Details finden Sie in der Dokumentation unter https://docs.groupdocs.com/viewer/net/set-image-size-limits-when-rendering-to-pdf/.

Wenn Sie diese Eigenschaft festlegen, wird die [`PdfViewOptions.ImageMaxHeight`](/viewer/python-net/groupdocs.viewer.options/pdfviewoptions/image_max_height/) Eigenschaft ignoriert.

### Definition:
```python
@property
def image_height(self):
    ...
@image_height.setter
def image_height(self, value):
    ...
```

### Siehe auch
* class [`PdfViewOptions`](/viewer/python-net/groupdocs.viewer.options/pdfviewoptions/)
