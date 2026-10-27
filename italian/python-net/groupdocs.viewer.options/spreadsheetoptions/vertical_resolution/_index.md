---
title: "proprietà vertical_resolution"
second_title: "Riferimenti API di GroupDocs.Viewer per Python via .NET"
description: "La risoluzione verticale per le immagini generate in punti per pollice."
type: docs
url: /it/python-net/groupdocs.viewer.options/spreadsheetoptions/vertical_resolution/
is_root: false
weight: 2160
---


## vertical_resolution property

La risoluzione verticale per le immagini generate in punti per pollice. Questa opzione è utilizzata solo durante il rendering dei fogli di calcolo in formati PNG o JPEG.

Il valore predefinito è 96 DPI. Il valore minimo possibile è 72 DPI; il valore massimo possibile è 600 DPI. Se un valore specificato dall'utente è al di fuori di questi limiti, verrà applicato il limite più vicino.

### Definition:
```python
@property
def vertical_resolution(self):
    ...
@vertical_resolution.setter
def vertical_resolution(self, value):
    ...
```

### Vedi anche
* class [`SpreadsheetOptions`](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/)
