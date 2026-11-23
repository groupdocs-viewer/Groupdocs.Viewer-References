---
title: "Rgb24Color"
second_title: "GroupDocs.Viewer için .NET API Referansı"
description: "RGB formatında, her bir kırmızı, yeşil, mavi kanalına 8 bit olmak üzere 24 bit rengi temsil eder. Şeffaflığı desteklemez."
type: docs
weight: 970
url: /tr/net/groupdocs.viewer.drawing/rgb24color/
---

## Rgb24Color structure

RGB formatında 24-bit rengi temsil eder, her kanal (Kırmızı, Yeşil, Mavi) için 8 bit vardır. Şeffaflığı desteklemez.

```csharp
public struct Rgb24Color : IEquatable<Argb32Color>, IEquatable<Rgb24Color>
```

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [B](../../groupdocs.viewer.drawing/rgb24color/b) { get; } | Rengin mavi kısmını 8 bit işaretsiz tamsayı olarak alır [0..255] |
| [G](../../groupdocs.viewer.drawing/rgb24color/g) { get; } | Rengin yeşil kısmını 8 bit işaretsiz tamsayı olarak alır [0..255] |
| [IsDefault](../../groupdocs.viewer.drawing/rgb24color/isdefault) { get; } | Bu [`Rgb24Color`](../rgb24color) örneğinin varsayılan (Siyah) olup olmadığını gösterir - tüm 3 kanal 0 olarak ayarlanmıştır. |
| [R](../../groupdocs.viewer.drawing/rgb24color/r) { get; } | Renklerin kırmızı kısmını 8-bit işaretsiz tamsayı olarak [0..255] alır |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| static [FromRgb](../../groupdocs.viewer.drawing/rgb24color/fromrgb)(byte, byte, byte) | Belirtilen Kırmızı, Yeşil, Mavi kanallarından bir [`Rgb24Color`](../rgb24color) değeri oluşturur. |
| [Equals](../../groupdocs.viewer.drawing/rgb24color/equals#equals)(Argb32Color) | Bu rengi belirtilen [`Argb32Color`](../argb32color) rengiyle eşitlik açısından kontrol eder |
| override [Equals](../../groupdocs.viewer.drawing/rgb24color/equals#equals_2)(object) | Bu rengi belirtilen dönüştürülmemiş ile kontrol eder |
| [Equals](../../groupdocs.viewer.drawing/rgb24color/equals#equals_1)(Rgb24Color) | Bu rengi belirtilen [`Rgb24Color`](../rgb24color) rengiyle eşitlik açısından kontrol eder |
| [GetBrightness](../../groupdocs.viewer.drawing/rgb24color/getbrightness)() | Bu [`Rgb24Color`](../rgb24color) örneği için Hue-Saturation-Lightness (HSL) parlaklığını/aydınlığı döndürür. |
| override [GetHashCode](../../groupdocs.viewer.drawing/rgb24color/gethashcode)() | Geçerli rengi tanımlayan bir hash kodu döndürür. GetHashCode ile uyumlu değildir |
| [GetHue](../../groupdocs.viewer.drawing/rgb24color/gethue)() | Bu [`Rgb24Color`](../rgb24color) örneği için Hue-Saturation-Lightness (HSL) ton değerini derece cinsinden döndürür. R == G == B ise ton anlamsızdır ve döndürülen değer 0'dır. |
| [GetSaturation](../../groupdocs.viewer.drawing/rgb24color/getsaturation)() | Bu [`Rgb24Color`](../rgb24color) örneği için Hue-Saturation-Lightness (HSL) doygunluğu |
| [ToArgb](../../groupdocs.viewer.drawing/rgb24color/toargb)() | Bu [`Rgb24Color`](../rgb24color) örneğinin ARGB değerini, Color ile uyumlu olarak döndürür |
| [ToHex](../../groupdocs.viewer.drawing/rgb24color/tohex)() | Bu rengi onaltılık dize temsili olarak döndürür |
| [ToRGB](../../groupdocs.viewer.drawing/rgb24color/torgb)() | Bu [`Rgb24Color`](../rgb24color) örneğini 'rgb' CSS fonksiyon notasyonuna serileştirir. |
| override [ToString](../../groupdocs.viewer.drawing/rgb24color/tostring)() | Bu [`Rgb24Color`](../rgb24color) örneğini 'rgb(r, g, b)' biçimine serileştirir |
| [operator ==](../../groupdocs.viewer.drawing/rgb24color/op_equality#op_equality_1) | İki [`Rgb24Color`](../rgb24color) rengini karşılaştırır ve iki rengin eşleşip eşleşmediğini gösteren bir boolean döndürür. (2 operatör) |
| [operator !=](../../groupdocs.viewer.drawing/rgb24color/op_inequality#op_inequality_1) | İki [`Rgb24Color`](../rgb24color) rengini karşılaştırır ve iki rengin eşleşmediğini gösteren bir boolean döndürür. (2 operatör) |

## Diğer Üyeler

| Ad | Açıklama |
| --- | --- |
| static class [KnownColors](rgb24color.knowncolors) | Tüm "bilinen renkleri" içerir, bunlar CSS standardında sabit benzersiz isim ve değere sahiptir. |

### Açıklamalar

Bu tip, (ancak bununla sınırlı olmamak üzere) CSS işlemleri için kullanışlı olacak şekilde tasarlanmıştır. Daha fazla bilgi: https://developer.mozilla.org/en-US/docs/Web/CSS/color_value

### Ayrıca Bakınız

* struct [Argb32Color](../argb32color)
* namespace [GroupDocs.Viewer.Drawing](../../groupdocs.viewer.drawing)
* assembly [GroupDocs.Viewer](../../)

<!-- DÜZENLEMEYİN: xmldocmd tarafından GroupDocs.Viewer.dll için oluşturuldu -->
