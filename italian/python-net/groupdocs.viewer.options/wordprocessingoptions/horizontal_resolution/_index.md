---
title: "proprietà horizontal_resolution"
second_title: "Riferimenti API di GroupDocs.Viewer per Python via .NET"
description: "La risoluzione orizzontale per le immagini generate in punti per pollice."
type: docs
url: /it/python-net/groupdocs.viewer.options/wordprocessingoptions/horizontal_resolution/
is_root: false
weight: 2030
---


## horizontal_resolution property

La risoluzione orizzontale per le immagini generate in punti per pollice. Questa opzione è usata solo durante il rendering di documenti WordProcessing in formati PNG o JPEG.

Il valore predefinito è 96 DPI. Il valore minimo possibile è 72 DPI; il valore massimo possibile è 600 DPI. Se un valore specificato dall'utente è al di fuori di questi limiti, verrà applicato il limite più vicino (minimo o massimo).

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
* class [`WordProcessingOptions`](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/)
