---
title: "from_html_view_options मेथड"
second_title: "GroupDocs.Viewer Python के लिए .NET के माध्यम से API संदर्भ"
description: "HtmlViewOptions ऑब्जेक्ट के आधार पर ViewInfoOptions क्लास का एक इंस्टेंस प्रारंभ करता है।"
type: docs
url: /hi/python-net/groupdocs.viewer.options/viewinfooptions/from_html_view_options/
is_root: false
weight: 1080
---


## from_html_view_options {#options}

HtmlViewOptions ऑब्जेक्ट के आधार पर ViewInfoOptions क्लास का एक इंस्टेंस प्रारंभ करता है।

```python
def from_html_view_options(cls, options):
    ...
```

| पैरामीटर | टाइप | विवरण |
| :- | :- | :- |
| options | `HtmlViewOptions` | HTML व्यू विकल्प। |

**Returns:** A new ViewInfoOptions instance.

| उत्पन्न करता है | विवरण |
| :- | :- |
| `ValueError` | यदि `options` None है। |

### उदाहरण

```python
from groupdocs.viewer.options import ViewInfoOptions, HtmlViewOptions

html_opts = HtmlViewOptions()
view_info_opts = ViewInfoOptions.from_html_view_options(html_opts)
```

### साथ में देखें
* class [`ViewInfoOptions`](/viewer/python-net/groupdocs.viewer.options/viewinfooptions/)
