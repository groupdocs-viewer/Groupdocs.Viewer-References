---
title: "Attachment"
second_title: "مرجع API الخاص بـ GroupDocs.Viewer لـ .NET"
description: "يمثل ملف مرفق موجود في رسالة بريد إلكتروني أو أرشيف PDF أو ملف بيانات Outlook."
type: docs
weight: 80
url: /ar/net/groupdocs.viewer.results/attachment/
---

## Attachment class

يمثل ملف المرفق الموجود في رسالة بريد إلكتروني أو أرشيف أو مستند PDF أو ملف بيانات Outlook.

```csharp
public class Attachment
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [Attachment](attachment#constructor)() | يُنشئ مثلاً جديدًا من الفئة [`Attachment`](../attachment). |
| [Attachment](attachment#constructor_1)(string, string) | يُنشئ مثلاً جديدًا من الفئة [`Attachment`](../attachment). |
| [Attachment](attachment#constructor_3)(string, string, string, long) | يُنشئ مثلاً جديدًا من الفئة [`Attachment`](../attachment). |
| [Attachment](attachment#constructor_2)(string, string, string, FileType, long) | يُنشئ مثلاً جديدًا من الفئة [`Attachment`](../attachment). |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [FileName](../../groupdocs.viewer.results/attachment/filename) { get; set; } | اسم ملف المرفق. |
| [FilePath](../../groupdocs.viewer.results/attachment/filepath) { get; set; } | المسار النسبي للمرفق مثل folder/file.docx أو اسم الملف عندما يكون الملف موجودًا في جذر الأرشيف أو في رسالة بريد إلكتروني أو ملف بيانات. |
| [FileType](../../groupdocs.viewer.results/attachment/filetype) { get; set; } | نوع ملف المرفق. |
| [Id](../../groupdocs.viewer.results/attachment/id) { get; set; } | المعرّف الفريد للمرفق في سياق ملف واحد يحتوي على هذا المرفق. |
| [Size](../../groupdocs.viewer.results/attachment/size) { get; set; } | حجم ملف المرفق بالبايت. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| override [ToString](../../groupdocs.viewer.results/attachment/tostring)() | يعيد سلسلة تمثل الكائن الحالي. |

### انظر أيضًا

* namespace [GroupDocs.Viewer.Results](../../groupdocs.viewer.results)
* assembly [GroupDocs.Viewer](../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.Viewer.dll -->
