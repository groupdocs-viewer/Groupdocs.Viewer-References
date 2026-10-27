---
title: "image_height eigenschap"
second_title: "GroupDocs.Viewer voor Python via .NET API-referenties"
description: "De hoogte van een uitvoerafbeelding in pixels."
type: docs
url: /nl/python-net/groupdocs.viewer.options/pdfviewoptions/image_height/
is_root: false
weight: 2010
---


## image_height property

De hoogte van een uitvoerafbeelding in pixels.

Gebruik deze eigenschap om de uitvoerafbeeldingshoogte (in pixels) in te stellen. GroupDocs.Viewer past deze eigenschap alleen toe bij het renderen van een enkele afbeelding naar HTML. Zie voor details de documentatie op https://docs.groupdocs.com/viewer/net/set-image-size-limits-when-rendering-to-pdf/.

Als je deze eigenschap instelt, wordt de eigenschap [`PdfViewOptions.ImageMaxHeight`](/viewer/python-net/groupdocs.viewer.options/pdfviewoptions/image_max_height/) genegeerd.

### Definition:
```python
@property
def image_height(self):
    ...
@image_height.setter
def image_height(self, value):
    ...
```

### Zie ook
* class [`PdfViewOptions`](/viewer/python-net/groupdocs.viewer.options/pdfviewoptions/)
