---
title: "groupdocs.viewer.fonts"
second_title: "GroupDocs.Viewer Python के लिए .NET के माध्यम से API संदर्भ"
description: "फ़ॉन्ट लोडिंग और प्रतिस्थापन कॉन्फ़िगरेशन।"
type: docs
url: /hi/python-net/groupdocs.viewer.fonts/
is_root: false
weight: 40
---


फ़ॉन्ट लोडिंग और प्रतिस्थापन कॉन्फ़िगरेशन।

### क्लास
| क्लास | विवरण |
| :- | :- |
| [`FolderFontSource`](/viewer/python-net/groupdocs.viewer.fonts/folderfontsource/) | TrueType फ़ॉन्ट्स वाले फ़ोल्डर का प्रतिनिधित्व करता है। |
| [`FontSettings`](/viewer/python-net/groupdocs.viewer.fonts/fontsettings/) | TrueType फ़ॉन्ट्स खोजने के लिए स्रोतों के साथ काम करने के लिए मेथड प्रदान करता है। |
| [`FontStyles`](/viewer/python-net/groupdocs.viewer.fonts/fontstyles/) | फ़ॉन्ट के 4 संभावित शैलियों का प्रतिनिधित्व करता है, जो दस्तावेज़ में उपयोग होते हैं: Regular, Bold, Italic, या Bold Italic। |
| [`IFontInfo`](/viewer/python-net/groupdocs.viewer.fonts/ifontinfo/) | सभी फ़ॉन्ट्स के लिए एक सामान्य इंटरफ़ेस का प्रतिनिधित्व करता है, जिन्हें सभी समर्थित दस्तावेज़ फ़ॉर्मेट परिवारों से निकाला जा सकता है: PDF, WordProcessing, Spreadsheet, और Presentation। |
| [`PdfFontInfo`](/viewer/python-net/groupdocs.viewer.fonts/pdffontinfo/) | एक PDF फ़ॉन्ट के मेटाडेटा और बाइनरी डेटा को encapsulate करता है जो एक [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/) इंस्टेंस में लोड किया गया है, जिसे दस्तावेज़ में एम्बेड किया जा सकता है या उस ऑपरेटिंग सिस्टम पर स्थापित किया जा सकता है जहाँ GroupDocs.Viewer चलता है। |
| [`PresentationFontInfo`](/viewer/python-net/groupdocs.viewer.fonts/presentationfontinfo/) | एक Presentation दस्तावेज़ से फ़ॉन्ट के मेटा जानकारी और बाइनरी डेटा का प्रतिनिधित्व करता है जो एक [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/) इंस्टेंस में लोड किया गया है। फ़ॉन्ट दस्तावेज़ सामग्री में उपयोग होता है और इसे दस्तावेज़ में एम्बेड किया जा सकता है या उस ऑपरेटिंग सिस्टम में स्थापित किया जा सकता है जहाँ viewer चलता है। |
| [`SpreadsheetFontInfo`](/viewer/python-net/groupdocs.viewer.fonts/spreadsheetfontinfo/) | एक स्प्रेडशीट दस्तावेज़ से फ़ॉन्ट के मेटा जानकारी और बाइनरी डेटा को encapsulate करता है जो एक [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/) इंस्टेंस में लोड किया गया है। स्प्रेडशीट दस्तावेज़ों में एम्बेडेड फ़ॉन्ट नहीं हो सकते, इसलिए एक फ़ॉन्ट जो [`Viewer.get_all_fonts`](/viewer/python-net/groupdocs.viewer/viewer/get_all_fonts/) द्वारा लौटाया जाता है, उसे उस ऑपरेटिंग सिस्टम में स्थापित किया जाता है जहाँ viewer चलता है। |
| [`WordProcessingFontInfo`](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingfontinfo/) | एक WordProcessing दस्तावेज़ से फ़ॉन्ट के मेटा जानकारी और बाइनरी डेटा को encapsulate करता है जो एक [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/) इंस्टेंस में लोड किया गया है। |
| [`WordProcessingSubstitutedFontInfo`](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/) | एक WordProcessing दस्तावेज़ से एक फ़ॉन्ट के मेटा जानकारी और बाइनरी डेटा को encapsulate करता है, जो मूल रूप से लोड किए गए [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/) इंस्टेंस दस्तावेज़ में उपयोग नहीं होता, लेकिन उन फ़ॉन्ट्स के लिए प्रतिस्थापन फ़ॉन्ट के रूप में कार्य करता है जो लक्ष्य मशीन पर नहीं मिलते। प्रतिस्थापित फ़ॉन्ट्स केवल WordProcessing फ़ॉर्मेट परिवार के लिए मौजूद होते हैं। |

### एन्यूमरेशन
| एन्यूम | विवरण |
| :- | :- |
| [`FontFormat`](/viewer/python-net/groupdocs.viewer.fonts/fontformat/) |  |
| [`IFontSource`](/viewer/python-net/groupdocs.viewer.fonts/ifontsource/) | फ़ॉन्ट स्रोतों के लिए एक मार्कर इंटरफ़ेस का प्रतिनिधित्व करता है। |
| [`SearchOption`](/viewer/python-net/groupdocs.viewer.fonts/searchoption/) |  |
