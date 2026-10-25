---
title: "PdfViewOptions"
second_title: "مرجع API الخاص بـ GroupDocs.Viewer لـ .NET"
description: "ينشئ مثيلاً من الفئة PdfViewOptionsgroupdocs.viewer.options/pdfviewoptions class."
type: docs
weight: 10
url: /ar/net/groupdocs.viewer.options/pdfviewoptions/pdfviewoptions/
---

## PdfViewOptions(CreateFileStream) {#constructor_1}

ينشئ مثيلاً من الفئة [`PdfViewOptions`](../../pdfviewoptions) class.

```csharp
public PdfViewOptions(CreateFileStream createFileStream)
```

| Parameter | النوع | الوصف |
| --- | --- | --- |
| createFileStream | CreateFileStream | الطريقة التي تنشئ الدفق المستخدم لكتابة بيانات ملف الإخراج. |

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | يتم إلقاؤه عندما تكون *createFileStream* null. |

### ملاحظات

للحصول على مثال الشيفرة، راجع [التوثيق](https://docs.groupdocs.com/viewer/net/rendering-to-pdf/).

### انظر أيضًا

* delegate [CreateFileStream](../../../groupdocs.viewer.interfaces/createfilestream)
* class [PdfViewOptions](../../pdfviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

---

## PdfViewOptions(CreateFileStream, ReleaseFileStream) {#constructor_2}

ينشئ مثيلاً من الفئة [`PdfViewOptions`](../../pdfviewoptions) class.

```csharp
public PdfViewOptions(CreateFileStream createFileStream, ReleaseFileStream releaseFileStream)
```

| Parameter | النوع | الوصف |
| --- | --- | --- |
| createFileStream | CreateFileStream | الطريقة التي تنشئ الدفق المستخدم لكتابة بيانات ملف الإخراج. |
| releaseFileStream | ReleaseFileStream | الطريقة التي تُطلق الدفق الذي تم إنشاؤه بواسطة الطريقة المعينة للمندوب الذي تم تمريره إلى معامل *createFileStream*. |

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | يتم إلقاؤه عندما تكون *createFileStream* null. |
| ArgumentNullException | يتم إلقاؤه عندما تكون *releaseFileStream* null. |

### ملاحظات

للحصول على مثال الشيفرة، راجع [التوثيق](https://docs.groupdocs.com/viewer/net/rendering-to-pdf/).

### انظر أيضًا

* delegate [CreateFileStream](../../../groupdocs.viewer.interfaces/createfilestream)
* delegate [ReleaseFileStream](../../../groupdocs.viewer.interfaces/releasefilestream)
* class [PdfViewOptions](../../pdfviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

---

## PdfViewOptions(IFileStreamFactory) {#constructor_3}

ينشئ مثيلاً من الفئة [`PdfViewOptions`](../../pdfviewoptions) class.

```csharp
public PdfViewOptions(IFileStreamFactory fileStreamFactory)
```

| Parameter | النوع | الوصف |
| --- | --- | --- |
| fileStreamFactory | IFileStreamFactory | المصنع الذي ينفّذ طرقًا لإنشاء وإصدار تدفق ملف الإخراج. |

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | يُرمى عندما يكون *fileStreamFactory* null. |

### ملاحظات

للحصول على مثال الشيفرة، راجع [التوثيق](https://docs.groupdocs.com/viewer/net/rendering-to-pdf/).

### انظر أيضًا

* interface [IFileStreamFactory](../../../groupdocs.viewer.interfaces/ifilestreamfactory)
* class [PdfViewOptions](../../pdfviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

---

## PdfViewOptions() {#constructor}

ينشئ مثيلاً من الفئة [`PdfViewOptions`](../../pdfviewoptions) class.

```csharp
public PdfViewOptions()
```

### ملاحظات

يقوم هذا المُنشئ بتهيئة نسخة من [`PdfViewOptions`](../../pdfviewoptions) باستخدام "output.pdf" كصيغة مسار للملف الناتج. سيتم وضع الملف الناتج في الدليل الحالي لتطبيق البرنامج.

للحصول على مثال الشيفرة، راجع [التوثيق](https://docs.groupdocs.com/viewer/net/rendering-to-pdf/).

### انظر أيضًا

* class [PdfViewOptions](../../pdfviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

---

## PdfViewOptions(string) {#constructor_4}

ينشئ مثيلاً من الفئة [`PdfViewOptions`](../../pdfviewoptions) class.

```csharp
public PdfViewOptions(string outputFilePath)
```

| Parameter | النوع | الوصف |
| --- | --- | --- |
| outputFilePath | String | المسار لملف PDF الناتج. |

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentException | يُرمى عندما يكون *outputFilePath* null أو فارغًا. |

### ملاحظات

للحصول على مثال الشيفرة، راجع [التوثيق](https://docs.groupdocs.com/viewer/net/rendering-to-pdf/).

### انظر أيضًا

* class [PdfViewOptions](../../pdfviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.Viewer.dll -->
