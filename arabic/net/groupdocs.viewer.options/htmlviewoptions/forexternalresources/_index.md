---
title: ForExternalResources
second_title: GroupDocs.Viewer لمرجع .NET API
description: تهيئة مثيل جديد لـHtmlViewOptionsgroupdocs.viewer.options/htmlviewoptions فئة للعرض في HTML مع الموارد الخارجية .
type: docs
weight: 20
url: /ar/net/groupdocs.viewer.options/htmlviewoptions/forexternalresources/
---
## ForExternalResources(CreatePageStream, CreateResourceStream, CreateResourceUrl) {#forexternalresources_1}

تهيئة مثيل جديد لـ[`HtmlViewOptions`](../../htmlviewoptions) فئة للعرض في HTML مع الموارد الخارجية .

```csharp
public static HtmlViewOptions ForExternalResources(CreatePageStream createPageStream, 
    CreateResourceStream createResourceStream, CreateResourceUrl createResourceUrl)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| createPageStream | CreatePageStream | طريقة إنشاء الدفق المستخدمة لكتابة بيانات صفحة الإخراج. |
| createResourceStream | CreateResourceStream | الطريقة التي تطلق الدفق الذي تم إنشاؤه بواسطة*createPageStream* طريقة. |
| createResourceUrl | CreateResourceUrl | الطريقة التي تنشئ URL لمورد HTML. |

### قيمة الإرجاع

مثيل جديد من[`HtmlViewOptions`](../../htmlviewoptions) فئة لتقديمها إلى HTML باستخدام موارد خارجية.

### استثناءات

| استثناء | حالة |
| --- | --- |
| ArgumentNullException | عندما ألقيت*createPageStream* باطل. |
| ArgumentNullException | عندما ألقيت*createResourceStream* باطل. |
| ArgumentNullException | عندما ألقيت*createResourceUrl* باطل. |

### أنظر أيضا

* delegate [CreatePageStream](../../../groupdocs.viewer.interfaces/createpagestream)
* delegate [CreateResourceStream](../../../groupdocs.viewer.interfaces/createresourcestream)
* delegate [CreateResourceUrl](../../../groupdocs.viewer.interfaces/createresourceurl)
* class [HtmlViewOptions](../../htmlviewoptions)
* مساحة الاسم [GroupDocs.Viewer.Options](../../htmlviewoptions)
* المجسم [GroupDocs.Viewer](../../../)

---

## ForExternalResources(CreatePageStream, CreateResourceStream, CreateResourceUrl, ReleasePageStream, ReleaseResourceStream) {#forexternalresources_2}

تهيئة مثيل جديد لـ[`HtmlViewOptions`](../../htmlviewoptions) فئة للعرض في HTML مع الموارد الخارجية .

```csharp
public static HtmlViewOptions ForExternalResources(CreatePageStream createPageStream, 
    CreateResourceStream createResourceStream, CreateResourceUrl createResourceUrl, 
    ReleasePageStream releasePageStream, ReleaseResourceStream releaseResourceStream)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| createPageStream | CreatePageStream | طريقة إنشاء الدفق المستخدمة لكتابة بيانات صفحة الإخراج. |
| createResourceStream | CreateResourceStream | الأسلوب الذي ينشئ الدفق المستخدم لكتابة بيانات مورد HTML. |
| createResourceUrl | CreateResourceUrl | الطريقة التي تنشئ URL لمورد HTML. |
| releasePageStream | ReleasePageStream | الطريقة التي تطلق الدفق الذي تم إنشاؤه بواسطة الطريقة المخصصة للمفوض الذي تم تمريره إليه*createPageStream* معامل. |
| releaseResourceStream | ReleaseResourceStream | الطريقة التي تطلق الدفق الذي تم إنشاؤه بواسطة الطريقة المخصصة للمفوض الذي تم تمريره إليه*createResourceStream* معامل. |

### قيمة الإرجاع

مثيل جديد من[`HtmlViewOptions`](../../htmlviewoptions) فئة لتقديمها إلى HTML باستخدام موارد خارجية.

### استثناءات

| استثناء | حالة |
| --- | --- |
| ArgumentNullException | عندما ألقيت*createPageStream* باطل. |
| ArgumentNullException | عندما ألقيت*createResourceStream* باطل. |
| ArgumentNullException | عندما ألقيت*createResourceUrl* باطل. |
| ArgumentNullException | عندما ألقيت*releasePageStream* باطل. |
| ArgumentNullException | عندما ألقيت*releaseResourceStream* باطل. |

### أنظر أيضا

* delegate [CreatePageStream](../../../groupdocs.viewer.interfaces/createpagestream)
* delegate [CreateResourceStream](../../../groupdocs.viewer.interfaces/createresourcestream)
* delegate [CreateResourceUrl](../../../groupdocs.viewer.interfaces/createresourceurl)
* delegate [ReleasePageStream](../../../groupdocs.viewer.interfaces/releasepagestream)
* delegate [ReleaseResourceStream](../../../groupdocs.viewer.interfaces/releaseresourcestream)
* class [HtmlViewOptions](../../htmlviewoptions)
* مساحة الاسم [GroupDocs.Viewer.Options](../../htmlviewoptions)
* المجسم [GroupDocs.Viewer](../../../)

---

## ForExternalResources(IPageStreamFactory, IResourceStreamFactory) {#forexternalresources_3}

تهيئة مثيل جديد لـ[`HtmlViewOptions`](../../htmlviewoptions) فئة للعرض في HTML مع الموارد الخارجية .

```csharp
public static HtmlViewOptions ForExternalResources(IPageStreamFactory pageStreamFactory, 
    IResourceStreamFactory resourceStreamFactory)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| pageStreamFactory | IPageStreamFactory | المصنع الذي ينفذ طرقًا لإنشاء دفق صفحة الإخراج وتحريره. |
| resourceStreamFactory | IResourceStreamFactory | المصنع الذي ينفذ الطرق المطلوبة لإنشاء عنوان URL للمورد ، وإنشاء وإطلاق دفق موارد HTML الناتج. |

### قيمة الإرجاع

مثيل جديد من[`HtmlViewOptions`](../../htmlviewoptions) فئة لتقديمها إلى HTML باستخدام موارد خارجية.

### استثناءات

| استثناء | حالة |
| --- | --- |
| ArgumentNullException | عندما ألقيت*pageStreamFactory* باطل. |
| ArgumentNullException | عندما ألقيت*resourceStreamFactory* باطل. |

### أنظر أيضا

* interface [IPageStreamFactory](../../../groupdocs.viewer.interfaces/ipagestreamfactory)
* interface [IResourceStreamFactory](../../../groupdocs.viewer.interfaces/iresourcestreamfactory)
* class [HtmlViewOptions](../../htmlviewoptions)
* مساحة الاسم [GroupDocs.Viewer.Options](../../htmlviewoptions)
* المجسم [GroupDocs.Viewer](../../../)

---

## ForExternalResources() {#forexternalresources}

تهيئة مثيل جديد لـ[`HtmlViewOptions`](../../htmlviewoptions) فئة .

```csharp
public static HtmlViewOptions ForExternalResources()
```

### ملاحظات

يقوم المُنشئ هذا بتهيئة مثيل جديد لـ[`HtmlViewOptions`](../../htmlviewoptions) - باستخدام "p_ {0} .html" كتنسيق مسار الملف لملفات HTML الناتجة ؛ - مع "p_ {0} _ {1}" كتنسيق مسار الملف لملفات موارد HTML الناتجة ؛ - مع " p_ {0} _ {1} "كتنسيق URL لموارد HTML ؛ سيتم وضع ملفات الإخراج في دليل العمل الحالي للتطبيق.

### أنظر أيضا

* class [HtmlViewOptions](../../htmlviewoptions)
* مساحة الاسم [GroupDocs.Viewer.Options](../../htmlviewoptions)
* المجسم [GroupDocs.Viewer](../../../)

---

## ForExternalResources(string, string, string) {#forexternalresources_4}

تهيئة مثيل جديد لـ[`HtmlViewOptions`](../../htmlviewoptions) فئة .

```csharp
public static HtmlViewOptions ForExternalResources(string filePathFormat, 
    string resourceFilePathFormat, string resourceUrlFormat)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| filePathFormat | String | تنسيق مسار الملف ، مثل "page_ {0} .html". |
| resourceFilePathFormat | String | تنسيق مسار ملف المصدر ، على سبيل المثال "page_ {0} / Resource_ {1}". |
| resourceUrlFormat | String | تنسيق عنوان URL للمورد ، على سبيل المثال "page_ {0} / Resource_ {1}". |

### استثناءات

| استثناء | حالة |
| --- | --- |
| ArgumentException | عندما ألقيت*filePathFormat* فارغ أو فارغ. |
| ArgumentException | عندما ألقيت*resourceFilePathFormat* فارغ أو فارغ. |
| ArgumentException | عندما ألقيت*resourceUrlFormat* فارغ أو فارغ. |

### أنظر أيضا

* class [HtmlViewOptions](../../htmlviewoptions)
* مساحة الاسم [GroupDocs.Viewer.Options](../../htmlviewoptions)
* المجسم [GroupDocs.Viewer](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Viewer.dll -->
