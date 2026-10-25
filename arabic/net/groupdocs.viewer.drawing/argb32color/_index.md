---
title: "Argb32Color"
second_title: "مرجع API الخاص بـ GroupDocs.Viewer لـ .NET"
description: "يمثل لونًا 32 بتًا بتنسيق ARGB مع 8 بتات لكل قناة (ألفا، أحمر، أخضر، أزرق). يدعم الشفافية."
type: docs
weight: 950
url: /ar/net/groupdocs.viewer.drawing/argb32color/
---

## Argb32Color structure

يمثل لونًا 32-بتًا بتنسيق ARGB، مع 8 بتات لكل قناة (Alpha، Red، Green، Blue). يدعم الشفافية.

```csharp
public struct Argb32Color : IEquatable<Argb32Color>, IEquatable<Rgb24Color>
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [A](../../groupdocs.viewer.drawing/argb32color/a) { get; } | يحصل على الجزء ألفا من اللون كعدد صحيح غير موقع 8 بت [0..255] |
| [Alpha](../../groupdocs.viewer.drawing/argb32color/alpha) { get; } | يحصل على الجزء ألفا من اللون كنسبة مئوية في النطاق (0..1). |
| [B](../../groupdocs.viewer.drawing/argb32color/b) { get; } | يحصل على الجزء أزرق من اللون كعدد صحيح غير موقع 8 بت [0..255] |
| [G](../../groupdocs.viewer.drawing/argb32color/g) { get; } | يحصل على الجزء أخضر من اللون كعدد صحيح غير موقع 8 بت [0..255] |
| [IsDefault](../../groupdocs.viewer.drawing/argb32color/isdefault) { get; } | يشير إلى ما إذا كان هذا [`Argb32Color`](../argb32color) هو الافتراضي (شفاف) - جميع القنوات الأربعة مضبوطة على 0. نفس ما هو [`IsEmpty`](./isempty) |
| [IsEmpty](../../groupdocs.viewer.drawing/argb32color/isempty) { get; } | يشير إلى ما إذا كان هذا الكائن اللوني [`Argb32Color`](../argb32color) غير مهيأ - جميع القنوات الأربعة مضبوطة على 0. نفس ما هو الافتراضي والشفاف. نفس ما هو [`IsDefault`](./isdefault) |
| [IsFullyOpaque](../../groupdocs.viewer.drawing/argb32color/isfullyopaque) { get; } | يشير إلى ما إذا كان هذا [`Argb32Color`](../argb32color) غير شفاف بالكامل، بدون شفافية (قناة ألفا لديها القيمة القصوى) |
| [IsFullyTransparent](../../groupdocs.viewer.drawing/argb32color/isfullytransparent) { get; } | يشير إلى ما إذا كان هذا [`Argb32Color`](../argb32color) شفافًا بالكامل - قناة ألفا لديها القيمة الدنيا (0)، لذا لا تؤثر القنوات R و G و B الأخرى بشكل مرئي. |
| [IsTranslucent](../../groupdocs.viewer.drawing/argb32color/istranslucent) { get; } | يشير إلى ما إذا كانت هذه الحالة من [`Argb32Color`](../argb32color) شفافة جزئياً (ليست شفافة بالكامل، ولكنها ليست معتمة بالكامل) |
| [R](../../groupdocs.viewer.drawing/argb32color/r) { get; } | يحصل على الجزء الأحمر من اللون كعدد صحيح غير موقع 8‑بت [0..255] |
| [Value](../../groupdocs.viewer.drawing/argb32color/value) { get; } | يحصل على قيمة Int32 للون كعدد صحيح موقع 32‑بت |

## الطرق

| الاسم | الوصف |
| --- | --- |
| static [FromArgb](../../groupdocs.viewer.drawing/argb32color/fromargb)(int) | ينشئ كائن [`Argb32Color`](../argb32color) من مكوناته 32‑بت (ألفا، أحمر، أخضر، وأزرق)، متوافق مع القيمة التي ينتجها أسلوب `System.Drawing.Color.ToArgb()` |
| static [FromOtherWithAlpha](../../groupdocs.viewer.drawing/argb32color/fromotherwithalpha#fromotherwithalpha)(Argb32Color, byte) | ينشئ كائنًا جديدًا من [`Argb32Color`](../argb32color) من القيم المحددة، ولكن مع قيمة ألفا (الشفافية) معاد تعريفها |
| static [FromOtherWithAlpha](../../groupdocs.viewer.drawing/argb32color/fromotherwithalpha#fromotherwithalpha_1)(Rgb24Color, byte) | ينشئ كائنًا جديدًا من [`Argb32Color`](../argb32color) من [`Rgb24Color`](../rgb24color) المحدد، ولكن مع قيمة ألفا (الشفافية) المحددة |
| static [FromRgb](../../groupdocs.viewer.drawing/argb32color/fromrgb)(byte, byte, byte) | ينشئ قيمة واحدة من [`Argb32Color`](../argb32color) من القنوات الأحمر، الأخضر، والأزرق المحددة، بينما قناة ألفا تكون معتمة بالكامل |
| static [FromRgba](../../groupdocs.viewer.drawing/argb32color/fromrgba)(byte, byte, byte, byte) | ينشئ قيمة واحدة من [`Argb32Color`](../argb32color) من القنوات الأحمر، الأخضر، الأزرق، وألفا المحددة |
| static [FromSingleValueRgb](../../groupdocs.viewer.drawing/argb32color/fromsinglevaluergb)(byte) | ينشئ لونًا معتمًا بالكامل (A=255) من قيمة واحدة، تُطبق على جميع القنوات |
| [Equals](../../groupdocs.viewer.drawing/argb32color/equals#equals)(Argb32Color) | يفحص هذا اللون مع اللون [`Argb32Color`](../argb32color) المحدد للتحقق من المساواة |
| override [Equals](../../groupdocs.viewer.drawing/argb32color/equals#equals_2)(object) | يفحص هذا اللون مع القيمة غير المحولة المحددة |
| [Equals](../../groupdocs.viewer.drawing/argb32color/equals#equals_1)(Rgb24Color) | يفحص هذا اللون مع اللون [`Rgb24Color`](../rgb24color) المحدد للتحقق من المساواة |
| [GetBrightness](../../groupdocs.viewer.drawing/argb32color/getbrightness)() | يعيد قيمة الإضاءة/السطوع في نظام Hue‑Saturation‑Lightness (HSL) لهذا الكائن [`Argb32Color`](../argb32color). |
| override [GetHashCode](../../groupdocs.viewer.drawing/argb32color/gethashcode)() | يعيد رمز تجزئة يحدد اللون الحالي. غير متوافق مع GetHashCode |
| [GetHue](../../groupdocs.viewer.drawing/argb32color/gethue)() | يعيد قيمة درجة اللون (Hue) في نظام Hue‑Saturation‑Lightness (HSL) لهذا الكائن [`Argb32Color`](../argb32color) بالدرجات. إذا كان R == G == B، فإن درجة اللون لا معنى لها، وتكون القيمة المرجعة 0. |
| [GetSaturation](../../groupdocs.viewer.drawing/argb32color/getsaturation)() | تشبع نظام Hue‑Saturation‑Lightness (HSL) لهذا الكائن [`Argb32Color`](../argb32color) |
| [ToArgb](../../groupdocs.viewer.drawing/argb32color/toargb)() | يعيد قيمة ARGB لهذا الكائن [`Argb32Color`](../argb32color)، متوافق مع أسلوب `System.Drawing.Color.ToArgb()` |
| [ToHexRGB](../../groupdocs.viewer.drawing/argb32color/tohexrgb)() | يسلسل هذا الكائن [`Argb32Color`](../argb32color) إلى الصيغة السداسية عشرية `##RRGGBB` كسلسلة دون قناة ألفا |
| [ToHexRGBA](../../groupdocs.viewer.drawing/argb32color/tohexrgba)() | يسلسل هذا الكائن [`Argb32Color`](../argb32color) إلى الصيغة السداسية عشرية `##RRGGBBAA` كسلسلة مع قناة ألفا |
| [ToRGB](../../groupdocs.viewer.drawing/argb32color/torgb)() | يسلسل هذا الكائن [`Argb32Color`](../argb32color) إلى صيغة الدالة CSS 'rgb'. سيتم حذف قناة ألفا لهذا اللون أثناء التسلسل. |
| [ToRGBA](../../groupdocs.viewer.drawing/argb32color/torgba)() | يسلسل هذا الكائن [`Argb32Color`](../argb32color) إلى صيغة الدالة CSS 'rgba' |
| override [ToString](../../groupdocs.viewer.drawing/argb32color/tostring)() | يسلسل هذا الكائن [`Argb32Color`](../argb32color) إلى صيغة الدالة CSS الأنسب اعتمادًا على الشفافية الجزئية |
| [operator ==](../../groupdocs.viewer.drawing/argb32color/op_equality#op_equality) | يقارن لونين من [`Argb32Color`](../argb32color) ويعيد قيمة منطقية تشير إلى ما إذا كان اللونان متطابقين. (عاملان) |
| [explicit operator](../../groupdocs.viewer.drawing/argb32color/op_explicit) | يحول صراحةً الـ[`Argb32Color`](../argb32color) 32‑بت إلى [`Rgb24Color`](../rgb24color) 24‑بت. ستفقد قناة ألفا في المصدر [`Argb32Color`](../argb32color) بعد التحويل، لأن [`Rgb24Color`](../rgb24color) لا يدعم الشفافية. |
| [implicit operator](../../groupdocs.viewer.drawing/argb32color/op_implicit) | يحول ضمنيًا الـ[`Rgb24Color`](../rgb24color) 24‑بت إلى [`Argb32Color`](../argb32color) 32‑بت. ستُضبط قناة ألفا في الناتج [`Argb32Color`](../argb32color) إلى `255` - معتمة بالكامل |
| [operator !=](../../groupdocs.viewer.drawing/argb32color/op_inequality#op_inequality) | يقارن لونين من [`Argb32Color`](../argb32color) ويعيد قيمة منطقية تشير إلى ما إذا كان اللونان غير متطابقين. (عاملين) |

## الحقول

| الاسم | الوصف |
| --- | --- |
| static readonly [Empty](../../groupdocs.viewer.drawing/argb32color/empty) | يعيد لونًا فارغًا، لا يحتوي على معلومات القنوات وهو شفاف تمامًا. نفس '[`Transparent`](./transparent)'. القيمة الافتراضية. |
| static readonly [Transparent](../../groupdocs.viewer.drawing/argb32color/transparent) | لون فارغ شفاف تمامًا. وهو نفس قيمة اللون الافتراضية '[`Empty`](./empty)'. |

### ملاحظات

تم تصميم هذا النوع ليكون مفيدًا لـ (ولكن ليس محصورًا على) عمليات CSS. راجع المزيد: https://developer.mozilla.org/en-US/docs/Web/CSS/color_value

### انظر أيضًا

* struct [Rgb24Color](../rgb24color)
* namespace [GroupDocs.Viewer.Drawing](../../groupdocs.viewer.drawing)
* assembly [GroupDocs.Viewer](../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.Viewer.dll -->
