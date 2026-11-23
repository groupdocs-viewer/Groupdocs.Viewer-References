---
title: "for_html_view मेथड"
second_title: "GroupDocs.Viewer Python के लिए .NET के माध्यम से API संदर्भ"
description: "HTML में रेंडर करते समय दृश्य जानकारी प्राप्त करने के लिए एक ViewInfoOptions इंस्टेंस को प्रारंभ करता है।"
type: docs
url: /hi/python-net/groupdocs.viewer.options/viewinfooptions/for_html_view/
is_root: false
weight: 1010
---


## for_html_view

HTML में रेंडर करते समय दृश्य जानकारी प्राप्त करने के लिए एक ViewInfoOptions इंस्टेंस को प्रारंभ करता है।

```python
def for_html_view(cls):
    ...
```

**Returns:** ViewInfoOptions: A new ViewInfoOptions instance.

### उदाहरण

```python
    from groupdocs.viewer import Viewer
    from groupdocs.viewer.options import ViewInfoOptions

    # HTML फ़ॉर्मेट (सिंगल पेज) के लिए व्यू इन्फो ऑप्शन बनाएं
    options = ViewInfoOptions.for_html_view(True)

    # एक दस्तावेज़ लोड करें और व्यू जानकारी प्राप्त करें
    with Viewer("sample.xml") as viewer:
        info = viewer.get_view_info(options)
    ```

## for_html_view {#render_single_page}

HTML में रेंडर करते समय दृश्य जानकारी प्राप्त करने के लिए एक ViewInfoOptions इंस्टेंस को प्रारंभ करता है।

```python
def for_html_view(cls, render_single_page):
    ...
```

| पैरामीटर | टाइप | विवरण |
| :- | :- | :- |
| render_single_page | `bool` | HTML कंटेंट को सिंगल पेज पर रेंडर करना सक्षम करता है। |

**Returns:** ViewInfoOptions: New instance of the ViewInfoOptions class.

### उदाहरण

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import ViewInfoOptions

# HTML के लिए एकल पृष्ठ के साथ दृश्य जानकारी प्राप्त करें
options = ViewInfoOptions.for_html_view(True)

with Viewer("sample.xml") as viewer:
    info = viewer.get_view_info(options)
    print("Document type:", info.file_type)
    print("Pages count:", len(info.pages))
```

### साथ में देखें
* class [`ViewInfoOptions`](/viewer/python-net/groupdocs.viewer.options/viewinfooptions/)
