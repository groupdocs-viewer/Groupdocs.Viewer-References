---
title: "IFontInfo"
second_title: "GroupDocs.Viewer के लिए .NET API Reference"
description: "सभी फ़ॉन्ट्स के लिए सामान्य इंटरफ़ेस जो PDF, WordProcessing, Spreadsheet और Presentation जैसे सभी समर्थित दस्तावेज़ फ़ॉर्मेट परिवारों से निकाले जा सकते हैं।"
type: docs
weight: 820
url: /hi/net/groupdocs.viewer.fonts/ifontinfo/
---

## IFontInfo interface

सभी फ़ॉन्ट्स के लिए सामान्य इंटरफ़ेस, जिसे सभी समर्थित दस्तावेज़ फ़ॉर्मेट परिवारों: PDF, WordProcessing, Spreadsheet, और Presentation से निकाला जा सकता है।

```csharp
public interface IFontInfo
```

## गुण

| नाम | विवरण |
| --- | --- |
| [Content](../../groupdocs.viewer.fonts/ifontinfo/content) { get; } | फ़ॉन्ट की बाइनरी सामग्री बाइट एरे के रूप में, यदि उपलब्ध हो, अन्यथा `null`। |
| [FamilyName](../../groupdocs.viewer.fonts/ifontinfo/familyname) { get; } | फ़ॉन्ट का फ़ैमिली नाम स्ट्रिंग के रूप में |
| [Format](../../groupdocs.viewer.fonts/ifontinfo/format) { get; } | इस फ़ॉन्ट का फ़ॉर्मेट enum के रूप में — TrueType, TrueType Collection, OpenType, Embedded OpenType, या Unknown। |
| [Style](../../groupdocs.viewer.fonts/ifontinfo/style) { get; } | फ़ॉन्ट की शैली enum के रूप में — Regular, Bold, Italic, या Bold Italic। कुछ दस्तावेज़ फ़ॉर्मेट में केवल एक [`Regular`](../fontstyles/regular) शैली के फ़ॉन्ट हो सकते हैं। |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| [SerializeToCss](../../groupdocs.viewer.fonts/ifontinfo/serializetocss)(TextWriter) | इस फ़ॉन्ट जानकारी को @font-face एट-रूल के रूप में क्रमबद्ध करता है और इसे निर्दिष्ट टेक्स्ट राइटर में लिखता है |

### संबंधित देखें

* namespace [GroupDocs.Viewer.Fonts](../../groupdocs.viewer.fonts)
* assembly [GroupDocs.Viewer](../../)

<!-- संपादित न करें: xmldocmd द्वारा GroupDocs.Viewer.dll के लिए उत्पन्न -->
