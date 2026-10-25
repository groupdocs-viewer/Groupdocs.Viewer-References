---
title: "FontStyles"
second_title: "مرجع API الخاص بـ GroupDocs.Viewer لـ .NET"
description: "يمثل 4 أنماط محتملة للخط المستخدم في المستند Regular Bold Italic أو Bold Italic"
type: docs
weight: 810
url: /ar/net/groupdocs.viewer.fonts/fontstyles/
---

## FontStyles structure

يمثل 4 أنماط محتملة للخط، المستخدمة في المستند: Regular، Bold، Italic، أو Bold Italic

```csharp
public struct FontStyles : IEquatable<FontStyles>
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [FontStyles](fontstyles)(bool, bool) | ينشئ نسخة واحدة من [`FontStyles`](../fontstyles) من العلامات bold و italic المحددة |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [IsBold](../../groupdocs.viewer.fonts/fontstyles/isbold) { get; } | يشير إلى ما إذا كانت نسخة [`FontStyles`](../fontstyles) هذه تحتوي على علامة **bold** مفعلة (`true`) أو معطلة (`false`) |
| [IsItalic](../../groupdocs.viewer.fonts/fontstyles/isitalic) { get; } | يشير إلى ما إذا كانت نسخة [`FontStyles`](../fontstyles) هذه تحتوي على علامة **italic** مفعلة (`true`) أو معطلة (`false`) |
| [Name](../../groupdocs.viewer.fonts/fontstyles/name) { get; } | اسم نمط الخط هذا |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [Equals](../../groupdocs.viewer.fonts/fontstyles/equals#equals)(FontStyles) | يشير إلى ما إذا كانت نسخة [`FontStyles`](../fontstyles) هذه مساوية للمعطى |
| override [Equals](../../groupdocs.viewer.fonts/fontstyles/equals#equals_1)(object) | يشير إلى ما إذا كانت نسخة [`FontStyles`](../fontstyles) هذه مساوية للمعطى غير محول |
| override [GetHashCode](../../groupdocs.viewer.fonts/fontstyles/gethashcode)() | يرجع رمز تجزئة (hash-code) لهذه النسخة |
| override [ToString](../../groupdocs.viewer.fonts/fontstyles/tostring)() | يرجع اسم نمط الخط هذا، وهو نفسه كما في [`Name`](./name) |
| static [TryParse](../../groupdocs.viewer.fonts/fontstyles/tryparse)(string, out FontStyles) | يحاول تحليل السلسلة الخام المحددة كاسم لنمط الخط |
| [operator +](../../groupdocs.viewer.fonts/fontstyles/op_addition) | يجمع (يدمج) نمطي خط محددين وينتج نمط خط جديد ناتج، حيث تُدمج العلامات (union) |
| [operator ==](../../groupdocs.viewer.fonts/fontstyles/op_equality) | يتحقق مما إذا كانت قيمتي [`FontStyles`](../fontstyles) متساويتين |
| [explicit operator](../../groupdocs.viewer.fonts/fontstyles/op_explicit) | يحوّل نسخة [`FontStyles`](../fontstyles) المحددة إلى الأوكتت المكافئ (حقل بت 8‑بت) في النطاق العشري [0..3] |
| [operator !=](../../groupdocs.viewer.fonts/fontstyles/op_inequality) | يتحقق مما إذا كانت قيمتي [`FontStyles`](../fontstyles) غير متساويتين |
| [operator -](../../groupdocs.viewer.fonts/fontstyles/op_subtraction) | يطرح نمط الخط المحدد الثاني (subtrahend) من نمط الخط المحدد الأول (minuend) وينتج نمط خط جديد ناتج، حيث تكون موجودة فقط العلامات من العامل الأول التي لا توجد في العامل الثاني (difference) |

## الحقول

| الاسم | الوصف |
| --- | --- |
| static readonly [Bold](../../groupdocs.viewer.fonts/fontstyles/bold) | نمط الخط Bold (bold فقط، بدون italic) |
| static readonly [BoldItalic](../../groupdocs.viewer.fonts/fontstyles/bolditalic) | نمط الخط BoldItalic (bold و italic معًا) |
| static readonly [Italic](../../groupdocs.viewer.fonts/fontstyles/italic) | نمط الخط Italic (italic فقط، بدون bold) |
| static readonly [Regular](../../groupdocs.viewer.fonts/fontstyles/regular) | نمط الخط Regular، القيمة الافتراضية (بدون bold و italic) |

### ملاحظات

هيكل غير قابل للتغيير مع واجهة برمجة تطبيقات (API) مريحة وعمليات الجمع

### انظر أيضًا

* namespace [GroupDocs.Viewer.Fonts](../../groupdocs.viewer.fonts)
* assembly [GroupDocs.Viewer](../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.Viewer.dll -->
