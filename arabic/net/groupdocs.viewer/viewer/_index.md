---
title: "عارض"
second_title: "مرجع API الخاص بـ GroupDocs.Viewer لـ .NET"
description: "يمثل الفئة الرئيسية التي تتحكم في عملية تصيير المستند."
type: docs
weight: 50
url: /ar/net/groupdocs.viewer/viewer/
---

## Viewer class

يمثل الفئة الرئيسية التي تتحكم في عملية تصيير المستند.

```csharp
public class Viewer : IDisposable
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [Viewer](viewer#constructor)(Func&lt;Stream&gt;) | يُهيئ نسخة جديدة من الفئة [`Viewer`](../viewer). |
| [Viewer](viewer#constructor_4)(Stream) | يُهيئ نسخة جديدة من الفئة [`Viewer`](../viewer). |
| [Viewer](viewer#constructor_12)(string) | يُهيئ نسخة جديدة من الفئة [`Viewer`](../viewer). |
| [Viewer](viewer#constructor_2)(Func&lt;Stream&gt;, Func&lt;LoadOptions&gt;) | يُهيئ نسخة جديدة من الفئة [`Viewer`](../viewer). |
| [Viewer](viewer#constructor_1)(Func&lt;Stream&gt;, ViewerSettings) | يُهيئ نسخة جديدة من الفئة [`Viewer`](../viewer). |
| [Viewer](viewer#constructor_5)(Stream, bool) | يُهيئ نسخة جديدة من الفئة [`Viewer`](../viewer). |
| [Viewer](viewer#constructor_6)(Stream, LoadOptions) | يُهيئ نسخة جديدة من الفئة [`Viewer`](../viewer). |
| [Viewer](viewer#constructor_10)(Stream, ViewerSettings) | يُهيئ نسخة جديدة من الفئة [`Viewer`](../viewer). |
| [Viewer](viewer#constructor_13)(string, LoadOptions) | يُهيئ نسخة جديدة من الفئة [`Viewer`](../viewer). |
| [Viewer](viewer#constructor_15)(string, ViewerSettings) | يُهيئ نسخة جديدة من الفئة [`Viewer`](../viewer). |
| [Viewer](viewer#constructor_3)(Func&lt;Stream&gt;, Func&lt;LoadOptions&gt;, ViewerSettings) | يُهيئ نسخة جديدة من الفئة [`Viewer`](../viewer). |
| [Viewer](viewer#constructor_7)(Stream, LoadOptions, bool) | يُهيئ نسخة جديدة من الفئة [`Viewer`](../viewer). |
| [Viewer](viewer#constructor_8)(Stream, LoadOptions, ViewerSettings) | يُهيئ نسخة جديدة من الفئة [`Viewer`](../viewer). |
| [Viewer](viewer#constructor_11)(Stream, ViewerSettings, bool) | يُهيئ نسخة جديدة من الفئة [`Viewer`](../viewer). |
| [Viewer](viewer#constructor_14)(string, LoadOptions, ViewerSettings) | يُهيئ نسخة جديدة من الفئة [`Viewer`](../viewer). |
| [Viewer](viewer#constructor_9)(Stream, LoadOptions, ViewerSettings, bool) | يُهيئ نسخة جديدة من الفئة [`Viewer`](../viewer). |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [Dispose](../../groupdocs.viewer/viewer/dispose)() | يُطلق تدفق الملف والموارد الداخلية المُدارة. |
| [GetAllFonts](../../groupdocs.viewer/viewer/getallfonts)() | يرجع جميع الخطوط المستخدمة في المستندات المحملة، بما في ذلك تلك المدمجة داخل المستند نفسه وتلك الخطوط النظامية المثبتة في نظام التشغيل والمستخدمة في المستند. |
| [GetAttachments](../../groupdocs.viewer/viewer/getattachments#getattachments)() | يرجع المرفقات الموجودة في المستند. |
| [GetAttachments](../../groupdocs.viewer/viewer/getattachments#getattachments_1)(CancellationToken) | يرجع المرفقات الموجودة في المستند. |
| [GetFileInfo](../../groupdocs.viewer/viewer/getfileinfo)() | يرجع معلومات حول الملف مثل نوع الملف والعلامة التي تشير إلى ما إذا كان الملف مشفراً. |
| [GetViewInfo](../../groupdocs.viewer/viewer/getviewinfo#getviewinfo)(ViewInfoOptions) | يرجع معلومات حول العرض ومعلومات خاصة بالمستند. |
| [GetViewInfo](../../groupdocs.viewer/viewer/getviewinfo#getviewinfo_1)(ViewInfoOptions, CancellationToken) | يرجع معلومات حول العرض ومعلومات خاصة بالمستند. |
| [SaveAttachment](../../groupdocs.viewer/viewer/saveattachment#saveattachment)(Attachment, Stream) | يحفظ ملف المرفق إلى تدفق *الوجهة*. |
| [SaveAttachment](../../groupdocs.viewer/viewer/saveattachment#saveattachment_1)(Attachment, Stream, CancellationToken) | يحفظ ملف المرفق إلى تدفق *الوجهة*. |
| [Search](../../groupdocs.viewer/viewer/search)(SearchHighlightOptions) | ينفّذ بحثًا نصيًا وتظليله (إن وجد) في المستند المحمل وفقًا للخيارات المحملة. |
| [View](../../groupdocs.viewer/viewer/view#view)(ViewOptions) | ينشئ عرضًا لجميع صفحات المستند. |
| [View](../../groupdocs.viewer/viewer/view#view_2)(ViewOptions, CancellationToken) | ينشئ عرضًا لجميع صفحات المستند. |
| [View](../../groupdocs.viewer/viewer/view#view_1)(ViewOptions, params int[]) | ينشئ عرضًا لصفحات مستند محددة. |
| [View](../../groupdocs.viewer/viewer/view#view_3)(ViewOptions, CancellationToken, params int[]) | ينشئ عرضًا لصفحات مستند محددة. |

### انظر أيضًا

* namespace [GroupDocs.Viewer](../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.Viewer.dll -->
