---
title: ProjectManagementViewInfo
second_title: GroupDocs.Viewer for Node.js via Java API Reference
description: Represents view information for an MS Project document.
type: docs
weight: 23
url: /nodejs-java/com.groupdocs.viewer.results/projectmanagementviewinfo/
---
**All Implemented Interfaces:**
[com.groupdocs.viewer.results.ViewInfo](../../com.groupdocs.viewer.results/viewinfo)
```
public interface ProjectManagementViewInfo extends ViewInfo
```

Represents view information for an MS Project document.

The ProjectManagementViewInfo interface defines the contract for accessing and manipulating view information for an MS Project document in the GroupDocs.Viewer component. It provides methods to retrieve information such as the start and end dates, and other properties.

Example usage:

```

 try (Viewer viewer = new Viewer("document.mpp")) {
     final ProjectManagementViewInfo viewInfo = (ProjectManagementViewInfo) viewer.getViewInfo(ViewInfoOptions.forPngView());
     // Use the viewInfo object for further operations
 }
 
```

***Note:** The default implementation of this interface is ProjectManagementViewInfoImpl.*
## Methods

| Method | Description |
| --- | --- |
| [getStartDate()](#getStartDate--) | Retrieves the date and time from which the project started. |
| [getEndDate()](#getEndDate--) | Retrieves the date and time when the project is to be completed. |
### getStartDate() {#getStartDate--}
```
public abstract Date getStartDate()
```


Retrieves the date and time from which the project started.

**Returns:**
java.util.Date - the start date and time of the project.
### getEndDate() {#getEndDate--}
```
public abstract Date getEndDate()
```


Retrieves the date and time when the project is to be completed.

**Returns:**
java.util.Date - the end date and time of the project.
