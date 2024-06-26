---
title: Attachment
second_title: GroupDocs.Viewer for .NET API Reference
description: Initializes new instance of Attachmentgroupdocs.viewer.results/attachment class.
type: docs
weight: 10
url: /net/groupdocs.viewer.results/attachment/attachment/
---
## Attachment() {#constructor}

Initializes new instance of [`Attachment`](../../attachment) class.

```csharp
public Attachment()
```

### See Also

* class [Attachment](../../attachment)
* namespace [GroupDocs.Viewer.Results](../../../groupdocs.viewer.results)
* assembly [GroupDocs.Viewer](../../../)

---

## Attachment(string, string) {#constructor_1}

Initializes new instance of [`Attachment`](../../attachment) class.

```csharp
public Attachment(string fileName, string filePath)
```

| Parameter | Type | Description |
| --- | --- | --- |
| fileName | String | Attachment file name. |
| filePath | String | Attachment relative path e.g. folder/file.docx or filename when the file is located in the root of an archive, in e-mail message or data file. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | Thrown when *fileName* is null or empty. |
| ArgumentException | Thrown when *filePath* is null or empty. |

### See Also

* class [Attachment](../../attachment)
* namespace [GroupDocs.Viewer.Results](../../../groupdocs.viewer.results)
* assembly [GroupDocs.Viewer](../../../)

---

## Attachment(string, string, string, long) {#constructor_3}

Initializes new instance of [`Attachment`](../../attachment) class.

```csharp
public Attachment(string id, string fileName, string filePath, long size)
```

| Parameter | Type | Description |
| --- | --- | --- |
| id | String | Unique (in context of single file) identifier of the attachment. |
| fileName | String | Attachment file name. |
| filePath | String | Attachment relative path e.g. folder/file.docx or filename when the file is located in the root of an archive, in e-mail message or data file. |
| size | Int64 | Attachment file size in bytes. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | Thrown when *id* is null or empty. |
| ArgumentException | Thrown when *fileName* is null or empty. |
| ArgumentException | Thrown when *filePath* is null or empty. |

### See Also

* class [Attachment](../../attachment)
* namespace [GroupDocs.Viewer.Results](../../../groupdocs.viewer.results)
* assembly [GroupDocs.Viewer](../../../)

---

## Attachment(string, string, string, FileType, long) {#constructor_2}

Initializes new instance of [`Attachment`](../../attachment) class.

```csharp
public Attachment(string id, string fileName, string filePath, FileType fileType, long size)
```

| Parameter | Type | Description |
| --- | --- | --- |
| id | String | Unique (in context of single file) identifier of the attachment. |
| fileName | String | Attachment file name. |
| filePath | String | Attachment relative path e.g. folder/file.docx or filename when the file is located in the root of an archive, in e-mail message or data file. |
| fileType | FileType | Attachment file type. |
| size | Int64 | Attachment file size in bytes. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | Thrown when *id* is null or empty. |
| ArgumentException | Thrown when *fileName* is null or empty. |
| ArgumentException | Thrown when *filePath* is null or empty. |
| ArgumentNullException | Thrown when *fileType* is null. |

### See Also

* class [FileType](../../../groupdocs.viewer/filetype)
* class [Attachment](../../attachment)
* namespace [GroupDocs.Viewer.Results](../../../groupdocs.viewer.results)
* assembly [GroupDocs.Viewer](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.viewer.dll -->
