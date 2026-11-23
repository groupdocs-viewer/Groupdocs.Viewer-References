---
title: "proprietà image_height"
second_title: "Riferimenti API di GroupDocs.Viewer per Python via .NET"
description: "L'altezza di un'immagine di output in pixel."
type: docs
url: /it/python-net/groupdocs.viewer.options/pdfviewoptions/image_height/
is_root: false
weight: 2010
---


## image_height property

L'altezza di un'immagine di output in pixel.

Utilizza questa proprietà per impostare l'altezza dell'immagine di output (in pixel). GroupDocs.Viewer applica questa proprietà solo durante il rendering di un'unica immagine in HTML. Per ulteriori dettagli, consulta la documentazione all'indirizzo https://docs.groupdocs.com/viewer/net/set-image-size-limits-when-rendering-to-pdf/.

Se imposti questa proprietà, la proprietà [`PdfViewOptions.ImageMaxHeight`](/viewer/python-net/groupdocs.viewer.options/pdfviewoptions/image_max_height/) viene ignorata.

### Definition:
```python
@property
def image_height(self):
    ...
@image_height.setter
def image_height(self, value):
    ...
```

### Vedi anche
* class [`PdfViewOptions`](/viewer/python-net/groupdocs.viewer.options/pdfviewoptions/)
