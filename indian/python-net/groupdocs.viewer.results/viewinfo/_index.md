---
title: "ViewInfo क्लास"
second_title: "GroupDocs.Viewer Python के लिए .NET के माध्यम से API संदर्भ"
description: "एक सामान्य दस्तावेज़ के लिए दृश्य जानकारी का प्रतिनिधित्व करता है।"
type: docs
url: /hi/python-net/groupdocs.viewer.results/viewinfo/
is_root: false
weight: 180
---


## ViewInfo class

एक सामान्य दस्तावेज़ के लिए दृश्य जानकारी का प्रतिनिधित्व करता है।

ViewInfo प्रकार निम्नलिखित सदस्यों को उजागर करता है:

### कंस्ट्रक्टर्स
| कंस्ट्रक्टर | विवरण |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.results/viewinfo/__init__/) | एक नया [`ViewInfo`](/viewer/python-net/groupdocs.viewer.results/viewinfo/) का उदाहरण आरंभ करता है। |
| [__init__](/viewer/python-net/groupdocs.viewer.results/viewinfo/__init__/#file_type-pages) | एक नया ViewInfo उदाहरण आरंभ करता है। |

### मेथड्स
| मेथड | विवरण |
| :- | :- |
| [to_string](/viewer/python-net/groupdocs.viewer.results/viewinfo/to_string/) | एक स्ट्रिंग लौटाता है जो वर्तमान ऑब्जेक्ट का प्रतिनिधित्व करती है। |

### प्रॉपर्टीज़
| प्रॉपर्टी | विवरण |
| :- | :- |
| [file_type](/viewer/python-net/groupdocs.viewer.results/viewinfo/file_type/) | फ़ाइल का प्रकार। |
| [pages](/viewer/python-net/groupdocs.viewer.results/viewinfo/pages/) | देखने के लिए पृष्ठों की सूची। |

### उदाहरण

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import ViewInfoOptions

with Viewer("sample.docx") as viewer:
    options = ViewInfoOptions.for_html_view()
    view_info = viewer.get_view_info(options)
    for page in view_info.pages:
        print(f"Page {page.number}: {page.name}")
```

### साथ में देखें
* module [`groupdocs.viewer.results`](/viewer/python-net/groupdocs.viewer.results/)
