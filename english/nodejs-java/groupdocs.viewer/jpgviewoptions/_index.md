---
title: JpgViewOptions
second_title: GroupDocs.Viewer for Node.js via Java API Reference
description: 
type: docs

url: /nodejs-java/groupdocs.viewer/jpgviewoptions/
---

## JpgViewOptions class

 Provides options for rendering documents into JPG format.
 
| [JpgViewOptions](jpgviewoptions)([CreatePageStream](../createpagestream)) | Initializes new instance of JpgViewOptions class. |
| [JpgViewOptions](jpgviewoptions)([CreatePageStream](../createpagestream), [ReleasePageStream](../releasepagestream)) | Initializes new instance of JpgViewOptions class. |
| [JpgViewOptions](jpgviewoptions)([PageStreamFactory](../pagestreamfactory)) | Initializes new instance of JpgViewOptions class. |
| [JpgViewOptions](jpgviewoptions)() | Initializes new instance of JpgViewOptions class. This function initializes new instance of JpgViewOptions with "p_{0}.jpg" as file path format for the output files. The output files will be placed into current working directory of the application. |
| [JpgViewOptions](jpgviewoptions)(String) | Initializes new instance of JpgViewOptions class. |
| [JpgViewOptions](jpgviewoptions)(Path) | Initializes new instance of JpgViewOptions class. |

## Functions

| Name | Description |
| --- | --- |
| [getDocumentSavingCallback](getdocumentsavingcallback)() | Callback to estimate Words or Email document saving progress |
| [getHeight](getheight)() | The height of an output image in pixels. |
| [getMaxHeight](getmaxheight)() | Max height of an output image in pixels. |
| [getMaxWidth](getmaxwidth)() | Max width of an output image in pixels. |
| [getPageStreamFactory](getpagestreamfactory)() | The factory which implements functions for creating and releasing output page stream. |
| [getQuality](getquality)() | Quality of the output image; Valid values are between 1 and 100; Default value is 90. |
| [getWidth](getwidth)() | The width of the output image in pixels. |
| [isExtractText](isextracttext)() | Enables text extraction. This option might be useful when you want to add selectable text layer over the image. |
| [setDocumentSavingCallback](setdocumentsavingcallback)(IDocumentSavingCallback) | Callback to estimate Words or Email document saving progress |
| [setExtractText](setextracttext)(boolean) | Enables text extraction. This option might be useful when you want to add selectable text layer over the image. |
| [setHeight](setheight)(int) | The height of an output image in pixels. |
| [setMaxHeight](setmaxheight)(int) | Max height of an output image in pixels. |
| [setMaxWidth](setmaxwidth)(int) | Max width of an output image in pixels. |
| [setQuality](setquality)(int) | Quality of the output image; Valid values are between 1 and 100; Default value is 90. |
| [setWidth](setwidth)(int) | The width of the output image in pixels. |
