---
title: "FromStream"
second_title: "مرجع API الخاص بـ GroupDocs.Viewer لـ .NET"
description: "يكتشف نوع الملف بقراءة توقيع الملف."
type: docs
weight: 2000
url: /ar/net/groupdocs.viewer/filetype/fromstream/
---

## FromStream(Stream) {#fromstream}

يكتشف نوع الملف بقراءة توقيع الملف.

```csharp
public static FileType FromStream(Stream stream)
```

| Parameter | النوع | الوصف |
| --- | --- | --- |
| تدفق | تدفق | تدفق الملف. |

### انظر أيضًا

* class [FileType](../../filetype)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## FromStream(Stream, string) {#fromstream_2}

يكتشف نوع الملف بقراءة توقيع الملف.

```csharp
public static FileType FromStream(Stream stream, string password)
```

| Parameter | النوع | الوصف |
| --- | --- | --- |
| تدفق | تدفق | تدفق الملف. |
| password | String | كلمة المرور لفتح الملف. |

### انظر أيضًا

* class [FileType](../../filetype)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## FromStream(Stream, ILogger) {#fromstream_1}

يكتشف نوع الملف بقراءة توقيع الملف.

```csharp
public static FileType FromStream(Stream stream, ILogger logger)
```

| Parameter | النوع | الوصف |
| --- | --- | --- |
| تدفق | تدفق | تدفق الملف. |
| logger | ILogger | المسجل. |

### قيمة الإرجاع

يعيد نوع الملف في حال تم اكتشافه بنجاح وإلا يعيد النوع الافتراضي [`Unknown`](../unknown).

### انظر أيضًا

* interface [ILogger](../../../groupdocs.viewer.logging/ilogger)
* class [FileType](../../filetype)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## FromStream(Stream, string, ILogger) {#fromstream_3}

يكتشف نوع الملف بقراءة توقيع الملف.

```csharp
public static FileType FromStream(Stream stream, string password, ILogger logger)
```

| Parameter | النوع | الوصف |
| --- | --- | --- |
| تدفق | تدفق | تدفق الملف. |
| password | String | كلمة المرور لفتح الملف. |
| logger | ILogger | المسجل. |

### قيمة الإرجاع

يعيد نوع الملف في حال تم اكتشافه بنجاح وإلا يعيد النوع الافتراضي [`Unknown`](../unknown).

### انظر أيضًا

* interface [ILogger](../../../groupdocs.viewer.logging/ilogger)
* class [FileType](../../filetype)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.Viewer.dll -->
