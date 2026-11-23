---
title: "disable_copy_protection Eigenschaft"
second_title: "GroupDocs.Viewer für Python über .NET API-Referenzen"
description: "Die Eigenschaft deaktiviert den Kopierschutz für Inhalte beim Rendern zu HTML."
type: docs
url: /de/python-net/groupdocs.viewer.options/pdfoptions/disable_copy_protection/
is_root: false
weight: 2020
---


## disable_copy_protection property

Die Eigenschaft deaktiviert den Kopierschutz für Inhalte beim Rendern zu HTML.

Beim Rendern von PDF-Dateien mit Schutz gegen das Kopieren von Text und Bildern nach HTML fügt GroupDocs.Viewer ein `inert` HTML‑Attribut zum HTML‑BODY‑Tag hinzu. Der Standardwert ist `False`, was bedeutet, dass das `inert`‑Attribut nur hinzugefügt wird, wenn das PDF‑Dokument geschützt ist.

Für ein Codebeispiel siehe die Dokumentation.

### Definition:
```python
@property
def disable_copy_protection(self):
    ...
@disable_copy_protection.setter
def disable_copy_protection(self, value):
    ...
```

### Siehe auch
* class [`PdfOptions`](/viewer/python-net/groupdocs.viewer.options/pdfoptions/)
