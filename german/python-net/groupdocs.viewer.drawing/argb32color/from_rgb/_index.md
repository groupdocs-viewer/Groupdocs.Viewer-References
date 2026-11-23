---
title: "from_rgb Methode"
second_title: "GroupDocs.Viewer für Python über .NET API-Referenzen"
description: "Erstellt einen Argb32Color‑Wert aus angegebenen Rot‑, Grün‑ und Blau‑Kanälen, wobei der Alpha‑Kanal vollständig undurchsichtig gesetzt wird."
type: docs
url: /de/python-net/groupdocs.viewer.drawing/argb32color/from_rgb/
is_root: false
weight: 1090
---


## from_rgb {#red-green-blue}

Erstellt einen Argb32Color‑Wert aus angegebenen Rot‑, Grün‑ und Blau‑Kanälen, wobei der Alpha‑Kanal vollständig undurchsichtig gesetzt wird.

```python
def from_rgb(cls, red, green, blue):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| red | `int` | Rot‑Kanalwert. |
| green | `int` | Grün‑Kanalwert. |
| blue | `int` | Blauer Kanalwert. |

**Returns:** Argb32Color: New Argb32Color value.

### Beispiel

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions
from groupdocs.viewer.drawing import Argb32Color

with Viewer("sample.dwg") as viewer:
    view_options = PdfViewOptions("output.pdf")
    view_options.cad_options.background_color = Argb32Color.from_rgb(255, 255, 0)  # yellow
    viewer.view(view_options)
```

### Siehe auch
* class [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/)
