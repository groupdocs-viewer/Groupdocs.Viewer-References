---
title: "Image2DFormat"
second_title: "مرجع API الخاص بـ GroupDocs.Viewer لـ .NET"
description: "يمثل أكثر صيغ الصور الثنائية الأبعاد شيوعًا ويدعم كلًا من الصيغ النقطية والمتجهة."
type: docs
weight: 960
url: /ar/net/groupdocs.viewer.drawing/image2dformat/
---

## Image2DFormat structure

يمثل أكثر تنسيقات الصور الثنائية الأبعاد شيوعًا، يدعم كلًا من التنسيقات النقطية والمتجهة.

```csharp
public struct Image2DFormat : IEquatable<Image2DFormat>
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| static [Bmp](../../groupdocs.viewer.drawing/image2dformat/bmp) { get; } | نوع صورة BMP |
| static [Emf](../../groupdocs.viewer.drawing/image2dformat/emf) { get; } | نوع صورة EMF (Enhanced MetaFile) المتجهة |
| static [Gif](../../groupdocs.viewer.drawing/image2dformat/gif) { get; } | نوع صورة GIF |
| static [Icon](../../groupdocs.viewer.drawing/image2dformat/icon) { get; } | نوع صورة ICON |
| static [Jpeg](../../groupdocs.viewer.drawing/image2dformat/jpeg) { get; } | نوع صورة JPEG |
| static [Png](../../groupdocs.viewer.drawing/image2dformat/png) { get; } | نوع صورة PNG |
| static [Svg](../../groupdocs.viewer.drawing/image2dformat/svg) { get; } | نوع صورة SVG المتجهة |
| static [Tiff](../../groupdocs.viewer.drawing/image2dformat/tiff) { get; } | نوع صورة TIFF (Tagged Image File Format) النقطية |
| static [Undefined](../../groupdocs.viewer.drawing/image2dformat/undefined) { get; } | نوع صورة غير معرف - قيمة خاصة، لا ينبغي أن تحدث عادةً |
| static [Wmf](../../groupdocs.viewer.drawing/image2dformat/wmf) { get; } | نوع صورة WMF (Windows MetaFile) المتجهة |
| [FileExtension](../../groupdocs.viewer.drawing/image2dformat/fileextension) { get; } | امتداد الملف (بدون حرف النقطة الأولي) لنوع صورة معين بحروف صغيرة. بالنسبة للقيمة [`Undefined`](./undefined) تُعيد سلسلة 'undefined'. |
| [IsVector](../../groupdocs.viewer.drawing/image2dformat/isvector) { get; } | يشير إلى ما إذا كان هذا التنسيق المحدد متجهًا (`true`) أو نقطيًا (`false`) |
| [MimeCode](../../groupdocs.viewer.drawing/image2dformat/mimecode) { get; } | رمز MIME لنوع صورة معين كسلسلة. بالنسبة للنوع غير المحدد يُرجع سلسلة 'unsefined'. |
| [Name](../../groupdocs.viewer.drawing/image2dformat/name) { get; } | يرجع اسمًا رسميًا لهذا تنسيق الصورة. لا يُرجع NULL أبدًا. إذا لم يكن الكائن تالفًا، لا يرمي استثناءً أبدًا. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| static [ParseFromFilenameWithExtension](../../groupdocs.viewer.drawing/image2dformat/parsefromfilenamewithextension)(string) | يرجع قيمة ImageFormat، والتي تعادل امتداد اسم الملف، المستخرج من اسم الملف المحدد |
| static [ParseFromMime](../../groupdocs.viewer.drawing/image2dformat/parsefrommime)(string) | يرجع قيمة [`Image2DFormat`](../image2dformat)، والتي تعادل رمز MIME المحدد |
| [Equals](../../groupdocs.viewer.drawing/image2dformat/equals#equals)(Image2DFormat) | يحدد ما إذا كان هذا الكائن مساويًا للكائن المحدد "[`Image2DFormat`](../image2dformat)" |
| override [Equals](../../groupdocs.viewer.drawing/image2dformat/equals#equals_1)(object) | يحدد ما إذا كان هذا الكائن مساويًا للكائن غير المحول المحدد، والذي من المفترض أنه كائن "[`Image2DFormat`](../image2dformat)" آخر |
| override [GetHashCode](../../groupdocs.viewer.drawing/image2dformat/gethashcode)() | يرجع رمز تجزئة (hash-code)، وهو رقم ثابت لهذا الكائن المحدد |
| override [ToString](../../groupdocs.viewer.drawing/image2dformat/tostring)() | يرجع خاصية [`Name`](./name) |
| [operator ==](../../groupdocs.viewer.drawing/image2dformat/op_equality) | يحدد ما إذا كان كائنان محددان من نوع [`Image2DFormat`](../image2dformat) متساويين |
| [operator !=](../../groupdocs.viewer.drawing/image2dformat/op_inequality) | يحدد ما إذا كان كائنان محددان من نوع [`Image2DFormat`](../image2dformat) غير متساويين |

### انظر أيضًا

* namespace [GroupDocs.Viewer.Drawing](../../groupdocs.viewer.drawing)
* assembly [GroupDocs.Viewer](../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.Viewer.dll -->
