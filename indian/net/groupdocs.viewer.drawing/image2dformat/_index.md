---
title: "Image2DFormat"
second_title: "GroupDocs.Viewer के लिए .NET API Reference"
description: "सबसे सामान्य 2D इमेज फ़ॉर्मेट्स को दर्शाता है, जो रास्टर और वेक्टर दोनों फ़ॉर्मेट्स को सपोर्ट करते हैं।"
type: docs
weight: 960
url: /hi/net/groupdocs.viewer.drawing/image2dformat/
---

## Image2DFormat structure

सबसे सामान्य 2D इमेज फ़ॉर्मेट्स का प्रतिनिधित्व करता है, रास्टर और वेक्टर दोनों फ़ॉर्मेट्स का समर्थन करता है।

```csharp
public struct Image2DFormat : IEquatable<Image2DFormat>
```

## गुण

| नाम | विवरण |
| --- | --- |
| static [Bmp](../../groupdocs.viewer.drawing/image2dformat/bmp) { get; } | BMP इमेज प्रकार |
| static [Emf](../../groupdocs.viewer.drawing/image2dformat/emf) { get; } | EMF (Enhanced MetaFile) वेक्टर इमेज प्रकार |
| static [Gif](../../groupdocs.viewer.drawing/image2dformat/gif) { get; } | GIF इमेज प्रकार |
| static [Icon](../../groupdocs.viewer.drawing/image2dformat/icon) { get; } | ICON इमेज प्रकार |
| static [Jpeg](../../groupdocs.viewer.drawing/image2dformat/jpeg) { get; } | JPEG इमेज प्रकार |
| static [Png](../../groupdocs.viewer.drawing/image2dformat/png) { get; } | PNG इमेज प्रकार |
| static [Svg](../../groupdocs.viewer.drawing/image2dformat/svg) { get; } | SVG वेक्टर इमेज प्रकार |
| static [Tiff](../../groupdocs.viewer.drawing/image2dformat/tiff) { get; } | TIFF (Tagged Image File Format) रास्टर इमेज प्रकार |
| static [Undefined](../../groupdocs.viewer.drawing/image2dformat/undefined) { get; } | अपरिभाषित इमेज प्रकार - विशेष मान, जो सामान्यतः नहीं होना चाहिए। |
| static [Wmf](../../groupdocs.viewer.drawing/image2dformat/wmf) { get; } | WMF (Windows MetaFile) वेक्टर इमेज प्रकार |
| [FileExtension](../../groupdocs.viewer.drawing/image2dformat/fileextension) { get; } | किसी विशेष इमेज प्रकार का फ़ाइल एक्सटेंशन (शुरुआती डॉट के बिना) लोअर केस में। [`Undefined`](./undefined) मान के लिए स्ट्रिंग 'undefined' लौटाता है। |
| [IsVector](../../groupdocs.viewer.drawing/image2dformat/isvector) { get; } | यह दर्शाता है कि यह विशेष फ़ॉर्मेट वेक्टर (`true`) है या रास्टर (`false`) |
| [MimeCode](../../groupdocs.viewer.drawing/image2dformat/mimecode) { get; } | किसी विशेष इमेज प्रकार का MIME कोड स्ट्रिंग के रूप में। Undefined प्रकार के लिए स्ट्रिंग 'unsefined' लौटाता है। |
| [Name](../../groupdocs.viewer.drawing/image2dformat/name) { get; } | इस इमेज फ़ॉर्मेट का औपचारिक नाम लौटाता है। कभी भी NULL नहीं लौटाता। यदि इंस्टेंस भ्रष्ट नहीं है, तो कभी भी अपवाद नहीं फेंकता। |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| static [ParseFromFilenameWithExtension](../../groupdocs.viewer.drawing/image2dformat/parsefromfilenamewithextension)(string) | ImageFormat मान लौटाता है, जो फ़ाइलनाम एक्सटेंशन के बराबर है, जिसे निर्दिष्ट फ़ाइलनाम से निकाला जाता है। |
| static [ParseFromMime](../../groupdocs.viewer.drawing/image2dformat/parsefrommime)(string) | [`Image2DFormat`](../image2dformat) मान लौटाता है, जो निर्दिष्ट MIME कोड के बराबर है। |
| [Equals](../../groupdocs.viewer.drawing/image2dformat/equals#equals)(Image2DFormat) | निर्धारित करता है कि यह इंस्टेंस निर्दिष्ट "[`Image2DFormat`](../image2dformat)" इंस्टेंस के बराबर है या नहीं। |
| override [Equals](../../groupdocs.viewer.drawing/image2dformat/equals#equals_1)(object) | निर्धारित करता है कि यह इंस्टेंस निर्दिष्ट अनकास्टेड ऑब्जेक्ट के बराबर है या नहीं, जो सम्भवतः एक अन्य "[`Image2DFormat`](../image2dformat)" इंस्टेंस है। |
| override [GetHashCode](../../groupdocs.viewer.drawing/image2dformat/gethashcode)() | हैश-कोड लौटाता है, जो इस विशिष्ट इंस्टेंस के लिए अपरिवर्तनीय संख्या है। |
| override [ToString](../../groupdocs.viewer.drawing/image2dformat/tostring)() | एक [`Name`](./name) प्रॉपर्टी लौटाता है |
| [operator ==](../../groupdocs.viewer.drawing/image2dformat/op_equality) | परिभाषित करता है कि दो विशिष्ट [`Image2DFormat`](../image2dformat) इंस्टेंस बराबर हैं या नहीं |
| [operator !=](../../groupdocs.viewer.drawing/image2dformat/op_inequality) | परिभाषित करता है कि दो विशिष्ट [`Image2DFormat`](../image2dformat) इंस्टेंस असमान हैं या नहीं |

### संबंधित देखें

* namespace [GroupDocs.Viewer.Drawing](../../groupdocs.viewer.drawing)
* assembly [GroupDocs.Viewer](../../)

<!-- संपादित न करें: xmldocmd द्वारा GroupDocs.Viewer.dll के लिए उत्पन्न -->
