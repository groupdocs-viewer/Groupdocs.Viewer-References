---
title: "WordProcessingFontInfo क्लास"
second_title: "GroupDocs.Viewer Python के लिए .NET के माध्यम से API संदर्भ"
description: "Viewer इंस्टेंस में लोड किए गए WordProcessing दस्तावेज़ से फ़ॉन्ट की मेटा जानकारी और बाइनरी डेटा को संलग्न करता है।"
type: docs
url: /hi/python-net/groupdocs.viewer.fonts/wordprocessingfontinfo/
is_root: false
weight: 110
---


## WordProcessingFontInfo class

एक WordProcessing दस्तावेज़ से फ़ॉन्ट के मेटा जानकारी और बाइनरी डेटा को encapsulate करता है जो एक [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/) इंस्टेंस में लोड किया गया है।

अपरिवर्तनीय स्ट्रक्ट।

इसके इंस्टेंस [`GroupDocs.Viewer`](/viewer/python-net/groupdocs.viewer/viewer/) सार्वजनिक API द्वारा उत्पन्न और लौटाए जाते हैं और सामान्यतः उपयोगकर्ता द्वारा नहीं बनाए जाने चाहिए।

विवरण के लिए, दस्तावेज़ देखें: https://docs.groupdocs.com/viewer/net/getting-used-fonts/

WordProcessingFontInfo प्रकार निम्नलिखित सदस्यों को उजागर करता है:

### कंस्ट्रक्टर्स
| कंस्ट्रक्टर | विवरण |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingfontinfo/__init__/) |  |

### मेथड्स
| मेथड | विवरण |
| :- | :- |
| [serialize_to_css](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingfontinfo/serialize_to_css/#output) | फ़ॉन्ट जानकारी को @font-face at-rule के रूप में क्रमबद्ध करता है और इसे निर्दिष्ट टेक्स्ट राइटर में लिखता है। |
| [serialize_to_css_text_writer](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingfontinfo/serialize_to_css_text_writer/) |  |
| [to_string](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingfontinfo/to_string/) | इस फ़ॉन्ट डेटा के बारे में डिबग जानकारी लौटाता है निम्न टेम्पलेट के रूप में: "name style, embedded/system, format"। |

### प्रॉपर्टीज़
| प्रॉपर्टी | विवरण |
| :- | :- |
| [alt_family_name](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingfontinfo/alt_family_name/) | फ़ॉन्ट का वैकल्पिक फ़ैमिली नाम। यदि अनुपलब्ध हो, तो खाली स्ट्रिंग। |
| [charset](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingfontinfo/charset/) | इस फ़ॉन्ट का कैरेक्टर सेट। |
| [content](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingfontinfo/content/) | इस फ़ॉन्ट की सामग्री बाइट एरे के रूप में। यदि केवल इस फ़ॉन्ट की मेटा जानकारी उपलब्ध है और बाइनरी सामग्री अनुपलब्ध है, तो प्रॉपर्टी None लौटाती है। |
| [family_name](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingfontinfo/family_name/) | फ़ॉन्ट का फ़ैमिली नाम, शैली के बिना; कभी None या खाली स्ट्रिंग नहीं। |
| [format](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingfontinfo/format/) | इस फ़ॉन्ट का फ़ॉर्मेट। |
| [is_embedded](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingfontinfo/is_embedded/) | यह प्रॉपर्टी दर्शाती है कि यह फ़ॉन्ट दस्तावेज़ के भीतर एम्बेडेड है, [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/) इंस्टेंस में लोड किया गया है (`True`), या यह सिस्टम फ़ॉन्ट है (`False`). |
| [style](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingfontinfo/style/) | फ़ॉन्ट की शैली — Regular, Bold, Italic, या Bold Italic हो सकती है। |

### साथ में देखें
* module [`groupdocs.viewer.fonts`](/viewer/python-net/groupdocs.viewer.fonts/)
