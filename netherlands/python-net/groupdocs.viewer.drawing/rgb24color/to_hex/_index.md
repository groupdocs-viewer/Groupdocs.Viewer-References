---
title: "to_hex methode"
second_title: "GroupDocs.Viewer voor Python via .NET API-referenties"
description: "Retourneert deze kleur in hexadecimale tekenreeksrepresentatie."
type: docs
url: /nl/python-net/groupdocs.viewer.drawing/rgb24color/to_hex/
is_root: false
weight: 1110
---


## to_hex

Retourneert deze kleur in hexadecimale tekenreeksrepresentatie.

```python
def to_hex(self):
    ...
```

**Returns:** str: Color hex representation string.

### Voorbeeld

```python
    from GroupDocs.Viewer.Drawing import Rgb24Color

    hex_str = Rgb24Color.KnownColors.CssLevel1.Red.to_hex()
    print(hex_str)  # "#FF0000"
    ```

### Zie ook
* class [`Rgb24Color`](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/)
