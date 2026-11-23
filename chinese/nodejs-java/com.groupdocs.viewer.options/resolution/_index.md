---
title: "Resolution"
second_title: "GroupDocs.Viewer for Node.js via Java API 参考"
description: "提供设置图像输出文档分辨率的选项。"
type: docs
weight: 44
url: /zh/nodejs-java/com.groupdocs.viewer.options/resolution/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum Resolution extends Enum<Resolution>
```

提供设置图像分辨率的选项：输出文档。
## 字段

| 字段 | 描述 |
| --- | --- |
| [DPI_330](#DPI-330) | 适用于高清 (HD) 显示器的良好质量。 |
| [DPI_220](#DPI-220) | 在大多数打印机和屏幕上提供卓越质量。 |
| [DPI_150](#DPI-150) | 适用于网页和投影仪的良好效果。 |
| [DPI_96](#DPI-96) | 适用于网页和投影仪的良好效果。 |
| [DPI_72](#DPI-72) | 默认压缩级别。 |
| [DOCUMENT_RESOLUTION](#DOCUMENT-RESOLUTION) | 默认压缩级别 - 与文档相同。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
| [getValue()](#getValue--) | 质量 DPI。 |
| [getSlidesPicturesResolution()](#getSlidesPicturesResolution--) | 从 options Resolution 类获取 Aspose.Slides 图片的分辨率。 |
### DPI_330 {#DPI-330}
```
public static final Resolution DPI_330
```


适用于高清 (HD) 显示器的良好质量。

### DPI_220 {#DPI-220}
```
public static final Resolution DPI_220
```


在大多数打印机和屏幕上提供卓越质量。

### DPI_150 {#DPI-150}
```
public static final Resolution DPI_150
```


适用于网页和投影仪的良好效果。

### DPI_96 {#DPI-96}
```
public static final Resolution DPI_96
```


适用于网页和投影仪的良好效果。

### DPI_72 {#DPI-72}
```
public static final Resolution DPI_72
```


默认压缩级别。

### DOCUMENT_RESOLUTION {#DOCUMENT-RESOLUTION}
```
public static final Resolution DOCUMENT_RESOLUTION
```


默认压缩级别 - 与文档相同。

### values() {#values--}
```
public static Resolution[] values()
```




**Returns:**
com.groupdocs.viewer.options.Resolution[]
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static Resolution valueOf(String name)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 名称 | java.lang.String |  |

**Returns:**
com.groupdocs.viewer.options.Resolution
### getValue() {#getValue--}
```
public int getValue()
```


质量 DPI。

**Returns:**
int
### getSlidesPicturesResolution() {#getSlidesPicturesResolution--}
```
public int getSlidesPicturesResolution()
```


从 options Resolution 类获取 Aspose.Slides 图片的分辨率。

**Returns:**
int
