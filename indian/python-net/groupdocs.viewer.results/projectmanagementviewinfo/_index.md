---
title: "ProjectManagementViewInfo क्लास"
second_title: "GroupDocs.Viewer Python के लिए .NET के माध्यम से API संदर्भ"
description: "MS Project दस्तावेज़ के लिए दृश्य जानकारी का प्रतिनिधित्व करता है।"
type: docs
url: /hi/python-net/groupdocs.viewer.results/projectmanagementviewinfo/
is_root: false
weight: 150
---


## ProjectManagementViewInfo class

MS Project दस्तावेज़ के लिए दृश्य जानकारी का प्रतिनिधित्व करता है।

ProjectManagementViewInfo प्रकार निम्नलिखित सदस्यों को उजागर करता है:

### कंस्ट्रक्टर्स
| कंस्ट्रक्टर | विवरण |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.results/projectmanagementviewinfo/__init__/) | एक नया उदाहरण प्रारंभ करता है [`ProjectManagementViewInfo`](/viewer/python-net/groupdocs.viewer.results/projectmanagementviewinfo/) का। |
| [__init__](/viewer/python-net/groupdocs.viewer.results/projectmanagementviewinfo/__init__/#file_type-pages-start_date-end_date) | ProjectManagementViewInfo का नया उदाहरण प्रारंभ करता है। |

### मेथड्स
| मेथड | विवरण |
| :- | :- |
| [to_string](/viewer/python-net/groupdocs.viewer.results/viewinfo/to_string/) | एक स्ट्रिंग लौटाता है जो वर्तमान ऑब्जेक्ट का प्रतिनिधित्व करती है। ([`ViewInfo`](/viewer/python-net/groupdocs.viewer.results/viewinfo/) से विरासत में मिली) |

### प्रॉपर्टीज़
| प्रॉपर्टी | विवरण |
| :- | :- |
| [end_date](/viewer/python-net/groupdocs.viewer.results/projectmanagementviewinfo/end_date/) | प्रोजेक्ट के पूर्ण होने की तिथि और समय। |
| [start_date](/viewer/python-net/groupdocs.viewer.results/projectmanagementviewinfo/start_date/) | प्रोजेक्ट के शुरू होने की तिथि और समय। |
| [file_type](/viewer/python-net/groupdocs.viewer.results/viewinfo/file_type/) | फ़ाइल का प्रकार। ([`ViewInfo`](/viewer/python-net/groupdocs.viewer.results/viewinfo/) से विरासत में मिला) |
| [pages](/viewer/python-net/groupdocs.viewer.results/viewinfo/pages/) | देखने के लिए पृष्ठों की सूची। ([`ViewInfo`](/viewer/python-net/groupdocs.viewer.results/viewinfo/) से विरासत में मिली) |

### उदाहरण

```python
from typing import cast
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import ViewInfoOptions
from groupdocs.viewer.results import ProjectManagementViewInfo

def get_project_info():
    with Viewer("sample.mpp") as viewer:
        info = viewer.get_view_info(ViewInfoOptions.for_html_view())
        project_info = cast(ProjectManagementViewInfo, info)

        print("File type:", project_info.file_type)
        print("Pages count:", len(project_info.pages))
        print("Start date:", project_info.start_date)
        print("End date:", project_info.end_date)

if __name__ == "__main__":
    get_project_info()
```

### Guides
`ProjectManagementViewInfo` का उपयोग करने वाले कार्य गाइड:

* [Get Document Information](/viewer/python-net/guides/get-document-info/)

### साथ में देखें
* module [`groupdocs.viewer.results`](/viewer/python-net/groupdocs.viewer.results/)
