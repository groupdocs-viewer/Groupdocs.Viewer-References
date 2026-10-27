---
title: "page_size Eigenschaft"
second_title: "GroupDocs.Viewer für Python über .NET API-Referenzen"
description: "Die Größe der Ausgabeseite."
type: docs
url: /de/python-net/groupdocs.viewer.options/wordprocessingoptions/page_size/
is_root: false
weight: 2060
---


## page_size property

Die Größe der Ausgabeseite.

Der Standardwert ist `PageSize.Unspecified`, was bedeutet, dass eine in den Seiteneinstellungen (Page Setup) festgelegte Seitengröße verwendet wird.

Beim Rendern von HTM- und HTML-Dateien wird die Standardseitengröße auf Letter 792 x 612 Punkte gesetzt.

Infolgedessen passt ein Teil des Inhalts möglicherweise nicht in den Seitenrahmen.

Legen Sie eine größere Seitengröße fest, z. B. `PageSize.A3`, um den Inhalt anzupassen.

### Definition:
```python
@property
def page_size(self):
    ...
@page_size.setter
def page_size(self, value):
    ...
```

### Siehe auch
* class [`WordProcessingOptions`](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/)
