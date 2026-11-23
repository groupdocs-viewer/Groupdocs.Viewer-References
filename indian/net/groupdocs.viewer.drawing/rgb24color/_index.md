---
title: "Rgb24Color"
second_title: "GroupDocs.Viewer के लिए .NET API Reference"
description: "RGB प्रारूप में 24 बिट रंग का प्रतिनिधित्व करता है, जहाँ प्रत्येक चैनल (लाल, हरा, नीला) के लिए 8 बिट होते हैं। पारदर्शिता का समर्थन नहीं करता।"
type: docs
weight: 970
url: /hi/net/groupdocs.viewer.drawing/rgb24color/
---

## Rgb24Color structure

RGB फ़ॉर्मेट में 24-बिट रंग का प्रतिनिधित्व करता है, प्रत्येक चैनल (Red, Green, Blue) के लिए 8 बिट्स के साथ। ट्रांसपेरेंसी का समर्थन नहीं करता।

```csharp
public struct Rgb24Color : IEquatable<Argb32Color>, IEquatable<Rgb24Color>
```

## गुण

| नाम | विवरण |
| --- | --- |
| [B](../../groupdocs.viewer.drawing/rgb24color/b) { get; } | रंग के नीले भाग को 8-बिट अनसाइन्ड इंटीजर [0..255] के रूप में प्राप्त करता है। |
| [G](../../groupdocs.viewer.drawing/rgb24color/g) { get; } | रंग के हरे भाग को 8-बिट अनसाइन्ड इंटीजर [0..255] के रूप में प्राप्त करता है। |
| [IsDefault](../../groupdocs.viewer.drawing/rgb24color/isdefault) { get; } | यह दर्शाता है कि यह [`Rgb24Color`](../rgb24color) उदाहरण डिफ़ॉल्ट (काला) है या नहीं - सभी 3 चैनल 0 पर सेट हैं। |
| [R](../../groupdocs.viewer.drawing/rgb24color/r) { get; } | रंग के लाल भाग को 8-बिट अनसाइन्ड इंटीजर [0..255] के रूप में प्राप्त करता है |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| static [FromRgb](../../groupdocs.viewer.drawing/rgb24color/fromrgb)(byte, byte, byte) | निर्दिष्ट लाल, हरे, नीले चैनलों से एक [`Rgb24Color`](../rgb24color) मान बनाता है |
| [Equals](../../groupdocs.viewer.drawing/rgb24color/equals#equals)(Argb32Color) | इस रंग की निर्दिष्ट [`Argb32Color`](../argb32color) रंग के साथ समानता की जाँच करता है |
| override [Equals](../../groupdocs.viewer.drawing/rgb24color/equals#equals_2)(object) | इस रंग की निर्दिष्ट अनकास्टेड के साथ जाँच करता है |
| [Equals](../../groupdocs.viewer.drawing/rgb24color/equals#equals_1)(Rgb24Color) | इस रंग की निर्दिष्ट [`Rgb24Color`](../rgb24color) रंग के साथ समानता की जाँच करता है |
| [GetBrightness](../../groupdocs.viewer.drawing/rgb24color/getbrightness)() | इस [`Rgb24Color`](../rgb24color) उदाहरण के लिए Hue-Saturation-Lightness (HSL) लाइटनेस/ब्राइटनेस लौटाता है |
| override [GetHashCode](../../groupdocs.viewer.drawing/rgb24color/gethashcode)() | एक हैश कोड लौटाता है जो वर्तमान रंग को परिभाषित करता है। GetHashCode के साथ संगत नहीं है। |
| [GetHue](../../groupdocs.viewer.drawing/rgb24color/gethue)() | इस [`Rgb24Color`](../rgb24color) इंस्टेंस के लिए Hue-Saturation-Lightness (HSL) ह्यू मान को डिग्री में लौटाता है। यदि R == G == B है, तो ह्यू का कोई अर्थ नहीं है, और लौटाया गया मान 0 है। |
| [GetSaturation](../../groupdocs.viewer.drawing/rgb24color/getsaturation)() | इस [`Rgb24Color`](../rgb24color) इंस्टेंस के लिए Hue-Saturation-Lightness (HSL) संतृप्ति |
| [ToArgb](../../groupdocs.viewer.drawing/rgb24color/toargb)() | इस [`Rgb24Color`](../rgb24color) इंस्टेंस का ARGB मान लौटाता है, जो Color के साथ संगत है |
| [ToHex](../../groupdocs.viewer.drawing/rgb24color/tohex)() | इस रंग को हेक्साडेसिमल स्ट्रिंग प्रतिनिधित्व में लौटाता है |
| [ToRGB](../../groupdocs.viewer.drawing/rgb24color/torgb)() | इस [`Rgb24Color`](../rgb24color) इंस्टेंस को 'rgb' CSS फ़ंक्शन नोटेशन में क्रमबद्ध करता है। |
| override [ToString](../../groupdocs.viewer.drawing/rgb24color/tostring)() | इस [`Rgb24Color`](../rgb24color) इंस्टेंस को 'rgb(r, g, b)' फ़ॉर्मेट में क्रमबद्ध करता है |
| [operator ==](../../groupdocs.viewer.drawing/rgb24color/op_equality#op_equality_1) | दो [`Rgb24Color`](../rgb24color) रंगों की तुलना करता है और एक बूलियन लौटाता है जो दर्शाता है कि दोनों मेल खाते हैं या नहीं। (2 ऑपरेटर्स) |
| [operator !=](../../groupdocs.viewer.drawing/rgb24color/op_inequality#op_inequality_1) | दो [`Rgb24Color`](../rgb24color) रंगों की तुलना करता है और एक बूलियन लौटाता है जो दर्शाता है कि दोनों मेल नहीं खाते। (2 ऑपरेटर्स) |

## अन्य सदस्य

| नाम | विवरण |
| --- | --- |
| static class [KnownColors](rgb24color.knowncolors) | सभी "known colors" को शामिल करता है, जिनका CSS standart में स्थिर अद्वितीय नाम और मान है। |

### टिप्पणियाँ

यह प्रकार (लेकिन केवल CSS संचालन तक सीमित नहीं) उपयोगी होने के लिए डिज़ाइन किया गया है। अधिक देखें: https://developer.mozilla.org/en-US/docs/Web/CSS/color_value

### संबंधित देखें

* struct [Argb32Color](../argb32color)
* namespace [GroupDocs.Viewer.Drawing](../../groupdocs.viewer.drawing)
* assembly [GroupDocs.Viewer](../../)

<!-- संपादित न करें: xmldocmd द्वारा GroupDocs.Viewer.dll के लिए उत्पन्न -->
