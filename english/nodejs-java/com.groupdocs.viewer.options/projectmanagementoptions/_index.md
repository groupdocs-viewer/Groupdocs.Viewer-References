---
title: ProjectManagementOptions
second_title: GroupDocs.Viewer for Node.js via Java API Reference
description: Provides options for rendering project management files.
type: docs
weight: 25
url: /nodejs-java/com.groupdocs.viewer.options/projectmanagementoptions/
---
**Inheritance:**
java.lang.Object
```
public class ProjectManagementOptions
```

Provides options for rendering project management files.

The ProjectManagementOptions class encapsulates various settings and parameters that can be used to control the rendering of project management files (such as Microsoft Project or similar) in the GroupDocs.Viewer component.

Example usage:

```

 PngViewOptions pngViewOptions = new PngViewOptions();
 ProjectManagementOptions projectManagementOptions = pngViewOptions.getProjectManagementOptions();
 projectManagementOptions.setPageSize(PageSize.A4);
 projectManagementOptions.setStartDate(new Date(2021, 11, 23));

 try (Viewer viewer = new Viewer("document.docx")) {
     viewer.view(pngViewOptions);
     // Use the viewer object for further operations
 }
 
```
## Constructors

| Constructor | Description |
| --- | --- |
| [ProjectManagementOptions()](#ProjectManagementOptions--) | Initializes a new instance of the  ProjectManagementOptions  class. |
## Methods

| Method | Description |
| --- | --- |
| [getPageSize()](#getPageSize--) | Retrieves the output page size. |
| [setPageSize(PageSize value)](#setPageSize-com.groupdocs.viewer.options.PageSize-) | Sets the output page size. |
| [getTimeUnit()](#getTimeUnit--) | Retrieves the time unit. |
| [setTimeUnit(TimeUnit value)](#setTimeUnit-com.groupdocs.viewer.options.TimeUnit-) | Retrieves the time unit. |
| [getStartDate()](#getStartDate--) | Retrieves the start date of the Gantt Chart View to be included in the output. |
| [setStartDate(Date value)](#setStartDate-java.util.Date-) | Sets the start date of the Gantt Chart View to be included in the output. |
| [getEndDate()](#getEndDate--) | Retrieves the end date of the Gantt Chart View to be included in the output. |
| [setEndDate(Date value)](#setEndDate-java.util.Date-) | Sets the end date of the Gantt Chart View to be included in the output. |
### ProjectManagementOptions() {#ProjectManagementOptions--}
```
public ProjectManagementOptions()
```


Initializes a new instance of the  ProjectManagementOptions  class.

### getPageSize() {#getPageSize--}
```
public final PageSize getPageSize()
```


Retrieves the output page size.

**Returns:**
[PageSize](../../com.groupdocs.viewer.options/pagesize) - the output page size.
### setPageSize(PageSize value) {#setPageSize-com.groupdocs.viewer.options.PageSize-}
```
public final void setPageSize(PageSize value)
```


Sets the output page size.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [PageSize](../../com.groupdocs.viewer.options/pagesize) | The output page size. |

### getTimeUnit() {#getTimeUnit--}
```
public final TimeUnit getTimeUnit()
```


Retrieves the time unit.

**Returns:**
[TimeUnit](../../com.groupdocs.viewer.options/timeunit) - the time unit.
### setTimeUnit(TimeUnit value) {#setTimeUnit-com.groupdocs.viewer.options.TimeUnit-}
```
public final void setTimeUnit(TimeUnit value)
```


Retrieves the time unit.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [TimeUnit](../../com.groupdocs.viewer.options/timeunit) | The time unit. |

### getStartDate() {#getStartDate--}
```
public final Date getStartDate()
```


Retrieves the start date of the Gantt Chart View to be included in the output.

***Note:** Use this option when you need to render a specific time interval of the project within the Gantt Chart View.*

**Returns:**
java.util.Date - the start date of the Gantt Chart View.
### setStartDate(Date value) {#setStartDate-java.util.Date-}
```
public final void setStartDate(Date value)
```


Sets the start date of the Gantt Chart View to be included in the output.

***Note:** Use this option when you need to render a specific time interval of the project within the Gantt Chart View.*

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.Date | The start date of the Gantt Chart View. |

### getEndDate() {#getEndDate--}
```
public final Date getEndDate()
```


Retrieves the end date of the Gantt Chart View to be included in the output.

***Note:** Use this option when you need to render a specific time interval of the project within the Gantt Chart View.*

**Returns:**
java.util.Date - the end date of the Gantt Chart View.
### setEndDate(Date value) {#setEndDate-java.util.Date-}
```
public final void setEndDate(Date value)
```


Sets the end date of the Gantt Chart View to be included in the output.

***Note:** Use this option when you need to render a specific time interval of the project within the Gantt Chart View.*

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.Date | The end date of the Gantt Chart View. |

