---
title: "ForEmbeddedResources"
second_title: "مرجع API الخاص بـ GroupDocs.Viewer لـ .NET"
description: "ينشئ مثيلًا من الفئة HtmlViewOptionsgroupdocs.viewer.options/htmlviewoptions للتصيير إلى HTML مع الموارد المضمنة."
type: docs
weight: 10
url: /ar/net/groupdocs.viewer.options/htmlviewoptions/forembeddedresources/
---

## ForEmbeddedResources(CreatePageStream) {#forembeddedresources_1}

ينشئ مثيلًا من الفئة [`HtmlViewOptions`](../../htmlviewoptions) للتصيير إلى HTML مع الموارد المضمنة.

```csharp
public static HtmlViewOptions ForEmbeddedResources(CreatePageStream createPageStream)
```

| Parameter | النوع | الوصف |
| --- | --- | --- |
| createPageStream | CreatePageStream | الطريقة التي تُنشئ الدفق المستخدم لكتابة بيانات صفحة الإخراج. |

### قيمة الإرجاع

مثيل جديد من الفئة [`HtmlViewOptions`](../../htmlviewoptions) للتصيير إلى HTML مع الموارد المضمنة.

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | يتم إلقاؤه عندما تكون *createPageStream* ذات قيمة null. |

### ملاحظات

لمثال الشيفرة، راجع [التوثيق](https://docs.groupdocs.com/viewer/net/rendering-to-html/#rendering-to-html-with-embedded-resources).

### انظر أيضًا

* delegate [CreatePageStream](../../../groupdocs.viewer.interfaces/createpagestream)
* class [HtmlViewOptions](../../htmlviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

---

## ForEmbeddedResources(CreatePageStream, ReleasePageStream) {#forembeddedresources_2}

ينشئ مثيلًا من الفئة [`HtmlViewOptions`](../../htmlviewoptions) للتصيير إلى HTML مع الموارد المضمنة.

```csharp
public static HtmlViewOptions ForEmbeddedResources(CreatePageStream createPageStream, 
    ReleasePageStream releasePageStream)
```

| Parameter | النوع | الوصف |
| --- | --- | --- |
| createPageStream | CreatePageStream | الطريقة التي تُنشئ الدفق المستخدم لكتابة بيانات صفحة الإخراج. |
| releasePageStream | ReleasePageStream | الطريقة التي تُفرج عن الدفق الذي تم إنشاؤه بواسطة الطريقة المخصصة للموكِّل الذي تم تمريره إلى معامل *createPageStream*. |

### قيمة الإرجاع

مثيل جديد من الفئة [`HtmlViewOptions`](../../htmlviewoptions) للتصيير إلى HTML مع الموارد المضمنة.

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | يتم إلقاؤه عندما تكون *createPageStream* ذات قيمة null. |
| ArgumentNullException | يتم إلقاؤه عندما تكون *releasePageStream* ذات قيمة null. |

### ملاحظات

لمثال الشيفرة، راجع [التوثيق](https://docs.groupdocs.com/viewer/net/rendering-to-html/#rendering-to-html-with-embedded-resources).

### انظر أيضًا

* delegate [CreatePageStream](../../../groupdocs.viewer.interfaces/createpagestream)
* delegate [ReleasePageStream](../../../groupdocs.viewer.interfaces/releasepagestream)
* class [HtmlViewOptions](../../htmlviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

---

## ForEmbeddedResources(IPageStreamFactory) {#forembeddedresources_3}

ينشئ مثيلًا من الفئة [`HtmlViewOptions`](../../htmlviewoptions) للتصيير إلى HTML مع الموارد المضمنة.

```csharp
public static HtmlViewOptions ForEmbeddedResources(IPageStreamFactory pageStreamFactory)
```

| Parameter | النوع | الوصف |
| --- | --- | --- |
| pageStreamFactory | IPageStreamFactory | المصنع الذي يطبق طرق إنشاء وإصدار دفق صفحة الإخراج. |

### قيمة الإرجاع

مثيل جديد من الفئة [`HtmlViewOptions`](../../htmlviewoptions) للتصيير إلى HTML مع الموارد المضمنة.

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | يتم إلقاؤه عندما تكون *pageStreamFactory* ذات قيمة null. |

### ملاحظات

لمثال الشيفرة، راجع [التوثيق](https://docs.groupdocs.com/viewer/net/rendering-to-html/#rendering-to-html-with-embedded-resources).

### انظر أيضًا

* interface [IPageStreamFactory](../../../groupdocs.viewer.interfaces/ipagestreamfactory)
* class [HtmlViewOptions](../../htmlviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

---

## ForEmbeddedResources() {#forembeddedresources}

يُهيئ مثيلًا من الفئة [`HtmlViewOptions`](../../htmlviewoptions).

```csharp
public static HtmlViewOptions ForEmbeddedResources()
```

### ملاحظات

لمثال الشيفرة، راجع [التوثيق](https://docs.groupdocs.com/viewer/net/rendering-to-html/#rendering-to-html-with-embedded-resources).

### انظر أيضًا

* class [HtmlViewOptions](../../htmlviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

---

## ForEmbeddedResources(string) {#forembeddedresources_4}

يُهيئ مثيلًا من الفئة [`HtmlViewOptions`](../../htmlviewoptions).

```csharp
public static HtmlViewOptions ForEmbeddedResources(string filePathFormat)
```

| Parameter | النوع | الوصف |
| --- | --- | --- |
| filePathFormat | String | تنسيق مسار الملف، مثال: 'page_{0}.html'. |

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentException | يُرمى عندما يكون *filePathFormat* فارغًا أو null. |

### ملاحظات

لمثال الشيفرة، راجع [التوثيق](https://docs.groupdocs.com/viewer/net/rendering-to-html/#rendering-to-html-with-embedded-resources).

### انظر أيضًا

* class [HtmlViewOptions](../../htmlviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.Viewer.dll -->
