---
title: "Rotation"
second_title: "GroupDocs.Viewer for Java API 参考"
description: "包含页面顺时针旋转的角度（度）。"
type: docs
weight: 45
url: /zh/java/com.groupdocs.viewer.options/rotation/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum Rotation extends Enum<Rotation>
```

包含页面旋转角度（顺时针）。


Rotation 枚举表示 GroupDocs.Viewer 组件中页面的不同旋转角度。
它提供了一组预定义的旋转选项，可用于指定旋转角度
用于在各种文档查看或转换场景中渲染页面。


示例用法：

````

 PdfViewOptions pdfViewOptions = new PdfViewOptions();

 pdfViewOptions.rotatePage(1, Rotation.ON_90_DEGREE);
 pdfViewOptions.rotatePage(2, Rotation.ON_180_DEGREE);

 try (Viewer viewer = new Viewer("document.docx")) {
     viewer.view(pdfViewOptions);
     // Use the viewer object for further operations
 }
 
````


## 字段

| 字段 | 描述 |
| --- | --- |
|  | [ON_90_DEGREE](#ON-90-DEGREE) | 90 度页面旋转。 |
|
|  | [ON_180_DEGREE](#ON-180-DEGREE) | 180 度页面旋转。 |
|
|  | [ON_270_DEGREE](#ON-270-DEGREE) | 270 度页面旋转。 |
|
## 方法

| 方法 | 描述 |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
### ON_90_DEGREE {#ON-90-DEGREE}
```
public static final Rotation ON_90_DEGREE
```


90 度页面旋转。
此旋转表示页面顺时针旋转 90 度。


### ON_180_DEGREE {#ON-180-DEGREE}
```
public static final Rotation ON_180_DEGREE
```


180 度页面旋转。
此旋转表示页面顺时针旋转 180 度。


### ON_270_DEGREE {#ON-270-DEGREE}
```
public static final Rotation ON_270_DEGREE
```


270 度页面旋转。
此旋转表示页面顺时针旋转 270 度。


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
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 名称 | java.lang.String |  |

**Returns:**
[Rotation](../../com.groupdocs.viewer.options/rotation)
