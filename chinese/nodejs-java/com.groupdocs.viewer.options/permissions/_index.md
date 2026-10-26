---
title: "Permissions"
second_title: "GroupDocs.Viewer for Node.js via Java API 参考"
description: "定义 PDF 文档权限。"
type: docs
weight: 24
url: /zh/nodejs-java/com.groupdocs.viewer.options/permissions/
---
**Inheritance:**
java.lang.Object
```
public class Permissions
```

定义 PDF 文档权限。

Permissions 类提供表示可在 GroupDocs.Viewer 组件的 PDF 文档上应用的不同权限的常量。这些权限控制对 PDF 文档可执行的操作，例如打印、复制文本、修改批注等。

示例用法：

```

 int permissions = Permissions.DENY_PRINTING | Permissions.DENY_MODIFICATION;
 final Security security = new Security();
 security.setPermissions(permissions);
 final PdfViewOptions pdfViewOptions = new PdfViewOptions();
 pdfViewOptions.setSecurity(security);

 try (Viewer viewer = new Viewer("document.pdf")) {
     viewer.view(pdfViewOptions);
     // Use the viewer object for further operations
 }
 
```
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [Permissions()](#Permissions--) |  |
## 字段

| 字段 | 描述 |
| --- | --- |
| [ALLOW_ALL](#ALLOW-ALL) | 允许打印、修改和数据提取。 |
| [DENY_PRINTING](#DENY-PRINTING) | 禁止打印。 |
| [DENY_MODIFICATION](#DENY-MODIFICATION) | 禁止内容修改、填写表单、添加或修改批注。 |
| [DENY_DATA_EXTRACTION](#DENY-DATA-EXTRACTION) | 禁止提取文本和图形。 |
| [DENY_ALL](#DENY-ALL) | 禁止打印、修改和数据提取。 |
### Permissions() {#Permissions--}
```
public Permissions()
```


### ALLOW_ALL {#ALLOW-ALL}
```
public static final int ALLOW_ALL
```


允许打印、修改和数据提取。

### DENY_PRINTING {#DENY-PRINTING}
```
public static final int DENY_PRINTING
```


禁止打印。

### DENY_MODIFICATION {#DENY-MODIFICATION}
```
public static final int DENY_MODIFICATION
```


禁止内容修改、填写表单、添加或修改批注。

### DENY_DATA_EXTRACTION {#DENY-DATA-EXTRACTION}
```
public static final int DENY_DATA_EXTRACTION
```


禁止提取文本和图形。

### DENY_ALL {#DENY-ALL}
```
public static final int DENY_ALL
```


禁止打印、修改和数据提取。

