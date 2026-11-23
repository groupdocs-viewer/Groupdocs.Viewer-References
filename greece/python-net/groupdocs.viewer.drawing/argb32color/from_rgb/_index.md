---
title: "μέθοδος from_rgb"
second_title: "GroupDocs.Viewer για Python μέσω .NET Αναφορές API"
description: "Δημιουργεί μια τιμή Argb32Color από καθορισμένα κανάλια Κόκκινο, Πράσινο, Μπλε, με το κανάλι Alpha ορισμένο σε πλήρη αδιαφάνεια."
type: docs
url: /el/python-net/groupdocs.viewer.drawing/argb32color/from_rgb/
is_root: false
weight: 1090
---


## from_rgb {#red-green-blue}

Δημιουργεί μια τιμή Argb32Color από καθορισμένα κανάλια Κόκκινο, Πράσινο, Μπλε, με το κανάλι Alpha ορισμένο σε πλήρη αδιαφάνεια.

```python
def from_rgb(cls, red, green, blue):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| red | `int` | Τιμή καναλιού κόκκινου. |
| green | `int` | Τιμή καναλιού πράσινου. |
| blue | `int` | Τιμή καναλιού μπλε. |

**Returns:** Argb32Color: New Argb32Color value.

### Παράδειγμα

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions
from groupdocs.viewer.drawing import Argb32Color

with Viewer("sample.dwg") as viewer:
    view_options = PdfViewOptions("output.pdf")
    view_options.cad_options.background_color = Argb32Color.from_rgb(255, 255, 0)  # yellow
    viewer.view(view_options)
```

### Δείτε επίσης
* class [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/)
