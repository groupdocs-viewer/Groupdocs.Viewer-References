---
title: "Argb32Color"
second_title: "GroupDocs.Viewer के लिए .NET API Reference"
description: "ARGB प्रारूप में 32-बिट रंग का प्रतिनिधित्व करता है, जिसमें प्रत्येक चैनल (अल्फा, रेड, ग्रीन, ब्लू) के लिए 8 बिट होते हैं। पारदर्शिता का समर्थन करता है।"
type: docs
weight: 950
url: /hi/net/groupdocs.viewer.drawing/argb32color/
---

## Argb32Color structure

ARGB फ़ॉर्मेट में 32-बिट रंग का प्रतिनिधित्व करता है, प्रत्येक चैनल (Alpha, Red, Green, Blue) के लिए 8 बिट्स के साथ। ट्रांसपेरेंसी का समर्थन करता है।

```csharp
public struct Argb32Color : IEquatable<Argb32Color>, IEquatable<Rgb24Color>
```

## गुण

| नाम | विवरण |
| --- | --- |
| [A](../../groupdocs.viewer.drawing/argb32color/a) { get; } | रंग के अल्फा भाग को 8-बिट अनसाइन्ड इंटीजर [0..255] के रूप में प्राप्त करता है। |
| [Alpha](../../groupdocs.viewer.drawing/argb32color/alpha) { get; } | रंग के अल्फा भाग को प्रतिशत में (0..1) सीमा में प्राप्त करता है। |
| [B](../../groupdocs.viewer.drawing/argb32color/b) { get; } | रंग के नीले भाग को 8-बिट अनसाइन्ड इंटीजर [0..255] के रूप में प्राप्त करता है। |
| [G](../../groupdocs.viewer.drawing/argb32color/g) { get; } | रंग के हरे भाग को 8-बिट अनसाइन्ड इंटीजर [0..255] के रूप में प्राप्त करता है। |
| [IsDefault](../../groupdocs.viewer.drawing/argb32color/isdefault) { get; } | यह दर्शाता है कि यह [`Argb32Color`](../argb32color) उदाहरण डिफ़ॉल्ट (पारदर्शी) है या नहीं - सभी 4 चैनल 0 पर सेट हैं। समान है [`IsEmpty`](./isempty) के। |
| [IsEmpty](../../groupdocs.viewer.drawing/argb32color/isempty) { get; } | यह दर्शाता है कि यह [`Argb32Color`](../argb32color) रंग उदाहरण अनइनिशियलाइज़्ड है या नहीं - सभी 4 चैनल 0 पर सेट हैं। डिफ़ॉल्ट और पारदर्शी के समान। समान है [`IsDefault`](./isdefault) के। |
| [IsFullyOpaque](../../groupdocs.viewer.drawing/argb32color/isfullyopaque) { get; } | यह दर्शाता है कि यह [`Argb32Color`](../argb32color) उदाहरण पूरी तरह अपारदर्शी है, बिना पारदर्शिता के (इसका अल्फा चैनल अधिकतम मान रखता है)। |
| [IsFullyTransparent](../../groupdocs.viewer.drawing/argb32color/isfullytransparent) { get; } | यह दर्शाता है कि यह [`Argb32Color`](../argb32color) उदाहरण पूरी तरह पारदर्शी है - इसका अल्फा चैनल न्यूनतम (0) मान रखता है, इसलिए अन्य R, G, और B चैनलों का कोई दृश्य प्रभाव नहीं रहता। |
| [IsTranslucent](../../groupdocs.viewer.drawing/argb32color/istranslucent) { get; } | यह दर्शाता है कि यह [`Argb32Color`](../argb32color) इंस्टेंस पारदर्शी है (पूरी तरह से पारदर्शी नहीं, लेकिन पूरी तरह से अपारदर्शी भी नहीं) |
| [R](../../groupdocs.viewer.drawing/argb32color/r) { get; } | रंग के लाल भाग को 8-बिट अनसाइन्ड इंटीजर [0..255] के रूप में प्राप्त करता है |
| [Value](../../groupdocs.viewer.drawing/argb32color/value) { get; } | रंग का Int32 मान 32-बिट साइन्ड इंटीजर के रूप में प्राप्त करता है |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| static [FromArgb](../../groupdocs.viewer.drawing/argb32color/fromargb)(int) | एक [`Argb32Color`](../argb32color) इंस्टेंस बनाता है उसके 32-बिट घटकों (अल्फा, लाल, हरा, और नीला) मानों से, `System.Drawing.Color.ToArgb()` मेथड द्वारा उत्पन्न मान के साथ संगत |
| static [FromOtherWithAlpha](../../groupdocs.viewer.drawing/argb32color/fromotherwithalpha#fromotherwithalpha)(Argb32Color, byte) | निर्दिष्ट मानों से एक नया [`Argb32Color`](../argb32color) इंस्टेंस बनाता है, लेकिन पुनः परिभाषित अल्फा (अपारदर्शिता) मान के साथ |
| static [FromOtherWithAlpha](../../groupdocs.viewer.drawing/argb32color/fromotherwithalpha#fromotherwithalpha_1)(Rgb24Color, byte) | निर्दिष्ट [`Rgb24Color`](../rgb24color) से एक नया [`Argb32Color`](../argb32color) इंस्टेंस बनाता है, लेकिन निर्दिष्ट अल्फा (अपारदर्शिता) मान के साथ |
| static [FromRgb](../../groupdocs.viewer.drawing/argb32color/fromrgb)(byte, byte, byte) | निर्दिष्ट लाल, हरा, नीला चैनलों से एक [`Argb32Color`](../argb32color) मान बनाता है, जबकि अल्फा चैनल पूरी तरह अपारदर्शी है |
| static [FromRgba](../../groupdocs.viewer.drawing/argb32color/fromrgba)(byte, byte, byte, byte) | निर्दिष्ट लाल, हरा, नीला, और अल्फा चैनलों से एक [`Argb32Color`](../argb32color) मान बनाता है |
| static [FromSingleValueRgb](../../groupdocs.viewer.drawing/argb32color/fromsinglevaluergb)(byte) | एकल मान से पूरी तरह अपारदर्शी (A=255) रंग बनाता है, जो सभी चैनलों पर लागू होगा |
| [Equals](../../groupdocs.viewer.drawing/argb32color/equals#equals)(Argb32Color) | इस रंग की निर्दिष्ट [`Argb32Color`](../argb32color) रंग के साथ समानता की जाँच करता है |
| override [Equals](../../groupdocs.viewer.drawing/argb32color/equals#equals_2)(object) | इस रंग की निर्दिष्ट अनकास्टेड के साथ जाँच करता है |
| [Equals](../../groupdocs.viewer.drawing/argb32color/equals#equals_1)(Rgb24Color) | इस रंग की निर्दिष्ट [`Rgb24Color`](../rgb24color) रंग के साथ समानता की जाँच करता है |
| [GetBrightness](../../groupdocs.viewer.drawing/argb32color/getbrightness)() | इस [`Argb32Color`](../argb32color) इंस्टेंस के लिए Hue-Saturation-Lightness (HSL) लाइटनेस/ब्राइटनेस लौटाता है। |
| override [GetHashCode](../../groupdocs.viewer.drawing/argb32color/gethashcode)() | एक हैश कोड लौटाता है जो वर्तमान रंग को परिभाषित करता है। GetHashCode के साथ संगत नहीं है। |
| [GetHue](../../groupdocs.viewer.drawing/argb32color/gethue)() | इस [`Argb32Color`](../argb32color) इंस्टेंस के लिए Hue-Saturation-Lightness (HSL) ह्यू मान डिग्री में लौटाता है। यदि R == G == B है, तो ह्यू का कोई अर्थ नहीं है, और लौटाया गया मान 0 है। |
| [GetSaturation](../../groupdocs.viewer.drawing/argb32color/getsaturation)() | इस [`Argb32Color`](../argb32color) इंस्टेंस के लिए Hue-Saturation-Lightness (HSL) संतृप्ति |
| [ToArgb](../../groupdocs.viewer.drawing/argb32color/toargb)() | इस [`Argb32Color`](../argb32color) इंस्टेंस का ARGB मान लौटाता है, `System.Drawing.Color.ToArgb()` मेथड के साथ संगत |
| [ToHexRGB](../../groupdocs.viewer.drawing/argb32color/tohexrgb)() | इस [`Argb32Color`](../argb32color) इंस्टेंस को हेक्साडेसिमल नोटेशन `##RRGGBB` में एक स्ट्रिंग के रूप में सीरियलाइज़ करता है, जिसमें अल्फा चैनल नहीं होता |
| [ToHexRGBA](../../groupdocs.viewer.drawing/argb32color/tohexrgba)() | इस [`Argb32Color`](../argb32color) इंस्टेंस को हेक्साडेसिमल नोटेशन `##RRGGBBAA` में एक स्ट्रिंग के रूप में सीरियलाइज़ करता है, जिसमें अल्फा चैनल शामिल होता है |
| [ToRGB](../../groupdocs.viewer.drawing/argb32color/torgb)() | इस [`Argb32Color`](../argb32color) इंस्टेंस को 'rgb' CSS फ़ंक्शन नोटेशन में सीरियलाइज़ करता है। इस रंग का अल्फा चैनल सीरियलाइज़ेशन के दौरान छोड़ दिया जाएगा। |
| [ToRGBA](../../groupdocs.viewer.drawing/argb32color/torgba)() | इस [`Argb32Color`](../argb32color) इंस्टेंस को 'rgba' CSS फ़ंक्शन नोटेशन में सीरियलाइज़ करता है |
| override [ToString](../../groupdocs.viewer.drawing/argb32color/tostring)() | इस [`Argb32Color`](../argb32color) इंस्टेंस को पारदर्शिता के आधार पर सबसे उपयुक्त CSS फ़ंक्शन नोटेशन में सीरियलाइज़ करता है |
| [operator ==](../../groupdocs.viewer.drawing/argb32color/op_equality#op_equality) | दो [`Argb32Color`](../argb32color) रंगों की तुलना करता है और एक बूलियन लौटाता है जो दर्शाता है कि दोनों मेल खाते हैं या नहीं। (2 ऑपरेटर्स) |
| [explicit operator](../../groupdocs.viewer.drawing/argb32color/op_explicit) | स्पष्ट रूप से 32-बिट [`Argb32Color`](../argb32color) को 24-बिट [`Rgb24Color`](../rgb24color) में कास्ट करता है। स्रोत [`Argb32Color`](../argb32color) का अल्फा चैनल कास्टिंग के बाद खो जाएगा, क्योंकि [`Rgb24Color`](../rgb24color) पारदर्शिता का समर्थन नहीं करता। |
| [implicit operator](../../groupdocs.viewer.drawing/argb32color/op_implicit) | अस्पष्ट रूप से 24-बिट [`Rgb24Color`](../rgb24color) को 32-बिट [`Argb32Color`](../argb32color) में कास्ट करता है। आउटपुट [`Argb32Color`](../argb32color) का अल्फा चैनल `255` पर सेट किया जाएगा - पूरी तरह अपारदर्शी। |
| [operator !=](../../groupdocs.viewer.drawing/argb32color/op_inequality#op_inequality) | दो [`Argb32Color`](../argb32color) रंगों की तुलना करता है और एक बूलियन लौटाता है जो दर्शाता है कि दोनों मेल नहीं खाते। (2 ऑपरेटर) |

## फ़ील्ड्स

| नाम | विवरण |
| --- | --- |
| static readonly [Empty](../../groupdocs.viewer.drawing/argb32color/empty) | एक खाली रंग लौटाता है, जिसमें कोई चैनल जानकारी नहीं होती और वह पूरी तरह पारदर्शी होता है। यह '[`Transparent`](./transparent)' के समान है। डिफ़ॉल्ट मान। |
| static readonly [Transparent](../../groupdocs.viewer.drawing/argb32color/transparent) | पूरी तरह पारदर्शी खाली रंग। यह डिफ़ॉल्ट '[`Empty`](./empty)' रंग मान के समान है। |

### टिप्पणियाँ

यह प्रकार (लेकिन केवल CSS संचालन तक सीमित नहीं) उपयोगी होने के लिए डिज़ाइन किया गया है। अधिक देखें: https://developer.mozilla.org/en-US/docs/Web/CSS/color_value

### संबंधित देखें

* struct [Rgb24Color](../rgb24color)
* namespace [GroupDocs.Viewer.Drawing](../../groupdocs.viewer.drawing)
* assembly [GroupDocs.Viewer](../../)

<!-- संपादित न करें: xmldocmd द्वारा GroupDocs.Viewer.dll के लिए उत्पन्न -->
