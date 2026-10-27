---
title: "VisioRenderingOptions क्लास"
second_title: "GroupDocs.Viewer Python के लिए .NET के माध्यम से API संदर्भ"
description: "Visio दस्तावेज़ों को रेंडर करने के विकल्प का प्रतिनिधित्व करता है।"
type: docs
url: /hi/python-net/groupdocs.viewer.options/visiorenderingoptions/
is_root: false
weight: 350
---


## VisioRenderingOptions class

Visio दस्तावेज़ों को रेंडर करने के विकल्प का प्रतिनिधित्व करता है।

विवरण के लिए, दस्तावेज़ देखें।

VisioRenderingOptions प्रकार निम्नलिखित सदस्य उजागर करता है:

### कंस्ट्रक्टर्स
| कंस्ट्रक्टर | विवरण |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.options/visiorenderingoptions/__init__/) | एक उदाहरण को प्रारंभ करता है [`VisioRenderingOptions`](/viewer/python-net/groupdocs.viewer.options/visiorenderingoptions/) क्लास का। |

### प्रॉपर्टीज़
| प्रॉपर्टी | विवरण |
| :- | :- |
| [figure_width](/viewer/python-net/groupdocs.viewer.options/visiorenderingoptions/figure_width/) | फ़िगर की चौड़ाई; ऊँचाई स्वचालित रूप से गणना की जाती है। डिफ़ॉल्ट मान 100 है। |
| [render_figures_only](/viewer/python-net/groupdocs.viewer.options/visiorenderingoptions/render_figures_only/) | यह प्रॉपर्टी केवल Visio फ़िगर को रेंडर करती है, न कि एक डायग्राम। |

### उदाहरण

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions

def render_visio_shapes_only():
    # Visio दस्तावेज़ लोड करें
    with Viewer("map.vsdx") as viewer:
        # Visio फ़ाइल को PDF में परिवर्तित करें।
        view_options = PdfViewOptions("render_visio_shapes_only/visio_shapes_only.pdf")
        # केवल मास्टर शैप्स को रेंडर करें।
        view_options.visio_rendering_options.render_figures_only = True
        # पिक्सेल में शैप की चौड़ाई निर्दिष्ट करें।
        view_options.visio_rendering_options.figure_width = 200
        viewer.view(view_options)

if __name__ == "__main__":
    render_visio_shapes_only()
```

### साथ में देखें
* module [`groupdocs.viewer.options`](/viewer/python-net/groupdocs.viewer.options/)
