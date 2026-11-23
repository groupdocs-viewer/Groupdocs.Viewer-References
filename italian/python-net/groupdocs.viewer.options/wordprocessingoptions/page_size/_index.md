---
title: "proprietà page_size"
second_title: "Riferimenti API di GroupDocs.Viewer per Python via .NET"
description: "La dimensione della pagina di output."
type: docs
url: /it/python-net/groupdocs.viewer.options/wordprocessingoptions/page_size/
is_root: false
weight: 2060
---


## page_size property

La dimensione della pagina di output.

Il valore predefinito è `PageSize.Unspecified`, il che significa che viene utilizzata una dimensione di pagina impostata nelle impostazioni della pagina (Impostazione pagina).

Durante il rendering di file HTM e HTML la dimensione di pagina predefinita è impostata a Letter 792 x 612 punti.

Di conseguenza, parte del contenuto potrebbe non adattarsi al riquadro della pagina.

Imposta una dimensione di pagina più grande, ad esempio `PageSize.A3`, per adattare il contenuto.

### Definition:
```python
@property
def page_size(self):
    ...
@page_size.setter
def page_size(self, value):
    ...
```

### Vedi anche
* class [`WordProcessingOptions`](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/)
