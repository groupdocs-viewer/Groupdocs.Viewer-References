---
title: "Attachment"
second_title: "مرجع API الخاص بـ GroupDocs.Viewer لـ .NET"
description: "يُنشئ نسخة جديدة من فئة Attachmentgroupdocs.viewer.results/attachment."
type: docs
weight: 10
url: /ar/net/groupdocs.viewer.results/attachment/attachment/
---

## Attachment() {#constructor}

يُنشئ نسخة جديدة من فئة [`Attachment`](../../attachment).

```csharp
public Attachment()
```

### انظر أيضًا

* class [Attachment](../../attachment)
* namespace [GroupDocs.Viewer.Results](../../../groupdocs.viewer.results)
* assembly [GroupDocs.Viewer](../../../)

---

## Attachment(string, string) {#constructor_1}

يُنشئ نسخة جديدة من فئة [`Attachment`](../../attachment).

```csharp
public Attachment(string fileName, string filePath)
```

| Parameter | النوع | الوصف |
| --- | --- | --- |
| fileName | String | اسم ملف المرفق. |
| filePath | String | المسار النسبي للمرفق مثل folder/file.docx أو اسم الملف عندما يكون الملف موجودًا في جذر الأرشيف أو في رسالة بريد إلكتروني أو ملف بيانات. |

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentException | يتم رمي الاستثناء عندما تكون *fileName* فارغة أو خالية. |
| ArgumentException | يتم إلقاؤه عندما يكون *filePath* null أو فارغ. |

### انظر أيضًا

* class [Attachment](../../attachment)
* namespace [GroupDocs.Viewer.Results](../../../groupdocs.viewer.results)
* assembly [GroupDocs.Viewer](../../../)

---

## Attachment(string, string, string, long) {#constructor_3}

يُنشئ نسخة جديدة من فئة [`Attachment`](../../attachment).

```csharp
public Attachment(string id, string fileName, string filePath, long size)
```

| Parameter | النوع | الوصف |
| --- | --- | --- |
| معرّف | String | معرف فريد (في سياق ملف واحد) للمرفق. |
| fileName | String | اسم ملف المرفق. |
| filePath | String | المسار النسبي للمرفق مثل folder/file.docx أو اسم الملف عندما يكون الملف موجودًا في جذر الأرشيف أو في رسالة بريد إلكتروني أو ملف بيانات. |
| الحجم | Int64 | حجم ملف المرفق بالبايت. |

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentException | يُرمى عندما يكون *id* فارغًا أو null. |
| ArgumentException | يتم رمي الاستثناء عندما تكون *fileName* فارغة أو خالية. |
| ArgumentException | يتم إلقاؤه عندما يكون *filePath* null أو فارغ. |

### انظر أيضًا

* class [Attachment](../../attachment)
* namespace [GroupDocs.Viewer.Results](../../../groupdocs.viewer.results)
* assembly [GroupDocs.Viewer](../../../)

---

## Attachment(string, string, string, FileType, long) {#constructor_2}

يُنشئ نسخة جديدة من فئة [`Attachment`](../../attachment).

```csharp
public Attachment(string id, string fileName, string filePath, FileType fileType, long size)
```

| Parameter | النوع | الوصف |
| --- | --- | --- |
| معرّف | String | معرف فريد (في سياق ملف واحد) للمرفق. |
| fileName | String | اسم ملف المرفق. |
| filePath | String | المسار النسبي للمرفق مثل folder/file.docx أو اسم الملف عندما يكون الملف موجودًا في جذر الأرشيف أو في رسالة بريد إلكتروني أو ملف بيانات. |
| fileType | FileType | نوع ملف المرفق. |
| الحجم | Int64 | حجم ملف المرفق بالبايت. |

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentException | يُرمى عندما يكون *id* فارغًا أو null. |
| ArgumentException | يتم رمي الاستثناء عندما تكون *fileName* فارغة أو خالية. |
| ArgumentException | يتم إلقاؤه عندما يكون *filePath* null أو فارغ. |
| ArgumentNullException | يُرمى عندما يكون *fileType* فارغًا. |

### انظر أيضًا

* class [FileType](../../../groupdocs.viewer/filetype)
* class [Attachment](../../attachment)
* namespace [GroupDocs.Viewer.Results](../../../groupdocs.viewer.results)
* assembly [GroupDocs.Viewer](../../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.Viewer.dll -->
