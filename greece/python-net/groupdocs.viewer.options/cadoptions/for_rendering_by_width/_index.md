---
title: "for_rendering_by_width μέθοδος"
second_title: "GroupDocs.Viewer για Python μέσω .NET Αναφορές API"
description: "Αρχικοποιεί μια παρουσία της κλάσης CadOptions για απόδοση ανά πλάτος."
type: docs
url: /el/python-net/groupdocs.viewer.options/cadoptions/for_rendering_by_width/
is_root: false
weight: 1030
---


## for_rendering_by_width {#width}

Αρχικοποιεί ένα αντικείμενο της κλάσης [`CadOptions`](/viewer/python-net/groupdocs.viewer.options/cadoptions/) για απόδοση με βάση το πλάτος.

```python
def for_rendering_by_width(cls, width):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| width | `int` | Το πλάτος του αποτελέσματος εξόδου (σε εικονοστοιχεία). |

**Returns:** CadOptions: New instance of the `CadOptions` class for rendering by width.

| Αναφέρει | Περιγραφή |
| :- | :- |
| `ValueError` | Εάν το `width` είναι μικρότερο ή ίσο με το μηδέν. |

### Παράδειγμα

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions, CadOptions

def enable_performance_mode():
    # Φόρτωση αρχείου CAD
    with Viewer("sample.dwg") as viewer:
        view_options = HtmlViewOptions.for_embedded_resources(
            "enable_performance_mode/Output-Page#{0}.html"
        )
        view_options.cad_options = CadOptions.for_rendering_by_width(1000)
        view_options.cad_options.enable_performance_conversion_mode = True
        viewer.view(view_options)

if __name__ == "__main__":
    enable_performance_mode()
```

### Δείτε επίσης
* class [`CadOptions`](/viewer/python-net/groupdocs.viewer.options/cadoptions/)
