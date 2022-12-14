---
title: ForEmbeddedResources
second_title: GroupDocs.Viewer لمرجع .NET API
description: تهيئة مثيل جديد لـHtmlViewOptionsgroupdocs.viewer.options/htmlviewoptions فئة للعرض في HTML مع الموارد المضمنة .
type: docs
weight: 10
url: /ar/net/groupdocs.viewer.options/htmlviewoptions/forembeddedresources/
---
## ForEmbeddedResources(CreatePageStream) {#forembeddedresources_1}

تهيئة مثيل جديد لـ[`HtmlViewOptions`](../../htmlviewoptions) فئة للعرض في HTML مع الموارد المضمنة .

```csharp
public static HtmlViewOptions ForEmbeddedResources(CreatePageStream createPageStream)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| createPageStream | CreatePageStream | طريقة إنشاء الدفق المستخدمة لكتابة بيانات صفحة الإخراج. |

### قيمة الإرجاع

مثيل جديد من[`HtmlViewOptions`](../../htmlviewoptions) فئة للعرض في HTML مع الموارد المضمنة.

### استثناءات

| استثناء | حالة |
| --- | --- |
| ArgumentNullException | عندما ألقيت*createPageStream* باطل. |

### أنظر أيضا

* delegate [CreatePageStream](../../../groupdocs.viewer.interfaces/createpagestream)
* class [HtmlViewOptions](../../htmlviewoptions)
* مساحة الاسم [GroupDocs.Viewer.Options](../../htmlviewoptions)
* المجسم [GroupDocs.Viewer](../../../)

---

## ForEmbeddedResources(CreatePageStream, ReleasePageStream) {#forembeddedresources_2}

تهيئة مثيل جديد لـ[`HtmlViewOptions`](../../htmlviewoptions) فئة للعرض في HTML مع الموارد المضمنة .

```csharp
public static HtmlViewOptions ForEmbeddedResources(CreatePageStream createPageStream, 
    ReleasePageStream releasePageStream)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| createPageStream | CreatePageStream | طريقة إنشاء الدفق المستخدمة لكتابة بيانات صفحة الإخراج. |
| releasePageStream | ReleasePageStream | الطريقة التي تطلق الدفق الذي تم إنشاؤه بواسطة الطريقة المخصصة للمفوض الذي تم تمريره إليه*createPageStream* معامل. |

### قيمة الإرجاع

مثيل جديد من[`HtmlViewOptions`](../../htmlviewoptions) فئة للعرض في HTML مع الموارد المضمنة.

### استثناءات

| استثناء | حالة |
| --- | --- |
| ArgumentNullException | عندما ألقيت*createPageStream* باطل. |
| ArgumentNullException | عندما ألقيت*releasePageStream* باطل. |

### أنظر أيضا

* delegate [CreatePageStream](../../../groupdocs.viewer.interfaces/createpagestream)
* delegate [ReleasePageStream](../../../groupdocs.viewer.interfaces/releasepagestream)
* class [HtmlViewOptions](../../htmlviewoptions)
* مساحة الاسم [GroupDocs.Viewer.Options](../../htmlviewoptions)
* المجسم [GroupDocs.Viewer](../../../)

---

## ForEmbeddedResources(IPageStreamFactory) {#forembeddedresources_3}

تهيئة مثيل جديد لـ[`HtmlViewOptions`](../../htmlviewoptions) فئة للعرض في HTML مع الموارد المضمنة .

```csharp
public static HtmlViewOptions ForEmbeddedResources(IPageStreamFactory pageStreamFactory)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| pageStreamFactory | IPageStreamFactory | المصنع الذي ينفذ طرقًا لإنشاء دفق صفحة الإخراج وتحريره. |

### قيمة الإرجاع

مثيل جديد من[`HtmlViewOptions`](../../htmlviewoptions) فئة للعرض في HTML مع الموارد المضمنة.

### استثناءات

| استثناء | حالة |
| --- | --- |
| ArgumentNullException | عندما ألقيت*pageStreamFactory* باطل. |

### أنظر أيضا

* interface [IPageStreamFactory](../../../groupdocs.viewer.interfaces/ipagestreamfactory)
* class [HtmlViewOptions](../../htmlviewoptions)
* مساحة الاسم [GroupDocs.Viewer.Options](../../htmlviewoptions)
* المجسم [GroupDocs.Viewer](../../../)

---

## ForEmbeddedResources() {#forembeddedresources}

تهيئة مثيل جديد لـ[`HtmlViewOptions`](../../htmlviewoptions) فئة .

```csharp
public static HtmlViewOptions ForEmbeddedResources()
```

### أنظر أيضا

* class [HtmlViewOptions](../../htmlviewoptions)
* مساحة الاسم [GroupDocs.Viewer.Options](../../htmlviewoptions)
* المجسم [GroupDocs.Viewer](../../../)

---

## ForEmbeddedResources(string) {#forembeddedresources_4}

تهيئة مثيل جديد لـ[`HtmlViewOptions`](../../htmlviewoptions) فئة .

```csharp
public static HtmlViewOptions ForEmbeddedResources(string filePathFormat)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| filePathFormat | String | تنسيق مسار الملف ، مثل "page_ {0} .html". |

### استثناءات

| استثناء | حالة |
| --- | --- |
| ArgumentException | عندما ألقيت*filePathFormat* فارغ أو فارغ. |

### أنظر أيضا

* class [HtmlViewOptions](../../htmlviewoptions)
* مساحة الاسم [GroupDocs.Viewer.Options](../../htmlviewoptions)
* المجسم [GroupDocs.Viewer](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Viewer.dll -->
