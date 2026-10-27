---
title: "طريقة to_hex"
second_title: "مراجع API لـ GroupDocs.Viewer لـ Python عبر .NET"
description: "يرجع هذا اللون في تمثيل سلسلة سداسي عشرية."
type: docs
url: /ar/python-net/groupdocs.viewer.drawing/rgb24color/to_hex/
is_root: false
weight: 1110
---


## to_hex

يرجع هذا اللون في تمثيل سلسلة سداسي عشرية.

```python
def to_hex(self):
    ...
```

**Returns:** str: Color hex representation string.

### مثال

```python
    from GroupDocs.Viewer.Drawing import Rgb24Color

    hex_str = Rgb24Color.KnownColors.CssLevel1.Red.to_hex()
    print(hex_str)  # "#FF0000"
    ```

### انظر أيضًا
* class [`Rgb24Color`](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/)
