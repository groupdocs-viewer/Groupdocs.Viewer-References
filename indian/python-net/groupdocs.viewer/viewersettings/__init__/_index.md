---
title: "__init__ कंस्ट्रक्टर"
second_title: "GroupDocs.Viewer Python के लिए .NET के माध्यम से API संदर्भ"
description: "एक नया ViewerSettings इंस्टेंस प्रारंभ करता है।"
type: docs
url: /hi/python-net/groupdocs.viewer/viewersettings/__init__/
is_root: false
weight: 10
---


## __init__ {#cache-logger}

एक नया ViewerSettings इंस्टेंस प्रारंभ करता है।

```python
def __init__(self, cache, logger):
    ...
```

| पैरामीटर | टाइप | विवरण |
| :- | :- | :- |
| cache | `ICache` | कैश। |
| logger | `ILogger` | लॉगर। |

| उत्पन्न करता है | विवरण |
| :- | :- |
| `ValueError` | जब `cache` None हो तो उठाया जाता है। |

### उदाहरण

```python
from groupdocs.viewer import Viewer, ViewerSettings
from groupdocs.viewer.logging import ConsoleLogger
from groupdocs.viewer.options import HtmlViewOptions

viewer_settings = ViewerSettings(logger=ConsoleLogger())
with Viewer("./sample.docx", settings=viewer_settings) as viewer:
    html_options = HtmlViewOptions.for_embedded_resources("output/page_{0}.html")
    viewer.view(html_options)
```

## __init__ {#cache}

एक नया ViewerSettings इंस्टेंस प्रारंभ करता है।

```python
def __init__(self, cache):
    ...
```

| पैरामीटर | टाइप | विवरण |
| :- | :- | :- |
| cache | `ICache` | कैश। |

| उत्पन्न करता है | विवरण |
| :- | :- |
| `ValueError` | जब `cache` None हो तो उठाया जाता है। |

## __init__ {#logger}

एक नया ViewerSettings इंस्टेंस प्रारंभ करता है।

```python
def __init__(self, logger):
    ...
```

| पैरामीटर | टाइप | विवरण |
| :- | :- | :- |
| logger | `ILogger` | लॉगर। |

| उत्पन्न करता है | विवरण |
| :- | :- |
| `ValueError` | जब `logger` None हो तो उठाया जाता है। |

### उदाहरण

```python
from groupdocs.viewer import Viewer, ViewerSettings
from groupdocs.viewer.logging import ConsoleLogger
from groupdocs.viewer.options import HtmlViewOptions

viewer_settings = ViewerSettings(logger=ConsoleLogger())
with Viewer("./sample.docx", settings=viewer_settings) as viewer:
    html_options = HtmlViewOptions.for_embedded_resources("output/page_{0}.html")
    viewer.view(html_options)
```

### साथ में देखें
* class [`ViewerSettings`](/viewer/python-net/groupdocs.viewer/viewersettings/)
