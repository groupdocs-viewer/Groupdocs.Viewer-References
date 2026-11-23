---
title: "OutlookViewInfo क्लास"
second_title: "GroupDocs.Viewer Python के लिए .NET के माध्यम से API संदर्भ"
description: "Outlook डेटा फ़ाइल के लिए दृश्य जानकारी का प्रतिनिधित्व करता है।"
type: docs
url: /hi/python-net/groupdocs.viewer.results/outlookviewinfo/
is_root: false
weight: 120
---


## OutlookViewInfo class

Outlook डेटा फ़ाइल के लिए दृश्य जानकारी का प्रतिनिधित्व करता है।

OutlookViewInfo प्रकार निम्नलिखित सदस्यों को उजागर करता है:

### कंस्ट्रक्टर्स
| कंस्ट्रक्टर | विवरण |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.results/outlookviewinfo/__init__/) | एक नया उदाहरण प्रारंभ करता है [`OutlookViewInfo`](/viewer/python-net/groupdocs.viewer.results/outlookviewinfo/) का। |
| [__init__](/viewer/python-net/groupdocs.viewer.results/outlookviewinfo/__init__/#file_type-pages-folders) | एक नया OutlookViewInfo उदाहरण प्रारंभ करता है। |

### मेथड्स
| मेथड | विवरण |
| :- | :- |
| [to_string](/viewer/python-net/groupdocs.viewer.results/viewinfo/to_string/) | एक स्ट्रिंग लौटाता है जो वर्तमान ऑब्जेक्ट का प्रतिनिधित्व करती है। ([`ViewInfo`](/viewer/python-net/groupdocs.viewer.results/viewinfo/) से विरासत में मिली) |

### प्रॉपर्टीज़
| प्रॉपर्टी | विवरण |
| :- | :- |
| [folders](/viewer/python-net/groupdocs.viewer.results/outlookviewinfo/folders/) | Outlook डेटा फ़ाइल में सम्मिलित फ़ोल्डरों की सूची। |
| [file_type](/viewer/python-net/groupdocs.viewer.results/viewinfo/file_type/) | फ़ाइल का प्रकार। ([`ViewInfo`](/viewer/python-net/groupdocs.viewer.results/viewinfo/) से विरासत में मिला) |
| [pages](/viewer/python-net/groupdocs.viewer.results/viewinfo/pages/) | देखने के लिए पृष्ठों की सूची। ([`ViewInfo`](/viewer/python-net/groupdocs.viewer.results/viewinfo/) से विरासत में मिली) |

### उदाहरण

```python
from typing import cast
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import ViewInfoOptions
from groupdocs.viewer.results import OutlookViewInfo

def get_outlook_info():
    with Viewer("sample.pst") as viewer:
        info = viewer.get_view_info(ViewInfoOptions.for_html_view())
        outlook_info = cast(OutlookViewInfo, info)

        print("File type:", outlook_info.file_type)
        print("Pages count:", len(outlook_info.pages))
        print("Folders:")
        for folder in outlook_info.folders:
            print(f"  {folder}")

if __name__ == "__main__":
    get_outlook_info()
```

### Guides
`OutlookViewInfo` का उपयोग करने वाले कार्य गाइड:

* [Get Document Information](/viewer/python-net/guides/get-document-info/)

### साथ में देखें
* module [`groupdocs.viewer.results`](/viewer/python-net/groupdocs.viewer.results/)
