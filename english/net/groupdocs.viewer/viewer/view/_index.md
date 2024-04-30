---
title: View
second_title: GroupDocs.Viewer for .NET API Reference
description: Creates view of all document pages.
type: docs
weight: 70
url: /net/groupdocs.viewer/viewer/view/
---
## View(ViewOptions) {#view}

Creates view of all document pages.

```csharp
public void View(ViewOptions options)
```

| Parameter | Type | Description |
| --- | --- | --- |
| options | ViewOptions | The view options. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | Thrown when *options* is null. |
| [PasswordRequiredException](../../../groupdocs.viewer.exceptions/passwordrequiredexception) | Thrown when password is required to open the document. |
| [IncorrectPasswordException](../../../groupdocs.viewer.exceptions/incorrectpasswordexception) | Thrown when password that was specified is incorrect. |
| [GroupDocsViewerException](../../../groupdocs.viewer.exceptions/groupdocsviewerexception) | Thrown when attachment could not be found. |

### Remarks

**Learn more**

* More about different viewing options following this guide: [How to customize document viewing output using GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Viewing)

### See Also

* class [ViewOptions](../../../groupdocs.viewer.options/viewoptions)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## View(ViewOptions, CancellationToken) {#view_2}

Creates view of all document pages.

```csharp
public void View(ViewOptions options, CancellationToken cancellationToken)
```

| Parameter | Type | Description |
| --- | --- | --- |
| options | ViewOptions | The view options. |
| cancellationToken | CancellationToken | Cancellation token to send a request to cancel current view process. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | Thrown when *options* is null. |
| [PasswordRequiredException](../../../groupdocs.viewer.exceptions/passwordrequiredexception) | Thrown when password is required to open the document. |
| [IncorrectPasswordException](../../../groupdocs.viewer.exceptions/incorrectpasswordexception) | Thrown when password that was specified is incorrect. |
| [GroupDocsViewerException](../../../groupdocs.viewer.exceptions/groupdocsviewerexception) | Thrown when attachment could not be found. |

### Remarks

**Learn more**

* More about different viewing options following this guide: [How to customize document viewing output using GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Viewing)

### See Also

* class [ViewOptions](../../../groupdocs.viewer.options/viewoptions)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## View(ViewOptions, params int[]) {#view_1}

Creates view of specific document pages.

```csharp
public void View(ViewOptions options, params int[] pageNumbers)
```

| Parameter | Type | Description |
| --- | --- | --- |
| options | ViewOptions | The view options. |
| pageNumbers | Int32[] | The page numbers to view. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | Thrown when *options* is null. |
| ArgumentNullException | Thrown when *pageNumbers* is null. |
| ArgumentException | Thrown when *pageNumbers* is empty. |
| [PasswordRequiredException](../../../groupdocs.viewer.exceptions/passwordrequiredexception) | Thrown when password is required to open the document. |
| [IncorrectPasswordException](../../../groupdocs.viewer.exceptions/incorrectpasswordexception) | Thrown when password that was specified is incorrect. |
| [GroupDocsViewerException](../../../groupdocs.viewer.exceptions/groupdocsviewerexception) | Thrown when attachment could not be found. |

### Remarks

**Learn more**

* More about different viewing options following this guide: [How to customize document viewing output using GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Viewing)

### See Also

* class [ViewOptions](../../../groupdocs.viewer.options/viewoptions)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## View(ViewOptions, CancellationToken, params int[]) {#view_3}

Creates view of specific document pages.

```csharp
public void View(ViewOptions options, CancellationToken cancellationToken, params int[] pageNumbers)
```

| Parameter | Type | Description |
| --- | --- | --- |
| options | ViewOptions | The view options. |
| pageNumbers | CancellationToken | The page numbers to view. |
| cancellationToken | Int32[] | Cancellation token to cancel processing. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | Thrown when *options* is null. |
| ArgumentNullException | Thrown when *pageNumbers* is null. |
| ArgumentException | Thrown when *pageNumbers* is empty. |
| [PasswordRequiredException](../../../groupdocs.viewer.exceptions/passwordrequiredexception) | Thrown when password is required to open the document. |
| [IncorrectPasswordException](../../../groupdocs.viewer.exceptions/incorrectpasswordexception) | Thrown when password that was specified is incorrect. |
| [GroupDocsViewerException](../../../groupdocs.viewer.exceptions/groupdocsviewerexception) | Thrown when attachment could not be found. |

### Remarks

**Learn more**

* More about different viewing options following this guide: [How to customize document viewing output using GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Viewing)

### See Also

* class [ViewOptions](../../../groupdocs.viewer.options/viewoptions)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.viewer.dll -->
