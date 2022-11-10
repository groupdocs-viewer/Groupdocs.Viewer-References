---
title: ProjectManagementViewInfo
second_title: GroupDocs.Viewer for Java API Reference
description: Represents view information for MS Project document.
type: docs
weight: 23
url: /java/com.groupdocs.viewer.results/projectmanagementviewinfo/
---
**All Implemented Interfaces:**
[com.groupdocs.viewer.results.ViewInfo](../../com.groupdocs.viewer.results/viewinfo)
```
public interface ProjectManagementViewInfo extends ViewInfo
```

Represents view information for MS Project document. Default implementation is ProjectManagementViewInfoImpl
## Methods

| Method | Description |
| --- | --- |
| [getStartDate()](#getStartDate--) | The date time from which the project started. |
| [getEndDate()](#getEndDate--) | The date time when the project is to be completed. |
### getStartDate() {#getStartDate--}
```
public abstract Date getStartDate()
```


The date time from which the project started.

**Returns:**
java.util.Date
### getEndDate() {#getEndDate--}
```
public abstract Date getEndDate()
```


The date time when the project is to be completed.

**Returns:**
java.util.Date
