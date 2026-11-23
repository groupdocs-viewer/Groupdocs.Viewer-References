---
title: "عرض"
second_title: "مرجع API الخاص بـ GroupDocs.Viewer لـ .NET"
description: "ينشئ عرضًا لجميع صفحات المستند."
type: docs
weight: 90
url: /ar/net/groupdocs.viewer/viewer/view/
---

## View(ViewOptions) {#view}

ينشئ عرضًا لجميع صفحات المستند.

```csharp
public void View(ViewOptions options)
```

| Parameter | النوع | الوصف |
| --- | --- | --- |
| الخيارات | ViewOptions | خيارات العرض. |

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | يتم رميه عندما يكون *options* هو `null`. |
| [PasswordRequiredException](../../../groupdocs.viewer.exceptions/passwordrequiredexception) | يتم إلقاؤه عندما تكون كلمة المرور مطلوبة لفتح المستند. |
| [IncorrectPasswordException](../../../groupdocs.viewer.exceptions/incorrectpasswordexception) | يتم إلقاؤه عندما تكون كلمة المرور المحددة غير صحيحة. |
| [GroupDocsViewerException](../../../groupdocs.viewer.exceptions/groupdocsviewerexception) | يتم رميه عندما لا يمكن العثور على المرفق. |

### ملاحظات

**Learn more**

* More about different viewing options following this guide: [How to customize document viewing output using GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Viewing)

### انظر أيضًا

* class [ViewOptions](../../../groupdocs.viewer.options/viewoptions)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## View(ViewOptions, CancellationToken) {#view_2}

ينشئ عرضًا لجميع صفحات المستند.

```csharp
public void View(ViewOptions options, CancellationToken cancellationToken)
```

| Parameter | النوع | الوصف |
| --- | --- | --- |
| الخيارات | ViewOptions | خيارات العرض. |
| cancellationToken | CancellationToken | رمز الإلغاء لإرسال طلب لإلغاء عملية العرض الحالية. |

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | يتم رميه عندما يكون *options* هو `null`. |
| [PasswordRequiredException](../../../groupdocs.viewer.exceptions/passwordrequiredexception) | يتم إلقاؤه عندما تكون كلمة المرور مطلوبة لفتح المستند. |
| [IncorrectPasswordException](../../../groupdocs.viewer.exceptions/incorrectpasswordexception) | يتم إلقاؤه عندما تكون كلمة المرور المحددة غير صحيحة. |
| [GroupDocsViewerException](../../../groupdocs.viewer.exceptions/groupdocsviewerexception) | يتم رميه عندما لا يمكن العثور على المرفق. |

### ملاحظات

**Learn more**

* More about different viewing options following this guide: [How to customize document viewing output using GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Viewing)

### انظر أيضًا

* class [ViewOptions](../../../groupdocs.viewer.options/viewoptions)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## View(ViewOptions, params int[]) {#view_1}

ينشئ عرضًا لصفحات مستند محددة.

```csharp
public void View(ViewOptions options, params int[] pageNumbers)
```

| Parameter | النوع | الوصف |
| --- | --- | --- |
| الخيارات | ViewOptions | خيارات العرض. |
| pageNumbers | Int32[] | أرقام الصفحات للعرض. |

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | يتم رميه عندما يكون *options* هو `null`. |
| ArgumentNullException | يتم إلقاؤه عندما تكون *pageNumbers* null. |
| ArgumentException | يتم إلقاؤه عندما تكون *pageNumbers* فارغة. |
| [PasswordRequiredException](../../../groupdocs.viewer.exceptions/passwordrequiredexception) | يتم إلقاؤه عندما تكون كلمة المرور مطلوبة لفتح المستند. |
| [IncorrectPasswordException](../../../groupdocs.viewer.exceptions/incorrectpasswordexception) | يتم إلقاؤه عندما تكون كلمة المرور المحددة غير صحيحة. |
| [GroupDocsViewerException](../../../groupdocs.viewer.exceptions/groupdocsviewerexception) | يتم رميه عندما لا يمكن العثور على المرفق. |

### ملاحظات

**Learn more**

* More about different viewing options following this guide: [How to customize document viewing output using GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Viewing)

### انظر أيضًا

* class [ViewOptions](../../../groupdocs.viewer.options/viewoptions)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## View(ViewOptions, CancellationToken, params int[]) {#view_3}

ينشئ عرضًا لصفحات مستند محددة.

```csharp
public void View(ViewOptions options, CancellationToken cancellationToken, params int[] pageNumbers)
```

| Parameter | النوع | الوصف |
| --- | --- | --- |
| الخيارات | ViewOptions | خيارات العرض. |
| pageNumbers | CancellationToken | أرقام الصفحات للعرض. |
| cancellationToken | Int32[] | رمز الإلغاء لإلغاء المعالجة. |

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | يتم رميه عندما يكون *options* هو `null`. |
| ArgumentNullException | يتم إلقاؤه عندما تكون *pageNumbers* null. |
| ArgumentException | يتم إلقاؤه عندما تكون *pageNumbers* فارغة. |
| [PasswordRequiredException](../../../groupdocs.viewer.exceptions/passwordrequiredexception) | يتم إلقاؤه عندما تكون كلمة المرور مطلوبة لفتح المستند. |
| [IncorrectPasswordException](../../../groupdocs.viewer.exceptions/incorrectpasswordexception) | يتم إلقاؤه عندما تكون كلمة المرور المحددة غير صحيحة. |
| [GroupDocsViewerException](../../../groupdocs.viewer.exceptions/groupdocsviewerexception) | يتم رميه عندما لا يمكن العثور على المرفق. |

### ملاحظات

**Learn more**

* More about different viewing options following this guide: [How to customize document viewing output using GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Viewing)

### انظر أيضًا

* class [ViewOptions](../../../groupdocs.viewer.options/viewoptions)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.Viewer.dll -->
