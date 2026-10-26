---
title: "ProjectManagementOptions"
second_title: "GroupDocs.Viewer for Node.js via Java API 参考"
description: "提供渲染项目管理文件的选项。"
type: docs
weight: 27
url: /zh/nodejs-java/com.groupdocs.viewer.options/projectmanagementoptions/
---
**Inheritance:**
java.lang.Object
```
public class ProjectManagementOptions
```

提供渲染项目管理文件的选项。

ProjectManagementOptions 类封装了各种设置和参数，可用于控制在 GroupDocs.Viewer 组件中渲染项目管理文件（如 Microsoft Project 或类似文件）。有关详细信息，请参阅[documentation][].

示例用法：

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


[documentation]: https://docs.groupdocs.com/viewer/java/render-ms-project-files/
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [ProjectManagementOptions()](#ProjectManagementOptions--) | 初始化 ProjectManagementOptions 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getPageSize()](#getPageSize--) | 检索输出页面大小。 |
| [setPageSize(PageSize value)](#setPageSize-com.groupdocs.viewer.options.PageSize-) | 设置输出页面大小。 |
| [getTimeUnit()](#getTimeUnit--) | 检索时间单位。 |
| [setTimeUnit(TimeUnit value)](#setTimeUnit-com.groupdocs.viewer.options.TimeUnit-) | 检索时间单位。 |
| [getStartDate()](#getStartDate--) | 检索要包含在输出中的甘特图视图的开始日期。 |
| [setStartDate(Date value)](#setStartDate-java.util.Date-) | 设置要包含在输出中的甘特图视图的开始日期。 |
| [getEndDate()](#getEndDate--) | 检索要包含在输出中的甘特图视图的结束日期。 |
| [setEndDate(Date value)](#setEndDate-java.util.Date-) | 设置要包含在输出中的甘特图视图的结束日期。 |
### ProjectManagementOptions() {#ProjectManagementOptions--}
```
public ProjectManagementOptions()
```


初始化 ProjectManagementOptions 类的新实例。

### getPageSize() {#getPageSize--}
```
public final PageSize getPageSize()
```


检索输出页面大小。

有关代码示例，请参阅[文档][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-ms-project-files/#specify-the-output-page-size

**Returns:**
[PageSize](../../com.groupdocs.viewer.options/pagesize) - the output page size.
### setPageSize(PageSize value) {#setPageSize-com.groupdocs.viewer.options.PageSize-}
```
public final void setPageSize(PageSize value)
```


设置输出页面大小。

有关代码示例，请参阅[文档][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-ms-project-files/#specify-the-output-page-size

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [PageSize](../../com.groupdocs.viewer.options/pagesize) | 输出页面大小。 |

### getTimeUnit() {#getTimeUnit--}
```
public final TimeUnit getTimeUnit()
```


检索时间单位。

有关代码示例，请参阅[文档][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-ms-project-files/#adjust-the-time-unit

**Returns:**
[TimeUnit](../../com.groupdocs.viewer.options/timeunit) - the time unit.
### setTimeUnit(TimeUnit value) {#setTimeUnit-com.groupdocs.viewer.options.TimeUnit-}
```
public final void setTimeUnit(TimeUnit value)
```


检索时间单位。

有关代码示例，请参阅[文档][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-ms-project-files/#adjust-the-time-unit

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [TimeUnit](../../com.groupdocs.viewer.options/timeunit) | 时间单位。 |

### getStartDate() {#getStartDate--}
```
public final Date getStartDate()
```


检索要包含在输出中的甘特图视图的开始日期。

***Note:** Use this option when you need to render a specific time interval of the project within the Gantt Chart View.* For code sample, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-ms-project-files/#render-specific-dates

**Returns:**
java.util.Date - 甘特图视图的开始日期。
### setStartDate(Date value) {#setStartDate-java.util.Date-}
```
public final void setStartDate(Date value)
```


设置要包含在输出中的甘特图视图的开始日期。

***Note:** Use this option when you need to render a specific time interval of the project within the Gantt Chart View.* For code sample, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-ms-project-files/#render-specific-dates

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.util.Date | 甘特图视图的开始日期。 |

### getEndDate() {#getEndDate--}
```
public final Date getEndDate()
```


检索要包含在输出中的甘特图视图的结束日期。

***Note:** Use this option when you need to render a specific time interval of the project within the Gantt Chart View.* For code sample, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-ms-project-files/#render-specific-dates

**Returns:**
java.util.Date - 甘特图视图的结束日期。
### setEndDate(Date value) {#setEndDate-java.util.Date-}
```
public final void setEndDate(Date value)
```


设置要包含在输出中的甘特图视图的结束日期。

***Note:** Use this option when you need to render a specific time interval of the project within the Gantt Chart View.* For code sample, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-ms-project-files/#render-specific-dates

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.util.Date | 甘特图视图的结束日期。 |

