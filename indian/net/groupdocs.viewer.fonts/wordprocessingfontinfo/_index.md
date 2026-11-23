---
title: "WordProcessingFontInfo"
second_title: "GroupDocs.Viewer के लिए .NET API Reference"
description: "एक WordProcessing दस्तावेज़ से एक फ़ॉन्ट की मेटा जानकारी और बाइनरी डेटा को संलग्न करता है जो Viewer../groupdocs.viewer/viewer इंस्टेंस में लोड किया गया है। यह फ़ॉन्ट दस्तावेज़ सामग्री में उपयोग किया जाता है और दस्तावेज़ के भीतर एम्बेड किया गया है या ऑपरेटिंग सिस्टम में इंस्टॉल है जहाँ GroupDocs.Viewer चल रहा है।"
type: docs
weight: 880
url: /hi/net/groupdocs.viewer.fonts/wordprocessingfontinfo/
---

## WordProcessingFontInfo structure

एक फ़ॉन्ट की मेटा जानकारी और बाइनरी डेटा को WordProcessing दस्तावेज़ से संलग्न करता है, जिसे [`Viewer`](../../groupdocs.viewer/viewer) इंस्टेंस में लोड किया गया है। यह फ़ॉन्ट दस्तावेज़ की सामग्री में उपयोग किया जाता है और दस्तावेज़ के भीतर एम्बेडेड होता है या ऑपरेटिंग सिस्टम में स्थापित होता है, जहाँ GroupDocs.Viewer चल रहा है।

```csharp
public struct WordProcessingFontInfo : IFontInfo
```

## गुण

| नाम | विवरण |
| --- | --- |
| [AltFamilyName](../../groupdocs.viewer.fonts/wordprocessingfontinfo/altfamilyname) { get; } | फ़ॉन्ट का वैकल्पिक फ़ैमिली नाम। यदि अनुपलब्ध है, तो खाली स्ट्रिंग होगी। |
| [Charset](../../groupdocs.viewer.fonts/wordprocessingfontinfo/charset) { get; } | इस फ़ॉन्ट का कैरेक्टर सेट |
| [Content](../../groupdocs.viewer.fonts/wordprocessingfontinfo/content) { get; } | इस फ़ॉन्ट की सामग्री बाइट एरे के रूप में। यदि इस फ़ॉन्ट के बारे में केवल मेटा जानकारी है, लेकिन उसकी बाइनरी सामग्री उपलब्ध नहीं है, तो यह प्रॉपर्टी `null` लौटाती है। |
| [FamilyName](../../groupdocs.viewer.fonts/wordprocessingfontinfo/familyname) { get; } | फ़ॉन्ट का फ़ैमिली नाम, शैली के बिना, कभी भी null या खाली स्ट्रिंग नहीं होता। |
| [Format](../../groupdocs.viewer.fonts/wordprocessingfontinfo/format) { get; } | इस फ़ॉन्ट का फ़ॉर्मेट। दस्तावेज़ निम्न फ़ॉर्मेट में फ़ॉन्ट का उपयोग कर सकते हैं: TrueType, TrueType Collection, OpenType, Embedded OpenType। यदि इस फ़ॉन्ट के बारे में केवल मेटा जानकारी है, लेकिन उसकी बाइनरी सामग्री उपलब्ध नहीं है, तो यह प्रॉपर्टी Unknown मान लौटाती है। |
| [IsEmbedded](../../groupdocs.viewer.fonts/wordprocessingfontinfo/isembedded) { get; } | यह दर्शाता है कि यह फ़ॉन्ट दस्तावेज़ के भीतर एम्बेडेड है, जिसे [`Viewer`](../../groupdocs.viewer/viewer) इंस्टेंस में लोड किया गया है (`true`), या यह एक सिस्टम फ़ॉन्ट है (`false`). |
| [Style](../../groupdocs.viewer.fonts/wordprocessingfontinfo/style) { get; } | फ़ॉन्ट की शैली — यह Regular, Bold, Italic, या Bold Italic हो सकती है। |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| [SerializeToCss](../../groupdocs.viewer.fonts/wordprocessingfontinfo/serializetocss)(TextWriter) | इस फ़ॉन्ट जानकारी को @font-face एट-रूल के रूप में क्रमबद्ध करता है और इसे निर्दिष्ट टेक्स्ट राइटर में लिखता है |
| override [ToString](../../groupdocs.viewer.fonts/wordprocessingfontinfo/tostring)() | यह फ़ॉन्ट डेटा के बारे में डिबग जानकारी को निम्न टेम्पलेट के रूप में लौटाता है: "name style, embedded/system, format" |

### टिप्पणियाँ

अपरिवर्तनीय स्ट्रक्ट। इसके इंस्टेंस GroupDocs.Viewer सार्वजनिक API द्वारा निर्मित और लौटाए जाते हैं और सामान्यतः उपयोगकर्ता द्वारा निर्मित नहीं होने चाहिए। विवरण के लिए, [documentation](https://docs.groupdocs.com/viewer/net/getting-used-fonts/) देखें।

### संबंधित देखें

* interface [IFontInfo](../ifontinfo)
* namespace [GroupDocs.Viewer.Fonts](../../groupdocs.viewer.fonts)
* assembly [GroupDocs.Viewer](../../)

<!-- संपादित न करें: xmldocmd द्वारा GroupDocs.Viewer.dll के लिए उत्पन्न -->
