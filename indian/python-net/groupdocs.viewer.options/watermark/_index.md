---
title: "Watermark क्लास"
second_title: "GroupDocs.Viewer Python के लिए .NET के माध्यम से API संदर्भ"
description: "एक टेक्स्ट वॉटरमार्क का प्रतिनिधित्व करता है।"
type: docs
url: /hi/python-net/groupdocs.viewer.options/watermark/
is_root: false
weight: 360
---


## Watermark class

एक टेक्स्ट वॉटरमार्क का प्रतिनिधित्व करता है।

अधिक जानकारी के लिए ऑनलाइन दस्तावेज़ देखें।

Watermark प्रकार निम्नलिखित सदस्य प्रदर्शित करता है:

### कंस्ट्रक्टर्स
| कंस्ट्रक्टर | विवरण |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.options/watermark/__init__/#text) | [`Watermark`](/viewer/python-net/groupdocs.viewer.options/watermark/) क्लास का एक उदाहरण प्रारंभ करता है। |

### प्रॉपर्टीज़
| प्रॉपर्टी | विवरण |
| :- | :- |
| [color](/viewer/python-net/groupdocs.viewer.options/watermark/color/) | वॉटरमार्क का रंग। डिफ़ॉल्ट मान `Rgb24Color.known_colors.css_level1.red` है। |
| [font_name](/viewer/python-net/groupdocs.viewer.options/watermark/font_name/) | वॉटरमार्क के लिए उपयोग किया गया फ़ॉन्ट नाम। |
| [position](/viewer/python-net/groupdocs.viewer.options/watermark/position/) | वॉटरमार्क की स्थिति। डिफ़ॉल्ट मान `Position.diagonal` है। |
| [size](/viewer/python-net/groupdocs.viewer.options/watermark/size/) | वॉटरमार्क का आकार। डिफ़ॉल्ट मान [`Size.full_size`](/viewer/python-net/groupdocs.viewer.options/size/full_size/) है। |
| [text](/viewer/python-net/groupdocs.viewer.options/watermark/text/) | वॉटरमार्क पाठ। |

### उदाहरण

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions, Watermark

def add_text_watermark():
    # दस्तावेज़ लोड करें
    with Viewer("sample.docx") as viewer:
        # एक HTML फ़ाइल बनाएं।
        viewOptions = HtmlViewOptions.for_embedded_resources(
            "add_text_watermark/output-watermark.html"
        )
        # वॉटरमार्क जोड़ें।
        viewOptions.watermark = Watermark("This is a watermark")
        viewer.view(viewOptions)

if __name__ == "__main__":
    add_text_watermark()
```

### Guides
`Watermark` का उपयोग करने वाले कार्य गाइड:

* [Add text watermarks](/viewer/python-net/guides/add-text-watermark/)

### साथ में देखें
* module [`groupdocs.viewer.options`](/viewer/python-net/groupdocs.viewer.options/)
