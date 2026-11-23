---
title: "image_height-egenskap"
second_title: "GroupDocs.Viewer för Python via .NET API-referenser"
description: "Höjden på en utdata bild i pixlar."
type: docs
url: /sv/python-net/groupdocs.viewer.options/pdfviewoptions/image_height/
is_root: false
weight: 2010
---


## image_height property

Höjden på en utdata bild i pixlar.

Använd den här egenskapen för att ange bildhöjden för utdata (i pixlar). GroupDocs.Viewer tillämpar denna egenskap endast när en enda bild renderas till HTML. För detaljer, se dokumentationen på https://docs.groupdocs.com/viewer/net/set-image-size-limits-when-rendering-to-pdf/.

Om du anger denna egenskap, ignoreras egenskapen [`PdfViewOptions.ImageMaxHeight`](/viewer/python-net/groupdocs.viewer.options/pdfviewoptions/image_max_height/).

### Definition:
```python
@property
def image_height(self):
    ...
@image_height.setter
def image_height(self, value):
    ...
```

### Se även
* class [`PdfViewOptions`](/viewer/python-net/groupdocs.viewer.options/pdfviewoptions/)
