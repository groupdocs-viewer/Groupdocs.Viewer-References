---
title: "ImageQuality"
second_title: "GroupDocs.Viewer for Java API 参考"
description: "PDF 文档中包含的输出 HTML 的图像质量。"
type: docs
weight: 41
url: /zh/java/com.groupdocs.viewer.options/imagequality/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum ImageQuality extends Enum<ImageQuality>
```

PDF 文档中包含的输出 HTML 的图像质量。


ImageQuality 枚举表示 PDF 文档中输出 HTML 的图像质量
在 GroupDocs.Viewer 组件中。它提供可使用的不同图像质量级别
用于控制生成的 HTML 输出中图像的渲染和压缩。


示例用法：

````

 HtmlViewOptions htmlViewOptions = HtmlViewOptions.forEmbeddedResources();
 PdfOptions pdfOptions = htmlViewOptions.getPdfOptions();
 pdfOptions.setImageQuality(ImageQuality.HIGH);

 try (Viewer viewer = new Viewer("document.pdf")) {
     viewer.view(htmlViewOptions);
     // Use the viewer object for further operations
 }
 
````


## 字段

| 字段 | 描述 |
| --- | --- |
|  | [LOW](#LOW) | 可接受的质量和最佳性能。 |
|
|  | [MEDIUM](#MEDIUM) | 更好的质量和较慢的性能。 |
|
|  | [HIGH](#HIGH) | 最佳质量，但性能较慢。 |
|
## 方法

| 方法 | 描述 |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
### LOW {#LOW}
```
public static final ImageQuality LOW
```


可接受的质量和最佳性能。
此设置优先考虑渲染速度而非图像质量。


### MEDIUM {#MEDIUM}
```
public static final ImageQuality MEDIUM
```


更好的质量和较慢的性能。
此设置在图像质量和渲染速度之间提供平衡。


### HIGH {#HIGH}
```
public static final ImageQuality HIGH
```


最佳质量，但性能较慢。
此设置优先考虑图像质量而非渲染速度。


### values() {#values--}
```
public static ImageQuality[] values()
```




**Returns:**
com.groupdocs.viewer.options.ImageQuality[]
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static ImageQuality valueOf(String name)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 名称 | java.lang.String |  |

**Returns:**
[ImageQuality](../../com.groupdocs.viewer.options/imagequality)
