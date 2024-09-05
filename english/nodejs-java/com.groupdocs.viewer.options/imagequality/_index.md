---
title: ImageQuality
second_title: GroupDocs.Viewer for Node.js via Java API Reference
description: The quality of images in the output HTML contained by the PDF documents.
type: docs
weight: 38
url: /nodejs-java/com.groupdocs.viewer.options/imagequality/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum ImageQuality extends Enum<ImageQuality>
```

The quality of images in the output HTML contained by the PDF documents.

The ImageQuality enum represents the quality of images in the output HTML contained by the PDF documents in the GroupDocs.Viewer component. It provides different levels of image quality that can be used to control the rendering and compression of images in the generated HTML output.

Example usage:

```

 HtmlViewOptions htmlViewOptions = HtmlViewOptions.forEmbeddedResources();
 PdfOptions pdfOptions = htmlViewOptions.getPdfOptions();
 pdfOptions.setImageQuality(ImageQuality.HIGH);

 try (Viewer viewer = new Viewer("document.pdf")) {
     viewer.view(htmlViewOptions);
     // Use the viewer object for further operations
 }
 
```
## Fields

| Field | Description |
| --- | --- |
| [LOW](#LOW) | The acceptable quality and best performance. |
| [MEDIUM](#MEDIUM) | Better quality and slower performance. |
| [HIGH](#HIGH) | The best quality but slow performance. |
## Methods

| Method | Description |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
### LOW {#LOW}
```
public static final ImageQuality LOW
```


The acceptable quality and best performance. This setting prioritizes rendering speed over image quality.

### MEDIUM {#MEDIUM}
```
public static final ImageQuality MEDIUM
```


Better quality and slower performance. This setting provides a balance between image quality and rendering speed.

### HIGH {#HIGH}
```
public static final ImageQuality HIGH
```


The best quality but slow performance. This setting prioritizes image quality over rendering speed.

### values() {#values--}
```
public static ImageQuality[] values()
```




**Returns:**
com.groupdocs.viewer.options.ImageQuality[]
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static ImageQuality valueOf(String name)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String |  |

**Returns:**
[ImageQuality](../../com.groupdocs.viewer.options/imagequality)
