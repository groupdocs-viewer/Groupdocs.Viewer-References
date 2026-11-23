---
title: "TextOverflowMode"
second_title: "مرجع API الخاص بـ GroupDocs.Viewer لـ .NET"
description: "يضبط وضع تجاوز النص عند عرض مستندات الجداول إلى HTML."
type: docs
weight: 550
url: /ar/net/groupdocs.viewer.options/textoverflowmode/
---

## TextOverflowMode enumeration

يضبط وضع تجاوز النص عند عرض مستندات الجداول إلى HTML.

```csharp
public enum TextOverflowMode
```

### القيم

| الاسم | القيمة | الوصف |
| --- | --- | --- |
| Overlay | `0` | تراكب الخلايا التالية حتى وإن لم تكن فارغة. |
| OverlayIfNextIsEmpty | `1` | تراكب الخلايا التالية فقط إذا كانت فارغة. القيمة الافتراضية. |
| AutoFitColumn | `2` | توسيع الأعمدة لتناسب النص. |
| HideText | `3` | إخفاء النص المتجاوز. |

### ملاحظات

للتفاصيل، راجع [التوثيق](https://docs.groupdocs.com/viewer/net/specify-rendering-options/#control-cell-text-overflow).

### انظر أيضًا

* namespace [GroupDocs.Viewer.Options](../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.Viewer.dll -->
