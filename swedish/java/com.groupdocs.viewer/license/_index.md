---
title: "License"
second_title: "GroupDocs.Viewer för Java API-referens"
description: "Tillhandahåller metoder för att licensiera komponenten och låsa upp dess fulla funktionalitet."
type: docs
weight: 10
url: /sv/java/com.groupdocs.viewer/license/
---
**Inheritance:**
java.lang.Object
```
public class License
```

Tillhandahåller metoder för att licensiera komponenten och låsa upp dess fulla funktionalitet.


License-klassen låter dig tillämpa en giltig licens på GroupDocs.Viewer-komponenten, vilket gör att du kan använda alla funktioner och ta bort eventuella utvärderingsbegränsningar.


Exempel på användning:

````

 License license = new License();
 license.setLicense("path/to/license/file.lic");
 
````


## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [License()](#License--) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [resetLicense()](#resetLicense--) |  |
|  | [setLicense(InputStream licenseStream)](#setLicense-java.io.InputStream-) | Licensierar komponenten. |
|
|  | [setLicense(Path licensePath)](#setLicense-java.nio.file.Path-) | Licensierar komponenten. |
|
|  | [setLicense(String licensePath)](#setLicense-java.lang.String-) | Licensierar komponenten. |
|
|  | [setLicense(URL licenseUri)](#setLicense-java.net.URL-) | Licensierar komponenten. |
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


Licensierar komponenten.


Följande exempel visar hur man ställer in en licens genom att skicka InputStream för licensfilen.


För mer information om licensiering, se
[GroupDocs Licensing FAQ](../https://purchase.groupdocs.com/faqs/licensing).
Du kan också hitta detaljerad information om GroupDocs.Viewer-licensiering i
[Evaluation Limitations and Licensing](../https://docs.groupdocs.com/display/viewernet/Evaluation+Limitations+and+Licensing+of+GroupDocs.Viewer) documentation.

**Example:**

````

 FileInputStream licenseStream = new FileInputStream("LicenseFile.lic");
 License license = new License();
 license.setLicense(licenseStream);
 
````



**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | licenseStream | java.io.InputStream | Licensströmmen. |
|

### setLicense(Path licensePath) {#setLicense-java.nio.file.Path-}
```
public final void setLicense(Path licensePath)
```


Licensierar komponenten.


Ställer in licensen för komponenten med den angivna licensvägen.


**Note:** This method should be called before using any functionality of the component.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | licensePath | java.nio.file.Path | Licensvägen. |
|

### setLicense(String licensePath) {#setLicense-java.lang.String-}
```
public final void setLicense(String licensePath)
```


Licensierar komponenten.


Denna metod bör anropas innan någon funktionalitet används.


Exempel på användning:

````

 String licensePath = "GroupDocs.Viewer.lic";
 License license = new License();
 license.setLicense(licensePath);
 
````

<br />



**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | licensePath | java.lang.String | Licensvägen eller URL. |
|

### setLicense(URL licenseUri) {#setLicense-java.net.URL-}
```
public void setLicense(URL licenseUri)
```


Licensierar komponenten.


Denna metod bör anropas innan någon funktionalitet används.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | licenseUri | java.net.URL | Licens-URI:n. |
|

### isLicensed() {#isLicensed--}
```
public final boolean isLicensed()
```




**Returns:**
boolean
