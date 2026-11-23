---
title: "to_hex Methode"
second_title: "GroupDocs.Viewer für Python über .NET API-Referenzen"
description: "Gibt diese Farbe in hexadezimaler String-Darstellung zurück."
type: docs
url: /de/python-net/groupdocs.viewer.drawing/rgb24color/to_hex/
is_root: false
weight: 1110
---


## to_hex

Gibt diese Farbe in hexadezimaler String-Darstellung zurück.

```python
def to_hex(self):
    ...
```

**Returns:** str: Color hex representation string.

### Beispiel

```python
    from GroupDocs.Viewer.Drawing import Rgb24Color

    hex_str = Rgb24Color.KnownColors.CssLevel1.Red.to_hex()
    print(hex_str)  # "#FF0000"
    ```

### Siehe auch
* class [`Rgb24Color`](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/)
