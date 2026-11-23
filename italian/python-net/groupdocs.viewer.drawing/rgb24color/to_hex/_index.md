---
title: "metodo to_hex"
second_title: "Riferimenti API di GroupDocs.Viewer per Python via .NET"
description: "Restituisce questo colore in rappresentazione stringa esadecimale."
type: docs
url: /it/python-net/groupdocs.viewer.drawing/rgb24color/to_hex/
is_root: false
weight: 1110
---


## to_hex

Restituisce questo colore in rappresentazione stringa esadecimale.

```python
def to_hex(self):
    ...
```

**Returns:** str: Color hex representation string.

### Esempio

```python
    from GroupDocs.Viewer.Drawing import Rgb24Color

    hex_str = Rgb24Color.KnownColors.CssLevel1.Red.to_hex()
    print(hex_str)  # "#FF0000"
    ```

### Vedi anche
* class [`Rgb24Color`](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/)
