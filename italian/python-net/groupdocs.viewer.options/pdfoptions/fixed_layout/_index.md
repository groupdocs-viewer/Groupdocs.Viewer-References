---
title: "proprietà fixed_layout"
second_title: "Riferimenti API di GroupDocs.Viewer per Python via .NET"
description: "L'opzione layout fisso abilita il rendering di documenti PDF ed EPUB in HTML con un layout fisso."
type: docs
url: /it/python-net/groupdocs.viewer.options/pdfoptions/fixed_layout/
is_root: false
weight: 2060
---


## fixed_layout property

L'opzione layout fisso abilita il rendering di documenti PDF ed EPUB in HTML con un layout fisso.

I documenti PDF ed EPUB vengono inizialmente renderizzati in HTML con un layout fisso per mantenere l'aspetto del documento originale. Questo layout fisso significa che tutti gli elementi HTML hanno posizioni precise all'interno di un contenitore con dimensioni impostate. Ridimensionare la finestra del browser non influisce sulla posizione e sulle dimensioni degli elementi nel documento.

Questa opzione è disponibile solo durante il rendering in HTML. Il valore predefinito è `True`. Per renderizzare con un layout fluido, impostare questa proprietà a `False`.

Durante il rendering con layout fluido, le immagini vengono ignorate. Utilizzare il layout fluido quando si renderizzano documenti PDF con contenuto testuale.

Per un esempio di codice, vedere la documentazione.

### Definition:
```python
@property
def fixed_layout(self):
    ...
@fixed_layout.setter
def fixed_layout(self, value):
    ...
```

### Vedi anche
* class [`PdfOptions`](/viewer/python-net/groupdocs.viewer.options/pdfoptions/)
