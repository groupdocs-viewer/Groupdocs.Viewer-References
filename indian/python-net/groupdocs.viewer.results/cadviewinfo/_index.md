---
title: "CadViewInfo क्लास"
second_title: "GroupDocs.Viewer Python के लिए .NET के माध्यम से API संदर्भ"
description: "CAD ड्राइंग के लिए दृश्य जानकारी का प्रतिनिधित्व करता है।"
type: docs
url: /hi/python-net/groupdocs.viewer.results/cadviewinfo/
is_root: false
weight: 30
---


## CadViewInfo class

CAD ड्राइंग के लिए दृश्य जानकारी का प्रतिनिधित्व करता है।

CadViewInfo प्रकार निम्नलिखित सदस्यों को उजागर करता है:

### कंस्ट्रक्टर्स
| कंस्ट्रक्टर | विवरण |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.results/cadviewinfo/__init__/#file_type-pages-layers-layouts) | CadViewInfo का नया उदाहरण प्रारंभ करता है। |

### मेथड्स
| मेथड | विवरण |
| :- | :- |
| [to_string](/viewer/python-net/groupdocs.viewer.results/viewinfo/to_string/) | एक स्ट्रिंग लौटाता है जो वर्तमान ऑब्जेक्ट का प्रतिनिधित्व करती है। ([`ViewInfo`](/viewer/python-net/groupdocs.viewer.results/viewinfo/) से विरासत में मिली) |

### प्रॉपर्टीज़
| प्रॉपर्टी | विवरण |
| :- | :- |
| [layers](/viewer/python-net/groupdocs.viewer.results/cadviewinfo/layers/) | CAD ड्राइंग में शामिल लेयर्स की सूची। |
| [layouts](/viewer/python-net/groupdocs.viewer.results/cadviewinfo/layouts/) | CAD ड्राइंग में शामिल लेआउट्स की सूची। |
| [file_type](/viewer/python-net/groupdocs.viewer.results/viewinfo/file_type/) | फ़ाइल का प्रकार। ([`ViewInfo`](/viewer/python-net/groupdocs.viewer.results/viewinfo/) से विरासत में मिला) |
| [pages](/viewer/python-net/groupdocs.viewer.results/viewinfo/pages/) | देखने के लिए पृष्ठों की सूची। ([`ViewInfo`](/viewer/python-net/groupdocs.viewer.results/viewinfo/) से विरासत में मिली) |

### उदाहरण

```python
from typing import cast
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import ViewInfoOptions
from groupdocs.viewer.results import CadViewInfo

def get_cad_info():
    with Viewer("sample.dwg") as viewer:
        info = viewer.get_view_info(ViewInfoOptions.for_html_view())
        cad_info = cast(CadViewInfo, info)

        print("File type:", cad_info.file_type)
        print("Pages count:", len(cad_info.pages))
        print("Layers:")
        for layer in cad_info.layers:
            print(f"  {layer.name} (visible={layer.visible})")
        print("Layouts:")
        for layout in cad_info.layouts:
            print(f"  {layout.name} ({layout.width}x{layout.height})")

if __name__ == "__main__":
    get_cad_info()
```

### Guides
`CadViewInfo` का उपयोग करने वाले कार्य गाइड:

* [Get Document Information](/viewer/python-net/guides/get-document-info/)

### साथ में देखें
* module [`groupdocs.viewer.results`](/viewer/python-net/groupdocs.viewer.results/)
