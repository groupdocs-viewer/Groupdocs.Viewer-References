---
title: "Rgb24Color"
second_title: "مرجع API الخاص بـ GroupDocs.Viewer لـ .NET"
description: "يمثل لونًا بعمق 24 بت بتنسيق RGB مع 8 بت لكل قناة من القنوات الأحمر والأخضر والأزرق. لا يدعم الشفافية."
type: docs
weight: 970
url: /ar/net/groupdocs.viewer.drawing/rgb24color/
---

## Rgb24Color structure

يمثل لونًا 24-بتًا بتنسيق RGB، مع 8 بتات لكل قناة (Red، Green، Blue). لا يدعم الشفافية.

```csharp
public struct Rgb24Color : IEquatable<Argb32Color>, IEquatable<Rgb24Color>
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [B](../../groupdocs.viewer.drawing/rgb24color/b) { get; } | يحصل على الجزء أزرق من اللون كعدد صحيح غير موقع 8 بت [0..255] |
| [G](../../groupdocs.viewer.drawing/rgb24color/g) { get; } | يحصل على الجزء أخضر من اللون كعدد صحيح غير موقع 8 بت [0..255] |
| [IsDefault](../../groupdocs.viewer.drawing/rgb24color/isdefault) { get; } | يشير إلى ما إذا كان هذا [`Rgb24Color`](../rgb24color) هو الافتراضي (Black) - جميع القنوات الثلاثة مضبوطة على 0. |
| [R](../../groupdocs.viewer.drawing/rgb24color/r) { get; } | يحصل على الجزء الأحمر من اللون كعدد صحيح غير موقع 8‑بت [0..255] |

## الطرق

| الاسم | الوصف |
| --- | --- |
| static [FromRgb](../../groupdocs.viewer.drawing/rgb24color/fromrgb)(byte, byte, byte) | ينشئ قيمة واحدة من نوع [`Rgb24Color`](../rgb24color) من القنوات الأحمر، الأخضر، الأزرق المحددة |
| [Equals](../../groupdocs.viewer.drawing/rgb24color/equals#equals)(Argb32Color) | يفحص هذا اللون مع اللون [`Argb32Color`](../argb32color) المحدد للتحقق من المساواة |
| override [Equals](../../groupdocs.viewer.drawing/rgb24color/equals#equals_2)(object) | يفحص هذا اللون مع القيمة غير المحولة المحددة |
| [Equals](../../groupdocs.viewer.drawing/rgb24color/equals#equals_1)(Rgb24Color) | يفحص هذا اللون مع اللون [`Rgb24Color`](../rgb24color) المحدد للتحقق من المساواة |
| [GetBrightness](../../groupdocs.viewer.drawing/rgb24color/getbrightness)() | يرجع قيمة الإضاءة/السطوع في نظام Hue-Saturation-Lightness (HSL) لهذا [`Rgb24Color`](../rgb24color) |
| override [GetHashCode](../../groupdocs.viewer.drawing/rgb24color/gethashcode)() | يعيد رمز تجزئة يحدد اللون الحالي. غير متوافق مع GetHashCode |
| [GetHue](../../groupdocs.viewer.drawing/rgb24color/gethue)() | يعيد قيمة درجة اللون (Hue) في نظام Hue-Saturation-Lightness (HSL) بالدرجات لهذا الكائن [`Rgb24Color`](../rgb24color). إذا كان R == G == B، فإن درجة اللون لا معنى لها، وقيمة الإرجاع هي 0. |
| [GetSaturation](../../groupdocs.viewer.drawing/rgb24color/getsaturation)() | التشبع في نظام Hue-Saturation-Lightness (HSL) لهذا الكائن [`Rgb24Color`](../rgb24color) |
| [ToArgb](../../groupdocs.viewer.drawing/rgb24color/toargb)() | يعيد قيمة ARGB لهذا الكائن [`Rgb24Color`](../rgb24color)، متوافقة مع Color |
| [ToHex](../../groupdocs.viewer.drawing/rgb24color/tohex)() | يعيد هذا اللون في تمثيل سلسلة سداسي عشرية |
| [ToRGB](../../groupdocs.viewer.drawing/rgb24color/torgb)() | يسلسل هذا الكائن [`Rgb24Color`](../rgb24color) إلى تدوين دالة CSS 'rgb' |
| override [ToString](../../groupdocs.viewer.drawing/rgb24color/tostring)() | يسلسل هذا الكائن [`Rgb24Color`](../rgb24color) إلى تنسيق 'rgb(r, g, b)' |
| [operator ==](../../groupdocs.viewer.drawing/rgb24color/op_equality#op_equality_1) | يقارن لونين من نوع [`Rgb24Color`](../rgb24color) ويعيد قيمة منطقية تشير إلى ما إذا كان اللونان متطابقين. (عاملين) |
| [operator !=](../../groupdocs.viewer.drawing/rgb24color/op_inequality#op_inequality_1) | يقارن لونين من نوع [`Rgb24Color`](../rgb24color) ويعيد قيمة منطقية تشير إلى ما إذا كان اللونان غير متطابقين. (عاملين) |

## الأعضاء الآخرين

| الاسم | الوصف |
| --- | --- |
| static class [KnownColors](rgb24color.knowncolors) | يحتوي على جميع "الألوان المعروفة"، التي لها اسم فريد ثابت وقيمة في معيار CSS |

### ملاحظات

تم تصميم هذا النوع ليكون مفيدًا لـ (ولكن ليس محصورًا على) عمليات CSS. راجع المزيد: https://developer.mozilla.org/en-US/docs/Web/CSS/color_value

### انظر أيضًا

* struct [Argb32Color](../argb32color)
* namespace [GroupDocs.Viewer.Drawing](../../groupdocs.viewer.drawing)
* assembly [GroupDocs.Viewer](../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.Viewer.dll -->
