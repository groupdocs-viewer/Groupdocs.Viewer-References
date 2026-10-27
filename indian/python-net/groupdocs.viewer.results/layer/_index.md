---
title: "Layer वर्ग"
second_title: "GroupDocs.Viewer Python के लिए .NET के माध्यम से API संदर्भ"
description: "CAD ड्राइंग में सम्मिलित एक लेयर का प्रतिनिधित्व करता है।"
type: docs
url: /hi/python-net/groupdocs.viewer.results/layer/
is_root: false
weight: 60
---


## Layer class

CAD ड्राइंग में सम्मिलित एक लेयर का प्रतिनिधित्व करता है।

Layer प्रकार निम्नलिखित सदस्यों को उजागर करता है:

### कंस्ट्रक्टर्स
| कंस्ट्रक्टर | विवरण |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.results/layer/__init__/) | [`Layer`](/viewer/python-net/groupdocs.viewer.results/layer/) क्लास का एक नया उदाहरण प्रारंभ करता है। |
| [__init__](/viewer/python-net/groupdocs.viewer.results/layer/__init__/#name) | एक नया Layer उदाहरण प्रारंभ करता है। |
| [__init__](/viewer/python-net/groupdocs.viewer.results/layer/__init__/#name-visible) | एक नया Layer उदाहरण प्रारंभ करता है। |

### मेथड्स
| मेथड | विवरण |
| :- | :- |
| [equals](/viewer/python-net/groupdocs.viewer.results/layer/equals/#other) | निर्धारित करता है कि वर्तमान Layer निर्दिष्ट Layer वस्तु के समान है या नहीं। |
| [equals](/viewer/python-net/groupdocs.viewer.results/layer/equals/#obj) | जाँचता है कि वर्तमान [`Layer`](/viewer/python-net/groupdocs.viewer.results/layer/) निर्दिष्ट वस्तु के बराबर है या नहीं। |
| [equals_layer](/viewer/python-net/groupdocs.viewer.results/layer/equals_layer/) |  |
| [equals_object](/viewer/python-net/groupdocs.viewer.results/layer/equals_object/) |  |
| [get_hash_code](/viewer/python-net/groupdocs.viewer.results/layer/get_hash_code/) | वर्तमान Layer वस्तु के लिए हैश कोड लौटाता है। |
| [to_string](/viewer/python-net/groupdocs.viewer.results/layer/to_string/) | एक स्ट्रिंग लौटाता है जो वर्तमान ऑब्जेक्ट का प्रतिनिधित्व करती है। |

### प्रॉपर्टीज़
| प्रॉपर्टी | विवरण |
| :- | :- |
| [name](/viewer/python-net/groupdocs.viewer.results/layer/name/) | लेयर का नाम। |
| [visible](/viewer/python-net/groupdocs.viewer.results/layer/visible/) | लेयर दृश्यता संकेतक। |

### उदाहरण

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions
from groupdocs.viewer.results import Layer

with Viewer("sample.dwg") as viewer:
    options = PdfViewOptions("output.pdf")
    options.cad_options.layers = [Layer("QUADRANT")]
    viewer.view(options)
```

### साथ में देखें
* module [`groupdocs.viewer.results`](/viewer/python-net/groupdocs.viewer.results/)
