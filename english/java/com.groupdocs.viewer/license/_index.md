---
title: License
second_title: GroupDocs.Viewer for Java API Reference
description: Provides methods to license the component and unlock its full functionality.
type: docs
weight: 10
url: /java/com.groupdocs.viewer/license/
---
**Inheritance:**
java.lang.Object
```
public class License
```

Provides methods to license the component and unlock its full functionality.

The License class allows you to apply a valid license to the GroupDocs.Viewer component, enabling you to utilize all the features and remove any evaluation limitations.

Example usage:

```

 License license = new License();
 license.setLicense("path/to/license/file.lic");
 
```
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
| [setLicense(URL licenseUri)](#setLicense-java.net.URL-) | Licenses the component. |
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

The following example demonstrates how to set a license passing InputStream of the license file.

For more information about licensing, please refer to the [GroupDocs Licensing FAQ][]. You can also find detailed information about GroupDocs.Viewer licensing in the [Evaluation Limitations and Licensing][] documentation.

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

Sets the license for the component using the specified license path.

**Note:** This method should be called before using any functionality of the component.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| licensePath | java.nio.file.Path | The license path. |

### setLicense(String licensePath) {#setLicense-java.lang.String-}
```
public final void setLicense(String licensePath)
```


Licenses the component.

This method should be called before using any functionality.

Example usage:

```

 String licensePath = "GroupDocs.Viewer.lic";
 License license = new License();
 license.setLicense(licensePath);
 
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| licensePath | java.lang.String | The license path or url. |

### setLicense(URL licenseUri) {#setLicense-java.net.URL-}
```
public void setLicense(URL licenseUri)
```


Licenses the component.

This method should be called before using any functionality.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| licenseUri | java.net.URL | The license URI. |

