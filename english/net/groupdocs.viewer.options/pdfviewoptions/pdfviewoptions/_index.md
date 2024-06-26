---
title: PdfViewOptions
second_title: GroupDocs.Viewer for .NET API Reference
description: Initializes an instance of PdfViewOptionsgroupdocs.viewer.options/pdfviewoptions class.
type: docs
weight: 10
url: /net/groupdocs.viewer.options/pdfviewoptions/pdfviewoptions/
---
## PdfViewOptions(CreateFileStream) {#constructor_1}

Initializes an instance of [`PdfViewOptions`](../../pdfviewoptions) class.

```csharp
public PdfViewOptions(CreateFileStream createFileStream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| createFileStream | CreateFileStream | The method that instantiates stream used to write output file data. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | Thrown when *createFileStream* is null. |

### Remarks

For the code example, see the [documentation](https://docs.groupdocs.com/viewer/net/rendering-to-pdf/).

### See Also

* delegate [CreateFileStream](../../../groupdocs.viewer.interfaces/createfilestream)
* class [PdfViewOptions](../../pdfviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

---

## PdfViewOptions(CreateFileStream, ReleaseFileStream) {#constructor_2}

Initializes an instance of [`PdfViewOptions`](../../pdfviewoptions) class.

```csharp
public PdfViewOptions(CreateFileStream createFileStream, ReleaseFileStream releaseFileStream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| createFileStream | CreateFileStream | The method that instantiates stream used to write output file data. |
| releaseFileStream | ReleaseFileStream | The method that releases stream created by method assigned to delegate that passed to *createFileStream* parameter. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | Thrown when *createFileStream* is null. |
| ArgumentNullException | Thrown when *releaseFileStream* is null. |

### Remarks

For the code example, see the [documentation](https://docs.groupdocs.com/viewer/net/rendering-to-pdf/).

### See Also

* delegate [CreateFileStream](../../../groupdocs.viewer.interfaces/createfilestream)
* delegate [ReleaseFileStream](../../../groupdocs.viewer.interfaces/releasefilestream)
* class [PdfViewOptions](../../pdfviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

---

## PdfViewOptions(IFileStreamFactory) {#constructor_3}

Initializes an instance of [`PdfViewOptions`](../../pdfviewoptions) class.

```csharp
public PdfViewOptions(IFileStreamFactory fileStreamFactory)
```

| Parameter | Type | Description |
| --- | --- | --- |
| fileStreamFactory | IFileStreamFactory | The factory which implements methods for creating and releasing output file stream. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | Thrown when *fileStreamFactory* is null. |

### Remarks

For the code example, see the [documentation](https://docs.groupdocs.com/viewer/net/rendering-to-pdf/).

### See Also

* interface [IFileStreamFactory](../../../groupdocs.viewer.interfaces/ifilestreamfactory)
* class [PdfViewOptions](../../pdfviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

---

## PdfViewOptions() {#constructor}

Initializes an instance of [`PdfViewOptions`](../../pdfviewoptions) class.

```csharp
public PdfViewOptions()
```

### Remarks

This constructor Initializes an instance of [`PdfViewOptions`](../../pdfviewoptions) with "output.pdf" as file path format for the output file. The output file will be placed into current working directory of the application.

For the code example, see the [documentation](https://docs.groupdocs.com/viewer/net/rendering-to-pdf/).

### See Also

* class [PdfViewOptions](../../pdfviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

---

## PdfViewOptions(string) {#constructor_4}

Initializes an instance of [`PdfViewOptions`](../../pdfviewoptions) class.

```csharp
public PdfViewOptions(string outputFilePath)
```

| Parameter | Type | Description |
| --- | --- | --- |
| outputFilePath | String | The path for output PDF file. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | Thrown when *outputFilePath* is null or empty. |

### Remarks

For the code example, see the [documentation](https://docs.groupdocs.com/viewer/net/rendering-to-pdf/).

### See Also

* class [PdfViewOptions](../../pdfviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.viewer.dll -->
