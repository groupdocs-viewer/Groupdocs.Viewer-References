---
title: "for_png_view मेथड"
second_title: "GroupDocs.Viewer Python के लिए .NET के माध्यम से API संदर्भ"
description: "PNG में रेंडर करते समय दृश्य जानकारी प्राप्त करने के लिए ViewInfoOptions क्लास का एक इंस्टेंस प्रारंभ करता है।"
type: docs
url: /hi/python-net/groupdocs.viewer.options/viewinfooptions/for_png_view/
is_root: false
weight: 1060
---


## for_png_view

PNG में रेंडर करते समय दृश्य जानकारी प्राप्त करने के लिए [`ViewInfoOptions`](/viewer/python-net/groupdocs.viewer.options/viewinfooptions/) क्लास का एक इंस्टेंस प्रारंभ करता है।

```python
def for_png_view(cls):
    ...
```

**Returns:** ViewInfoOptions: New instance of the `ViewInfoOptions` class.

### उदाहरण

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import ViewInfoOptions

# PNG प्रारूप के लिए दृश्य जानकारी विकल्प बनाएं
view_info_options_png = ViewInfoOptions.for_png_view()

# एक दस्तावेज़ लोड करें और PNG के लिए दृश्य जानकारी प्राप्त करें
with Viewer("sample.xml") as viewer:
    result_png = viewer.get_view_info(view_info_options_png)
```

## for_png_view {#extract_text}

PNG में रेंडर करते समय दृश्य जानकारी प्राप्त करने के लिए ViewInfoOptions क्लास का एक इंस्टेंस प्रारंभ करता है।

```python
def for_png_view(cls, extract_text):
    ...
```

| पैरामीटर | टाइप | विवरण |
| :- | :- | :- |
| extract_text | `bool` | टेक्स्ट एक्सट्रैक्शन सक्षम करता है। |

**Returns:** ViewInfoOptions: New instance of the ViewInfoOptions class.

### उदाहरण

```python
from groupdocs.viewer.options import ViewInfoOptions

# पाठ निष्कर्षण सक्षम के साथ PNG प्रारूप के लिए दृश्य जानकारी विकल्प बनाएं
options = ViewInfoOptions.for_png_view(extractText=True)
```

### साथ में देखें
* class [`ViewInfoOptions`](/viewer/python-net/groupdocs.viewer.options/viewinfooptions/)
