---
title: "FontStyles"
second_title: "GroupDocs.Viewer के लिए .NET API Reference"
description: "दस्तावेज़ में उपयोग किए गए फ़ॉन्ट के 4 संभावित शैलियों का प्रतिनिधित्व करता है: Regular, Bold, Italic या Bold Italic"
type: docs
weight: 810
url: /hi/net/groupdocs.viewer.fonts/fontstyles/
---

## FontStyles structure

दस्तावेज़ में उपयोग किए जाने वाले फ़ॉन्ट के 4 संभावित शैलियों का प्रतिनिधित्व करता है: रेगुलर, बोल्ड, इटैलिक, या बोल्ड इटैलिक।

```csharp
public struct FontStyles : IEquatable<FontStyles>
```

## निर्माता

| नाम | विवरण |
| --- | --- |
| [FontStyles](fontstyles)(bool, bool) | निर्दिष्ट बोल्ड और इटैलिक फ़्लैग्स से एक [`FontStyles`](../fontstyles) इंस्टेंस बनाता है |

## गुण

| नाम | विवरण |
| --- | --- |
| [IsBold](../../groupdocs.viewer.fonts/fontstyles/isbold) { get; } | यह दर्शाता है कि यह [`FontStyles`](../fontstyles) इंस्टेंस में **bold** फ़्लैग सक्षम (`true`) है या अक्षम (`false`) |
| [IsItalic](../../groupdocs.viewer.fonts/fontstyles/isitalic) { get; } | यह दर्शाता है कि यह [`FontStyles`](../fontstyles) इंस्टेंस में **italic** फ़्लैग सक्षम (`true`) है या अक्षम (`false`) |
| [Name](../../groupdocs.viewer.fonts/fontstyles/name) { get; } | इस फ़ॉन्ट शैली का नाम |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| [Equals](../../groupdocs.viewer.fonts/fontstyles/equals#equals)(FontStyles) | यह दर्शाता है कि यह [`FontStyles`](../fontstyles) इंस्टेंस निर्दिष्ट के बराबर है या नहीं |
| override [Equals](../../groupdocs.viewer.fonts/fontstyles/equals#equals_1)(object) | यह दर्शाता है कि यह [`FontStyles`](../fontstyles) इंस्टेंस निर्दिष्ट अनकास्टेड के बराबर है या नहीं |
| override [GetHashCode](../../groupdocs.viewer.fonts/fontstyles/gethashcode)() | इस इंस्टेंस का हैश-कोड लौटाता है |
| override [ToString](../../groupdocs.viewer.fonts/fontstyles/tostring)() | इस फ़ॉन्ट शैली का नाम लौटाता है, जो [`Name`](./name) के समान है |
| static [TryParse](../../groupdocs.viewer.fonts/fontstyles/tryparse)(string, out FontStyles) | निर्दिष्ट कच्ची स्ट्रिंग को फ़ॉन्ट शैली नाम के रूप में पार्स करने का प्रयास करता है |
| [operator +](../../groupdocs.viewer.fonts/fontstyles/op_addition) | दो निर्दिष्ट फ़ॉन्ट शैलियों को मिलाता (विलय) है और नया परिणामस्वरूप फ़ॉन्ट शैली बनाता है, जहाँ फ़्लैग्स मिलाए जाते हैं (संघ) |
| [operator ==](../../groupdocs.viewer.fonts/fontstyles/op_equality) | जाँचता है कि दो [`FontStyles`](../fontstyles) मान बराबर हैं या नहीं |
| [explicit operator](../../groupdocs.viewer.fonts/fontstyles/op_explicit) | निर्दिष्ट [`FontStyles`](../fontstyles) इंस्टेंस को समतुल्य ऑक्टेट (8-बिट बिटफ़ील्ड) में [0..3] दशमलव सीमा में कास्ट करता है |
| [operator !=](../../groupdocs.viewer.fonts/fontstyles/op_inequality) | जाँचता है कि दो [`FontStyles`](../fontstyles) मान बराबर नहीं हैं या नहीं |
| [operator -](../../groupdocs.viewer.fonts/fontstyles/op_subtraction) | दूसरे (सब्ट्राहेंड) निर्दिष्ट फ़ॉन्ट शैली को पहले (मिन्यूएंड) निर्दिष्ट फ़ॉन्ट शैली से घटाता है और नया परिणामस्वरूप फ़ॉन्ट शैली बनाता है, जहाँ केवल पहले ऑपरेण्ड के वे फ़्लैग्स उपस्थित होते हैं जो दूसरे ऑपरेण्ड में नहीं मिलते (भिन्न) |

## फ़ील्ड्स

| नाम | विवरण |
| --- | --- |
| static readonly [Bold](../../groupdocs.viewer.fonts/fontstyles/bold) | Bold फ़ॉन्ट शैली (केवल बोल्ड, इटैलिक के बिना) |
| static readonly [BoldItalic](../../groupdocs.viewer.fonts/fontstyles/bolditalic) | BoldItalic फ़ॉन्ट शैली (बोल्ड और इटैलिक साथ में) |
| static readonly [Italic](../../groupdocs.viewer.fonts/fontstyles/italic) | Italic फ़ॉन्ट शैली (केवल इटैलिक, बोल्ड के बिना) |
| static readonly [Regular](../../groupdocs.viewer.fonts/fontstyles/regular) | Regular फ़ॉन्ट शैली, डिफ़ॉल्ट मान (कोई बोल्ड और इटैलिक नहीं) |

### टिप्पणियाँ

सुविधाजनक API और संयोजन ऑपरेशन्स के साथ अपरिवर्तनीय स्ट्रक्ट

### संबंधित देखें

* namespace [GroupDocs.Viewer.Fonts](../../groupdocs.viewer.fonts)
* assembly [GroupDocs.Viewer](../../)

<!-- संपादित न करें: xmldocmd द्वारा GroupDocs.Viewer.dll के लिए उत्पन्न -->
