---
title: "Licenza"
second_title: "GroupDocs.Viewer per Node.js via Java Riferimento API"
description: "Fornisce metodi per licenziare il componente e sbloccare tutte le sue funzionalità."
type: docs
weight: 10
url: /it/nodejs-java/com.groupdocs.viewer/license/
---
**Inheritance:**
java.lang.Object
```
public class License
```

Fornisce metodi per licenziare il componente e sbloccare tutte le sue funzionalità.

La classe Licenza consente di applicare una licenza valida al componente GroupDocs.Viewer, permettendo di utilizzare tutte le funzionalità e rimuovere eventuali limitazioni di valutazione.

Esempio di utilizzo:

```

 License license = new License();
 license.setLicense("path/to/license/file.lic");
 
```
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [License()](#License--) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [resetLicense()](#resetLicense--) |  |
| [setLicense(InputStream licenseStream)](#setLicense-java.io.InputStream-) | Concede licenza al componente. |
| [setLicense(Path licensePath)](#setLicense-java.nio.file.Path-) | Concede licenza al componente. |
| [setLicense(String licensePath)](#setLicense-java.lang.String-) | Concede licenza al componente. |
| [setLicense(URL licenseUri)](#setLicense-java.net.URL-) | Concede licenza al componente. |
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


Concede licenza al componente.

Il seguente esempio dimostra come impostare una licenza passando l'InputStream del file di licenza.

Per ulteriori informazioni sulla licenza, consultare le [GroupDocs Licensing FAQ][]. È inoltre possibile trovare informazioni dettagliate sulla licenza di GroupDocs.Viewer nella documentazione [Evaluation Limitations and Licensing][].

**Example:**

```

 FileInputStream licenseStream = new FileInputStream("LicenseFile.lic");
 License license = new License();
 license.setLicense(licenseStream);
 
```


[GroupDocs Licensing FAQ]: https://purchase.groupdocs.com/faqs/licensing
[Evaluation Limitations and Licensing]: https://docs.groupdocs.com/display/viewernet/Evaluation+Limitations+and+Licensing+of+GroupDocs.Viewer

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| licenseStream | java.io.InputStream | Il flusso di licenza. |

### setLicense(Path licensePath) {#setLicense-java.nio.file.Path-}
```
public final void setLicense(Path licensePath)
```


Concede licenza al componente.

Imposta la licenza per il componente utilizzando il percorso di licenza specificato.

**Note:** This method should be called before using any functionality of the component.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| licensePath | java.nio.file.Path | Il percorso della licenza. |

### setLicense(String licensePath) {#setLicense-java.lang.String-}
```
public final void setLicense(String licensePath)
```


Concede licenza al componente.

Questo metodo dovrebbe essere chiamato prima di utilizzare qualsiasi funzionalità.

Esempio di utilizzo:

```

 String licensePath = "GroupDocs.Viewer.lic";
 License license = new License();
 license.setLicense(licensePath);
 
```

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| licensePath | java.lang.String | Il percorso o l'URL della licenza. |

### setLicense(URL licenseUri) {#setLicense-java.net.URL-}
```
public void setLicense(URL licenseUri)
```


Concede licenza al componente.

Questo metodo dovrebbe essere chiamato prima di utilizzare qualsiasi funzionalità.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| licenseUri | java.net.URL | L'URI della licenza. |

### isLicensed() {#isLicensed--}
```
public final boolean isLicensed()
```




**Returns:**
boolean
