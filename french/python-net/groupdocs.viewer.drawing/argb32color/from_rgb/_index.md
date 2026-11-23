---
title: "méthode from_rgb"
second_title: "Références API de GroupDocs.Viewer pour Python via .NET"
description: "Crée une valeur Argb32Color à partir des canaux Rouge, Vert, Bleu spécifiés, le canal Alpha étant réglé sur totalement opaque."
type: docs
url: /fr/python-net/groupdocs.viewer.drawing/argb32color/from_rgb/
is_root: false
weight: 1090
---


## from_rgb {#red-green-blue}

Crée une valeur Argb32Color à partir des canaux Rouge, Vert, Bleu spécifiés, le canal Alpha étant réglé sur totalement opaque.

```python
def from_rgb(cls, red, green, blue):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| red | `int` | Valeur du canal rouge. |
| green | `int` | Valeur du canal vert. |
| blue | `int` | Valeur du canal bleu. |

**Returns:** Argb32Color: New Argb32Color value.

### Exemple

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions
from groupdocs.viewer.drawing import Argb32Color

with Viewer("sample.dwg") as viewer:
    view_options = PdfViewOptions("output.pdf")
    view_options.cad_options.background_color = Argb32Color.from_rgb(255, 255, 0)  # yellow
    viewer.view(view_options)
```

### Voir aussi
* class [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/)
