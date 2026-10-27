---
title: "PdfFontInfo क्लास"
second_title: "GroupDocs.Viewer Python के लिए .NET के माध्यम से API संदर्भ"
description: "एक Viewer इंस्टेंस में लोड किए गए PDF फ़ॉन्ट के मेटाडेटा और बाइनरी डेटा को समाहित करता है, जो दस्तावेज़ में एम्बेडेड हो सकता है या उस ऑपरेटिंग सिस्टम पर स्थापित हो सकता है जहाँ GroupDocs.Viewer चलता है।"
type: docs
url: /hi/python-net/groupdocs.viewer.fonts/pdffontinfo/
is_root: false
weight: 70
---


## PdfFontInfo class

एक PDF फ़ॉन्ट के मेटाडेटा और बाइनरी डेटा को encapsulate करता है जो एक [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/) इंस्टेंस में लोड किया गया है, जिसे दस्तावेज़ में एम्बेड किया जा सकता है या उस ऑपरेटिंग सिस्टम पर स्थापित किया जा सकता है जहाँ GroupDocs.Viewer चलता है।

PdfFontInfo प्रकार निम्नलिखित सदस्य उजागर करता है:

### कंस्ट्रक्टर्स
| कंस्ट्रक्टर | विवरण |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.fonts/pdffontinfo/__init__/) |  |

### मेथड्स
| मेथड | विवरण |
| :- | :- |
| [serialize_to_css](/viewer/python-net/groupdocs.viewer.fonts/pdffontinfo/serialize_to_css/#output) | इस फ़ॉन्ट जानकारी को @font-face at-rule के रूप में क्रमबद्ध करता है और इसे निर्दिष्ट टेक्स्ट राइटर में लिखता है। |
| [serialize_to_css_text_writer](/viewer/python-net/groupdocs.viewer.fonts/pdffontinfo/serialize_to_css_text_writer/) |  |

### प्रॉपर्टीज़
| प्रॉपर्टी | विवरण |
| :- | :- |
| [content](/viewer/python-net/groupdocs.viewer.fonts/pdffontinfo/content/) | इस फ़ॉन्ट की सामग्री बाइट एरे के रूप में, या यदि केवल मेटाडेटा उपलब्ध है और बाइनरी सामग्री अनुपलब्ध है तो None। |
| [family_name](/viewer/python-net/groupdocs.viewer.fonts/pdffontinfo/family_name/) | फ़ॉन्ट का फ़ैमिली नाम, शैली के बिना; कभी None या खाली स्ट्रिंग नहीं। |
| [format](/viewer/python-net/groupdocs.viewer.fonts/pdffontinfo/format/) | इस फ़ॉन्ट का फ़ॉर्मेट। |
| [is_embedded](/viewer/python-net/groupdocs.viewer.fonts/pdffontinfo/is_embedded/) | यह प्रॉपर्टी दर्शाती है कि फ़ॉन्ट PDF दस्तावेज़ के भीतर एम्बेडेड है और Viewer इंस्टेंस में लोड किया गया है (`True`), या नहीं। |
| [is_installed](/viewer/python-net/groupdocs.viewer.fonts/pdffontinfo/is_installed/) | यह प्रॉपर्टी दर्शाती है कि यह फ़ॉन्ट उस ऑपरेटिंग सिस्टम में मौजूद (स्थापित) है जहाँ GroupDocs.Viewer चल रहा है। |
| [style](/viewer/python-net/groupdocs.viewer.fonts/pdffontinfo/style/) | फ़ॉन्ट की शैली; Regular, Bold, Italic, या Bold Italic हो सकती है। |

### साथ में देखें
* module [`groupdocs.viewer.fonts`](/viewer/python-net/groupdocs.viewer.fonts/)
