---
title: "Licentie"
second_title: "GroupDocs.Viewer for Java API-referentie"
description: "Biedt methoden om de component te licentiëren en de volledige functionaliteit te ontgrendelen."
type: docs
weight: 10
url: /nl/java/com.groupdocs.viewer/license/
---
**Inheritance:**
java.lang.Object
```
public class License
```

Biedt methoden om de component te licentiëren en de volledige functionaliteit te ontgrendelen.


De Licentie‑klasse stelt je in staat een geldige licentie toe te passen op de GroupDocs.Viewer‑component, waardoor je alle functies kunt gebruiken en eventuele evaluatiebeperkingen kunt verwijderen.


Voorbeeldgebruik:

````

 License license = new License();
 license.setLicense("path/to/license/file.lic");
 
````


## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [License()](#License--) |  |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [resetLicense()](#resetLicense--) |  |
|  | [setLicense(InputStream licenseStream)](#setLicense-java.io.InputStream-) | Licentieert de component. |
|
|  | [setLicense(Path licensePath)](#setLicense-java.nio.file.Path-) | Licentieert de component. |
|
|  | [setLicense(String licensePath)](#setLicense-java.lang.String-) | Licentieert de component. |
|
|  | [setLicense(URL licenseUri)](#setLicense-java.net.URL-) | Licentieert de component. |
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


Licentieert de component.


Het volgende voorbeeld toont hoe u een licentie instelt door een InputStream van het licentiebestand door te geven.


Voor meer informatie over licenties, raadpleeg de
[GroupDocs Licensing FAQ](../https://purchase.groupdocs.com/faqs/licensing).
U kunt ook gedetailleerde informatie over GroupDocs.Viewer-licenties vinden in de
[Evaluation Limitations and Licensing](../https://docs.groupdocs.com/display/viewernet/Evaluation+Limitations+and+Licensing+of+GroupDocs.Viewer) documentation.

**Example:**

````

 FileInputStream licenseStream = new FileInputStream("LicenseFile.lic");
 License license = new License();
 license.setLicense(licenseStream);
 
````



**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | licenseStream | java.io.InputStream | De licentiestroom. |
|

### setLicense(Path licensePath) {#setLicense-java.nio.file.Path-}
```
public final void setLicense(Path licensePath)
```


Licentieert de component.


Stelt de licentie voor het component in met behulp van het opgegeven licentiepad.


**Note:** This method should be called before using any functionality of the component.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | licensePath | java.nio.file.Path | Het licentiepad. |
|

### setLicense(String licensePath) {#setLicense-java.lang.String-}
```
public final void setLicense(String licensePath)
```


Licentieert de component.


Deze methode moet worden aangeroepen voordat u enige functionaliteit gebruikt.


Voorbeeldgebruik:

````

 String licensePath = "GroupDocs.Viewer.lic";
 License license = new License();
 license.setLicense(licensePath);
 
````

<br />



**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | licensePath | java.lang.String | Het licentiepad of URL. |
|

### setLicense(URL licenseUri) {#setLicense-java.net.URL-}
```
public void setLicense(URL licenseUri)
```


Licentieert de component.


Deze methode moet worden aangeroepen voordat u enige functionaliteit gebruikt.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | licenseUri | java.net.URL | De licentie-URI. |
|

### isLicensed() {#isLicensed--}
```
public final boolean isLicensed()
```




**Returns:**
boolean
