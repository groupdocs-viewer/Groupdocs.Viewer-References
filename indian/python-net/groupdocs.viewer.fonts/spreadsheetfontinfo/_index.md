---
title: "SpreadsheetFontInfo क्लास"
second_title: "GroupDocs.Viewer Python के लिए .NET के माध्यम से API संदर्भ"
description: "एक स्प्रेडशीट दस्तावेज़ से लोड किए गए Viewer इंस्टेंस में फ़ॉन्ट की मेटा जानकारी और बाइनरी डेटा को संलग्न करता है।"
type: docs
url: /hi/python-net/groupdocs.viewer.fonts/spreadsheetfontinfo/
is_root: false
weight: 100
---


## SpreadsheetFontInfo class

एक स्प्रेडशीट दस्तावेज़ से फ़ॉन्ट के मेटा जानकारी और बाइनरी डेटा को encapsulate करता है जो एक [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/) इंस्टेंस में लोड किया गया है। स्प्रेडशीट दस्तावेज़ों में एम्बेडेड फ़ॉन्ट नहीं हो सकते, इसलिए एक फ़ॉन्ट जो [`Viewer.get_all_fonts`](/viewer/python-net/groupdocs.viewer/viewer/get_all_fonts/) द्वारा लौटाया जाता है, उसे उस ऑपरेटिंग सिस्टम में स्थापित किया जाता है जहाँ viewer चलता है।

SpreadsheetFontInfo प्रकार निम्नलिखित सदस्य उजागर करता है:

### कंस्ट्रक्टर्स
| कंस्ट्रक्टर | विवरण |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.fonts/spreadsheetfontinfo/__init__/) |  |

### मेथड्स
| मेथड | विवरण |
| :- | :- |
| [serialize_to_css](/viewer/python-net/groupdocs.viewer.fonts/spreadsheetfontinfo/serialize_to_css/#output) | फ़ॉन्ट जानकारी को @font-face at-rule के रूप में क्रमबद्ध करता है और इसे निर्दिष्ट टेक्स्ट राइटर में लिखता है। |
| [serialize_to_css_text_writer](/viewer/python-net/groupdocs.viewer.fonts/spreadsheetfontinfo/serialize_to_css_text_writer/) |  |

### प्रॉपर्टीज़
| प्रॉपर्टी | विवरण |
| :- | :- |
| [charset](/viewer/python-net/groupdocs.viewer.fonts/spreadsheetfontinfo/charset/) | इस फ़ॉन्ट का कैरेक्टर सेट। |
| [color](/viewer/python-net/groupdocs.viewer.fonts/spreadsheetfontinfo/color/) | इस फ़ॉन्ट का रंग। |
| [content](/viewer/python-net/groupdocs.viewer.fonts/spreadsheetfontinfo/content/) | इस फ़ॉन्ट की सामग्री बाइट ऐरे के रूप में है। यदि केवल इस फ़ॉन्ट की मेटा जानकारी उपलब्ध है और उसका बाइनरी कंटेंट उपलब्ध नहीं है, तो प्रॉपर्टी None लौटाती है। |
| [family_name](/viewer/python-net/groupdocs.viewer.fonts/spreadsheetfontinfo/family_name/) | फ़ॉन्ट का फ़ैमिली नाम, शैली के बिना, कभी null या खाली स्ट्रिंग नहीं होता। |
| [format](/viewer/python-net/groupdocs.viewer.fonts/spreadsheetfontinfo/format/) | इस फ़ॉन्ट का फ़ॉर्मेट। |
| [is_strikeout](/viewer/python-net/groupdocs.viewer.fonts/spreadsheetfontinfo/is_strikeout/) | फ़ॉन्ट में एकल स्ट्राइकआउट है। |
| [is_underline](/viewer/python-net/groupdocs.viewer.fonts/spreadsheetfontinfo/is_underline/) | फ़ॉन्ट में अंडरलाइन है। |
| [style](/viewer/python-net/groupdocs.viewer.fonts/spreadsheetfontinfo/style/) | इस फ़ॉन्ट की शैली — Regular, Bold, Italic, या Bold Italic हो सकती है। |

### साथ में देखें
* module [`groupdocs.viewer.fonts`](/viewer/python-net/groupdocs.viewer.fonts/)
