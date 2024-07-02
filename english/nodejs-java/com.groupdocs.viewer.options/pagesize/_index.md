---
title: PageSize
second_title: GroupDocs.Viewer for Node.js via Java API Reference
description: The size of the page.
type: docs
weight: 39
url: /nodejs-java/com.groupdocs.viewer.options/pagesize/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum PageSize extends Enum<PageSize>
```

The size of the page.

The PageSize enum represents different page sizes in the GroupDocs.Viewer component. It provides a set of predefined page sizes that can be used to specify the dimensions of a page in various document rendering scenarios.

Example usage:

```

 HtmlViewOptions htmlViewOptions = HtmlViewOptions.forEmbeddedResources();
 ProjectManagementOptions projectManagementOptions = htmlViewOptions.getProjectManagementOptions();
 projectManagementOptions.setPageSize(PageSize.A4);

 try (Viewer viewer = new Viewer("document.mpp")) {
     viewer.view(htmlViewOptions);
     // Use the viewer object for further operations
 }
 
```
## Fields

| Field | Description |
| --- | --- |
| [UNSPECIFIED](#UNSPECIFIED) | The default, unspecified page size. |
| [LETTER](#LETTER) | The size of the Letter page in points is 792 x 612. |
| [LEDGER](#LEDGER) | The size of the A0 page in points is 3371 x 2384. |
| [A0](#A0) | The size of the A1 page in points is 2384 x 1685. |
| [A1](#A1) | The size of the A2 page in points is 1684 x 1190. |
| [A2](#A2) | The size of the A3 page in points is 1190 x 842. |
| [A3](#A3) | The size of the A3 page in points is 1190 x 842. |
| [A4](#A4) | The size of the A4 page in points is 842 x 595. |
## Methods

| Method | Description |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
### UNSPECIFIED {#UNSPECIFIED}
```
public static final PageSize UNSPECIFIED
```


The default, unspecified page size. This size is used when no specific page size is specified.

### LETTER {#LETTER}
```
public static final PageSize LETTER
```


The size of the Letter page in points is 792 x 612. This page size is commonly used for letters and documents in North America.

### LEDGER {#LEDGER}
```
public static final PageSize LEDGER
```


The size of the A0 page in points is 3371 x 2384. This large page size is part of the ISO 216 international standard.

### A0 {#A0}
```
public static final PageSize A0
```


The size of the A1 page in points is 2384 x 1685. This page size is part of the ISO 216 international standard.

### A1 {#A1}
```
public static final PageSize A1
```


The size of the A2 page in points is 1684 x 1190. This page size is part of the ISO 216 international standard.

### A2 {#A2}
```
public static final PageSize A2
```


The size of the A3 page in points is 1190 x 842. This page size is part of the ISO 216 international standard.

### A3 {#A3}
```
public static final PageSize A3
```


The size of the A3 page in points is 1190 x 842. This page size is part of the ISO 216 international standard.

### A4 {#A4}
```
public static final PageSize A4
```


The size of the A4 page in points is 842 x 595. This page size is part of the ISO 216 international standard.

### values() {#values--}
```
public static PageSize[] values()
```




**Returns:**
com.groupdocs.viewer.options.PageSize[]
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static PageSize valueOf(String name)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String |  |

**Returns:**
[PageSize](../../com.groupdocs.viewer.options/pagesize)
