---
title: "License"
second_title: "GroupDocs.Viewer for Java API 参考"
description: "提供对组件授权并解锁其全部功能的方法。"
type: docs
weight: 10
url: /zh/java/com.groupdocs.viewer/license/
---
**Inheritance:**
java.lang.Object
```
public class License
```

提供对组件授权并解锁其全部功能的方法。


License 类允许您向 GroupDocs.Viewer 组件应用有效许可证，从而使用所有功能并消除任何评估限制。


示例用法：

````

 License license = new License();
 license.setLicense("path/to/license/file.lic");
 
````


## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [License()](#License--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [resetLicense()](#resetLicense--) |  |
|  | [setLicense(InputStream licenseStream)](#setLicense-java.io.InputStream-) | 为组件授权。 |
|
|  | [setLicense(Path licensePath)](#setLicense-java.nio.file.Path-) | 为组件授权。 |
|
|  | [setLicense(String licensePath)](#setLicense-java.lang.String-) | 为组件授权。 |
|
|  | [setLicense(URL licenseUri)](#setLicense-java.net.URL-) | 为组件授权。 |
|
| [isLicensed()](#isLicensed--) |  |
### License() {#License--}
```
public License()
```


### resetLicense() {#resetLicense--}
```
public static void resetLicense()
```




### setLicense(InputStream licenseStream) {#setLicense-java.io.InputStream-}
```
public final void setLicense(InputStream licenseStream)
```


为组件授权。


以下示例演示如何通过传递许可证文件的 InputStream 来设置许可证。


有关许可的更多信息，请参阅
[GroupDocs Licensing FAQ](../https://purchase.groupdocs.com/faqs/licensing).
您还可以在以下位置找到有关 GroupDocs.Viewer 许可的详细信息
[Evaluation Limitations and Licensing](../https://docs.groupdocs.com/display/viewernet/Evaluation+Limitations+and+Licensing+of+GroupDocs.Viewer) documentation.

**Example:**

````

 FileInputStream licenseStream = new FileInputStream("LicenseFile.lic");
 License license = new License();
 license.setLicense(licenseStream);
 
````



**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | licenseStream | java.io.InputStream | 许可证流。 |
|

### setLicense(Path licensePath) {#setLicense-java.nio.file.Path-}
```
public final void setLicense(Path licensePath)
```


为组件授权。


使用指定的许可证路径为组件设置许可证。


**Note:** This method should be called before using any functionality of the component.


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | licensePath | java.nio.file.Path | 许可证路径。 |
|

### setLicense(String licensePath) {#setLicense-java.lang.String-}
```
public final void setLicense(String licensePath)
```


为组件授权。


在使用任何功能之前应调用此方法。


示例用法：

````

 String licensePath = "GroupDocs.Viewer.lic";
 License license = new License();
 license.setLicense(licensePath);
 
````

<br />



**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | licensePath | java.lang.String | 许可证路径或 URL。 |
|

### setLicense(URL licenseUri) {#setLicense-java.net.URL-}
```
public void setLicense(URL licenseUri)
```


为组件授权。


在使用任何功能之前应调用此方法。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | licenseUri | java.net.URL | 许可证 URI。 |
|

### isLicensed() {#isLicensed--}
```
public final boolean isLicensed()
```




**Returns:**
boolean
