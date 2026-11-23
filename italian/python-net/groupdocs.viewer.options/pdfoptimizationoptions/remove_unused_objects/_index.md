---
title: "proprietà remove_unused_objects"
second_title: "Riferimenti API di GroupDocs.Viewer per Python via .NET"
description: "La proprietà rimuove gli oggetti inutilizzati (orfani) da un file PDF."
type: docs
url: /it/python-net/groupdocs.viewer.options/pdfoptimizationoptions/remove_unused_objects/
is_root: false
weight: 2090
---


## remove_unused_objects property

La proprietà rimuove gli oggetti inutilizzati (orfani) da un file PDF.

Questi oggetti sono inseriti nel documento PDF ma non sono referenziati dai dizionari delle risorse di alcuna pagina e quindi non sono utilizzati. Attivare questa proprietà (`True`) ridurrà le dimensioni del documento PDF di output. Per impostazione predefinita è disabilitata (`False`).

### Definition:
```python
@property
def remove_unused_objects(self):
    ...
@remove_unused_objects.setter
def remove_unused_objects(self, value):
    ...
```

### Vedi anche
* class [`PdfOptimizationOptions`](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/)
