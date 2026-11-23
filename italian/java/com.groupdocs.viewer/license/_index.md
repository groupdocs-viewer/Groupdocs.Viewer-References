---
title: "Licenza"
second_title: "Riferimento API di GroupDocs.Viewer per Java"
description: "Fornisce metodi per licenziare il componente e sbloccare tutte le sue funzionalità."
type: docs
weight: 10
url: /it/java/com.groupdocs.viewer/license/
---
**Inheritance:**
java.lang.Object
```
public class License
```

Fornisce metodi per licenziare il componente e sbloccare tutte le sue funzionalità.


La classe Licenza consente di applicare una licenza valida al componente GroupDocs.Viewer, permettendo di utilizzare tutte le funzionalità e rimuovere eventuali limitazioni di valutazione.


Esempio di utilizzo:

````

 License license = new License();
 license.setLicense("path/to/license/file.lic");
 
````


## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [License()](#License--) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [resetLicense()](#resetLicense--) |  |
|  | [setLicense(InputStream licenseStream)](#setLicense-java.io.InputStream-) | Licenzia il componente. |
|
|  | [setLicense(Path licensePath)](#setLicense-java.nio.file.Path-) | Licenzia il componente. |
|
|  | [setLicense(String licensePath)](#setLicense-java.lang.String-) | Licenzia il componente. |
|
|  | [setLicense(URL licenseUri)](#setLicense-java.net.URL-) | Licenzia il componente. |
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


Licenzia il componente.


Il seguente esempio dimostra come impostare una licenza passando l'InputStream del file di licenza.


Per ulteriori informazioni sulla licenza, fare riferimento al
[GroupDocs Licensing FAQ](../https://purchase.groupdocs.com/faqs/licensing).
È possibile trovare anche informazioni dettagliate sulla licenza di GroupDocs.Viewer nella
[Evaluation Limitations and Licensing](../https://docs.groupdocs.com/display/viewernet/Evaluation+Limitations+and+Licensing+of+GroupDocs.Viewer) documentation.

**Example:**

````

 FileInputStream licenseStream = new FileInputStream("LicenseFile.lic");
 License license = new License();
 license.setLicense(licenseStream);
 
````



**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | licenseStream | java.io.InputStream | Lo stream della licenza. |
|

### setLicense(Path licensePath) {#setLicense-java.nio.file.Path-}
```
public final void setLicense(Path licensePath)
```


Licenzia il componente.


Imposta la licenza per il componente utilizzando il percorso della licenza specificato.


**Note:** This method should be called before using any functionality of the component.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | licensePath | java.nio.file.Path | Il percorso della licenza. |
|

### setLicense(String licensePath) {#setLicense-java.lang.String-}
```
public final void setLicense(String licensePath)
```


Licenzia il componente.


Questo metodo dovrebbe essere chiamato prima di utilizzare qualsiasi funzionalità.


Esempio di utilizzo:

````

 String licensePath = "GroupDocs.Viewer.lic";
 License license = new License();
 license.setLicense(licensePath);
 
````

<br />



**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | licensePath | java.lang.String | Il percorso o l'URL della licenza. |
|

### setLicense(URL licenseUri) {#setLicense-java.net.URL-}
```
public void setLicense(URL licenseUri)
```


Licenzia il componente.


Questo metodo dovrebbe essere chiamato prima di utilizzare qualsiasi funzionalità.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | licenseUri | java.net.URL | L'URI della licenza. |
|

### isLicensed() {#isLicensed--}
```
public final boolean isLicensed()
```




**Returns:**
boolean
