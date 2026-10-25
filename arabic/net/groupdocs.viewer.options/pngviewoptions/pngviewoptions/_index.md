---
title: "PngViewOptions"
second_title: "مرجع API الخاص بـ GroupDocs.Viewer لـ .NET"
description: "ينشئ مثيلًا من الفئة PngViewOptionsgroupdocs.viewer.options/pngviewoptions."
type: docs
weight: 10
url: /ar/net/groupdocs.viewer.options/pngviewoptions/pngviewoptions/
---

## PngViewOptions(CreatePageStream) {#constructor_1}

ينشئ مثيلًا من الفئة [`PngViewOptions`](../../pngviewoptions).

```csharp
public PngViewOptions(CreatePageStream createPageStream)
```

| Parameter | النوع | الوصف |
| --- | --- | --- |
| createPageStream | CreatePageStream | الطريقة التي تنشئ تدفقًا يُستخدم لكتابة بيانات صفحة الإخراج. |

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | يتم إلقاؤه عندما تكون *createPageStream* ذات قيمة null. |

### ملاحظات

لمثال الشيفرة، راجع [التوثيق](https://docs.groupdocs.com/viewer/net/rendering-to-png-or-jpeg/#rendering-to-png).

### انظر أيضًا

* delegate [CreatePageStream](../../../groupdocs.viewer.interfaces/createpagestream)
* class [PngViewOptions](../../pngviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

---

## PngViewOptions(CreatePageStream, ReleasePageStream) {#constructor_2}

ينشئ مثيلًا من الفئة [`PngViewOptions`](../../pngviewoptions).

```csharp
public PngViewOptions(CreatePageStream createPageStream, ReleasePageStream releasePageStream)
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

لمثال الشيفرة، راجع [التوثيق](https://docs.groupdocs.com/viewer/net/rendering-to-png-or-jpeg/#rendering-to-png).

### انظر أيضًا

* delegate [CreatePageStream](../../../groupdocs.viewer.interfaces/createpagestream)
* delegate [ReleasePageStream](../../../groupdocs.viewer.interfaces/releasepagestream)
* class [PngViewOptions](../../pngviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

---

## PngViewOptions(IPageStreamFactory) {#constructor_3}

ينشئ مثيلًا من الفئة [`PngViewOptions`](../../pngviewoptions).

```csharp
public PngViewOptions(IPageStreamFactory pageStreamFactory)
```

| Parameter | النوع | الوصف |
| --- | --- | --- |
| pageStreamFactory | IPageStreamFactory | المصنع الذي يطبق طرق إنشاء وإصدار دفق صفحة الإخراج. |

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | يتم إلقاؤه عندما تكون *pageStreamFactory* ذات قيمة null. |

### ملاحظات

لمثال الشيفرة، راجع [التوثيق](https://docs.groupdocs.com/viewer/net/rendering-to-png-or-jpeg/#rendering-to-png).

### انظر أيضًا

* interface [IPageStreamFactory](../../../groupdocs.viewer.interfaces/ipagestreamfactory)
* class [PngViewOptions](../../pngviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

---

## PngViewOptions() {#constructor}

ينشئ مثيلًا من الفئة [`PngViewOptions`](../../pngviewoptions).

```csharp
public PngViewOptions()
```

### ملاحظات

يقوم هذا المُنشئ بإنشاء مثيل من الفئة [`PngViewOptions`](../../pngviewoptions) باستخدام "p_{0}.png" كتنسيق مسار ملف للملفات الناتجة. تُوضع الملفات الناتجة في دليل العمل الحالي للتطبيق.

لمثال الشيفرة، راجع [التوثيق](https://docs.groupdocs.com/viewer/net/rendering-to-png-or-jpeg/#rendering-to-png).

### انظر أيضًا

* class [PngViewOptions](../../pngviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

---

## PngViewOptions(string) {#constructor_4}

ينشئ مثيلًا من الفئة [`PngViewOptions`](../../pngviewoptions).

```csharp
public PngViewOptions(string filePathFormat)
```

| Parameter | النوع | الوصف |
| --- | --- | --- |
| filePathFormat | String | تنسيق مسار الملف على سبيل المثال 'page_{0}.png'. |

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentException | يُرمى عندما يكون *filePathFormat* فارغًا أو null. |

### ملاحظات

لمثال الشيفرة، راجع [التوثيق](https://docs.groupdocs.com/viewer/net/rendering-to-png-or-jpeg/#rendering-to-png).

### انظر أيضًا

* class [PngViewOptions](../../pngviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.Viewer.dll -->
