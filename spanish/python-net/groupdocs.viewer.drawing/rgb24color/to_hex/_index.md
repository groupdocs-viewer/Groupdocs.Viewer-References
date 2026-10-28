---
title: "método to_hex"
second_title: "Referencias de API de GroupDocs.Viewer para Python vía .NET"
description: "Devuelve este color en representación de cadena hexadecimal."
type: docs
url: /es/python-net/groupdocs.viewer.drawing/rgb24color/to_hex/
is_root: false
weight: 1110
---


## to_hex

Devuelve este color en representación de cadena hexadecimal.

```python
def to_hex(self):
    ...
```

**Returns:** str: Color hex representation string.

### Ejemplo

```python
    from GroupDocs.Viewer.Drawing import Rgb24Color

    hex_str = Rgb24Color.KnownColors.CssLevel1.Red.to_hex()
    print(hex_str)  # "#FF0000"
    ```

### Ver también
* class [`Rgb24Color`](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/)
