---
title: "ForExternalResources"
second_title: "مرجع API الخاص بـ GroupDocs.Viewer لـ .NET"
description: "يُنشئ مثيلاً من الفئة HtmlViewOptionsgroupdocs.viewer.options/htmlviewoptions للتجسيد إلى HTML مع الموارد الخارجية."
type: docs
weight: 20
url: /ar/net/groupdocs.viewer.options/htmlviewoptions/forexternalresources/
---

## ForExternalResources(CreatePageStream, CreateResourceStream, CreateResourceUrl) {#forexternalresources_1}

يُنشئ مثيلاً من الفئة [`HtmlViewOptions`](../../htmlviewoptions) للتجسيد إلى HTML مع الموارد الخارجية.

```csharp
public static HtmlViewOptions ForExternalResources(CreatePageStream createPageStream, 
    CreateResourceStream createResourceStream, CreateResourceUrl createResourceUrl)
```

| Parameter | النوع | الوصف |
| --- | --- | --- |
| createPageStream | CreatePageStream | الطريقة التي تُنشئ الدفق المستخدم لكتابة بيانات صفحة الإخراج. |
| createResourceStream | CreateResourceStream | الطريقة التي تُفرج عن الدفق الذي أنشأته طريقة *createPageStream*. |
| createResourceUrl | CreateResourceUrl | الطريقة التي تنشئ عنوان URL لمورد HTML. |

### قيمة الإرجاع

كائن جديد من الفئة [`HtmlViewOptions`](../../htmlviewoptions) للتصيير إلى HTML مع موارد خارجية.

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | يتم إلقاؤه عندما تكون *createPageStream* ذات قيمة null. |
| ArgumentNullException | يتم إلقاؤه عندما تكون *createResourceStream* ذات قيمة null. |
| ArgumentNullException | يتم إلقاؤه عندما تكون *createResourceUrl* ذات قيمة null. |

### ملاحظات

للحصول على مثال الشيفرة، راجع [التوثيق](https://docs.groupdocs.com/viewer/net/rendering-to-html/#rendering-to-html-with-external-resources).

### انظر أيضًا

* delegate [CreatePageStream](../../../groupdocs.viewer.interfaces/createpagestream)
* delegate [CreateResourceStream](../../../groupdocs.viewer.interfaces/createresourcestream)
* delegate [CreateResourceUrl](../../../groupdocs.viewer.interfaces/createresourceurl)
* class [HtmlViewOptions](../../htmlviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

---

## ForExternalResources(CreatePageStream, CreateResourceStream, CreateResourceUrl, ReleasePageStream, ReleaseResourceStream) {#forexternalresources_2}

يُنشئ مثيلاً من الفئة [`HtmlViewOptions`](../../htmlviewoptions) للتجسيد إلى HTML مع الموارد الخارجية.

```csharp
public static HtmlViewOptions ForExternalResources(CreatePageStream createPageStream, 
    CreateResourceStream createResourceStream, CreateResourceUrl createResourceUrl, 
    ReleasePageStream releasePageStream, ReleaseResourceStream releaseResourceStream)
```

| Parameter | النوع | الوصف |
| --- | --- | --- |
| createPageStream | CreatePageStream | الطريقة التي تُنشئ الدفق المستخدم لكتابة بيانات صفحة الإخراج. |
| createResourceStream | CreateResourceStream | الطريقة التي تنشئ الدفق المستخدم لكتابة بيانات مورد HTML الناتج. |
| createResourceUrl | CreateResourceUrl | الطريقة التي تنشئ عنوان URL لمورد HTML. |
| releasePageStream | ReleasePageStream | الطريقة التي تُفرج عن الدفق الذي تم إنشاؤه بواسطة الطريقة المخصصة للموكِّل الذي تم تمريره إلى معامل *createPageStream*. |
| releaseResourceStream | ReleaseResourceStream | الطريقة التي تُفرج عن الدفق الذي تم إنشاؤه بواسطة الطريقة المخصصة للموكِّل الذي تم تمريره إلى معامل *createResourceStream*. |

### قيمة الإرجاع

كائن جديد من الفئة [`HtmlViewOptions`](../../htmlviewoptions) للتصيير إلى HTML مع موارد خارجية.

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | يتم إلقاؤه عندما تكون *createPageStream* ذات قيمة null. |
| ArgumentNullException | يتم إلقاؤه عندما تكون *createResourceStream* ذات قيمة null. |
| ArgumentNullException | يتم إلقاؤه عندما تكون *createResourceUrl* ذات قيمة null. |
| ArgumentNullException | يتم إلقاؤه عندما تكون *releasePageStream* ذات قيمة null. |
| ArgumentNullException | يتم إلقاؤه عندما تكون *releaseResourceStream* ذات قيمة null. |

### ملاحظات

للحصول على مثال الشيفرة، راجع [التوثيق](https://docs.groupdocs.com/viewer/net/rendering-to-html/#rendering-to-html-with-external-resources).

### انظر أيضًا

* delegate [CreatePageStream](../../../groupdocs.viewer.interfaces/createpagestream)
* delegate [CreateResourceStream](../../../groupdocs.viewer.interfaces/createresourcestream)
* delegate [CreateResourceUrl](../../../groupdocs.viewer.interfaces/createresourceurl)
* delegate [ReleasePageStream](../../../groupdocs.viewer.interfaces/releasepagestream)
* delegate [ReleaseResourceStream](../../../groupdocs.viewer.interfaces/releaseresourcestream)
* class [HtmlViewOptions](../../htmlviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

---

## ForExternalResources(IPageStreamFactory, IResourceStreamFactory) {#forexternalresources_3}

يُنشئ مثيلاً من الفئة [`HtmlViewOptions`](../../htmlviewoptions) للتجسيد إلى HTML مع الموارد الخارجية.

```csharp
public static HtmlViewOptions ForExternalResources(IPageStreamFactory pageStreamFactory, 
    IResourceStreamFactory resourceStreamFactory)
```

| Parameter | النوع | الوصف |
| --- | --- | --- |
| pageStreamFactory | IPageStreamFactory | المصنع الذي يطبق طرق إنشاء وإصدار دفق صفحة الإخراج. |
| resourceStreamFactory | IResourceStreamFactory | المصنع الذي يطبق الطرق المطلوبة لإنشاء عنوان URL للموارد، وإنشاء وإصدار دفق مورد HTML الناتج. |

### قيمة الإرجاع

كائن جديد من الفئة [`HtmlViewOptions`](../../htmlviewoptions) للتصيير إلى HTML مع موارد خارجية.

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | يتم إلقاؤه عندما تكون *pageStreamFactory* ذات قيمة null. |
| ArgumentNullException | يتم إلقاؤه عندما تكون *resourceStreamFactory* ذات قيمة null. |

### ملاحظات

للحصول على مثال الشيفرة، راجع [التوثيق](https://docs.groupdocs.com/viewer/net/rendering-to-html/#rendering-to-html-with-external-resources).

### انظر أيضًا

* interface [IPageStreamFactory](../../../groupdocs.viewer.interfaces/ipagestreamfactory)
* interface [IResourceStreamFactory](../../../groupdocs.viewer.interfaces/iresourcestreamfactory)
* class [HtmlViewOptions](../../htmlviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

---

## ForExternalResources() {#forexternalresources}

يُهيئ مثيلًا من الفئة [`HtmlViewOptions`](../../htmlviewoptions).

```csharp
public static HtmlViewOptions ForExternalResources()
```

### ملاحظات

يقوم هذا المُنشئ بتهيئة مثيل من الفئة [`HtmlViewOptions`](../../htmlviewoptions).

* with "p_{0}.html" as file path format for the output HTML files
* with "p_{0}_{1}" as file path format for the output HTML-resource files
* with "p_{0}_{1}" as URL format for HTML-resources

ستوضع ملفات الإخراج في دليل العمل الحالي للتطبيق.

للحصول على مثال الشيفرة، راجع [التوثيق](https://docs.groupdocs.com/viewer/net/rendering-to-html/#rendering-to-html-with-external-resources).

### انظر أيضًا

* class [HtmlViewOptions](../../htmlviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

---

## ForExternalResources(string, string, string) {#forexternalresources_4}

يُهيئ مثيلًا من الفئة [`HtmlViewOptions`](../../htmlviewoptions).

```csharp
public static HtmlViewOptions ForExternalResources(string filePathFormat, 
    string resourceFilePathFormat, string resourceUrlFormat)
```

| Parameter | النوع | الوصف |
| --- | --- | --- |
| filePathFormat | String | تنسيق مسار الملف، مثال: 'page_{0}.html'. |
| resourceFilePathFormat | String | تنسيق مسار ملف المورد على سبيل المثال 'page_{0}/resource_{1}'. |
| resourceUrlFormat | String | تنسيق عنوان URL للمورد على سبيل المثال 'page_{0}/resource_{1}'. |

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentException | يُرمى عندما يكون *filePathFormat* فارغًا أو null. |
| ArgumentException | يُرمى عندما يكون *resourceFilePathFormat* فارغًا أو null. |
| ArgumentException | يُرمى عندما يكون *resourceUrlFormat* فارغًا أو null. |

### ملاحظات

للحصول على مثال الشيفرة، راجع [التوثيق](https://docs.groupdocs.com/viewer/net/rendering-to-html/#rendering-to-html-with-external-resources).

### انظر أيضًا

* class [HtmlViewOptions](../../htmlviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.Viewer.dll -->
