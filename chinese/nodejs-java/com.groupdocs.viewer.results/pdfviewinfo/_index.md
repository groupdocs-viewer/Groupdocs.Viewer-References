---
title: "PdfViewInfo"
second_title: "GroupDocs.Viewer for Node.js via Java API 参考"
description: "表示 PDF 文档的视图信息。"
type: docs
weight: 22
url: /zh/nodejs-java/com.groupdocs.viewer.results/pdfviewinfo/
---
**All Implemented Interfaces:**
[com.groupdocs.viewer.results.ViewInfo](../../com.groupdocs.viewer.results/viewinfo)
```
public interface PdfViewInfo extends ViewInfo
```

表示 PDF 文档的视图信息。

PdfViewInfo 接口定义了在 GroupDocs.Viewer 组件中访问和操作 PDF 文档视图信息的契约。它提供了检索诸如是否允许打印等信息的方法以及其他属性。

示例用法：

```

 try (Viewer viewer = new Viewer("document.pdf")) {
     final PdfViewInfo viewInfo = (PdfViewInfo) viewer.getViewInfo(ViewInfoOptions.forPngView());
     // Use the viewInfo object for further operations
 }
 
```

***Note:** The default implementation of this interface is PdfViewInfoImpl.*
## 方法

| 方法 | 描述 |
| --- | --- |
| [isPrintingAllowed()](#isPrintingAllowed--) | 检查文档是否允许打印。 |
| [setPrintingAllowed(boolean allowPrinting)](#setPrintingAllowed-boolean-) | 设置文档是否允许打印。 |
### isPrintingAllowed() {#isPrintingAllowed--}
```
public abstract boolean isPrintingAllowed()
```


检查文档是否允许打印。

**Returns:**
boolean - 如果允许打印则为 true，否则为 false。
### setPrintingAllowed(boolean allowPrinting) {#setPrintingAllowed-boolean-}
```
public abstract void setPrintingAllowed(boolean allowPrinting)
```


设置文档是否允许打印。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| allowPrinting | boolean | true 表示允许打印，false 表示不允许。 |

