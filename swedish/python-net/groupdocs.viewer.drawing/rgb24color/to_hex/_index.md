---
title: "to_hex‑metod"
second_title: "GroupDocs.Viewer för Python via .NET API-referenser"
description: "Returnerar den här färgen i hexadecimal strängrepresentation."
type: docs
url: /sv/python-net/groupdocs.viewer.drawing/rgb24color/to_hex/
is_root: false
weight: 1110
---


## to_hex

Returnerar den här färgen i hexadecimal strängrepresentation.

```python
def to_hex(self):
    ...
```

**Returns:** str: Color hex representation string.

### Exempel

```python
    from GroupDocs.Viewer.Drawing import Rgb24Color

    hex_str = Rgb24Color.KnownColors.CssLevel1.Red.to_hex()
    print(hex_str)  # "#FF0000"
    ```

### Se även
* class [`Rgb24Color`](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/)
