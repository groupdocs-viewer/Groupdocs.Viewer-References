---
title: "proprietà horizontal_resolution"
second_title: "Riferimenti API di GroupDocs.Viewer per Python via .NET"
description: "La risoluzione orizzontale per le immagini generate in punti per pollice."
type: docs
url: /it/python-net/groupdocs.viewer.options/spreadsheetoptions/horizontal_resolution/
is_root: false
weight: 2050
---


## horizontal_resolution property

La risoluzione orizzontale per le immagini generate in punti per pollice. Questa opzione è utilizzata solo durante il rendering dei fogli di calcolo in formato PNG o JPEG.

Il valore predefinito è 96 DPI. Il valore minimo possibile è 72 DPI, il valore massimo possibile è 600 DPI. Se un valore specificato dall'utente è fuori da questi limiti, verrà applicato il valore minimo o massimo possibile.

### Definition:
```python
@property
def horizontal_resolution(self):
    ...
@horizontal_resolution.setter
def horizontal_resolution(self, value):
    ...
```

### Vedi anche
* class [`SpreadsheetOptions`](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/)
