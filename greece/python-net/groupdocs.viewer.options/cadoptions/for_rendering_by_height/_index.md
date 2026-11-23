---
title: "for_rendering_by_height μέθοδος"
second_title: "GroupDocs.Viewer για Python μέσω .NET Αναφορές API"
description: "Αρχικοποιεί ένα αντικείμενο CadOptions για απόδοση με βάση το ύψος."
type: docs
url: /el/python-net/groupdocs.viewer.options/cadoptions/for_rendering_by_height/
is_root: false
weight: 1010
---


## for_rendering_by_height {#height}

Αρχικοποιεί ένα αντικείμενο CadOptions για απόδοση με βάση το ύψος.

Για παράδειγμα κώδικα, δείτε την τεκμηρίωση.

```python
def for_rendering_by_height(cls, height):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| height | `int` | Το ύψος του αποτελέσματος εξόδου (σε εικονοστοιχεία). |

**Returns:** CadOptions: New instance configured for rendering by height.

| Αναφέρει | Περιγραφή |
| :- | :- |
| `ValueError` | Όταν το `height` είναι μικρότερο ή ίσο με το μηδέν. |

### Παράδειγμα

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PngViewOptions, CadOptions

def render_by_height():
    with Viewer("sample.dwg") as viewer:
        png_options = PngViewOptions("output_by_height.png")
        png_options.cad_options = CadOptions.for_rendering_by_height(1500)
        viewer.view(png_options)
```

### Δείτε επίσης
* class [`CadOptions`](/viewer/python-net/groupdocs.viewer.options/cadoptions/)
