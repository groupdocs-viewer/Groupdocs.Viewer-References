---
title: Attachment
second_title: GroupDocs.Viewer for Python via .NET API Reference
description: Represents attachment file contained by email message archive PDF document or Outlook data file.
type: docs
weight: 70
url: /python-net/groupdocs.viewer.results/attachment/
---
## Attachment class

Represents attachment file contained by email message, archive, PDF document or Outlook data file.

```csharp
public class Attachment
```

## Constructors

| Name | Description |
| --- | --- |
| [Attachment](attachment#constructor)() | Initializes new instance of [`Attachment`](../attachment) class. |
| [Attachment](attachment#constructor_1)(string, string) | Initializes new instance of [`Attachment`](../attachment) class. |
| [Attachment](attachment#constructor_3)(string, string, string, long) | Initializes new instance of [`Attachment`](../attachment) class. |
| [Attachment](attachment#constructor_2)(string, string, string, FileType, long) | Initializes new instance of [`Attachment`](../attachment) class. |

## Properties

| Name | Description |
| --- | --- |
| [FileName](../../groupdocs.viewer.results/attachment/filename) { get; set; } | Attachment file name. |
| [FilePath](../../groupdocs.viewer.results/attachment/filepath) { get; set; } | Attachment relative path e.g. folder/file.docx or filename when the file is located in the root of an archive, in e-mail message or data file. |
| [FileType](../../groupdocs.viewer.results/attachment/filetype) { get; set; } | Attachment file type. |
| [Id](../../groupdocs.viewer.results/attachment/id) { get; set; } | Unique identifier of the attachment in context of a single file that contains this attachment. |
| [Size](../../groupdocs.viewer.results/attachment/size) { get; set; } | Attachment file size in bytes. |

## Methods

| Name | Description |
| --- | --- |
| override [ToString](../../groupdocs.viewer.results/attachment/tostring)() | Returns a string that represents the current object. |

### See Also

* namespace [GroupDocs.Viewer.Results](../../groupdocs.viewer.results)
* assembly [GroupDocs.Viewer](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.viewer.dll -->