---
title: "FileName क्लास"
second_title: "GroupDocs.Viewer Python के लिए .NET के माध्यम से API संदर्भ"
description: "फ़ाइलनाम।"
type: docs
url: /hi/python-net/groupdocs.viewer.options/filename/
is_root: false
weight: 60
---


## FileName class

फ़ाइलनाम।

FileName प्रकार निम्नलिखित सदस्यों को उजागर करता है:

### कंस्ट्रक्टर्स
| कंस्ट्रक्टर | विवरण |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.options/filename/__init__/#file_name) | एक [`FileName`](/viewer/python-net/groupdocs.viewer.options/filename/) क्लास का इंस्टेंस प्रारंभ करता है। |

### मेथड्स
| मेथड | विवरण |
| :- | :- |
| [to_string](/viewer/python-net/groupdocs.viewer.options/filename/to_string/) | एक स्ट्रिंग लौटाता है जो वर्तमान ऑब्जेक्ट का प्रतिनिधित्व करती है। |

### फ़ील्ड्स
| फ़ील्ड | विवरण |
| :- | :- |
| [EMPTY](/viewer/python-net/groupdocs.viewer.options/filename/empty/) | खाली फ़ाइलनाम। |
| [SOURCE](/viewer/python-net/groupdocs.viewer.options/filename/source/) | स्रोत फ़ाइल का नाम। |

### उदाहरण

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions, FileName

with Viewer("documents.zip") as viewer:
    view_options = HtmlViewOptions.for_embedded_resources(
        "output/archive_{0}.html"
    )
    view_options.archive_options.file_name = FileName("Sample Files")
    viewer.view(view_options)
```

### साथ में देखें
* module [`groupdocs.viewer.options`](/viewer/python-net/groupdocs.viewer.options/)
