---
title: PdfViewOptions
second_title: GroupDocs.Viewer for Node.js via Java API Reference
description: 
type: docs

url: /nodejs-java/groupdocs.viewer/pdfviewoptions/pdfviewoptions/
---

## PdfViewOptions([CreateFileStream](../../createfilestream) createFileStream) function
Initializes new instance of  PdfViewOptions class.

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| createFileStream | [CreateFileStream](../../createfilestream) | The method that instantiates stream used to write output file data. |

### Result
PdfViewOptions


---


## PdfViewOptions([CreateFileStream](../../createfilestream) createFileStream, [ReleaseFileStream](../../releasefilestream) releaseFileStream) function
Initializes new instance of  PdfViewOptions class.

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| createFileStream | [CreateFileStream](../createfilestream) | The method that instantiates stream used to write output file data. |
| releaseFileStream | [ReleaseFileStream](../../releasefilestream) | The method that releases stream created by method assigned to delegate that passed to createFileStream parameter. |

### Result
PdfViewOptions


---


## PdfViewOptions([FileStreamFactory](../../filestreamfactory) fileStreamFactory) function

 Initializes new instance of  PdfViewOptions class.
 

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| fileStreamFactory | [FileStreamFactory](../../filestreamfactory) | The factory which implements methods for creating and releasing output file stream. |

### Result
PdfViewOptions

### Error

| Error | Condition |
| --- | --- |
 | IllegalArgumentException | Thrown when {@code fileStreamFactory} is null. |


---


## PdfViewOptions() function

 Initializes new instance of  PdfViewOptions class.
 
 This constructor initializes new instance of  PdfViewOptions
 with "output.pdf" as file path format for the output file.
 The output file will be placed into current working directory of the application.
 

### Result
PdfViewOptions


---


## PdfViewOptions(String outputFilePath) function

 Initializes new instance of  PdfViewOptions class.
 

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| outputFilePath | String | The path for output PDF file. |

### Result
PdfViewOptions

### Error

| Error | Condition |
| --- | --- |
 | IllegalArgumentException | Thrown when {@code outputFilePath} is null or empty. |


---


## PdfViewOptions(Path outputFilePath) function

 Initializes new instance of  PdfViewOptions class.
 

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| outputFilePath | Path | The path for output PDF file. |

### Result
PdfViewOptions

### Error

| Error | Condition |
| --- | --- |
 | IllegalArgumentException | Thrown when {@code outputFilePath} is null or empty. |


---


