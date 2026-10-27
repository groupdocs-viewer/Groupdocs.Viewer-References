---
title: "PdfOptions क्लास"
second_title: "GroupDocs.Viewer Python के लिए .NET के माध्यम से API संदर्भ"
description: "PDF दस्तावेज़ों को रेंडर करने के विकल्पों को दर्शाता है।"
type: docs
url: /hi/python-net/groupdocs.viewer.options/pdfoptions/
is_root: false
weight: 160
---


## PdfOptions class

PDF दस्तावेज़ों को रेंडर करने के विकल्पों को दर्शाता है।

विवरण के लिए, दस्तावेज़ देखें।

PdfOptions प्रकार निम्नलिखित सदस्यों को उजागर करता है:

### कंस्ट्रक्टर्स
| कंस्ट्रक्टर | विवरण |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.options/pdfoptions/__init__/) | PdfOptions क्लास का एक नया इंस्टेंस प्रारंभ करता है। |

### प्रॉपर्टीज़
| प्रॉपर्टी | विवरण |
| :- | :- |
| [disable_chars_grouping](/viewer/python-net/groupdocs.viewer.options/pdfoptions/disable_chars_grouping/) | यह प्रॉपर्टी पृष्ठ रेंडरिंग के दौरान सटीक प्रतीक स्थिति के लिए प्रतीक समूह बनाना निष्क्रिय करती है। |
| [disable_copy_protection](/viewer/python-net/groupdocs.viewer.options/pdfoptions/disable_copy_protection/) | HTML में रेंडर करते समय यह प्रॉपर्टी कंटेंट कॉपी प्रोटेक्शन को निष्क्रिय करती है। |
| [disable_font_license_verifications](/viewer/python-net/groupdocs.viewer.options/pdfoptions/disable_font_license_verifications/) | वर्तमान XPS/OXPS दस्तावेज़ में सभी फ़ॉन्ट्स के लिए यह प्रॉपर्टी किसी भी लाइसेंस प्रतिबंध को निष्क्रिय करती है। |
| [enable_font_hinting](/viewer/python-net/groupdocs.viewer.options/pdfoptions/enable_font_hinting/) | यह प्रॉपर्टी फ़ॉन्ट हिंटिंग को सक्षम करती है। |
| [enable_layered_rendering](/viewer/python-net/groupdocs.viewer.options/pdfoptions/enable_layered_rendering/) | HTML में रेंडर करते समय मूल PDF दस्तावेज़ के z-order में टेक्स्ट और ग्राफ़िक्स को रेंडर करने के लिए यह प्रॉपर्टी सक्षम करती है। |
| [fixed_layout](/viewer/python-net/groupdocs.viewer.options/pdfoptions/fixed_layout/) | फ़िक्स्ड लेआउट विकल्प PDF और EPUB दस्तावेज़ों को फ़िक्स्ड लेआउट के साथ HTML में रेंडर करने को सक्षम करता है। |
| [image_quality](/viewer/python-net/groupdocs.viewer.options/pdfoptions/image_quality/) | HTML में रेंडर करते समय इमेज संसाधनों के लिए आउटपुट इमेज क्वालिटी। डिफ़ॉल्ट क्वालिटी `ImageQuality.LOW` है। |
| [render_original_page_size](/viewer/python-net/groupdocs.viewer.options/pdfoptions/render_original_page_size/) | आउटपुट पृष्ठ आकार को स्रोत PDF दस्तावेज़ के पृष्ठ आकार से मेल खाने के लिए सेट किया गया है। |
| [render_text_as_image](/viewer/python-net/groupdocs.viewer.options/pdfoptions/render_text_as_image/) | यह विकल्प PDF फ़ाइलों में टेक्स्ट को HTML आउटपुट में इमेज के रूप में रेंडर करने को सक्षम करता है। |
| [wrap_images_in_svg](/viewer/python-net/groupdocs.viewer.options/pdfoptions/wrap_images_in_svg/) | यह प्रॉपर्टी आउटपुट HTML दस्तावेज़ में प्रत्येक इमेज को SVG टैग में रैप करके आउटपुट क्वालिटी सुधारती है। |

### उदाहरण

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PngViewOptions

with Viewer("sample.pdf") as viewer:
    view_options = PngViewOptions("output_{0}.png")
    # PDF पृष्ठों को इमेज में रेंडर करते समय फ़ॉन्ट हिंटिंग सक्षम करें।
    view_options.pdf_options.enable_font_hinting = True
    viewer.view(view_options)
```

### साथ में देखें
* module [`groupdocs.viewer.options`](/viewer/python-net/groupdocs.viewer.options/)
