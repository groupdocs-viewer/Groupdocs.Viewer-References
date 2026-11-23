---
title: "for_rendering_by_scale_factor μέθοδος"
second_title: "GroupDocs.Viewer για Python μέσω .NET Αναφορές API"
description: "Αρχικοποιεί ένα αντικείμενο CadOptions για απόδοση με βάση τον συντελεστή κλίμακας."
type: docs
url: /el/python-net/groupdocs.viewer.options/cadoptions/for_rendering_by_scale_factor/
is_root: false
weight: 1020
---


## for_rendering_by_scale_factor {#scale_factor}

Αρχικοποιεί ένα αντικείμενο CadOptions για απόδοση με βάση τον συντελεστή κλίμακας.

Για παράδειγμα κώδικα, δείτε την τεκμηρίωση.

```python
def for_rendering_by_scale_factor(cls, scale_factor):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| scale_factor | `float` | Τιμή μεγαλύτερη από 1 αυξάνει το αποτέλεσμα εξόδου· τιμή μεταξύ 0 και 1 μειώνει το αποτέλεσμα εξόδου. |

**Returns:** CadOptions: New instance of the CadOptions class for rendering by scale factor.

| Αναφέρει | Περιγραφή |
| :- | :- |
| `ValueError` | Εγείρεται όταν το `scale_factor` είναι μικρότερο ή ίσο με το μηδέν. |

### Παράδειγμα

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PngViewOptions, CadOptions

def set_image_size():
    with Viewer("sample.dwg") as viewer:
        png_options = PngViewOptions("set_image_size/image_with_size_limits.pdf")
        png_options.cad_options = CadOptions.for_rendering_by_scale_factor(0.5)
        viewer.view(png_options)

if __name__ == "__main__":
    set_image_size()
```

### Δείτε επίσης
* class [`CadOptions`](/viewer/python-net/groupdocs.viewer.options/cadoptions/)
