---
title: PngViewOptions
second_title: GroupDocs.Viewer لمرجع .NET API
description: تهيئة مثيل جديد لـPngViewOptionsgroupdocs.viewer.options/pngviewoptions فئة .
type: docs
weight: 10
url: /ar/net/groupdocs.viewer.options/pngviewoptions/pngviewoptions/
---
## PngViewOptions(CreatePageStream) {#constructor_1}

تهيئة مثيل جديد لـ[`PngViewOptions`](../../pngviewoptions) فئة .

```csharp
public PngViewOptions(CreatePageStream createPageStream)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| createPageStream | CreatePageStream | طريقة إنشاء الدفق المستخدمة لكتابة بيانات صفحة الإخراج. |

### استثناءات

| استثناء | حالة |
| --- | --- |
| ArgumentNullException | عندما ألقيت*createPageStream* باطل. |

### أنظر أيضا

* delegate [CreatePageStream](../../../groupdocs.viewer.interfaces/createpagestream)
* class [PngViewOptions](../../pngviewoptions)
* مساحة الاسم [GroupDocs.Viewer.Options](../../pngviewoptions)
* المجسم [GroupDocs.Viewer](../../../)

---

## PngViewOptions(CreatePageStream, ReleasePageStream) {#constructor_2}

تهيئة مثيل جديد لـ[`PngViewOptions`](../../pngviewoptions) فئة .

```csharp
public PngViewOptions(CreatePageStream createPageStream, ReleasePageStream releasePageStream)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| createPageStream | CreatePageStream | طريقة إنشاء الدفق المستخدمة لكتابة بيانات صفحة الإخراج. |
| releasePageStream | ReleasePageStream | الطريقة التي تطلق الدفق الذي تم إنشاؤه بواسطة الطريقة المخصصة للمفوض الذي تم تمريره إليه*createPageStream* معامل. |

### استثناءات

| استثناء | حالة |
| --- | --- |
| ArgumentNullException | عندما ألقيت*createPageStream* باطل. |
| ArgumentNullException | عندما ألقيت*releasePageStream* باطل. |

### أنظر أيضا

* delegate [CreatePageStream](../../../groupdocs.viewer.interfaces/createpagestream)
* delegate [ReleasePageStream](../../../groupdocs.viewer.interfaces/releasepagestream)
* class [PngViewOptions](../../pngviewoptions)
* مساحة الاسم [GroupDocs.Viewer.Options](../../pngviewoptions)
* المجسم [GroupDocs.Viewer](../../../)

---

## PngViewOptions(IPageStreamFactory) {#constructor_3}

تهيئة مثيل جديد لـ[`PngViewOptions`](../../pngviewoptions) فئة .

```csharp
public PngViewOptions(IPageStreamFactory pageStreamFactory)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| pageStreamFactory | IPageStreamFactory | المصنع الذي ينفذ طرقًا لإنشاء دفق صفحة الإخراج وتحريره. |

### استثناءات

| استثناء | حالة |
| --- | --- |
| ArgumentNullException | عندما ألقيت*pageStreamFactory* باطل. |

### أنظر أيضا

* interface [IPageStreamFactory](../../../groupdocs.viewer.interfaces/ipagestreamfactory)
* class [PngViewOptions](../../pngviewoptions)
* مساحة الاسم [GroupDocs.Viewer.Options](../../pngviewoptions)
* المجسم [GroupDocs.Viewer](../../../)

---

## PngViewOptions() {#constructor}

تهيئة مثيل جديد لـ[`PngViewOptions`](../../pngviewoptions) فئة .

```csharp
public PngViewOptions()
```

### ملاحظات

يقوم المُنشئ هذا بتهيئة مثيل جديد لـ[`PngViewOptions`](../../pngviewoptions) مع "p_ {0} .png" كتنسيق مسار الملف لملفات الإخراج. سيتم وضع ملفات الإخراج في دليل العمل الحالي للتطبيق.

### أنظر أيضا

* class [PngViewOptions](../../pngviewoptions)
* مساحة الاسم [GroupDocs.Viewer.Options](../../pngviewoptions)
* المجسم [GroupDocs.Viewer](../../../)

---

## PngViewOptions(string) {#constructor_4}

تهيئة مثيل جديد لـ[`PngViewOptions`](../../pngviewoptions) فئة .

```csharp
public PngViewOptions(string filePathFormat)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| filePathFormat | String | تنسيق مسار الملف ، مثل "page_ {0} .png". |

### استثناءات

| استثناء | حالة |
| --- | --- |
| ArgumentException | عندما ألقيت*filePathFormat* فارغ أو فارغ. |

### أنظر أيضا

* class [PngViewOptions](../../pngviewoptions)
* مساحة الاسم [GroupDocs.Viewer.Options](../../pngviewoptions)
* المجسم [GroupDocs.Viewer](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Viewer.dll -->