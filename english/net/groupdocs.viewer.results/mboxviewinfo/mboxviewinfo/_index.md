---
title: MboxViewInfo
second_title: GroupDocs.Viewer for .NET API Reference
description: Initializes new instance of MboxViewInfogroupdocs.viewer.results/mboxviewinfo class.
type: docs
weight: 10
url: /net/groupdocs.viewer.results/mboxviewinfo/mboxviewinfo/
---
## MboxViewInfo() {#constructor}

Initializes new instance of [`MboxViewInfo`](../../mboxviewinfo) class.

```csharp
public MboxViewInfo()
```

### See Also

* class [MboxViewInfo](../../mboxviewinfo)
* namespace [GroupDocs.Viewer.Results](../../../groupdocs.viewer.results)
* assembly [GroupDocs.Viewer](../../../)

---

## MboxViewInfo(FileType, List&lt;Page&gt;, int) {#constructor_1}

Initializes new instance of [`MboxViewInfo`](../../mboxviewinfo) class.

```csharp
public MboxViewInfo(FileType fileType, List<Page> pages, int notesCount)
```

| Parameter | Type | Description |
| --- | --- | --- |
| fileType | FileType | The type of the file. |
| pages | List`1 | The list of pages to view. |
| notesCount | Int32 | The notes count contained by the Lotus database storage file. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | Thrown when *fileType* is null. |
| ArgumentNullException | Thrown when *pages* is null. |
| ArgumentNullException | Thrown when *notesCount* is null. |

### See Also

* class [FileType](../../../groupdocs.viewer/filetype)
* class [Page](../../page)
* class [MboxViewInfo](../../mboxviewinfo)
* namespace [GroupDocs.Viewer.Results](../../../groupdocs.viewer.results)
* assembly [GroupDocs.Viewer](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.viewer.dll -->
