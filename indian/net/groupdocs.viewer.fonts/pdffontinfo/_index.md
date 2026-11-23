---
title: "PdfFontInfo"
second_title: "GroupDocs.Viewer के लिए .NET API Reference"
description: "PDF दस्तावेज़ से एक फ़ॉन्ट की मेटा जानकारी और बाइनरी डेटा को Viewer../groupdocs.viewer/viewer इंस्टेंस में लोड किए गए रूप में संलग्न करता है। यह फ़ॉन्ट दस्तावेज़ सामग्री में उपयोग किया जाता है और दस्तावेज़ के भीतर एम्बेड किया जाता है या उस ऑपरेटिंग सिस्टम में स्थापित होता है जहाँ GroupDocs.Viewer चल रहा है।"
type: docs
weight: 840
url: /hi/net/groupdocs.viewer.fonts/pdffontinfo/
---

## PdfFontInfo structure

PDF दस्तावेज़ से एक फ़ॉन्ट की मेटा जानकारी और बाइनरी डेटा को [`Viewer`](../../groupdocs.viewer/viewer) इंस्टेंस में लोड करके संलग्न करता है। यह फ़ॉन्ट दस्तावेज़ सामग्री में उपयोग किया जाता है और दस्तावेज़ के भीतर एम्बेड किया जाता है या ऑपरेटिंग सिस्टम में स्थापित होता है, जहाँ GroupDocs.Viewer चल रहा है।

```csharp
public struct PdfFontInfo : IFontInfo
```

## गुण

| नाम | विवरण |
| --- | --- |
| [Content](../../groupdocs.viewer.fonts/pdffontinfo/content) { get; } | इस फ़ॉन्ट की सामग्री बाइट एरे के रूप में। यदि इस फ़ॉन्ट के बारे में केवल मेटा जानकारी है, लेकिन उसकी बाइनरी सामग्री उपलब्ध नहीं है, तो यह प्रॉपर्टी `null` लौटाती है। |
| [FamilyName](../../groupdocs.viewer.fonts/pdffontinfo/familyname) { get; } | फ़ॉन्ट का फ़ैमिली नाम, शैली के बिना, कभी भी null या खाली स्ट्रिंग नहीं होता। |
| [Format](../../groupdocs.viewer.fonts/pdffontinfo/format) { get; } | इस फ़ॉन्ट का फ़ॉर्मेट। दस्तावेज़ निम्न फ़ॉर्मेट में फ़ॉन्ट का उपयोग कर सकते हैं: TrueType, TrueType Collection, OpenType, Embedded OpenType। यदि इस फ़ॉन्ट के बारे में केवल मेटा जानकारी है, लेकिन उसकी बाइनरी सामग्री उपलब्ध नहीं है, तो यह प्रॉपर्टी Unknown मान लौटाती है। |
| [IsEmbedded](../../groupdocs.viewer.fonts/pdffontinfo/isembedded) { get; } | निर्दिष्ट करता है कि यह फ़ॉन्ट PDF दस्तावेज़ के भीतर एम्बेड किया गया है, [`Viewer`](../../groupdocs.viewer/viewer) इंस्टेंस में लोड किया गया (`true`), या नहीं। |
| [IsInstalled](../../groupdocs.viewer.fonts/pdffontinfo/isinstalled) { get; } | निर्दिष्ट करता है कि यह फ़ॉन्ट ऑपरेटिंग सिस्टम में मौजूद (इंस्टॉल) है या नहीं, जहाँ GroupDocs.Viewer चल रहा है |
| [Style](../../groupdocs.viewer.fonts/pdffontinfo/style) { get; } | फ़ॉन्ट की शैली — यह Regular, Bold, Italic, या Bold Italic हो सकती है। |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| [SerializeToCss](../../groupdocs.viewer.fonts/pdffontinfo/serializetocss)(TextWriter) | इस फ़ॉन्ट जानकारी को @font-face एट-रूल के रूप में क्रमबद्ध करता है और इसे निर्दिष्ट टेक्स्ट राइटर में लिखता है |

### संबंधित देखें

* interface [IFontInfo](../ifontinfo)
* namespace [GroupDocs.Viewer.Fonts](../../groupdocs.viewer.fonts)
* assembly [GroupDocs.Viewer](../../)

<!-- संपादित न करें: xmldocmd द्वारा GroupDocs.Viewer.dll के लिए उत्पन्न -->
