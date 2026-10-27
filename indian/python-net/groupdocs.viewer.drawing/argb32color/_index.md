---
title: "Argb32Color क्लास"
second_title: "GroupDocs.Viewer Python के लिए .NET के माध्यम से API संदर्भ"
description: "ARGB फ़ॉर्मेट में 32-बिट रंग का प्रतिनिधित्व करता है, प्रत्येक चैनल (Alpha, Red, Green, Blue) के लिए 8 बिट्स के साथ।"
type: docs
url: /hi/python-net/groupdocs.viewer.drawing/argb32color/
is_root: false
weight: 10
---


## Argb32Color class

ARGB प्रारूप में 32-बिट रंग का प्रतिनिधित्व करता है, प्रत्येक चैनल (Alpha, Red, Green, Blue) के लिए 8 बिट्स के साथ। पारदर्शिता का समर्थन करता है।

यह प्रकार (लेकिन केवल CSS ऑपरेशनों तक सीमित नहीं) उपयोगी होने के लिए डिज़ाइन किया गया है। अधिक देखें: https://developer.mozilla.org/en-US/docs/Web/CSS/color_value

Argb32Color प्रकार निम्नलिखित सदस्यों को उजागर करता है:

### कंस्ट्रक्टर्स
| कंस्ट्रक्टर | विवरण |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.drawing/argb32color/__init__/) |  |

### मेथड्स
| मेथड | विवरण |
| :- | :- |
| [equals](/viewer/python-net/groupdocs.viewer.drawing/argb32color/equals/#other) | जाँचता है कि यह रंग निर्दिष्ट [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/) के बराबर है या नहीं। |
| [equals](/viewer/python-net/groupdocs.viewer.drawing/argb32color/equals/#other) | निर्धारित करता है कि यह रंग निर्दिष्ट [`Rgb24Color`](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/) के बराबर है या नहीं। |
| [equals](/viewer/python-net/groupdocs.viewer.drawing/argb32color/equals/#obj) | जाँचता है कि यह रंग निर्दिष्ट अनकास्टेड रंग के बराबर है या नहीं। |
| [equals_argb_32_color](/viewer/python-net/groupdocs.viewer.drawing/argb32color/equals_argb_32_color/) |  |
| [equals_object](/viewer/python-net/groupdocs.viewer.drawing/argb32color/equals_object/) |  |
| [equals_rgb_24_color](/viewer/python-net/groupdocs.viewer.drawing/argb32color/equals_rgb_24_color/) |  |
| [from_argb](/viewer/python-net/groupdocs.viewer.drawing/argb32color/from_argb/#argb) | एक 32-बिट ARGB मान से Argb32Color इंस्टेंस बनाता है, जो `System.Drawing.Color.ToArgb()` द्वारा उत्पन्न मानों के साथ संगत है। |
| [from_other_with_alpha](/viewer/python-net/groupdocs.viewer.drawing/argb32color/from_other_with_alpha/#other-new_alpha) | निर्दिष्ट इंस्टेंस से एक नया [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/) इंस्टेंस बनाता है, लेकिन पुनः परिभाषित अल्फा (अपारदर्शिता) मान के साथ। |
| [from_other_with_alpha](/viewer/python-net/groupdocs.viewer.drawing/argb32color/from_other_with_alpha/#other-new_alpha) | एक निर्दिष्ट Rgb24Color से नया Argb32Color इंस्टेंस बनाता है, लेकिन निर्दिष्ट अल्फा (अपारदर्शिता) मान के साथ। |
| [from_other_with_alpha_argb_32_color](/viewer/python-net/groupdocs.viewer.drawing/argb32color/from_other_with_alpha_argb_32_color/) |  |
| [from_other_with_alpha_rgb_24_color](/viewer/python-net/groupdocs.viewer.drawing/argb32color/from_other_with_alpha_rgb_24_color/) |  |
| [from_rgb](/viewer/python-net/groupdocs.viewer.drawing/argb32color/from_rgb/#red-green-blue) | निर्दिष्ट रेड, ग्रीन, ब्लू चैनलों से एक Argb32Color मान बनाता है, जिसमें अल्फा चैनल पूरी तरह अपारदर्शी सेट किया गया है। |
| [from_rgba](/viewer/python-net/groupdocs.viewer.drawing/argb32color/from_rgba/#red-green-blue-alpha) | निर्दिष्ट रेड, ग्रीन, ब्लू और अल्फा चैनल मानों से एक [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/) मान बनाता है। |
| [from_single_value_rgb](/viewer/python-net/groupdocs.viewer.drawing/argb32color/from_single_value_rgb/#value) | सभी चैनलों पर लागू एकल बाइट मान से पूरी तरह अपारदर्शी (A=255) रंग बनाता है। |
| [get_brightness](/viewer/python-net/groupdocs.viewer.drawing/argb32color/get_brightness/) | इस [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/) इंस्टेंस के लिए Hue‑Saturation‑Lightness (HSL) लाइटनेस/ब्राइटनेस लौटाता है। |
| [get_hash_code](/viewer/python-net/groupdocs.viewer.drawing/argb32color/get_hash_code/) | एक हैश कोड लौटाता है जो वर्तमान रंग को परिभाषित करता है; `System.Drawing.Color.GetHashCode` के साथ संगत नहीं है। |
| [get_hue](/viewer/python-net/groupdocs.viewer.drawing/argb32color/get_hue/) | इस [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/) इंस्टेंस के लिए Hue‑Saturation‑Lightness (HSL) ह्यू मान डिग्री में लौटाता है; यदि R == G == B है, तो ह्यू का कोई अर्थ नहीं है और मेथड 0 लौटाता है। |
| [get_saturation](/viewer/python-net/groupdocs.viewer.drawing/argb32color/get_saturation/) | इस [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/) इंस्टेंस का Hue‑Saturation‑Lightness (HSL) सैचुरेशन लौटाता है। |
| [to_argb](/viewer/python-net/groupdocs.viewer.drawing/argb32color/to_argb/) | इस [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/) इंस्टेंस का ARGB मान लौटाता है, जो `System.Drawing.Color.ToArgb()` मेथड के साथ संगत है। |
| [to_hex_rgb](/viewer/python-net/groupdocs.viewer.drawing/argb32color/to_hex_rgb/) | इस [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/) उदाहरण को हेक्साडेसिमल नोटेशन `##RRGGBB` में एक स्ट्रिंग के रूप में सीरियलाइज़ करता है, जिसमें अल्फा चैनल नहीं होता। |
| [to_hex_rgba](/viewer/python-net/groupdocs.viewer.drawing/argb32color/to_hex_rgba/) | इस [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/) उदाहरण को हेक्साडेसिमल नोटेशन `##RRGGBBAA` में एक स्ट्रिंग के रूप में सीरियलाइज़ करता है, जिसमें अल्फा चैनल शामिल होता है। |
| [to_rgb](/viewer/python-net/groupdocs.viewer.drawing/argb32color/to_rgb/) | इस [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/) उदाहरण को `rgb` CSS फ़ंक्शन नोटेशन में सीरियलाइज़ करता है, अल्फा चैनल को छोड़ते हुए। |
| [to_rgba](/viewer/python-net/groupdocs.viewer.drawing/argb32color/to_rgba/) | इस [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/) उदाहरण को 'rgba' CSS फ़ंक्शन नोटेशन में सीरियलाइज़ करता है। |
| [to_string](/viewer/python-net/groupdocs.viewer.drawing/argb32color/to_string/) | Argb32Color उदाहरण को पारदर्शिता के आधार पर सबसे उपयुक्त CSS फ़ंक्शन नोटेशन में सीरियलाइज़ करता है। |

### प्रॉपर्टीज़
| प्रॉपर्टी | विवरण |
| :- | :- |
| [a](/viewer/python-net/groupdocs.viewer.drawing/argb32color/a/) | रंग का अल्फा घटक 0..255 की सीमा में 8-बिट अनसाइन्ड इंटीजर के रूप में। |
| [alpha](/viewer/python-net/groupdocs.viewer.drawing/argb32color/alpha/) | रंग का अल्फा घटक 0..1 की सीमा में फ्लोट के रूप में। |
| [b](/viewer/python-net/groupdocs.viewer.drawing/argb32color/b/) | रंग का नीला घटक 0..255 की सीमा में 8-बिट अनसाइन्ड इंटीजर के रूप में। |
| [g](/viewer/python-net/groupdocs.viewer.drawing/argb32color/g/) | रंग का हरा घटक 0..255 की सीमा में 8-बिट अनसाइन्ड इंटीजर के रूप में। |
| [is_default](/viewer/python-net/groupdocs.viewer.drawing/argb32color/is_default/) | यह प्रॉपर्टी दर्शाती है कि यह [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/) उदाहरण डिफ़ॉल्ट (पारदर्शी) है या नहीं, जिसका अर्थ है सभी चार चैनल 0 पर सेट हैं; यह [`Argb32Color.is_empty`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/is_empty/) के बराबर है। |
| [is_empty](/viewer/python-net/groupdocs.viewer.drawing/argb32color/is_empty/) | यह प्रॉपर्टी दर्शाती है कि यह [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/) उदाहरण अनइनिशियलाइज़्ड है (सभी चार चैनल 0 पर सेट हैं)। यह डिफ़ॉल्ट या पारदर्शी रंग के बराबर है और [`Argb32Color.is_default`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/is_default/) से मेल खाता है। |
| [is_fully_opaque](/viewer/python-net/groupdocs.viewer.drawing/argb32color/is_fully_opaque/) | यह प्रॉपर्टी दर्शाती है कि यह [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/) उदाहरण पूरी तरह अपारदर्शी है, बिना किसी पारदर्शिता के (इसका अल्फा चैनल अधिकतम मान पर है)। |
| [is_fully_transparent](/viewer/python-net/groupdocs.viewer.drawing/argb32color/is_fully_transparent/) | यह प्रॉपर्टी दर्शाती है कि यह [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/) उदाहरण पूरी तरह पारदर्शी है—इसका अल्फा चैनल न्यूनतम (0) मान पर है, इसलिए R, G, और B चैनलों का कोई दृश्य प्रभाव नहीं रहता। |
| [is_translucent](/viewer/python-net/groupdocs.viewer.drawing/argb32color/is_translucent/) | यह प्रॉपर्टी दर्शाती है कि यह [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/) उदाहरण अर्ध-पारदर्शी है (पूरी तरह पारदर्शी नहीं, लेकिन पूरी तरह अपारदर्शी भी नहीं)। |
| [r](/viewer/python-net/groupdocs.viewer.drawing/argb32color/r/) | रंग का लाल घटक 0..255 की सीमा में 8-बिट अनसाइन्ड इंटीजर के रूप में। |
| [value](/viewer/python-net/groupdocs.viewer.drawing/argb32color/value/) | रंग का 32-बिट साइन्ड इंटीजर प्रतिनिधित्व। |

### फ़ील्ड्स
| फ़ील्ड | विवरण |
| :- | :- |
| [EMPTY](/viewer/python-net/groupdocs.viewer.drawing/argb32color/empty/) | एक खाली रंग लौटाता है, जिसमें कोई चैनल जानकारी नहीं होती और यह पूरी तरह पारदर्शी होता है। यह '' के समान है। डिफ़ॉल्ट मान। |
| [TRANSPARENT](/viewer/python-net/groupdocs.viewer.drawing/argb32color/transparent/) | पूरी तरह पारदर्शी खाली रंग। यह डिफ़ॉल्ट '' रंग मान के समान है। |

### उदाहरण

```python
from groupdocs.viewer.drawing import Argb32Color

# एक पूरी तरह अपारदर्शी पीला रंग बनाएं (RGB 255, 255, 0)
yellow = Argb32Color.from_rgb(255, 255, 0)
```

### साथ में देखें
* module [`groupdocs.viewer.drawing`](/viewer/python-net/groupdocs.viewer.drawing/)
