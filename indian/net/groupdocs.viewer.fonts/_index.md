---
title: "GroupDocs.Viewer.Fonts"
second_title: "GroupDocs.Viewer के लिए .NET API Reference"
description: "यह नेमस्पेस रेंडरिंग प्रक्रिया के दौरान उपयोग किए जाने वाले फ़ॉन्ट्स को प्रबंधित करने के लिए क्लासेस और एनेमरेशन प्रदान करता है।"
type: docs
weight: 50
url: /hi/net/groupdocs.viewer.fonts/
---

यह नेमस्पेस रेंडरिंग प्रक्रिया के दौरान उपयोग किए जाने वाले फ़ॉन्ट्स को प्रबंधित करने के लिए क्लासेस और एनेमरेशन प्रदान करता है।

## क्लासेस

| क्लास | विवरण |
| --- | --- |
| [FolderFontSource](./folderfontsource) | TrueType फ़ॉन्ट्स को समाहित करने वाले फ़ोल्डर का प्रतिनिधित्व करता है। |
| [FontSettings](./fontsettings) | TrueType फ़ॉन्ट्स की खोज के लिए स्रोतों के साथ काम करने के लिए विधियाँ प्रदान करता है। |
## Structures

| संरचना | विवरण |
| --- | --- |
| [FontStyles](./fontstyles) | दस्तावेज़ में उपयोग किए जाने वाले फ़ॉन्ट के 4 संभावित शैलियों का प्रतिनिधित्व करता है: रेगुलर, बोल्ड, इटैलिक, या बोल्ड इटैलिक। |
| [PdfFontInfo](./pdffontinfo) | PDF दस्तावेज़ से एक फ़ॉन्ट की मेटा जानकारी और बाइनरी डेटा को संलग्न करता है, जिसे [`Viewer`](../groupdocs.viewer/viewer) इंस्टेंस में लोड किया गया है। यह फ़ॉन्ट दस्तावेज़ की सामग्री में उपयोग किया जाता है और दस्तावेज़ के भीतर एम्बेड किया गया है या ऑपरेटिंग सिस्टम में स्थापित है, जहाँ GroupDocs.Viewer चल रहा है। |
| [PresentationFontInfo](./presentationfontinfo) | Presentation दस्तावेज़ से एक फ़ॉन्ट की मेटा जानकारी और बाइनरी डेटा को संलग्न करता है, जिसे [`Viewer`](../groupdocs.viewer/viewer) इंस्टेंस में लोड किया गया है। यह फ़ॉन्ट दस्तावेज़ की सामग्री में उपयोग किया जाता है और दस्तावेज़ के भीतर एम्बेड किया गया है या ऑपरेटिंग सिस्टम में स्थापित है, जहाँ GroupDocs.Viewer चल रहा है। |
| [SpreadsheetFontInfo](./spreadsheetfontinfo) | Spreadsheet दस्तावेज़ से एक फ़ॉन्ट की मेटा जानकारी और बाइनरी डेटा को संलग्न करता है, जिसे [`Viewer`](../groupdocs.viewer/viewer) इंस्टेंस में लोड किया गया है। Spreadsheet दस्तावेज़ों में एम्बेडेड फ़ॉन्ट नहीं हो सकते, इसलिए यह विशेष फ़ॉन्ट, यदि [`GetAllFonts`](../groupdocs.viewer/viewer/getallfonts) विधि द्वारा लौटाया गया हो, ऑपरेटिंग सिस्टम में स्थापित है, जहाँ GroupDocs.Viewer चल रहा है। |
| [WordProcessingFontInfo](./wordprocessingfontinfo) | WordProcessing दस्तावेज़ से एक फ़ॉन्ट की मेटा जानकारी और बाइनरी डेटा को संलग्न करता है, जिसे [`Viewer`](../groupdocs.viewer/viewer) इंस्टेंस में लोड किया गया है। यह फ़ॉन्ट दस्तावेज़ की सामग्री में उपयोग किया जाता है और दस्तावेज़ के भीतर एम्बेड किया गया है या ऑपरेटिंग सिस्टम में स्थापित है, जहाँ GroupDocs.Viewer चल रहा है। |
| [WordProcessingSubstitutedFontInfo](./wordprocessingsubstitutedfontinfo) | WordProcessing दस्तावेज़ से एक फ़ॉन्ट की मेटा जानकारी और बाइनरी डेटा को संलग्न करता है, जो मूल रूप से लोड किए गए [`Viewer`](../groupdocs.viewer/viewer) दस्तावेज़ में उपयोग नहीं किया जाता, लेकिन उन फ़ॉन्ट्स के लिए प्रतिस्थापन फ़ॉन्ट के रूप में कार्य करता है, जिन्हें लक्ष्य मशीन पर नहीं पाया जा सकता। प्रतिस्थापित फ़ॉन्ट्स केवल WordProcessing फ़ॉर्मेट परिवार के लिए मौजूद होते हैं। |
## इंटरफ़ेस

| इंटरफ़ेस | विवरण |
| --- | --- |
| [IFontInfo](./ifontinfo) | सभी फ़ॉन्ट्स के लिए सामान्य इंटरफ़ेस, जिसे सभी समर्थित दस्तावेज़ फ़ॉर्मेट परिवारों: PDF, WordProcessing, Spreadsheet, और Presentation से निकाला जा सकता है। |
| [IFontSource](./ifontsource) | फ़ॉन्ट स्रोतों के लिए मार्कर इंटरफ़ेस। |
## एन्यूमरेशन

| एन्यूमरेशन | विवरण |
| --- | --- |
| [FontFormat](./fontformat) | सभी फ़ॉन्ट फ़ॉर्मेट का प्रतिनिधित्व करता है, जो [`IFontInfo`](../groupdocs.viewer.fonts/ifontinfo) उत्तराधिकारियों में मौजूद हो सकते हैं। |
| [SearchOption](./searchoption) | निर्दिष्ट करता है कि वर्तमान फ़ोल्डर को खोजा जाए, या वर्तमान फ़ोल्डर और सभी उपफ़ोल्डर। |

<!-- संपादित न करें: xmldocmd द्वारा GroupDocs.Viewer.dll के लिए उत्पन्न -->
