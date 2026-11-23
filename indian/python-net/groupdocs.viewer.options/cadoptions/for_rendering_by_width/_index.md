---
title: "for_rendering_by_width मेथड"
second_title: "GroupDocs.Viewer Python के लिए .NET के माध्यम से API संदर्भ"
description: "चौड़ाई द्वारा रेंडरिंग के लिए CadOptions क्लास का एक इंस्टेंस इनिशियलाइज़ करता है।"
type: docs
url: /hi/python-net/groupdocs.viewer.options/cadoptions/for_rendering_by_width/
is_root: false
weight: 1030
---


## for_rendering_by_width {#width}

चौड़ाई के आधार पर रेंडरिंग के लिए [`CadOptions`](/viewer/python-net/groupdocs.viewer.options/cadoptions/) क्लास का एक इंस्टेंस प्रारंभ करता है।

```python
def for_rendering_by_width(cls, width):
    ...
```

| पैरामीटर | टाइप | विवरण |
| :- | :- | :- |
| width | `int` | आउटपुट परिणाम की चौड़ाई (पिक्सेल में)। |

**Returns:** CadOptions: New instance of the `CadOptions` class for rendering by width.

| उत्पन्न करता है | विवरण |
| :- | :- |
| `ValueError` | यदि `width` शून्य या उससे कम है। |

### उदाहरण

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions, CadOptions

def enable_performance_mode():
    # CAD फ़ाइल लोड करें
    with Viewer("sample.dwg") as viewer:
        view_options = HtmlViewOptions.for_embedded_resources(
            "enable_performance_mode/Output-Page#{0}.html"
        )
        view_options.cad_options = CadOptions.for_rendering_by_width(1000)
        view_options.cad_options.enable_performance_conversion_mode = True
        viewer.view(view_options)

if __name__ == "__main__":
    enable_performance_mode()
```

### साथ में देखें
* class [`CadOptions`](/viewer/python-net/groupdocs.viewer.options/cadoptions/)
