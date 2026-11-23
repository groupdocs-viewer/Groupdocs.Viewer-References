---
title: "for_rendering_by_width_and_height मेथड"
second_title: "GroupDocs.Viewer Python के लिए .NET के माध्यम से API संदर्भ"
description: "चौड़ाई और ऊँचाई के आधार पर रेंडरिंग के लिए CadOptions क्लास का एक इंस्टेंस प्रारंभ करता है।"
type: docs
url: /hi/python-net/groupdocs.viewer.options/cadoptions/for_rendering_by_width_and_height/
is_root: false
weight: 1040
---


## for_rendering_by_width_and_height {#width-height}

चौड़ाई और ऊँचाई के आधार पर रेंडरिंग के लिए CadOptions क्लास का एक इंस्टेंस प्रारंभ करता है।

कोड उदाहरण के लिए, दस्तावेज़ देखें।

```python
def for_rendering_by_width_and_height(cls, width, height):
    ...
```

| पैरामीटर | टाइप | विवरण |
| :- | :- | :- |
| width | `int` | आउटपुट परिणाम की चौड़ाई (पिक्सेल में)। |
| height | `int` | आउटपुट परिणाम की ऊँचाई (पिक्सेल में)। |

**Returns:** CadOptions: New instance of CadOptions class for rendering by width and height.

| उत्पन्न करता है | विवरण |
| :- | :- |
| `ValueError` | यदि `height` शून्य या उससे कम है। |

### साथ में देखें
* class [`CadOptions`](/viewer/python-net/groupdocs.viewer.options/cadoptions/)
