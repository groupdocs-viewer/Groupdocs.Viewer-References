---
title: "remove_unused_objects Eigenschaft"
second_title: "GroupDocs.Viewer für Python über .NET API-Referenzen"
description: "Die Eigenschaft entfernt ungenutzte (verwaiste) Objekte aus einer PDF-Datei."
type: docs
url: /de/python-net/groupdocs.viewer.options/pdfoptimizationoptions/remove_unused_objects/
is_root: false
weight: 2090
---


## remove_unused_objects property

Die Eigenschaft entfernt ungenutzte (verwaiste) Objekte aus einer PDF-Datei.

Diese Objekte befinden sich im PDF‑Dokument, werden jedoch von keinen Ressourcen‑Wörterbüchern einer Seite referenziert und sind daher überhaupt nicht verwendet. Das Aktivieren dieser Eigenschaft (`True`) verringert die Größe des ausgegebenen PDF‑Dokuments. Standardmäßig ist sie deaktiviert (`False`).

### Definition:
```python
@property
def remove_unused_objects(self):
    ...
@remove_unused_objects.setter
def remove_unused_objects(self, value):
    ...
```

### Siehe auch
* class [`PdfOptimizationOptions`](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/)
