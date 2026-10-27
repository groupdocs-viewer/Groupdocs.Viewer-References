---
title: "proprietà enable_layered_rendering"
second_title: "Riferimenti API di GroupDocs.Viewer per Python via .NET"
description: "La proprietà abilita il rendering di testo e grafica nell'ordine Z del documento PDF originale durante il rendering in HTML."
type: docs
url: /it/python-net/groupdocs.viewer.options/pdfoptions/enable_layered_rendering/
is_root: false
weight: 2050
---


## enable_layered_rendering property

La proprietà abilita il rendering di testo e grafica nell'ordine Z del documento PDF originale durante il rendering in HTML.

Per impostazione predefinita, GroupDocs.Viewer renderizza testo e grafica come un unico livello in HTML. Questa opzione consente di disporre gli oggetti nello stesso ordine del file di origine. Il valore predefinito è False.

Per un esempio di codice, vedere la documentazione.

### Definition:
```python
@property
def enable_layered_rendering(self):
    ...
@enable_layered_rendering.setter
def enable_layered_rendering(self, value):
    ...
```

### Vedi anche
* class [`PdfOptions`](/viewer/python-net/groupdocs.viewer.options/pdfoptions/)
