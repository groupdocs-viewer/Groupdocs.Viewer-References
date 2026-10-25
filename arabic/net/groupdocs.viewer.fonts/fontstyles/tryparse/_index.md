---
title: "TryParse"
second_title: "مرجع API الخاص بـ GroupDocs.Viewer لـ .NET"
description: "يحاول تحليل السلسلة الخام المحددة كاسم لنمط الخط"
type: docs
weight: 120
url: /ar/net/groupdocs.viewer.fonts/fontstyles/tryparse/
---

## FontStyles.TryParse method

يحاول تحليل السلسلة الخام المحددة كاسم لنمط الخط

```csharp
public static bool TryParse(string style, out FontStyles parsed)
```

| Parameter | النوع | الوصف |
| --- | --- | --- |
| نمط | String | سلسلة يجب تحليلها كنمط خط |
| parsed | FontStyles& | نمط الخط المحلل عند النجاح أو [`Regular`](../regular) عند الفشل |

### قيمة الإرجاع

`true` إذا تم تحليل السلسلة بنجاح كنمط خط صحيح؛ `false` غير ذلك

### انظر أيضًا

* struct [FontStyles](../../fontstyles)
* namespace [GroupDocs.Viewer.Fonts](../../../groupdocs.viewer.fonts)
* assembly [GroupDocs.Viewer](../../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.Viewer.dll -->
