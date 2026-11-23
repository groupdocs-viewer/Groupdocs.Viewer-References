---
title: "μέθοδος to_hex"
second_title: "GroupDocs.Viewer για Python μέσω .NET Αναφορές API"
description: "Επιστρέφει αυτό το χρώμα σε δεκαεξαδική αναπαράσταση συμβολοσειράς."
type: docs
url: /el/python-net/groupdocs.viewer.drawing/rgb24color/to_hex/
is_root: false
weight: 1110
---


## to_hex

Επιστρέφει αυτό το χρώμα σε δεκαεξαδική αναπαράσταση συμβολοσειράς.

```python
def to_hex(self):
    ...
```

**Returns:** str: Color hex representation string.

### Παράδειγμα

```python
    from GroupDocs.Viewer.Drawing import Rgb24Color

    hex_str = Rgb24Color.KnownColors.CssLevel1.Red.to_hex()
    print(hex_str)  # "#FF0000"
    ```

### Δείτε επίσης
* class [`Rgb24Color`](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/)
