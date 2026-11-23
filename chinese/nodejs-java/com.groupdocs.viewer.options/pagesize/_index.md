---
title: "PageSize"
second_title: "GroupDocs.Viewer for Node.js via Java API 参考"
description: "页面的尺寸。"
type: docs
weight: 42
url: /zh/nodejs-java/com.groupdocs.viewer.options/pagesize/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum PageSize extends Enum<PageSize>
```

页面的尺寸。

PageSize 枚举表示 GroupDocs.Viewer 组件中的不同页面大小。它提供了一组预定义的页面大小，可用于在各种文档渲染场景中指定页面的尺寸。

示例用法：

```

 HtmlViewOptions htmlViewOptions = HtmlViewOptions.forEmbeddedResources();
 ProjectManagementOptions projectManagementOptions = htmlViewOptions.getProjectManagementOptions();
 projectManagementOptions.setPageSize(PageSize.A4);

 try (Viewer viewer = new Viewer("document.mpp")) {
     viewer.view(htmlViewOptions);
     // Use the viewer object for further operations
 }
 
```
## 字段

| 字段 | 描述 |
| --- | --- |
| [UNSPECIFIED](#UNSPECIFIED) | 默认的未指定页面大小。 |
| [LETTER](#LETTER) | Letter 页面在点（points）单位下的尺寸为 792 x 612。 |
| [LEDGER](#LEDGER) | A0 页面在点（points）单位下的尺寸为 3371 x 2384。 |
| [A0](#A0) | A1 页面在点（points）单位下的尺寸为 2384 x 1685。 |
| [A1](#A1) | A2 页面在点（points）单位下的尺寸为 1684 x 1190。 |
| [A2](#A2) | A3 页面在点（points）单位下的尺寸为 1190 x 842。 |
| [A3](#A3) | A3 页面在点（points）单位下的尺寸为 1190 x 842。 |
| [A4](#A4) | A4 页面在点（points）单位下的尺寸为 842 x 595。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
### UNSPECIFIED {#UNSPECIFIED}
```
public static final PageSize UNSPECIFIED
```


默认的、未指定的页面尺寸。当未指定具体页面尺寸时使用此尺寸。

### LETTER {#LETTER}
```
public static final PageSize LETTER
```


Letter 页面在点（points）单位下的尺寸为 792 x 612。此页面尺寸在北美常用于信件和文档。

### LEDGER {#LEDGER}
```
public static final PageSize LEDGER
```


A0 页面在点（points）单位下的尺寸为 3371 x 2384。此大尺寸属于 ISO 216 国际标准。

### A0 {#A0}
```
public static final PageSize A0
```


A1 页面在点（points）单位下的尺寸为 2384 x 1685。此页面尺寸属于 ISO 216 国际标准。

### A1 {#A1}
```
public static final PageSize A1
```


A2 页面在点（points）单位下的尺寸为 1684 x 1190。此页面尺寸属于 ISO 216 国际标准。

### A2 {#A2}
```
public static final PageSize A2
```


A3 页面在点（points）单位下的尺寸为 1190 x 842。此页面尺寸属于 ISO 216 国际标准。

### A3 {#A3}
```
public static final PageSize A3
```


A3 页面在点（points）单位下的尺寸为 1190 x 842。此页面尺寸属于 ISO 216 国际标准。

### A4 {#A4}
```
public static final PageSize A4
```


A4 页面在点（points）单位下的尺寸为 842 x 595。此页面尺寸属于 ISO 216 国际标准。

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
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 名称 | java.lang.String |  |

**Returns:**
[PageSize](../../com.groupdocs.viewer.options/pagesize)
