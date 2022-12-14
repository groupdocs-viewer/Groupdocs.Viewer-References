---
title: PdfViewOptions
second_title: GroupDocs.Viewer لمرجع .NET API
description: تهيئة مثيل جديد لـPdfViewOptionsgroupdocs.viewer.options/pdfviewoptions فئة .
type: docs
weight: 10
url: /ar/net/groupdocs.viewer.options/pdfviewoptions/pdfviewoptions/
---
## PdfViewOptions(CreateFileStream) {#constructor_1}

تهيئة مثيل جديد لـ[`PdfViewOptions`](../../pdfviewoptions) فئة .

```csharp
public PdfViewOptions(CreateFileStream createFileStream)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| createFileStream | CreateFileStream | طريقة إنشاء الدفق المستخدمة لكتابة بيانات ملف الإخراج. |

### استثناءات

| استثناء | حالة |
| --- | --- |
| ArgumentNullException | عندما ألقيت*createFileStream* باطل. |

### أنظر أيضا

* delegate [CreateFileStream](../../../groupdocs.viewer.interfaces/createfilestream)
* class [PdfViewOptions](../../pdfviewoptions)
* مساحة الاسم [GroupDocs.Viewer.Options](../../pdfviewoptions)
* المجسم [GroupDocs.Viewer](../../../)

---

## PdfViewOptions(CreateFileStream, ReleaseFileStream) {#constructor_2}

تهيئة مثيل جديد لـ[`PdfViewOptions`](../../pdfviewoptions) فئة .

```csharp
public PdfViewOptions(CreateFileStream createFileStream, ReleaseFileStream releaseFileStream)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| createFileStream | CreateFileStream | طريقة إنشاء الدفق المستخدمة لكتابة بيانات ملف الإخراج. |
| releaseFileStream | ReleaseFileStream | الطريقة التي تطلق الدفق الذي تم إنشاؤه بواسطة الطريقة المخصصة للمفوض الذي تم تمريره إليه*createFileStream* معامل. |

### استثناءات

| استثناء | حالة |
| --- | --- |
| ArgumentNullException | عندما ألقيت*createFileStream* باطل. |
| ArgumentNullException | عندما ألقيت*releaseFileStream* باطل. |

### أنظر أيضا

* delegate [CreateFileStream](../../../groupdocs.viewer.interfaces/createfilestream)
* delegate [ReleaseFileStream](../../../groupdocs.viewer.interfaces/releasefilestream)
* class [PdfViewOptions](../../pdfviewoptions)
* مساحة الاسم [GroupDocs.Viewer.Options](../../pdfviewoptions)
* المجسم [GroupDocs.Viewer](../../../)

---

## PdfViewOptions(IFileStreamFactory) {#constructor_3}

تهيئة مثيل جديد لـ[`PdfViewOptions`](../../pdfviewoptions) فئة .

```csharp
public PdfViewOptions(IFileStreamFactory fileStreamFactory)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| fileStreamFactory | IFileStreamFactory | المصنع الذي ينفذ طرقًا لإنشاء دفق ملف الإخراج وتحريره. |

### استثناءات

| استثناء | حالة |
| --- | --- |
| ArgumentNullException | عندما ألقيت*fileStreamFactory* باطل. |

### أنظر أيضا

* interface [IFileStreamFactory](../../../groupdocs.viewer.interfaces/ifilestreamfactory)
* class [PdfViewOptions](../../pdfviewoptions)
* مساحة الاسم [GroupDocs.Viewer.Options](../../pdfviewoptions)
* المجسم [GroupDocs.Viewer](../../../)

---

## PdfViewOptions() {#constructor}

تهيئة مثيل جديد لـ[`PdfViewOptions`](../../pdfviewoptions) فئة .

```csharp
public PdfViewOptions()
```

### ملاحظات

يقوم المُنشئ هذا بتهيئة مثيل جديد لـ[`PdfViewOptions`](../../pdfviewoptions) مع "output.pdf" كتنسيق مسار الملف لملف الإخراج. سيتم وضع ملف الإخراج في دليل العمل الحالي للتطبيق.

### أنظر أيضا

* class [PdfViewOptions](../../pdfviewoptions)
* مساحة الاسم [GroupDocs.Viewer.Options](../../pdfviewoptions)
* المجسم [GroupDocs.Viewer](../../../)

---

## PdfViewOptions(string) {#constructor_4}

تهيئة مثيل جديد لـ[`PdfViewOptions`](../../pdfviewoptions) فئة .

```csharp
public PdfViewOptions(string outputFilePath)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| outputFilePath | String | مسار ملف PDF الناتج. |

### استثناءات

| استثناء | حالة |
| --- | --- |
| ArgumentException | عندما ألقيت*outputFilePath* فارغ أو فارغ. |

### أنظر أيضا

* class [PdfViewOptions](../../pdfviewoptions)
* مساحة الاسم [GroupDocs.Viewer.Options](../../pdfviewoptions)
* المجسم [GroupDocs.Viewer](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Viewer.dll -->
