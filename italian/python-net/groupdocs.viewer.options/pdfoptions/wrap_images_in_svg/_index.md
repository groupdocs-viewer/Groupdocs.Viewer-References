---
title: "proprietà wrap_images_in_svg"
second_title: "Riferimenti API di GroupDocs.Viewer per Python via .NET"
description: "La proprietà che abilita l'incapsulamento di ogni immagine nell'output HTML in un tag SVG per migliorare la qualità dell'output."
type: docs
url: /it/python-net/groupdocs.viewer.options/pdfoptions/wrap_images_in_svg/
is_root: false
weight: 2100
---


## wrap_images_in_svg property

La proprietà che abilita l'incapsulamento di ogni immagine nell'output HTML in un tag SVG per migliorare la qualità dell'output.

Per impostazione predefinita, durante il rendering di file PDF e Page Layout in HTML, tutte le immagini vengono renderizzate come un'unica immagine PNG. L'immagine PNG renderizzata viene utilizzata come sfondo per il documento HTML di output.

Questa opzione è disponibile durante il rendering dei formati di file PDF e Page Layout in HTML con risorse incorporate ed esterne. Consente di avvolgere ogni immagine nel documento HTML di output in un tag SVG. Il valore predefinito è False.

Per un esempio di codice, vedere la documentazione.

### Definition:
```python
@property
def wrap_images_in_svg(self):
    ...
@wrap_images_in_svg.setter
def wrap_images_in_svg(self, value):
    ...
```

### Vedi anche
* class [`PdfOptions`](/viewer/python-net/groupdocs.viewer.options/pdfoptions/)
