---
title: "disable_chars_grouping Eigenschaft"
second_title: "GroupDocs.Viewer für Python über .NET API-Referenzen"
description: "Die Eigenschaft deaktiviert die Symbolgruppierung für eine präzise Symbolpositionierung während der Seitenrenderung."
type: docs
url: /de/python-net/groupdocs.viewer.options/pdfoptions/disable_chars_grouping/
is_root: false
weight: 2010
---


## disable_chars_grouping property

Die Eigenschaft deaktiviert die Symbolgruppierung für eine präzise Symbolpositionierung während der Seitenrenderung.

Beim Konvertieren von PDF-Dateien gruppiert GroupDocs.Viewer einzelne Zeichen zu Wörtern, um die Rendering‑Leistung zu verbessern. Wenn Ihr Dokument Hieroglyphen oder Sonderzeichen enthält, möchten Sie möglicherweise die Zeichen­gruppierung verbieten, um ein präziseres Layout zu gewährleisten. Der Standardwert ist False.

Für ein Code‑Beispiel siehe die Dokumentation.

### Definition:
```python
@property
def disable_chars_grouping(self):
    ...
@disable_chars_grouping.setter
def disable_chars_grouping(self, value):
    ...
```

### Siehe auch
* class [`PdfOptions`](/viewer/python-net/groupdocs.viewer.options/pdfoptions/)
