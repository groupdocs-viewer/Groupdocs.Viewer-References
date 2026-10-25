---
title: "Licencia"
second_title: "GroupDocs.Viewer for Java Referencia de API"
description: "Proporciona métodos para licenciar el componente y desbloquear su funcionalidad completa."
type: docs
weight: 10
url: /es/java/com.groupdocs.viewer/license/
---
**Inheritance:**
java.lang.Object
```
public class License
```

Proporciona métodos para licenciar el componente y desbloquear su funcionalidad completa.


La clase Licencia le permite aplicar una licencia válida al componente GroupDocs.Viewer, habilitando el uso de todas las funciones y eliminando cualquier limitación de evaluación.


Ejemplo de uso:

````

 License license = new License();
 license.setLicense("path/to/license/file.lic");
 
````


## Constructores

| Constructor | Descripción |
| --- | --- |
| [License()](#License--) |  |
## Métodos

| Método | Descripción |
| --- | --- |
| [resetLicense()](#resetLicense--) |  |
|  | [setLicense(InputStream licenseStream)](#setLicense-java.io.InputStream-) | Licencia el componente. |
|
|  | [setLicense(Path licensePath)](#setLicense-java.nio.file.Path-) | Licencia el componente. |
|
|  | [setLicense(String licensePath)](#setLicense-java.lang.String-) | Licencia el componente. |
|
|  | [setLicense(URL licenseUri)](#setLicense-java.net.URL-) | Licencia el componente. |
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


Licencia el componente.


El siguiente ejemplo muestra cómo establecer una licencia pasando InputStream del archivo de licencia.


Para obtener más información sobre licencias, consulte el
[GroupDocs Licensing FAQ](../https://purchase.groupdocs.com/faqs/licensing).
También puede encontrar información detallada sobre la licencia de GroupDocs.Viewer en el
[Evaluation Limitations and Licensing](../https://docs.groupdocs.com/display/viewernet/Evaluation+Limitations+and+Licensing+of+GroupDocs.Viewer) documentation.

**Example:**

````

 FileInputStream licenseStream = new FileInputStream("LicenseFile.lic");
 License license = new License();
 license.setLicense(licenseStream);
 
````



**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | licenseStream | java.io.InputStream | El flujo de licencia. |
|

### setLicense(Path licensePath) {#setLicense-java.nio.file.Path-}
```
public final void setLicense(Path licensePath)
```


Licencia el componente.


Establece la licencia para el componente usando la ruta de licencia especificada.


**Note:** This method should be called before using any functionality of the component.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | licensePath | java.nio.file.Path | La ruta de licencia. |
|

### setLicense(String licensePath) {#setLicense-java.lang.String-}
```
public final void setLicense(String licensePath)
```


Licencia el componente.


Este método debe llamarse antes de usar cualquier funcionalidad.


Ejemplo de uso:

````

 String licensePath = "GroupDocs.Viewer.lic";
 License license = new License();
 license.setLicense(licensePath);
 
````

<br />



**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | licensePath | java.lang.String | La ruta de licencia o url. |
|

### setLicense(URL licenseUri) {#setLicense-java.net.URL-}
```
public void setLicense(URL licenseUri)
```


Licencia el componente.


Este método debe llamarse antes de usar cualquier funcionalidad.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | licenseUri | java.net.URL | El URI de licencia. |
|

### isLicensed() {#isLicensed--}
```
public final boolean isLicensed()
```




**Returns:**
boolean
