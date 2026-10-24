---
title: "Licence"
second_title: "Référence API de GroupDocs.Viewer pour Java"
description: "Fournit des méthodes pour licencier le composant et débloquer toutes ses fonctionnalités."
type: docs
weight: 10
url: /fr/java/com.groupdocs.viewer/license/
---
**Inheritance:**
java.lang.Object
```
public class License
```

Fournit des méthodes pour licencier le composant et débloquer toutes ses fonctionnalités.


La classe Licence vous permet d'appliquer une licence valide au composant GroupDocs.Viewer, vous permettant d'utiliser toutes les fonctionnalités et de supprimer toutes les limitations d'évaluation.


Exemple d'utilisation :

````

 License license = new License();
 license.setLicense("path/to/license/file.lic");
 
````


## Constructeurs

| Constructeur | Description |
| --- | --- |
| [License()](#License--) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
| [resetLicense()](#resetLicense--) |  |
|  | [setLicense(InputStream licenseStream)](#setLicense-java.io.InputStream-) | Licence le composant. |
|
|  | [setLicense(Path licensePath)](#setLicense-java.nio.file.Path-) | Licence le composant. |
|
|  | [setLicense(String licensePath)](#setLicense-java.lang.String-) | Licence le composant. |
|
|  | [setLicense(URL licenseUri)](#setLicense-java.net.URL-) | Licence le composant. |
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


Licence le composant.


L'exemple suivant montre comment définir une licence en passant un InputStream du fichier de licence.


Pour plus d'informations sur la licence, veuillez vous référer au
[GroupDocs Licensing FAQ](../https://purchase.groupdocs.com/faqs/licensing).
Vous pouvez également trouver des informations détaillées sur la licence de GroupDocs.Viewer dans le
[Evaluation Limitations and Licensing](../https://docs.groupdocs.com/display/viewernet/Evaluation+Limitations+and+Licensing+of+GroupDocs.Viewer) documentation.

**Example:**

````

 FileInputStream licenseStream = new FileInputStream("LicenseFile.lic");
 License license = new License();
 license.setLicense(licenseStream);
 
````



**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | licenseStream | java.io.InputStream | Le flux de licence. |
|

### setLicense(Path licensePath) {#setLicense-java.nio.file.Path-}
```
public final void setLicense(Path licensePath)
```


Licence le composant.


Définit la licence pour le composant en utilisant le chemin de licence spécifié.


**Note:** This method should be called before using any functionality of the component.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | licensePath | java.nio.file.Path | Le chemin de licence. |
|

### setLicense(String licensePath) {#setLicense-java.lang.String-}
```
public final void setLicense(String licensePath)
```


Licence le composant.


Cette méthode doit être appelée avant d'utiliser toute fonctionnalité.


Exemple d'utilisation :

````

 String licensePath = "GroupDocs.Viewer.lic";
 License license = new License();
 license.setLicense(licensePath);
 
````

<br />



**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | licensePath | java.lang.String | Le chemin de licence ou l'URL. |
|

### setLicense(URL licenseUri) {#setLicense-java.net.URL-}
```
public void setLicense(URL licenseUri)
```


Licence le composant.


Cette méthode doit être appelée avant d'utiliser toute fonctionnalité.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | licenseUri | java.net.URL | L'URI de licence. |
|

### isLicensed() {#isLicensed--}
```
public final boolean isLicensed()
```




**Returns:**
boolean
