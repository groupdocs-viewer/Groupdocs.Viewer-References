---
title: "proprietà disable_copy_protection"
second_title: "Riferimenti API di GroupDocs.Viewer per Python via .NET"
description: "La proprietà disabilita la protezione contro la copia del contenuto durante il rendering in HTML."
type: docs
url: /it/python-net/groupdocs.viewer.options/pdfoptions/disable_copy_protection/
is_root: false
weight: 2020
---


## disable_copy_protection property

La proprietà disabilita la protezione contro la copia del contenuto durante il rendering in HTML.

Durante il rendering di file PDF con protezione contro la copia di testo e immagini in HTML, GroupDocs.Viewer aggiunge un attributo HTML `inert` al tag BODY dell'HTML. Il valore predefinito è `False`, il che significa che l'attributo `inert` viene aggiunto solo se il documento PDF è protetto.

Per un esempio di codice, vedere la documentazione.

### Definition:
```python
@property
def disable_copy_protection(self):
    ...
@disable_copy_protection.setter
def disable_copy_protection(self, value):
    ...
```

### Vedi anche
* class [`PdfOptions`](/viewer/python-net/groupdocs.viewer.options/pdfoptions/)
