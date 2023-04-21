---
title: License
second_title: GroupDocs.Viewer for Java API Reference
description: Provides methods to license the component.
type: docs
weight: 10
url: /java/com.groupdocs.viewer/license/
---
**Inheritance:**
java.lang.Object
```
public class License
```

Provides methods to license the component. Learn more about licensing [here][].


[here]: https://purchase.groupdocs.com/faqs/licensing
## Constructors

| Constructor | Description |
| --- | --- |
| [License()](#License--) |  |
## Methods

| Method | Description |
| --- | --- |
| [resetLicense()](#resetLicense--) |  |
| [setLicense(InputStream licenseStream)](#setLicense-java.io.InputStream-) | Licenses the component. |
| [setLicense(Path licensePath)](#setLicense-java.nio.file.Path-) | Licenses the component. |
| [setLicense(String licensePath)](#setLicense-java.lang.String-) | Licenses the component. |
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


Licenses the component.

***Note:** 
The following example demonstrates how to set a license passing InputStream of the license file. More about licensing: [GroupDocs Licensing FAQ][] More about GroupDocs.Viewer licensing: [Evaluation Limitations and Licensing][]*

**Example:** 


```

 FileInputStream licenseStream = new FileInputStream("LicenseFile.lic");
 License license = new License();
 license.setLicense(licenseStream);
 
```


[GroupDocs Licensing FAQ]: https://purchase.groupdocs.com/faqs/licensing
[Evaluation Limitations and Licensing]: https://docs.groupdocs.com/display/viewernet/Evaluation+Limitations+and+Licensing+of+GroupDocs.Viewer

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| licenseStream | java.io.InputStream | The license stream. |

### setLicense(Path licensePath) {#setLicense-java.nio.file.Path-}
```
public final void setLicense(Path licensePath)
```


Licenses the component.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| licensePath | java.nio.file.Path | The license path. |

### setLicense(String licensePath) {#setLicense-java.lang.String-}
```
public final void setLicense(String licensePath)
```


Licenses the component.

**Example:** 
The following example demonstrates how to set a license passing a path or url to the license file.

```

 String licensePath = "GroupDocs.Viewer.lic";
 License license = new License();
 license.setLicense(licensePath);
 
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| licensePath | java.lang.String | The license file path or url. |

