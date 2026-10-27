---
title: "render_notes Eigenschaft"
second_title: "GroupDocs.Viewer für Python über .NET API-Referenzen"
description: "Die Eigenschaft ermöglicht das Rendern von Notizen und Anmerkungen für einige Formate."
type: docs
url: /de/python-net/groupdocs.viewer.options/baseviewoptions/render_notes/
is_root: false
weight: 2130
---


## render_notes property

Die Eigenschaft ermöglicht das Rendern von Notizen und Anmerkungen für einige Formate.

Einige Formate, wie Präsentationen oder Microsoft‑Project‑Dateien, können Notizen enthalten. Außerdem können PDF‑Dateien Popup‑Annotationen (Ballon‑Hinweise) besitzen, die standardmäßig ausgeblendet sind und in einem PDF‑Viewer nur sichtbar werden, wenn der Mauszeiger darauf zeigt. Standardmäßig rendert GroupDocs.Viewer solche Notizen und Annotationen nicht (`False`). Um dies zu erreichen, setzen Sie diese Eigenschaft auf `True`.

Für ein Codebeispiel siehe die Dokumentation.

### Definition:
```python
@property
def render_notes(self):
    ...
@render_notes.setter
def render_notes(self, value):
    ...
```

### Siehe auch
* class [`BaseViewOptions`](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/)
