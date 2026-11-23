---
title: "Metode to_hex"
second_title: "Referensi API GroupDocs.Viewer untuk Python via .NET"
description: "Mengembalikan warna ini dalam representasi string heksadesimal."
type: docs
url: /id/python-net/groupdocs.viewer.drawing/rgb24color/to_hex/
is_root: false
weight: 1110
---


## to_hex

Mengembalikan warna ini dalam representasi string heksadesimal.

```python
def to_hex(self):
    ...
```

**Returns:** str: Color hex representation string.

### Contoh

```python
    from GroupDocs.Viewer.Drawing import Rgb24Color

    hex_str = Rgb24Color.KnownColors.CssLevel1.Red.to_hex()
    print(hex_str)  # "#FF0000"
    ```

### Lihat Juga
* class [`Rgb24Color`](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/)
