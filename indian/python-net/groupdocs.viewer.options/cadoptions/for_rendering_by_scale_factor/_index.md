---
title: "for_rendering_by_scale_factor मेथड"
second_title: "GroupDocs.Viewer Python के लिए .NET के माध्यम से API संदर्भ"
description: "स्केल फ़ैक्टर के आधार पर रेंडरिंग के लिए CadOptions इंस्टेंस को प्रारंभ करता है।"
type: docs
url: /hi/python-net/groupdocs.viewer.options/cadoptions/for_rendering_by_scale_factor/
is_root: false
weight: 1020
---


## for_rendering_by_scale_factor {#scale_factor}

स्केल फ़ैक्टर के आधार पर रेंडरिंग के लिए CadOptions इंस्टेंस को प्रारंभ करता है।

कोड उदाहरण के लिए, दस्तावेज़ देखें।

```python
def for_rendering_by_scale_factor(cls, scale_factor):
    ...
```

| पैरामीटर | टाइप | विवरण |
| :- | :- | :- |
| scale_factor | `float` | 1 से अधिक मान आउटपुट परिणाम को बढ़ाता है; 0 और 1 के बीच का मान आउटपुट परिणाम को घटाता है। |

**Returns:** CadOptions: New instance of the CadOptions class for rendering by scale factor.

| उत्पन्न करता है | विवरण |
| :- | :- |
| `ValueError` | `scale_factor` शून्य या उससे कम होने पर उत्पन्न होता है। |

### उदाहरण

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PngViewOptions, CadOptions

def set_image_size():
    with Viewer("sample.dwg") as viewer:
        png_options = PngViewOptions("set_image_size/image_with_size_limits.pdf")
        png_options.cad_options = CadOptions.for_rendering_by_scale_factor(0.5)
        viewer.view(png_options)

if __name__ == "__main__":
    set_image_size()
```

### साथ में देखें
* class [`CadOptions`](/viewer/python-net/groupdocs.viewer.options/cadoptions/)
