---
title: PdfViewOptions
second_title: GroupDocs.Viewer for Node.js via Java API Reference
description: 
type: docs

url: /nodejs-java/groupdocs.viewer/pdfviewoptions/
---

## PdfViewOptions class

 Provides options for rendering documents into PDF format.
 

## Functions

| Name | Description |
| --- | --- |
| [PdfViewOptions](pdfviewoptions)([CreateFileStream](../createfilestream)) | Initializes new instance of PdfViewOptions class. |
| [PdfViewOptions](pdfviewoptions)([CreateFileStream](../createfilestream), [ReleaseFileStream](../releasefilestream)) | Initializes new instance of PdfViewOptions class. |
| [PdfViewOptions](pdfviewoptions)([FileStreamFactory](../filestreamfactory)) | Initializes new instance of PdfViewOptions class. |
| [PdfViewOptions](pdfviewoptions)() | Initializes new instance of PdfViewOptions class. This function initializes new instance of PdfViewOptions with "output.pdf" as file path format for the output file. The output file will be placed into current working directory of the application. |
| [PdfViewOptions](pdfviewoptions)(String) | Initializes new instance of PdfViewOptions class. |
| [PdfViewOptions](pdfviewoptions)(Path) | Initializes new instance of PdfViewOptions class. |

## Functions

| Name | Description |
| --- | --- |
| [getDocumentSavingCallback](getdocumentsavingcallback)() | Callback to estimate Words or Email document saving progress |
| [getFileStreamFactory](getfilestreamfactory)() |  |
| [getImageHeight](getimageheight)() | The height of an output image in pixels. (When converting single image to HTML only) |
| [getImageMaxHeight](getimagemaxheight)() | Max height of an output image in pixels. (When converting single image to HTML only) |
| [getImageMaxWidth](getimagemaxwidth)() | Max width of an output image in pixels. (When converting single image to HTML only) |
| [getImageWidth](getimagewidth)() | The width of the output image in pixels. (When converting single image to HTML only) |
| [getJpgQuality](getjpgquality)() | The quality of the JPG images contained by output PDF document; Valid values are between 1 and 100; Default value is 90. |
| [getSecurity](getsecurity)() | The output PDF document security options. |
| [setDocumentSavingCallback](setdocumentsavingcallback)(IDocumentSavingCallback) | Callback to estimate Words or Email document saving progress |
| [setImageHeight](setimageheight)(int) | The height of an output image in pixels. (When converting single image to HTML only) |
| [setImageMaxHeight](setimagemaxheight)(int) | Max height of an output image in pixels. (When converting single image to HTML only) |
| [setImageMaxWidth](setimagemaxwidth)(int) | Max width of an output image in pixels. (When converting single image to HTML only) |
| [setImageWidth](setimagewidth)(int) | The width of the output image in pixels. (When converting single image to HTML only) |
| [setJpgQuality](setjpgquality)(int) | The quality of the JPG images contained by output PDF document; Valid values are between 1 and 100; Default value is 90. |
| [setSecurity](setsecurity)([Security](../security)) | The output PDF document security options. |
