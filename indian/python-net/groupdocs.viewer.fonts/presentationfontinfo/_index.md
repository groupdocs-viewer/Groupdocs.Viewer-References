---
title: "PresentationFontInfo क्लास"
second_title: "GroupDocs.Viewer Python के लिए .NET के माध्यम से API संदर्भ"
description: "एक Presentation दस्तावेज़ से लोड किए गए Viewer इंस्टेंस में फ़ॉन्ट की मेटा जानकारी और बाइनरी डेटा का प्रतिनिधित्व करता है।"
type: docs
url: /hi/python-net/groupdocs.viewer.fonts/presentationfontinfo/
is_root: false
weight: 80
---


## PresentationFontInfo class

एक Presentation दस्तावेज़ से फ़ॉन्ट के मेटा जानकारी और बाइनरी डेटा का प्रतिनिधित्व करता है जो एक [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/) इंस्टेंस में लोड किया गया है। फ़ॉन्ट दस्तावेज़ सामग्री में उपयोग होता है और इसे दस्तावेज़ में एम्बेड किया जा सकता है या उस ऑपरेटिंग सिस्टम में स्थापित किया जा सकता है जहाँ viewer चलता है।

PresentationFontInfo प्रकार निम्नलिखित सदस्य उजागर करता है:

### कंस्ट्रक्टर्स
| कंस्ट्रक्टर | विवरण |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.fonts/presentationfontinfo/__init__/) |  |

### मेथड्स
| मेथड | विवरण |
| :- | :- |
| [serialize_to_css](/viewer/python-net/groupdocs.viewer.fonts/presentationfontinfo/serialize_to_css/#output) | इस फ़ॉन्ट जानकारी को @font-face at-rule के रूप में क्रमबद्ध करता है और इसे निर्दिष्ट टेक्स्ट राइटर में लिखता है। |
| [serialize_to_css_text_writer](/viewer/python-net/groupdocs.viewer.fonts/presentationfontinfo/serialize_to_css_text_writer/) |  |

### प्रॉपर्टीज़
| प्रॉपर्टी | विवरण |
| :- | :- |
| [content](/viewer/python-net/groupdocs.viewer.fonts/presentationfontinfo/content/) | इस फ़ॉन्ट की सामग्री बाइट ऐरे के रूप में है। |
| [family_name](/viewer/python-net/groupdocs.viewer.fonts/presentationfontinfo/family_name/) | फ़ॉन्ट का फ़ैमिली नाम, शैली के बिना; कभी None या खाली स्ट्रिंग नहीं। |
| [format](/viewer/python-net/groupdocs.viewer.fonts/presentationfontinfo/format/) | इस फ़ॉन्ट का फ़ॉर्मेट। |
| [is_embedded](/viewer/python-net/groupdocs.viewer.fonts/presentationfontinfo/is_embedded/) | यह प्रॉपर्टी दर्शाती है कि फ़ॉन्ट दस्तावेज़ के भीतर एम्बेडेड है और [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/) इंस्टेंस में लोड किया गया है (`True`), या यह सिस्टम फ़ॉन्ट है (`False`). |
| [style](/viewer/python-net/groupdocs.viewer.fonts/presentationfontinfo/style/) | फ़ॉन्ट की शैली — Regular, Bold, Italic, या Bold Italic हो सकती है। |

### साथ में देखें
* module [`groupdocs.viewer.fonts`](/viewer/python-net/groupdocs.viewer.fonts/)
