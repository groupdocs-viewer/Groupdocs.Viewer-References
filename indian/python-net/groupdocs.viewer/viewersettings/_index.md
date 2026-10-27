---
title: "ViewerSettings क्लास"
second_title: "GroupDocs.Viewer Python के लिए .NET के माध्यम से API संदर्भ"
description: "Viewer व्यवहार को अनुकूलित करने के लिए सेटिंग्स को परिभाषित करता है।"
type: docs
url: /hi/python-net/groupdocs.viewer/viewersettings/
is_root: false
weight: 110
---


## ViewerSettings class

[`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/) के व्यवहार को अनुकूलित करने के लिए सेटिंग्स को परिभाषित करता है।

ViewerSettings प्रकार निम्नलिखित सदस्यों को उजागर करता है:

### कंस्ट्रक्टर्स
| कंस्ट्रक्टर | विवरण |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer/viewersettings/__init__/#cache-logger) | एक नया ViewerSettings इंस्टेंस प्रारंभ करता है। |
| [__init__](/viewer/python-net/groupdocs.viewer/viewersettings/__init__/#cache) | एक नया ViewerSettings इंस्टेंस प्रारंभ करता है। |
| [__init__](/viewer/python-net/groupdocs.viewer/viewersettings/__init__/#logger) | एक नया ViewerSettings इंस्टेंस प्रारंभ करता है। |

### प्रॉपर्टीज़
| प्रॉपर्टी | विवरण |
| :- | :- |
| [cache](/viewer/python-net/groupdocs.viewer/viewersettings/cache/) | रेंडरिंग परिणामों को संग्रहीत करने के लिए उपयोग किया जाने वाला कैश कार्यान्वयन। |
| [logger](/viewer/python-net/groupdocs.viewer/viewersettings/logger/) | लॉगिंग (त्रुटियाँ, चेतावनियाँ, ट्रेस) के लिए उपयोग किया जाने वाला लॉगर कार्यान्वयन। |

### उदाहरण

```python
from groupdocs.viewer import Viewer, ViewerSettings
from groupdocs.viewer.logging import ConsoleLogger
from groupdocs.viewer.options import HtmlViewOptions

viewer_settings = ViewerSettings(logger=ConsoleLogger())
with Viewer("./sample.docx", settings=viewer_settings) as viewer:
    html_options = HtmlViewOptions.for_embedded_resources(
        "example/page_{0}.html"
    )
    viewer.view(html_options)
```

### साथ में देखें
* module [`groupdocs.viewer`](/viewer/python-net/groupdocs.viewer/)
