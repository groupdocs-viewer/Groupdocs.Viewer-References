---
title: to_hex method
second_title: GroupDocs.Viewer for Python via .NET API References
description: "Returns this color in hexadecimal string representation."
type: docs
url: /python-net/groupdocs.viewer.drawing/rgb24color/to_hex/
is_root: false
weight: 1080
---


## to_hex

Returns this color in hexadecimal string representation.

```python
def to_hex(self):
    ...
```

**Returns:** str: Color hex representation string.

### Example

```python
    from groupdocs.viewer.drawing import Rgb24Color

    hex_str = Rgb24Color.KnownColors.CssLevel1.red.to_hex()
    print(hex_str)  # "#FF0000"
    ```

### See Also
* class [`Rgb24Color`](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/)
