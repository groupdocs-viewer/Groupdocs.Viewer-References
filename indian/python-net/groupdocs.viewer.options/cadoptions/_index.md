---
title: "CadOptions क्लास"
second_title: "GroupDocs.Viewer Python के लिए .NET के माध्यम से API संदर्भ"
description: "CAD ड्रॉइंग्स को रेंडर करने के विकल्प।"
type: docs
url: /hi/python-net/groupdocs.viewer.options/cadoptions/
is_root: false
weight: 30
---


## CadOptions class

CAD ड्रॉइंग्स को रेंडर करने के विकल्प।

अधिक जानकारी और कोड उदाहरणों के लिए, Render CAD drawings and models as HTML, PDF, and image files और Specify rendering options for CAD files दस्तावेज़ देखें।

CadOptions प्रकार निम्नलिखित सदस्य उजागर करता है:

### मेथड्स
| मेथड | विवरण |
| :- | :- |
| [for_rendering_by_height](/viewer/python-net/groupdocs.viewer.options/cadoptions/for_rendering_by_height/#height) | ऊँचाई के आधार पर रेंडरिंग के लिए CadOptions इंस्टेंस को प्रारंभ करता है। |
| [for_rendering_by_scale_factor](/viewer/python-net/groupdocs.viewer.options/cadoptions/for_rendering_by_scale_factor/#scale_factor) | स्केल फ़ैक्टर के आधार पर रेंडरिंग के लिए CadOptions इंस्टेंस को प्रारंभ करता है। |
| [for_rendering_by_width](/viewer/python-net/groupdocs.viewer.options/cadoptions/for_rendering_by_width/#width) | चौड़ाई के आधार पर रेंडरिंग के लिए [`CadOptions`](/viewer/python-net/groupdocs.viewer.options/cadoptions/) क्लास का एक इंस्टेंस प्रारंभ करता है। |
| [for_rendering_by_width_and_height](/viewer/python-net/groupdocs.viewer.options/cadoptions/for_rendering_by_width_and_height/#width-height) | चौड़ाई और ऊँचाई के आधार पर रेंडरिंग के लिए CadOptions क्लास का एक इंस्टेंस प्रारंभ करता है। |

### प्रॉपर्टीज़
| प्रॉपर्टी | विवरण |
| :- | :- |
| [background_color](/viewer/python-net/groupdocs.viewer.options/cadoptions/background_color/) | छवि पृष्ठभूमि रंग। |
| [enable_performance_conversion_mode](/viewer/python-net/groupdocs.viewer.options/cadoptions/enable_performance_conversion_mode/) | यह फ़्लैग सभी CAD फ़ॉर्मैट्स के लिए प्रदर्शन-केंद्रित रूपांतरण मोड को सक्षम करता है, जहाँ इसे True सेट करने से रूपांतरण तेज़ हो जाता है लेकिन आउटपुट गुणवत्ता घटती है; अधिकतम गुणवत्ता के लिए डिफ़ॉल्ट रूप से False रहता है। |
| [height](/viewer/python-net/groupdocs.viewer.options/cadoptions/height/) | आउटपुट परिणाम की ऊँचाई (पिक्सेल में)। |
| [layers](/viewer/python-net/groupdocs.viewer.options/cadoptions/layers/) | रेंडर करने के लिए CAD ड्रॉइंग लेयर्स। |
| [layout_name](/viewer/python-net/groupdocs.viewer.options/cadoptions/layout_name/) | रेंडर करने के लिए विशिष्ट लेआउट का नाम। लेआउट नाम केस-सेंसिटिव है। |
| [pc3_file](/viewer/python-net/groupdocs.viewer.options/cadoptions/pc3_file/) | PC3 प्लॉटर कॉन्फ़िगरेशन फ़ाइल। |
| [render_layouts](/viewer/python-net/groupdocs.viewer.options/cadoptions/render_layouts/) | यह फ़्लैग दर्शाता है कि CAD दस्तावेज़ से लेआउट्स रेंडर किए जाने चाहिए या नहीं। |
| [scale_factor](/viewer/python-net/groupdocs.viewer.options/cadoptions/scale_factor/) | स्केल फ़ैक्टर। 1 से बड़ा मान आउटपुट परिणाम को बड़ा करता है; 0 और 1 के बीच का मान आउटपुट परिणाम को छोटा करता है। |
| [tiles](/viewer/python-net/groupdocs.viewer.options/cadoptions/tiles/) | रेंडर करने के लिए ड्रॉइंग क्षेत्र। |
| [width](/viewer/python-net/groupdocs.viewer.options/cadoptions/width/) | आउटपुट परिणाम की चौड़ाई (पिक्सेल में)। |

### उदाहरण

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions, CadOptions

def enable_performance_mode():
    # CAD फ़ाइल लोड करें
    with Viewer("sample.dwg") as viewer:
        view_options = HtmlViewOptions.for_embedded_resources(
            "enable_performance_mode/Output-Page#{0}.html"
        )
        # चौड़ाई के अनुसार रेंडर करें और प्रदर्शन मोड सक्षम करें
        view_options.cad_options = CadOptions.for_rendering_by_width(1000)
        view_options.cad_options.enable_performance_conversion_mode = True

        viewer.view(view_options)

if __name__ == "__main__":
    enable_performance_mode()
```

### साथ में देखें
* module [`groupdocs.viewer.options`](/viewer/python-net/groupdocs.viewer.options/)
