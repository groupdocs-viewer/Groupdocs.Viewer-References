---
title: "to_hex मेथड"
second_title: "GroupDocs.Viewer Python के लिए .NET के माध्यम से API संदर्भ"
description: "इस रंग को हेक्साडेसिमल स्ट्रिंग प्रतिनिधित्व में लौटाता है।"
type: docs
url: /hi/python-net/groupdocs.viewer.drawing/rgb24color/to_hex/
is_root: false
weight: 1110
---


## to_hex

इस रंग को हेक्साडेसिमल स्ट्रिंग प्रतिनिधित्व में लौटाता है।

```python
def to_hex(self):
    ...
```

**Returns:** str: Color hex representation string.

### उदाहरण

```python
    from GroupDocs.Viewer.Drawing import Rgb24Color

    hex_str = Rgb24Color.KnownColors.CssLevel1.Red.to_hex()
    print(hex_str)  # "#FF0000"
    ```

### साथ में देखें
* class [`Rgb24Color`](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/)
