---
title: Rotation
second_title: GroupDocs.Viewer for Java API Reference
description: Contains page rotation in degrees clockwise.
type: docs
weight: 43
url: /java/com.groupdocs.viewer.options/rotation/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum Rotation extends Enum<Rotation>
```

Contains page rotation in degrees (clockwise).

The Rotation enum represents different rotation angles for a page in the GroupDocs.Viewer component. It provides a set of predefined rotation options that can be used to specify the rotation angle for rendering a page in various document viewing or conversion scenarios.

Example usage:

```

 PdfViewOptions pdfViewOptions = new PdfViewOptions();

 pdfViewOptions.rotatePage(1, Rotation.ON_90_DEGREE);
 pdfViewOptions.rotatePage(2, Rotation.ON_180_DEGREE);

 try (Viewer viewer = new Viewer("document.docx")) {
     viewer.view(pdfViewOptions);
     // Use the viewer object for further operations
 }
 
```
## Fields

| Field | Description |
| --- | --- |
| [ON_90_DEGREE](#ON-90-DEGREE) | The 90 degree page rotation. |
| [ON_180_DEGREE](#ON-180-DEGREE) | The 180 degree page rotation. |
| [ON_270_DEGREE](#ON-270-DEGREE) | The 270 degree page rotation. |
## Methods

| Method | Description |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
### ON_90_DEGREE {#ON-90-DEGREE}
```
public static final Rotation ON_90_DEGREE
```


The 90 degree page rotation. This rotation represents a 90-degree clockwise rotation of the page.

### ON_180_DEGREE {#ON-180-DEGREE}
```
public static final Rotation ON_180_DEGREE
```


The 180 degree page rotation. This rotation represents a 180-degree clockwise rotation of the page.

### ON_270_DEGREE {#ON-270-DEGREE}
```
public static final Rotation ON_270_DEGREE
```


The 270 degree page rotation. This rotation represents a 270-degree clockwise rotation of the page.

### values() {#values--}
```
public static Rotation[] values()
```




**Returns:**
com.groupdocs.viewer.options.Rotation[]
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static Rotation valueOf(String name)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String |  |

**Returns:**
[Rotation](../../com.groupdocs.viewer.options/rotation)
