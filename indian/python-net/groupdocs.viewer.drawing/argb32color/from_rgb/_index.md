---
title: "from_rgb मेथड"
second_title: "GroupDocs.Viewer Python के लिए .NET के माध्यम से API संदर्भ"
description: "निर्दिष्ट रेड, ग्रीन, ब्लू चैनलों से एक Argb32Color मान बनाता है, जिसमें अल्फा चैनल पूरी तरह अपारदर्शी सेट किया गया है।"
type: docs
url: /hi/python-net/groupdocs.viewer.drawing/argb32color/from_rgb/
is_root: false
weight: 1090
---


## from_rgb {#red-green-blue}

निर्दिष्ट रेड, ग्रीन, ब्लू चैनलों से एक Argb32Color मान बनाता है, जिसमें अल्फा चैनल पूरी तरह अपारदर्शी सेट किया गया है।

```python
def from_rgb(cls, red, green, blue):
    ...
```

| पैरामीटर | टाइप | विवरण |
| :- | :- | :- |
| red | `int` | लाल चैनल मान। |
| green | `int` | हरा चैनल मान। |
| blue | `int` | नीला चैनल मान। |

**Returns:** Argb32Color: New Argb32Color value.

### उदाहरण

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions
from groupdocs.viewer.drawing import Argb32Color

with Viewer("sample.dwg") as viewer:
    view_options = PdfViewOptions("output.pdf")
    view_options.cad_options.background_color = Argb32Color.from_rgb(255, 255, 0)  # yellow
    viewer.view(view_options)
```

### साथ में देखें
* class [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/)
