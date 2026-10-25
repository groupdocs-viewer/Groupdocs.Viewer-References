---
title: "WordProcessingSubstitutedFontInfo"
second_title: "GroupDocs.Viewer के लिए .NET API Reference"
description: "एक WordProcessing दस्तावेज़ से एक फ़ॉन्ट की मेटा जानकारी और बाइनरी डेटा को संलग्न करता है, जो मूल रूप से Viewer../groupdocs.viewer/viewer इंस्टेंस दस्तावेज़ में उपयोग नहीं किया गया है, लेकिन लक्ष्य मशीन पर न मिलने वाले फ़ॉन्ट के लिए प्रतिस्थापन फ़ॉन्ट के रूप में कार्य करता है। प्रतिस्थापित फ़ॉन्ट केवल WordProcessing फ़ॉर्मेट परिवार के लिए मौजूद होते हैं।"
type: docs
weight: 890
url: /hi/net/groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/
---

## WordProcessingSubstitutedFontInfo structure

एक WordProcessing दस्तावेज़ से एक फ़ॉन्ट की मेटा जानकारी और बाइनरी डेटा को संलग्न करता है, जो मूल रूप से लोड किए गए [`Viewer`](../../groupdocs.viewer/viewer) इंस्टेंस दस्तावेज़ में उपयोग नहीं किया गया है, लेकिन उन फ़ॉन्ट्स के लिए प्रतिस्थापन फ़ॉन्ट के रूप में कार्य करता है, जिन्हें लक्ष्य मशीन पर नहीं पाया जा सकता। प्रतिस्थापित फ़ॉन्ट केवल WordProcessing फ़ॉर्मेट परिवार के लिए मौजूद होते हैं।

```csharp
public struct WordProcessingSubstitutedFontInfo : IFontInfo
```

## गुण

| नाम | विवरण |
| --- | --- |
| [Content](../../groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/content) { get; } | इस प्रतिस्थापित फ़ॉन्ट की सामग्री बाइट एरे के रूप में। कभी भी `null` नहीं होती। |
| [FamilyName](../../groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/familyname) { get; } | **substituted** फ़ॉन्ट का फ़ैमिली नाम, शैली के बिना, कभी भी null या खाली स्ट्रिंग नहीं होता |
| [Format](../../groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/format) { get; } | इस प्रतिस्थापित (मूल नहीं) फ़ॉन्ट का फ़ॉर्मेट। यह TrueType, TrueType Collection, OpenType, Embedded OpenType हो सकता है। प्रतिस्थापित फ़ॉन्ट के लिए, क्योंकि इसका बाइनरी कंटेंट परिभाषा के अनुसार उपलब्ध है, यह प्रॉपर्टी कभी भी Unknown मान नहीं लौटाती। |
| [OriginalFamilyName](../../groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/originalfamilyname) { get; } | मूल फ़ॉन्ट का फ़ैमिली नाम, जिसे लक्ष्य मशीन पर नहीं पाया जा सकता, शैली के बिना, कभी भी null या खाली स्ट्रिंग नहीं होता |
| [Style](../../groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/style) { get; } | मूल फ़ॉन्ट की शैली — यह Regular, Bold, Italic, या Bold Italic हो सकती है। प्रतिस्थापित फ़ॉन्ट आमतौर पर (परंतु हमेशा नहीं) समान शैली का होता है। |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| [SerializeToCss](../../groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/serializetocss)(TextWriter) | इस फ़ॉन्ट जानकारी को @font-face एट-रूल के रूप में क्रमबद्ध करता है और इसे निर्दिष्ट टेक्स्ट राइटर में लिखता है |
| override [ToString](../../groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/tostring)() | इस फ़ॉन्ट डेटा के बारे में डिबग जानकारी लौटाता है, निम्न टेम्पलेट के रूप में: "original-name -&gt; substituted-name style, format" |

### टिप्पणियाँ

अपरिवर्तनीय स्ट्रक्ट। इसके इंस्टेंस GroupDocs.Viewer सार्वजनिक API द्वारा निर्मित और लौटाए जाते हैं और सामान्यतः उपयोगकर्ता द्वारा निर्मित नहीं होने चाहिए। विवरण के लिए, [documentation](https://docs.groupdocs.com/viewer/net/getting-used-fonts/) देखें।

### संबंधित देखें

* interface [IFontInfo](../ifontinfo)
* namespace [GroupDocs.Viewer.Fonts](../../groupdocs.viewer.fonts)
* assembly [GroupDocs.Viewer](../../)

<!-- संपादित न करें: xmldocmd द्वारा GroupDocs.Viewer.dll के लिए उत्पन्न -->
