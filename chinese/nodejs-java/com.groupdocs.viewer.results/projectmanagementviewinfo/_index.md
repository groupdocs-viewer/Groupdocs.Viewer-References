---
title: "ProjectManagementViewInfo"
second_title: "GroupDocs.Viewer for Node.js via Java API 参考"
description: "表示 MS Project 文档的视图信息。"
type: docs
weight: 23
url: /zh/nodejs-java/com.groupdocs.viewer.results/projectmanagementviewinfo/
---
**All Implemented Interfaces:**
[com.groupdocs.viewer.results.ViewInfo](../../com.groupdocs.viewer.results/viewinfo)
```
public interface ProjectManagementViewInfo extends ViewInfo
```

表示 MS Project 文档的视图信息。

ProjectManagementViewInfo 接口定义了在 GroupDocs.Viewer 组件中访问和操作 MS Project 文档视图信息的契约。它提供了检索诸如开始和结束日期等信息以及其他属性的方法。

示例用法：

```

 try (Viewer viewer = new Viewer("document.mpp")) {
     final ProjectManagementViewInfo viewInfo = (ProjectManagementViewInfo) viewer.getViewInfo(ViewInfoOptions.forPngView());
     // Use the viewInfo object for further operations
 }
 
```

***Note:** The default implementation of this interface is ProjectManagementViewInfoImpl.*
## 方法

| 方法 | 描述 |
| --- | --- |
| [getStartDate()](#getStartDate--) | 检索项目开始的日期和时间。 |
| [setStartDate(Date startDate)](#setStartDate-java.util.Date-) | 设置项目的开始日期和时间。 |
| [getEndDate()](#getEndDate--) | 检索项目完成的日期和时间。 |
| [setEndDate(Date endDate)](#setEndDate-java.util.Date-) | 设置项目的结束日期和时间。 |
### getStartDate() {#getStartDate--}
```
public abstract Date getStartDate()
```


检索项目开始的日期和时间。

**Returns:**
java.util.Date - 项目的开始日期和时间。
### setStartDate(Date startDate) {#setStartDate-java.util.Date-}
```
public abstract void setStartDate(Date startDate)
```


设置项目的开始日期和时间。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| startDate | java.util.Date | 要设置的新开始日期和时间。 |

### getEndDate() {#getEndDate--}
```
public abstract Date getEndDate()
```


检索项目完成的日期和时间。

**Returns:**
java.util.Date - 项目的结束日期和时间。
### setEndDate(Date endDate) {#setEndDate-java.util.Date-}
```
public abstract void setEndDate(Date endDate)
```


设置项目的结束日期和时间。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| endDate | java.util.Date | 要设置的新结束日期和时间。 |

