---
title: "GetViewInfo"
second_title: "مرجع API الخاص بـ GroupDocs.Viewer لـ .NET"
description: "يرجع معلومات حول العرض ومعلومات خاصة بالمستند."
type: docs
weight: 60
url: /ar/net/groupdocs.viewer/viewer/getviewinfo/
---

## GetViewInfo(ViewInfoOptions) {#getviewinfo}

يرجع معلومات حول العرض ومعلومات خاصة بالمستند.

```csharp
public ViewInfo GetViewInfo(ViewInfoOptions options)
```

| Parameter | النوع | الوصف |
| --- | --- | --- |
| الخيارات | ViewInfoOptions | خيارات معلومات العرض. |

### قيمة الإرجاع

معلومات حول العرض ومعلومات خاصة بالمستند.

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | يتم رميه عندما يكون *options* هو `null`. |
| [PasswordRequiredException](../../../groupdocs.viewer.exceptions/passwordrequiredexception) | يتم إلقاؤه عندما تكون كلمة المرور مطلوبة لفتح المستند. |
| [IncorrectPasswordException](../../../groupdocs.viewer.exceptions/incorrectpasswordexception) | يتم إلقاؤه عندما تكون كلمة المرور المحددة غير صحيحة. |

### ملاحظات

**Learn more**

* Learn more about document - file type, pages count and other format specific properties: [How to get file information using GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Get+file+information)

### انظر أيضًا

* class [ViewInfo](../../../groupdocs.viewer.results/viewinfo)
* class [ViewInfoOptions](../../../groupdocs.viewer.options/viewinfooptions)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## GetViewInfo(ViewInfoOptions, CancellationToken) {#getviewinfo_1}

يرجع معلومات حول العرض ومعلومات خاصة بالمستند.

```csharp
public ViewInfo GetViewInfo(ViewInfoOptions options, CancellationToken cancellationToken)
```

| Parameter | النوع | الوصف |
| --- | --- | --- |
| الخيارات | ViewInfoOptions | خيارات معلومات العرض. |
| cancellationToken | CancellationToken | رمز الإلغاء. |

### قيمة الإرجاع

معلومات حول العرض ومعلومات خاصة بالمستند.

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | يتم رميه عندما يكون *options* هو `null`. |
| [PasswordRequiredException](../../../groupdocs.viewer.exceptions/passwordrequiredexception) | يتم إلقاؤه عندما تكون كلمة المرور مطلوبة لفتح المستند. |
| [IncorrectPasswordException](../../../groupdocs.viewer.exceptions/incorrectpasswordexception) | يتم إلقاؤه عندما تكون كلمة المرور المحددة غير صحيحة. |

### ملاحظات

**Learn more**

* Learn more about document - file type, pages count and other format specific properties: [How to get file information using GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Get+file+information)

### انظر أيضًا

* class [ViewInfo](../../../groupdocs.viewer.results/viewinfo)
* class [ViewInfoOptions](../../../groupdocs.viewer.options/viewinfooptions)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.Viewer.dll -->
