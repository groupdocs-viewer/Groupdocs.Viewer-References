---
title: "Rgb24Color वर्ग"
second_title: "GroupDocs.Viewer Python के लिए .NET के माध्यम से API संदर्भ"
description: "24-बिट RGB रंग का प्रतिनिधित्व करता है, प्रत्येक चैनल (Red, Green, Blue) के लिए 8 बिट्स के साथ और कोई पारदर्शिता नहीं।"
type: docs
url: /hi/python-net/groupdocs.viewer.drawing/rgb24color/
is_root: false
weight: 80
---


## Rgb24Color class

24-बिट RGB रंग का प्रतिनिधित्व करता है, प्रत्येक चैनल (Red, Green, Blue) के लिए 8 बिट्स के साथ और कोई पारदर्शिता नहीं।

यह प्रकार (लेकिन केवल CSS ऑपरेशनों तक सीमित नहीं) उपयोगी होने के लिए डिज़ाइन किया गया है। अधिक देखें: https://developer.mozilla.org/en-US/docs/Web/CSS/color_value

Rgb24Color प्रकार निम्नलिखित सदस्यों को उजागर करता है:

### कंस्ट्रक्टर्स
| कंस्ट्रक्टर | विवरण |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/__init__/) |  |

### मेथड्स
| मेथड | विवरण |
| :- | :- |
| [equals](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/equals/#other) | निर्धारित करता है कि यह रंग निर्दिष्ट [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/) के बराबर है या नहीं। |
| [equals](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/equals/#other) | निर्दिष्ट [`Rgb24Color`](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/) रंग के साथ इस रंग की समानता की जाँच करता है। |
| [equals](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/equals/#obj) | निर्दिष्ट अनकास्टेड रंग के विरुद्ध इस रंग की जाँच करता है। |
| [equals_argb_32_color](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/equals_argb_32_color/) |  |
| [equals_object](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/equals_object/) |  |
| [equals_rgb_24_color](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/equals_rgb_24_color/) |  |
| [from_rgb](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/from_rgb/#red-green-blue) | निर्दिष्ट लाल, हरे, और नीले चैनल मानों से एक [`Rgb24Color`](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/) मान बनाता है। |
| [get_brightness](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/get_brightness/) | इस [`Rgb24Color`](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/) उदाहरण के लिए Hue‑Saturation‑Lightness (HSL) लाइटनेस/ब्राइटनेस लौटाता है। |
| [get_hash_code](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/get_hash_code/) | वर्तमान रंग को परिभाषित करने वाला हैश कोड लौटाता है। `System.Drawing.Color.GetHashCode` के साथ संगत नहीं है। |
| [get_hue](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/get_hue/) | डिग्री में व्यक्त HSL रंग स्थान में रंग का ह्यू घटक लौटाता है। यदि रंग ग्रेस्केल है (R == G == B), तो ह्यू अपरिभाषित होता है और विधि 0 लौटाती है। |
| [get_saturation](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/get_saturation/) | इस [`Rgb24Color`](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/) उदाहरण के लिए Hue‑Saturation‑Lightness (HSL) संतृप्ति। |
| [to_argb](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/to_argb/) | इस [`Rgb24Color`](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/) उदाहरण का ARGB मान लौटाता है, जो `System.Drawing.Color` के साथ संगत है। |
| [to_hex](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/to_hex/) | इस रंग को हेक्साडेसिमल स्ट्रिंग प्रतिनिधित्व में लौटाता है। |
| [to_rgb](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/to_rgb/) | इस [`Rgb24Color`](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/) उदाहरण को 'rgb' CSS फ़ंक्शन नोटेशन में क्रमबद्ध करता है। |
| [to_string](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/to_string/) | इस [`Rgb24Color`](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/) उदाहरण को 'rgb(r, g, b)' प्रारूप में क्रमबद्ध करता है। |

### प्रॉपर्टीज़
| प्रॉपर्टी | विवरण |
| :- | :- |
| [b](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/b/) | रंग का नीला घटक 8-बिट अनसाइन्ड इंटीजर [0..255] के रूप में। |
| [g](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/g/) | रंग का हरा घटक 0..255 की सीमा में 8-बिट अनसाइन्ड इंटीजर के रूप में। |
| [is_default](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/is_default/) | यह प्रॉपर्टी दर्शाती है कि यह [`Rgb24Color`](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/) उदाहरण डिफ़ॉल्ट (काला) है या नहीं – सभी तीन चैनल 0 पर सेट हैं। |
| [r](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/r/) | रंग का लाल घटक 0..255 की सीमा में 8-बिट अनसाइन्ड इंटीजर के रूप में। |

### साथ में देखें
* module [`groupdocs.viewer.drawing`](/viewer/python-net/groupdocs.viewer.drawing/)
