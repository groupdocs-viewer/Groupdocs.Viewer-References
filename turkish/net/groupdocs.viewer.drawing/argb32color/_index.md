---
title: "Argb32Color"
second_title: "GroupDocs.Viewer için .NET API Referansı"
description: "ARGB formatında, her kanal (Alfa, Kırmızı, Yeşil, Mavi) için 8 bit olmak üzere 32 bit renk temsil eder. Şeffaflığı destekler."
type: docs
weight: 950
url: /tr/net/groupdocs.viewer.drawing/argb32color/
---

## Argb32Color structure

ARGB formatında 32-bit rengi temsil eder, her kanal (Alfa, Kırmızı, Yeşil, Mavi) için 8 bit vardır. Şeffaflığı destekler.

```csharp
public struct Argb32Color : IEquatable<Argb32Color>, IEquatable<Rgb24Color>
```

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [A](../../groupdocs.viewer.drawing/argb32color/a) { get; } | Rengin alfa kısmını 8 bit işaretsiz tamsayı olarak alır [0..255] |
| [Alpha](../../groupdocs.viewer.drawing/argb32color/alpha) { get; } | Rengin alfa kısmını (0..1) aralığında yüzde olarak alır. |
| [B](../../groupdocs.viewer.drawing/argb32color/b) { get; } | Rengin mavi kısmını 8 bit işaretsiz tamsayı olarak alır [0..255] |
| [G](../../groupdocs.viewer.drawing/argb32color/g) { get; } | Rengin yeşil kısmını 8 bit işaretsiz tamsayı olarak alır [0..255] |
| [IsDefault](../../groupdocs.viewer.drawing/argb32color/isdefault) { get; } | Bu [`Argb32Color`](../argb32color) örneğinin varsayılan (Şeffaf) olup olmadığını gösterir - tüm 4 kanal 0 olarak ayarlanır. Aynı [`IsEmpty`](./isempty) |
| [IsEmpty](../../groupdocs.viewer.drawing/argb32color/isempty) { get; } | Bu [`Argb32Color`](../argb32color) renk örneğinin başlatılmamış olup olmadığını gösterir - tüm 4 kanal 0 olarak ayarlanır. Varsayılan ve Şeffaf ile aynı. Aynı [`IsDefault`](./isdefault) |
| [IsFullyOpaque](../../groupdocs.viewer.drawing/argb32color/isfullyopaque) { get; } | Bu [`Argb32Color`](../argb32color) örneğinin tamamen opak olup olmadığını gösterir, şeffaflık yoktur (Alpha kanalı maksimum değere sahiptir) |
| [IsFullyTransparent](../../groupdocs.viewer.drawing/argb32color/isfullytransparent) { get; } | Bu [`Argb32Color`](../argb32color) örneğinin tamamen şeffaf olup olmadığını gösterir - Alpha kanalı minimum (0) değere sahiptir, bu yüzden diğer R, G ve B kanalları görünür bir etki yapmaz. |
| [IsTranslucent](../../groupdocs.viewer.drawing/argb32color/istranslucent) { get; } | Bu [`Argb32Color`](../argb32color) örneğinin yarı saydam olup olmadığını gösterir (tamamen şeffaf değil, ancak tamamen opak da değildir) |
| [R](../../groupdocs.viewer.drawing/argb32color/r) { get; } | Renklerin kırmızı kısmını 8-bit işaretsiz tamsayı olarak [0..255] alır |
| [Value](../../groupdocs.viewer.drawing/argb32color/value) { get; } | Rengin Int32 değerini 32-bit işaretli tamsayı olarak alır |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| static [FromArgb](../../groupdocs.viewer.drawing/argb32color/fromargb)(int) | 32-bit bileşen (alfa, kırmızı, yeşil ve mavi) değerlerinden bir [`Argb32Color`](../argb32color) örneği oluşturur, `System.Drawing.Color.ToArgb()` yöntemi tarafından üretilen değerle uyumludur |
| static [FromOtherWithAlpha](../../groupdocs.viewer.drawing/argb32color/fromotherwithalpha#fromotherwithalpha)(Argb32Color, byte) | Belirtilen değerlerden yeni bir [`Argb32Color`](../argb32color) örneği oluşturur, ancak alfa (opaklık) değeri yeniden tanımlanır |
| static [FromOtherWithAlpha](../../groupdocs.viewer.drawing/argb32color/fromotherwithalpha#fromotherwithalpha_1)(Rgb24Color, byte) | Belirtilen [`Rgb24Color`](../rgb24color) değerinden yeni bir [`Argb32Color`](../argb32color) örneği oluşturur, ancak belirtilen alfa (opaklık) değeri kullanılır |
| static [FromRgb](../../groupdocs.viewer.drawing/argb32color/fromrgb)(byte, byte, byte) | Belirtilen Kırmızı, Yeşil, Mavi kanallarından bir [`Argb32Color`](../argb32color) değeri oluşturur, Alfa kanalı tamamen opaktır |
| static [FromRgba](../../groupdocs.viewer.drawing/argb32color/fromrgba)(byte, byte, byte, byte) | Belirtilen Kırmızı, Yeşil, Mavi ve Alfa kanallarından bir [`Argb32Color`](../argb32color) değeri oluşturur |
| static [FromSingleValueRgb](../../groupdocs.viewer.drawing/argb32color/fromsinglevaluergb)(byte) | Tek bir değerden tamamen opak (A=255) bir renk oluşturur; bu değer tüm kanallara uygulanır |
| [Equals](../../groupdocs.viewer.drawing/argb32color/equals#equals)(Argb32Color) | Bu rengi belirtilen [`Argb32Color`](../argb32color) rengiyle eşitlik açısından kontrol eder |
| override [Equals](../../groupdocs.viewer.drawing/argb32color/equals#equals_2)(object) | Bu rengi belirtilen dönüştürülmemiş ile kontrol eder |
| [Equals](../../groupdocs.viewer.drawing/argb32color/equals#equals_1)(Rgb24Color) | Bu rengi belirtilen [`Rgb24Color`](../rgb24color) rengiyle eşitlik açısından kontrol eder |
| [GetBrightness](../../groupdocs.viewer.drawing/argb32color/getbrightness)() | Bu [`Argb32Color`](../argb32color) örneği için Hue-Saturation-Lightness (HSL) aydınlık/parlaklık değerini döndürür. |
| override [GetHashCode](../../groupdocs.viewer.drawing/argb32color/gethashcode)() | Geçerli rengi tanımlayan bir hash kodu döndürür. GetHashCode ile uyumlu değildir |
| [GetHue](../../groupdocs.viewer.drawing/argb32color/gethue)() | Bu [`Argb32Color`](../argb32color) örneği için Hue-Saturation-Lightness (HSL) renk tonu değerini derece cinsinden döndürür. Eğer R == G == B ise, renk tonu anlamsızdır ve döndürülen değer 0'dır. |
| [GetSaturation](../../groupdocs.viewer.drawing/argb32color/getsaturation)() | Bu [`Argb32Color`](../argb32color) örneği için Hue-Saturation-Lightness (HSL) doygunluğu |
| [ToArgb](../../groupdocs.viewer.drawing/argb32color/toargb)() | Bu [`Argb32Color`](../argb32color) örneğinin ARGB değerini döndürür, `System.Drawing.Color.ToArgb()` yöntemiyle uyumludur |
| [ToHexRGB](../../groupdocs.viewer.drawing/argb32color/tohexrgb)() | Bu [`Argb32Color`](../argb32color) örneğini alfa kanalı olmadan `##RRGGBB` onaltılık gösterimine bir dize olarak serileştirir |
| [ToHexRGBA](../../groupdocs.viewer.drawing/argb32color/tohexrgba)() | Bu [`Argb32Color`](../argb32color) örneğini alfa kanalıyla `##RRGGBBAA` onaltılık gösterimine bir dize olarak serileştirir |
| [ToRGB](../../groupdocs.viewer.drawing/argb32color/torgb)() | Bu [`Argb32Color`](../argb32color) örneğini 'rgb' CSS fonksiyon gösterimine serileştirir. Bu rengin alfa kanalı serileştirme sırasında atlanacaktır. |
| [ToRGBA](../../groupdocs.viewer.drawing/argb32color/torgba)() | Bu [`Argb32Color`](../argb32color) örneğini 'rgba' CSS fonksiyon gösterimine serileştirir |
| override [ToString](../../groupdocs.viewer.drawing/argb32color/tostring)() | Bu [`Argb32Color`](../argb32color) örneğini saydamlığa bağlı olarak en uygun CSS fonksiyon gösterimine serileştirir |
| [operator ==](../../groupdocs.viewer.drawing/argb32color/op_equality#op_equality) | İki [`Argb32Color`](../argb32color) rengini karşılaştırır ve iki rengin eşleşip eşleşmediğini gösteren bir boolean döndürür. (2 operatör) |
| [explicit operator](../../groupdocs.viewer.drawing/argb32color/op_explicit) | 32-bit [`Argb32Color`](../argb32color) değerini açıkça 24-bit [`Rgb24Color`](../rgb24color) değerine dönüştürür. Kaynak [`Argb32Color`](../argb32color) nin alfa kanalı, [`Rgb24Color`](../rgb24color) şeffaflığı desteklemediği için dönüşüm sonrası kaybolur. |
| [implicit operator](../../groupdocs.viewer.drawing/argb32color/op_implicit) | 24-bit [`Rgb24Color`](../rgb24color) değerini örtük olarak 32-bit [`Argb32Color`](../argb32color) değerine dönüştürür. Çıktı [`Argb32Color`](../argb32color) nin alfa kanalı `255` olarak ayarlanır - tamamen opaktır. |
| [operator !=](../../groupdocs.viewer.drawing/argb32color/op_inequality#op_inequality) | İki [`Argb32Color`](../argb32color) rengini karşılaştırır ve iki rengin eşleşip eşleşmediğini gösteren bir boolean döndürür. (2 operatör) |

## Alanlar

| Ad | Açıklama |
| --- | --- |
| static readonly [Empty](../../groupdocs.viewer.drawing/argb32color/empty) | Kanal bilgisi olmayan ve tamamen şeffaf bir boş renk döndürür. '[`Transparent`](./transparent)' ile aynı. Varsayılan değer. |
| static readonly [Transparent](../../groupdocs.viewer.drawing/argb32color/transparent) | Tamamen şeffaf boş renk. Varsayılan '[`Empty`](./empty)' renk değeri ile aynı. |

### Açıklamalar

Bu tip, (ancak bununla sınırlı olmamak üzere) CSS işlemleri için kullanışlı olacak şekilde tasarlanmıştır. Daha fazla bilgi: https://developer.mozilla.org/en-US/docs/Web/CSS/color_value

### Ayrıca Bakınız

* struct [Rgb24Color](../rgb24color)
* namespace [GroupDocs.Viewer.Drawing](../../groupdocs.viewer.drawing)
* assembly [GroupDocs.Viewer](../../)

<!-- DÜZENLEMEYİN: xmldocmd tarafından GroupDocs.Viewer.dll için oluşturuldu -->
