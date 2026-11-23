---
title: "WordProcessingSubstitutedFontInfo क्लास"
second_title: "GroupDocs.Viewer Python के लिए .NET के माध्यम से API संदर्भ"
description: "एक WordProcessing दस्तावेज़ से एक फ़ॉन्ट की मेटा जानकारी और बाइनरी डेटा को समाहित करता है, जो मूल रूप से लोड किए गए Viewer इंस्टेंस दस्तावेज़ में उपयोग नहीं होता, लेकिन उन फ़ॉन्टों के लिए प्रतिस्थापन फ़ॉन्ट के रूप में कार्य करता है…"
type: docs
url: /hi/python-net/groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/
is_root: false
weight: 120
---


## WordProcessingSubstitutedFontInfo class

एक WordProcessing दस्तावेज़ से एक फ़ॉन्ट के मेटा जानकारी और बाइनरी डेटा को encapsulate करता है, जो मूल रूप से लोड किए गए [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/) इंस्टेंस दस्तावेज़ में उपयोग नहीं होता, लेकिन उन फ़ॉन्ट्स के लिए प्रतिस्थापन फ़ॉन्ट के रूप में कार्य करता है जो लक्ष्य मशीन पर नहीं मिलते। प्रतिस्थापित फ़ॉन्ट्स केवल WordProcessing फ़ॉर्मेट परिवार के लिए मौजूद होते हैं।

अपरिवर्तनीय स्ट्रक्ट। इसके इंस्टेंस [`GroupDocs.Viewer`](/viewer/python-net/groupdocs.viewer/viewer/) सार्वजनिक API द्वारा उत्पन्न और लौटाए जाते हैं और सामान्यतः उपयोगकर्ता द्वारा नहीं बनाए जाने चाहिए। विवरण के लिए दस्तावेज़ देखें: https://docs.groupdocs.com/viewer/net/getting-used-fonts/

WordProcessingSubstitutedFontInfo प्रकार निम्नलिखित सदस्य उजागर करता है:

### कंस्ट्रक्टर्स
| कंस्ट्रक्टर | विवरण |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/__init__/) |  |

### मेथड्स
| मेथड | विवरण |
| :- | :- |
| [serialize_to_css](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/serialize_to_css/#output) | फ़ॉन्ट जानकारी को @font-face at-rule के रूप में क्रमबद्ध करता है और इसे निर्दिष्ट टेक्स्ट राइटर में लिखता है। |
| [serialize_to_css_text_writer](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/serialize_to_css_text_writer/) |  |
| [to_string](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/to_string/) | डिबग स्ट्रिंग लौटाता है जिसमें फ़ॉन्ट जानकारी "original-name -> substituted-name style, format" फ़ॉर्मेट में होती है। |

### प्रॉपर्टीज़
| प्रॉपर्टी | विवरण |
| :- | :- |
| [content](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/content/) | प्रतिस्थापित फ़ॉन्ट की सामग्री बाइट एरे के रूप में। यह कभी None नहीं होता। |
| [family_name](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/family_name/) | प्रतिस्थापित फ़ॉन्ट का फ़ैमिली नाम, शैली के बिना। |
| [format](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/format/) | इस प्रतिस्थापित (मूल नहीं) फ़ॉन्ट का फ़ॉर्मेट। |
| [original_family_name](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/original_family_name/) | मूल फ़ॉन्ट का फ़ैमिली नाम, जिसे लक्ष्य मशीन पर नहीं पाया जा सकता, शैली के बिना। यह कभी null या खाली स्ट्रिंग नहीं होता। |
| [style](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/style/) | मूल फ़ॉन्ट की शैली — Regular, Bold, Italic, या Bold Italic हो सकती है। |

### साथ में देखें
* module [`groupdocs.viewer.fonts`](/viewer/python-net/groupdocs.viewer.fonts/)
