---
title: "to_hex yöntemi"
second_title: "GroupDocs.Viewer Python için .NET üzerinden API Referansları"
description: "Bu rengi onaltılık dize temsili olarak döndürür."
type: docs
url: /tr/python-net/groupdocs.viewer.drawing/rgb24color/to_hex/
is_root: false
weight: 1110
---


## to_hex

Bu rengi onaltılık dize temsili olarak döndürür.

```python
def to_hex(self):
    ...
```

**Returns:** str: Color hex representation string.

### Örnek

```python
    from GroupDocs.Viewer.Drawing import Rgb24Color

    hex_str = Rgb24Color.KnownColors.CssLevel1.Red.to_hex()
    print(hex_str)  # "#FF0000"
    ```

### Ayrıca Bakınız
* class [`Rgb24Color`](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/)
