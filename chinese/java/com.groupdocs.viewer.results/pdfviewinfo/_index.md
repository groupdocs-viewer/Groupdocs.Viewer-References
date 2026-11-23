---
title: "PdfViewInfo"
second_title: "GroupDocs.Viewer for Java API 参考"
description: "表示 PDF 文档的视图信息。"
type: docs
weight: 24
url: /zh/java/com.groupdocs.viewer.results/pdfviewinfo/
---
**All Implemented Interfaces:**
[com.groupdocs.viewer.results.ViewInfo](../../com.groupdocs.viewer.results/viewinfo)
```
public interface PdfViewInfo extends ViewInfo
```

表示 PDF 文档的视图信息。


PdfViewInfo 接口定义了访问和操作视图信息的契约。
用于 GroupDocs.Viewer 组件中的 PDF 文档。它提供检索信息的方法
例如允许打印以及其他属性。


示例用法：

````

 try (Viewer viewer = new Viewer("document.pdf")) {
     final PdfViewInfo viewInfo = (PdfViewInfo) viewer.getViewInfo(ViewInfoOptions.forPngView());
     // Use the viewInfo object for further operations
 }
 
````


***Note:** The default implementation of this interface is PdfViewInfoImpl.*

## 方法

| 方法 | 描述 |
| --- | --- |
|  | [isPrintingAllowed()](#isPrintingAllowed--) | 检查文档是否允许打印。 |
|
|  | [setPrintingAllowed(boolean allowPrinting)](#setPrintingAllowed-boolean-) | 设置是否允许文档打印。 |
|
### isPrintingAllowed() {#isPrintingAllowed--}
```
public abstract boolean isPrintingAllowed()
```


检查文档是否允许打印。


**Returns:**
boolean -  true  如果允许打印，则为 true，否则为 false。

### setPrintingAllowed(boolean allowPrinting) {#setPrintingAllowed-boolean-}
```
public abstract void setPrintingAllowed(boolean allowPrinting)
```


设置是否允许文档打印。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | allowPrinting | boolean | true  允许打印，  false  否则。 |
|

