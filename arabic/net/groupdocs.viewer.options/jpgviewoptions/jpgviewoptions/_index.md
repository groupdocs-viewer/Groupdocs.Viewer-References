---
title: "خيارات عرض JPG"
second_title: "مرجع API الخاص بـ GroupDocs.Viewer لـ .NET"
description: "يُنشئ مثيلاً لفئة JpgViewOptionsgroupdocs.viewer.options/jpgviewoptions."
type: docs
weight: 10
url: /ar/net/groupdocs.viewer.options/jpgviewoptions/jpgviewoptions/
---

## JpgViewOptions(CreatePageStream) {#constructor_1}

ينشئ مثيلاً لفئة [`JpgViewOptions`](../../jpgviewoptions).

```csharp
public JpgViewOptions(CreatePageStream createPageStream)
```

| Parameter | النوع | الوصف |
| --- | --- | --- |
| createPageStream | CreatePageStream | الطريقة التي تنشئ تدفقًا يُستخدم لكتابة بيانات صفحة الإخراج. |

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | يتم إلقاؤه عندما تكون *createPageStream* ذات قيمة null. |

### ملاحظات

للحصول على مثال الشيفرة، راجع [التوثيق](https://docs.groupdocs.com/viewer/net/rendering-to-png-or-jpeg/#rendering-to-jpeg).

### انظر أيضًا

* delegate [CreatePageStream](../../../groupdocs.viewer.interfaces/createpagestream)
* class [JpgViewOptions](../../jpgviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

---

## JpgViewOptions(CreatePageStream, ReleasePageStream) {#constructor_2}

ينشئ مثيلاً لفئة [`JpgViewOptions`](../../jpgviewoptions).

```csharp
public JpgViewOptions(CreatePageStream createPageStream, ReleasePageStream releasePageStream)
```

| Parameter | النوع | الوصف |
| --- | --- | --- |
| createPageStream | CreatePageStream | الطريقة التي تنشئ تدفقًا يُستخدم لكتابة بيانات صفحة الإخراج. |
| releasePageStream | ReleasePageStream | الطريقة التي تُطلق تدفقًا تم إنشاؤه بواسطة طريقة مخصصة للمنفذ الذي تم تمريره إلى معلمة *createPageStream*. |

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | يتم إلقاؤه عندما تكون *createPageStream* ذات قيمة null. |
| ArgumentNullException | يتم إلقاؤه عندما تكون *releasePageStream* ذات قيمة null. |

### ملاحظات

للحصول على مثال الشيفرة، راجع [التوثيق](https://docs.groupdocs.com/viewer/net/rendering-to-png-or-jpeg/#rendering-to-jpeg).

### انظر أيضًا

* delegate [CreatePageStream](../../../groupdocs.viewer.interfaces/createpagestream)
* delegate [ReleasePageStream](../../../groupdocs.viewer.interfaces/releasepagestream)
* class [JpgViewOptions](../../jpgviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

---

## JpgViewOptions(IPageStreamFactory) {#constructor_3}

ينشئ مثيلاً لفئة [`JpgViewOptions`](../../jpgviewoptions).

```csharp
public JpgViewOptions(IPageStreamFactory pageStreamFactory)
```

| Parameter | النوع | الوصف |
| --- | --- | --- |
| pageStreamFactory | IPageStreamFactory | المصنع الذي يطبق طرق إنشاء وإصدار دفق صفحة الإخراج. |

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | يتم إلقاؤه عندما تكون *pageStreamFactory* ذات قيمة null. |

### ملاحظات

للحصول على مثال الشيفرة، راجع [التوثيق](https://docs.groupdocs.com/viewer/net/rendering-to-png-or-jpeg/#rendering-to-jpeg).

### انظر أيضًا

* interface [IPageStreamFactory](../../../groupdocs.viewer.interfaces/ipagestreamfactory)
* class [JpgViewOptions](../../jpgviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

---

## JpgViewOptions() {#constructor}

ينشئ مثيلاً لفئة [`JpgViewOptions`](../../jpgviewoptions).

```csharp
public JpgViewOptions()
```

### ملاحظات

يقوم هذا المُنشئ بإنشاء مثيل لفئة [`JpgViewOptions`](../../jpgviewoptions) مع \"p_{0}.jpg\" كتنسيق مسار الملف للملفات الناتجة. تُوضع الملفات الناتجة في دليل العمل الحالي للتطبيق.

للحصول على مثال الشيفرة، راجع [التوثيق](https://docs.groupdocs.com/viewer/net/rendering-to-png-or-jpeg/#rendering-to-jpeg).

### انظر أيضًا

* class [JpgViewOptions](../../jpgviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

---

## JpgViewOptions(string) {#constructor_4}

ينشئ مثيلاً لفئة [`JpgViewOptions`](../../jpgviewoptions).

```csharp
public JpgViewOptions(string filePathFormat)
```

| Parameter | النوع | الوصف |
| --- | --- | --- |
| filePathFormat | String | تنسيق مسار الملف مثال: 'page_{0}.jpg'. |

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentException | يُرمى عندما يكون *filePathFormat* فارغًا أو null. |

### ملاحظات

للحصول على مثال الشيفرة، راجع [التوثيق](https://docs.groupdocs.com/viewer/net/rendering-to-png-or-jpeg/#rendering-to-jpeg).

### انظر أيضًا

* class [JpgViewOptions](../../jpgviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.Viewer.dll -->
