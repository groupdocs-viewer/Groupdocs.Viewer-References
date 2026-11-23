---
title: "proprietà render_original_page_size"
second_title: "Riferimenti API di GroupDocs.Viewer per Python via .NET"
description: "La dimensione della pagina di output è impostata per corrispondere alla dimensione della pagina del documento PDF sorgente."
type: docs
url: /it/python-net/groupdocs.viewer.options/pdfoptions/render_original_page_size/
is_root: false
weight: 2080
---


## render_original_page_size property

La dimensione della pagina di output è impostata per corrispondere alla dimensione della pagina del documento PDF sorgente.

Per impostazione predefinita, GroupDocs.Viewer calcola la dimensione della pagina immagine di output per una migliore qualità di rendering. Abilitare questa opzione per garantire che le pagine di output abbiano la stessa dimensione della pagina del documento PDF di origine (in pixel). Il valore predefinito è False.

Questa opzione è disponibile per il rendering in formati PNG o JPG.

Per un esempio di codice, vedere la documentazione.

### Definition:
```python
@property
def render_original_page_size(self):
    ...
@render_original_page_size.setter
def render_original_page_size(self, value):
    ...
```

### Vedi anche
* class [`PdfOptions`](/viewer/python-net/groupdocs.viewer.options/pdfoptions/)
