---
title: "for_rendering_by_height मेथड"
second_title: "GroupDocs.Viewer Python के लिए .NET के माध्यम से API संदर्भ"
description: "ऊँचाई के आधार पर रेंडरिंग के लिए CadOptions इंस्टेंस को प्रारंभ करता है।"
type: docs
url: /hi/python-net/groupdocs.viewer.options/cadoptions/for_rendering_by_height/
is_root: false
weight: 1010
---


## for_rendering_by_height {#height}

ऊँचाई के आधार पर रेंडरिंग के लिए CadOptions इंस्टेंस को प्रारंभ करता है।

कोड उदाहरण के लिए, दस्तावेज़ देखें।

```python
def for_rendering_by_height(cls, height):
    ...
```

| पैरामीटर | टाइप | विवरण |
| :- | :- | :- |
| height | `int` | आउटपुट परिणाम की ऊँचाई (पिक्सेल में)। |

**Returns:** CadOptions: New instance configured for rendering by height.

| उत्पन्न करता है | विवरण |
| :- | :- |
| `ValueError` | जब `height` शून्य या उससे कम हो। |

### उदाहरण

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PngViewOptions, CadOptions

def render_by_height():
    with Viewer("sample.dwg") as viewer:
        png_options = PngViewOptions("output_by_height.png")
        png_options.cad_options = CadOptions.for_rendering_by_height(1500)
        viewer.view(png_options)
```

### साथ में देखें
* class [`CadOptions`](/viewer/python-net/groupdocs.viewer.options/cadoptions/)
