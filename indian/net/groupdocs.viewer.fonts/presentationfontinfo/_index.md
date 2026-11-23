---
title: "PresentationFontInfo"
second_title: "GroupDocs.Viewer के लिए .NET API Reference"
description: "एक प्रस्तुति दस्तावेज़ से एक फ़ॉन्ट की मेटा जानकारी और बाइनरी डेटा को Viewer../groupdocs.viewer/viewer इंस्टेंस में लोड करके संलग्न करता है। यह फ़ॉन्ट दस्तावेज़ की सामग्री में उपयोग किया जाता है और दस्तावेज़ के भीतर एम्बेडेड होता है या ऑपरेटिंग सिस्टम में स्थापित होता है जहाँ GroupDocs.Viewer चल रहा है।"
type: docs
weight: 850
url: /hi/net/groupdocs.viewer.fonts/presentationfontinfo/
---

## PresentationFontInfo structure

एक प्रस्तुति दस्तावेज़ से एक फ़ॉन्ट की मेटा जानकारी और बाइनरी डेटा को [`Viewer`](../../groupdocs.viewer/viewer) इंस्टेंस में लोड करके संलग्न करता है। यह फ़ॉन्ट दस्तावेज़ की सामग्री में उपयोग किया जाता है और दस्तावेज़ के भीतर एम्बेडेड होता है या ऑपरेटिंग सिस्टम में स्थापित होता है, जहाँ GroupDocs.Viewer चल रहा है।

```csharp
public struct PresentationFontInfo : IFontInfo
```

## गुण

| नाम | विवरण |
| --- | --- |
| [Content](../../groupdocs.viewer.fonts/presentationfontinfo/content) { get; } | इस फ़ॉन्ट की सामग्री बाइट एरे के रूप में। यदि इस फ़ॉन्ट के बारे में केवल मेटा जानकारी है, लेकिन उसकी बाइनरी सामग्री उपलब्ध नहीं है, तो यह प्रॉपर्टी `null` लौटाती है। |
| [FamilyName](../../groupdocs.viewer.fonts/presentationfontinfo/familyname) { get; } | फ़ॉन्ट का फ़ैमिली नाम, शैली के बिना, कभी भी null या खाली स्ट्रिंग नहीं होता। |
| [Format](../../groupdocs.viewer.fonts/presentationfontinfo/format) { get; } | इस फ़ॉन्ट का फ़ॉर्मेट। दस्तावेज़ निम्न फ़ॉर्मेट में फ़ॉन्ट का उपयोग कर सकते हैं: TrueType, TrueType Collection, OpenType, Embedded OpenType। यदि इस फ़ॉन्ट के बारे में केवल मेटा जानकारी है, लेकिन उसकी बाइनरी सामग्री उपलब्ध नहीं है, तो यह प्रॉपर्टी Unknown मान लौटाती है। |
| [IsEmbedded](../../groupdocs.viewer.fonts/presentationfontinfo/isembedded) { get; } | यह दर्शाता है कि यह फ़ॉन्ट दस्तावेज़ के भीतर एम्बेडेड है, जिसे [`Viewer`](../../groupdocs.viewer/viewer) इंस्टेंस में लोड किया गया है (`true`), या यह एक सिस्टम फ़ॉन्ट है (`false`). स्प्रेडशीट दस्तावेज़ एम्बेडेड फ़ॉन्ट नहीं रख सकते, इसलिए उनके लिए यह प्रॉपर्टी हमेशा `false` लौटाती है। |
| [Style](../../groupdocs.viewer.fonts/presentationfontinfo/style) { get; } | फ़ॉन्ट की शैली — यह Regular, Bold, Italic, या Bold Italic हो सकती है |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| [SerializeToCss](../../groupdocs.viewer.fonts/presentationfontinfo/serializetocss)(TextWriter) | इस फ़ॉन्ट जानकारी को @font-face एट-रूल के रूप में क्रमबद्ध करता है और इसे निर्दिष्ट टेक्स्ट राइटर में लिखता है |

### संबंधित देखें

* interface [IFontInfo](../ifontinfo)
* namespace [GroupDocs.Viewer.Fonts](../../groupdocs.viewer.fonts)
* assembly [GroupDocs.Viewer](../../)

<!-- संपादित न करें: xmldocmd द्वारा GroupDocs.Viewer.dll के लिए उत्पन्न -->
