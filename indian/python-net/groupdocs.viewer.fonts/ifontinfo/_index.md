---
title: "IFontInfo वर्ग"
second_title: "GroupDocs.Viewer Python के लिए .NET के माध्यम से API संदर्भ"
description: "सभी फ़ॉन्ट्स के लिए एक सामान्य इंटरफ़ेस का प्रतिनिधित्व करता है, जिन्हें सभी समर्थित दस्तावेज़ फ़ॉर्मेट परिवारों से निकाला जा सकता है: PDF, WordProcessing, Spreadsheet, और Presentation।"
type: docs
url: /hi/python-net/groupdocs.viewer.fonts/ifontinfo/
is_root: false
weight: 50
---


## IFontInfo class

सभी फ़ॉन्ट्स के लिए एक सामान्य इंटरफ़ेस का प्रतिनिधित्व करता है, जिन्हें सभी समर्थित दस्तावेज़ फ़ॉर्मेट परिवारों से निकाला जा सकता है: PDF, WordProcessing, Spreadsheet, और Presentation।

IFontInfo प्रकार निम्नलिखित सदस्यों को उजागर करता है:

### मेथड्स
| मेथड | विवरण |
| :- | :- |
| [serialize_to_css](/viewer/python-net/groupdocs.viewer.fonts/ifontinfo/serialize_to_css/#output) | इस फ़ॉन्ट जानकारी को @font-face at-rule के रूप में क्रमबद्ध करता है और इसे निर्दिष्ट टेक्स्ट राइटर में लिखता है। |
| [serialize_to_css_text_writer](/viewer/python-net/groupdocs.viewer.fonts/ifontinfo/serialize_to_css_text_writer/) |  |

### प्रॉपर्टीज़
| प्रॉपर्टी | विवरण |
| :- | :- |
| [content](/viewer/python-net/groupdocs.viewer.fonts/ifontinfo/content/) | फ़ॉन्ट की बाइनरी सामग्री बाइट एरे के रूप में, यदि उपलब्ध हो, अन्यथा None। |
| [family_name](/viewer/python-net/groupdocs.viewer.fonts/ifontinfo/family_name/) | फ़ॉन्ट का फ़ैमिली नाम स्ट्रिंग के रूप में। |
| [format](/viewer/python-net/groupdocs.viewer.fonts/ifontinfo/format/) | इस फ़ॉन्ट का फ़ॉर्मेट enum के रूप में — TrueType, TrueType Collection, OpenType, Embedded OpenType, या `FontFormat.unknown`। |
| [style](/viewer/python-net/groupdocs.viewer.fonts/ifontinfo/style/) | फ़ॉन्ट की शैली enum के रूप में (Regular, Bold, Italic, या Bold Italic); कुछ दस्तावेज़ फ़ॉर्मेट केवल [`FontStyles.regular`](/viewer/python-net/groupdocs.viewer.fonts/fontstyles/regular/) का समर्थन कर सकते हैं। |

### साथ में देखें
* module [`groupdocs.viewer.fonts`](/viewer/python-net/groupdocs.viewer.fonts/)
