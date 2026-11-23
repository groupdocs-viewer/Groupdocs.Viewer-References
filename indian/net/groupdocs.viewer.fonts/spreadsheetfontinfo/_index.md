---
title: "SpreadsheetFontInfo"
second_title: "GroupDocs.Viewer के लिए .NET API Reference"
description: "एक स्प्रेडशीट दस्तावेज़ से एक फ़ॉन्ट की मेटा जानकारी और बाइनरी डेटा को Viewer../groupdocs.viewer/viewer इंस्टेंस में लोड करके संलग्न करता है। स्प्रेडशीट दस्तावेज़ एम्बेडेड फ़ॉन्ट नहीं रख सकते, इसलिए यदि यह फ़ॉन्ट GetAllFonts../groupdocs.viewer/viewer/getallfonts मेथड द्वारा लौटाया गया था, तो यह ऑपरेटिंग सिस्टम में स्थापित होता है जहाँ GroupDocs.Viewer चल रहा है।"
type: docs
weight: 870
url: /hi/net/groupdocs.viewer.fonts/spreadsheetfontinfo/
---

## SpreadsheetFontInfo structure

एक स्प्रेडशीट दस्तावेज़ से एक फ़ॉन्ट की मेटा जानकारी और बाइनरी डेटा को [`Viewer`](../../groupdocs.viewer/viewer) इंस्टेंस में लोड करके संलग्न करता है। स्प्रेडशीट दस्तावेज़ एम्बेडेड फ़ॉन्ट नहीं रख सकते, इसलिए यह विशेष फ़ॉन्ट, यदि [`GetAllFonts`](../../groupdocs.viewer/viewer/getallfonts) मेथड द्वारा लौटाया गया था, तो ऑपरेटिंग सिस्टम में स्थापित होता है, जहाँ GroupDocs.Viewer चल रहा है।

```csharp
public struct SpreadsheetFontInfo : IFontInfo
```

## गुण

| नाम | विवरण |
| --- | --- |
| [Charset](../../groupdocs.viewer.fonts/spreadsheetfontinfo/charset) { get; } | इस फ़ॉन्ट का कैरेक्टर सेट |
| [Color](../../groupdocs.viewer.fonts/spreadsheetfontinfo/color) { get; } | इस फ़ॉन्ट का रंग |
| [Content](../../groupdocs.viewer.fonts/spreadsheetfontinfo/content) { get; } | इस फ़ॉन्ट की सामग्री बाइट एरे के रूप में। यदि इस फ़ॉन्ट के बारे में केवल मेटा जानकारी है, लेकिन उसकी बाइनरी सामग्री उपलब्ध नहीं है, तो यह प्रॉपर्टी `null` लौटाती है। |
| [FamilyName](../../groupdocs.viewer.fonts/spreadsheetfontinfo/familyname) { get; } | फ़ॉन्ट का फ़ैमिली नाम, शैली के बिना, कभी भी null या खाली स्ट्रिंग नहीं होता। |
| [Format](../../groupdocs.viewer.fonts/spreadsheetfontinfo/format) { get; } | इस फ़ॉन्ट का फ़ॉर्मेट |
| [IsStrikeout](../../groupdocs.viewer.fonts/spreadsheetfontinfo/isstrikeout) { get; } | यह दर्शाता है कि फ़ॉन्ट में एकल स्ट्राइकआउट है या नहीं |
| [IsUnderline](../../groupdocs.viewer.fonts/spreadsheetfontinfo/isunderline) { get; } | यह दर्शाता है कि फ़ॉन्ट में अंडरलाइन है या नहीं |
| [Style](../../groupdocs.viewer.fonts/spreadsheetfontinfo/style) { get; } | इस फ़ॉन्ट की शैली — यह Regular, Bold, Italic, या Bold Italic हो सकती है |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| [SerializeToCss](../../groupdocs.viewer.fonts/spreadsheetfontinfo/serializetocss)(TextWriter) | इस फ़ॉन्ट जानकारी को @font-face एट-रूल के रूप में क्रमबद्ध करता है और इसे निर्दिष्ट टेक्स्ट राइटर में लिखता है |

### संबंधित देखें

* interface [IFontInfo](../ifontinfo)
* namespace [GroupDocs.Viewer.Fonts](../../groupdocs.viewer.fonts)
* assembly [GroupDocs.Viewer](../../)

<!-- संपादित न करें: xmldocmd द्वारा GroupDocs.Viewer.dll के लिए उत्पन्न -->
