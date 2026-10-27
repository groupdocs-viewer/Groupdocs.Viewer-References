---
title: "render_notes eigenschap"
second_title: "GroupDocs.Viewer voor Python via .NET API-referenties"
description: "De eigenschap schakelt het renderen van notities en annotaties voor sommige formaten in."
type: docs
url: /nl/python-net/groupdocs.viewer.options/baseviewoptions/render_notes/
is_root: false
weight: 2130
---


## render_notes property

De eigenschap schakelt het renderen van notities en annotaties voor sommige formaten in.

Sommige formaten, zoals presentaties of Microsoft Project‑bestanden, kunnen notities bevatten. Ook kunnen PDF‑bestanden pop‑upannotaties (ballon‑tips) hebben die standaard verborgen zijn en alleen zichtbaar in een PDF‑viewer wanneer de muiscursor erover wordt bewogen. Standaard rendert GroupDocs.Viewer dergelijke notities en annotaties niet (`False`). Om dit te doen, stelt u deze eigenschap in op `True`.

Voor een codevoorbeeld, zie de documentatie.

### Definition:
```python
@property
def render_notes(self):
    ...
@render_notes.setter
def render_notes(self, value):
    ...
```

### Zie ook
* class [`BaseViewOptions`](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/)
