---
title: "méthode to_hex"
second_title: "Références API de GroupDocs.Viewer pour Python via .NET"
description: "Renvoie cette couleur sous forme de chaîne hexadécimale."
type: docs
url: /fr/python-net/groupdocs.viewer.drawing/rgb24color/to_hex/
is_root: false
weight: 1110
---


## to_hex

Renvoie cette couleur sous forme de chaîne hexadécimale.

```python
def to_hex(self):
    ...
```

**Returns:** str: Color hex representation string.

### Exemple

```python
    from GroupDocs.Viewer.Drawing import Rgb24Color

    hex_str = Rgb24Color.KnownColors.CssLevel1.Red.to_hex()
    print(hex_str)  # "#FF0000"
    ```

### Voir aussi
* class [`Rgb24Color`](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/)
