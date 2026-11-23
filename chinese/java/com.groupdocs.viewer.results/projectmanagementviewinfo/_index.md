---
title: "ProjectManagementViewInfo"
second_title: "GroupDocs.Viewer for Java API 参考"
description: "表示 MS Project 文档的视图信息。"
type: docs
weight: 25
url: /zh/java/com.groupdocs.viewer.results/projectmanagementviewinfo/
---
**All Implemented Interfaces:**
[com.groupdocs.viewer.results.ViewInfo](../../com.groupdocs.viewer.results/viewinfo)
```
public interface ProjectManagementViewInfo extends ViewInfo
```

表示 MS Project 文档的视图信息。


ProjectManagementViewInfo 接口定义了访问和操作视图信息的契约
用于 GroupDocs.Viewer 组件中的 MS Project 文档。它提供检索信息的方法
例如开始和结束日期以及其他属性。


示例用法：

````

 try (Viewer viewer = new Viewer("document.mpp")) {
     final ProjectManagementViewInfo viewInfo = (ProjectManagementViewInfo) viewer.getViewInfo(ViewInfoOptions.forPngView());
     // Use the viewInfo object for further operations
 }
 
````


***Note:** The default implementation of this interface is ProjectManagementViewInfoImpl.*

## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getStartDate()](#getStartDate--) | 检索项目开始的日期和时间。 |
|
|  | [setStartDate(Date startDate)](#setStartDate-java.util.Date-) | 设置项目的开始日期和时间。 |
|
|  | [getEndDate()](#getEndDate--) | 检索项目完成的日期和时间。 |
|
|  | [setEndDate(Date endDate)](#setEndDate-java.util.Date-) | 设置项目的结束日期和时间。 |
|
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
|  | startDate | java.util.Date | 要设置的新开始日期和时间。 |
|

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
|  | endDate | java.util.Date | 要设置的新结束日期和时间。 |
|

