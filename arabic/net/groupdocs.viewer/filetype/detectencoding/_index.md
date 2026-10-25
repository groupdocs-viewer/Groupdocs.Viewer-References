---
title: "DetectEncoding"
second_title: "مرجع API الخاص بـ GroupDocs.Viewer لـ .NET"
description: "محاولات لاكتشاف ترميز ملفات النص TXTgroupdocs.viewer/filetype/txt TSVgroupdocs.viewer/filetype/tsv و CSVgroupdocs.viewer/filetype/csv حسب المسار."
type: docs
weight: 2060
url: /ar/net/groupdocs.viewer/filetype/detectencoding/
---

## DetectEncoding(string) {#detectencoding_1}

محاولات لاكتشاف ترميز ملفات النص [`TXT`](../txt)، [`TSV`](../tsv) و[`CSV`](../csv) حسب المسار.

```csharp
public static Encoding DetectEncoding(string filePath)
```

| Parameter | النوع | الوصف |
| --- | --- | --- |
| filePath | String | اسم الملف أو مسار الملف. |

### قيمة الإرجاع

الترميز أو null عندما يفشل اكتشاف ترميز الملف.

### أمثلة

يوضح المثال كيفية اكتشاف ترميز ملف النص.

```csharp
Encoding encoding = FileType.DetectEncoding("message.txt");
```

### انظر أيضًا

* class [FileType](../../filetype)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## DetectEncoding(Stream) {#detectencoding}

محاولات لاكتشاف ترميز ملف النص [`TXT`](../txt)، [`TSV`](../tsv) و[`CSV`](../csv) عبر التدفق.

```csharp
public static Encoding DetectEncoding(Stream stream)
```

| Parameter | النوع | الوصف |
| --- | --- | --- |
| تدفق | تدفق | تدفق الملف. |

### قيمة الإرجاع

الترميز أو null عندما يفشل اكتشاف ترميز الملف.

### أمثلة

يوضح المثال كيفية اكتشاف ترميز ملف النص.

```csharp
Stream stream = File.OpenRead("message.txt");
Encoding encoding = FileType.DetectEncoding(stream);
```

### انظر أيضًا

* class [FileType](../../filetype)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.Viewer.dll -->
