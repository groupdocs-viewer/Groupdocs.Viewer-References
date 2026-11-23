---
title: "Security"
second_title: "GroupDocs.Viewer for Java API 参考"
description: "提供 PDF 文档安全选项。"
type: docs
weight: 29
url: /zh/java/com.groupdocs.viewer.options/security/
---
**Inheritance:**
java.lang.Object
```
public class Security
```

提供 PDF 文档安全选项。


Security 类封装了各种可用于应用安全措施的设置和选项。
对 GroupDocs.Viewer 组件中的 PDF 文档。这些选项包括密码保护，
权限，以及其他。
详情请参阅[文档](../https://docs.groupdocs.com/viewer/net/protect-pdf-documents/)。


示例用法：

````

 Security security = new Security();
 security.setDocumentOpenPassword("myPassword");
 security.setPermissions(Permissions.DENY_MODIFICATION);

 final PdfViewOptions pdfViewOptions = new PdfViewOptions();
 pdfViewOptions.setSecurity(security);

 try (Viewer viewer = new Viewer("document.pdf")) {
     viewer.view(pdfViewOptions);
     // Use the viewer object for further operations
 }
 
````


## 构造函数

| 构造函数 | 描述 |
| --- | --- |
|  | [Security()](#Security--) | 初始化一个新的实例 |
Security
类。
|
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getDocumentOpenPassword()](#getDocumentOpenPassword--) | 获取打开 PDF 文档所需的密码。 |
|
|  | [setDocumentOpenPassword(String value)](#setDocumentOpenPassword-java.lang.String-) | 设置打开 PDF 文档所需的密码。 |
|
|  | [getPermissionsPassword()](#getPermissionsPassword--) | 获取更改权限设置所需的密码。 |
|
|  | [setPermissionsPassword(String value)](#setPermissionsPassword-java.lang.String-) | 设置更改权限设置所需的密码。 |
|
|  | [getPermissions()](#getPermissions--) | 获取 PDF 文档的权限，例如打印、修改和数据提取。 |
|
|  | [setPermissions(int value)](#setPermissions-int-) | 设置 PDF 文档的权限，例如打印、修改和数据提取。 |
|
### Security() {#Security--}
```
public Security()
```


初始化一个新的实例
Security
类。


### getDocumentOpenPassword() {#getDocumentOpenPassword--}
```
public final String getDocumentOpenPassword()
```


获取打开 PDF 文档所需的密码。


有关代码示例，请参阅[文档](../https://docs.groupdocs.com/viewer/net/protect-pdf-documents/)。


**Returns:**
java.lang.String - 文档打开密码。

### setDocumentOpenPassword(String value) {#setDocumentOpenPassword-java.lang.String-}
```
public final void setDocumentOpenPassword(String value)
```


设置打开 PDF 文档所需的密码。


有关代码示例，请参阅[文档](../https://docs.groupdocs.com/viewer/net/protect-pdf-documents/)。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 值 | java.lang.String | 文档打开密码。 |
|

### getPermissionsPassword() {#getPermissionsPassword--}
```
public final String getPermissionsPassword()
```


获取更改权限设置所需的密码。


使用权限密码，您可以限制打印、修改和数据提取。
使用权限密码来限制打印、修改和数据提取。有关代码示例，请参阅[文档](../https://docs.groupdocs.com/viewer/net/protect-pdf-documents/)。


**Returns:**
java.lang.String - 权限密码。

### setPermissionsPassword(String value) {#setPermissionsPassword-java.lang.String-}
```
public final void setPermissionsPassword(String value)
```


设置更改权限设置所需的密码。


使用权限密码，您可以限制打印、修改和数据提取。
使用权限密码来限制打印、修改和数据提取。有关代码示例，请参阅[文档](../https://docs.groupdocs.com/viewer/net/protect-pdf-documents/)。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 值 | java.lang.String | 权限密码。 |
|

### getPermissions() {#getPermissions--}
```
public final int getPermissions()
```


获取 PDF 文档的权限，例如打印、修改和数据提取。


有关代码示例，请参阅[文档](../https://docs.groupdocs.com/viewer/net/protect-pdf-documents/)。


**Returns:**
int - PDF 文档权限。

### setPermissions(int value) {#setPermissions-int-}
```
public final void setPermissions(int value)
```


设置 PDF 文档的权限，例如打印、修改和数据提取。


有关代码示例，请参阅[文档](../https://docs.groupdocs.com/viewer/net/protect-pdf-documents/)。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 值 | int | PDF 文档权限。 |
|

