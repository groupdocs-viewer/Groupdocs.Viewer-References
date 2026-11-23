---
title: "Lizenz"
second_title: "GroupDocs.Viewer für Node.js über Java API-Referenz"
description: "Stellt Methoden zum Lizenzieren der Komponente und zum Freischalten ihrer vollen Funktionalität bereit."
type: docs
weight: 10
url: /de/nodejs-java/com.groupdocs.viewer/license/
---
**Inheritance:**
java.lang.Object
```
public class License
```

Stellt Methoden zum Lizenzieren der Komponente und zum Freischalten ihrer vollen Funktionalität bereit.

Die Lizenzklasse ermöglicht es Ihnen, eine gültige Lizenz auf die GroupDocs.Viewer-Komponente anzuwenden, sodass Sie alle Funktionen nutzen und etwaige Evaluationsbeschränkungen entfernen können.

Beispielhafte Verwendung:

```

 License license = new License();
 license.setLicense("path/to/license/file.lic");
 
```
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [License()](#License--) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [resetLicense()](#resetLicense--) |  |
| [setLicense(InputStream licenseStream)](#setLicense-java.io.InputStream-) | Lizenziert die Komponente. |
| [setLicense(Path licensePath)](#setLicense-java.nio.file.Path-) | Lizenziert die Komponente. |
| [setLicense(String licensePath)](#setLicense-java.lang.String-) | Lizenziert die Komponente. |
| [setLicense(URL licenseUri)](#setLicense-java.net.URL-) | Lizenziert die Komponente. |
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


Lizenziert die Komponente.

Das folgende Beispiel zeigt, wie eine Lizenz gesetzt wird, indem ein InputStream der Lizenzdatei übergeben wird.

Weitere Informationen zur Lizenzierung finden Sie im [GroupDocs Licensing FAQ][]. Detaillierte Informationen zur Lizenzierung von GroupDocs.Viewer finden Sie außerdem in der Dokumentation zu [Evaluation Limitations and Licensing][].

**Example:**

```

 FileInputStream licenseStream = new FileInputStream("LicenseFile.lic");
 License license = new License();
 license.setLicense(licenseStream);
 
```


[GroupDocs Licensing FAQ]: https://purchase.groupdocs.com/faqs/licensing
[Evaluation Limitations and Licensing]: https://docs.groupdocs.com/display/viewernet/Evaluation+Limitations+and+Licensing+of+GroupDocs.Viewer

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| licenseStream | java.io.InputStream | Der Lizenz-Stream. |

### setLicense(Path licensePath) {#setLicense-java.nio.file.Path-}
```
public final void setLicense(Path licensePath)
```


Lizenziert die Komponente.

Setzt die Lizenz für die Komponente mithilfe des angegebenen Lizenzpfads.

**Note:** This method should be called before using any functionality of the component.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| licensePath | java.nio.file.Path | Der Lizenzpfad. |

### setLicense(String licensePath) {#setLicense-java.lang.String-}
```
public final void setLicense(String licensePath)
```


Lizenziert die Komponente.

Diese Methode sollte aufgerufen werden, bevor irgendeine Funktionalität verwendet wird.

Beispielhafte Verwendung:

```

 String licensePath = "GroupDocs.Viewer.lic";
 License license = new License();
 license.setLicense(licensePath);
 
```

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| licensePath | java.lang.String | Der Lizenzpfad oder die URL. |

### setLicense(URL licenseUri) {#setLicense-java.net.URL-}
```
public void setLicense(URL licenseUri)
```


Lizenziert die Komponente.

Diese Methode sollte aufgerufen werden, bevor irgendeine Funktionalität verwendet wird.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| licenseUri | java.net.URL | Die Lizenz-URI. |

### isLicensed() {#isLicensed--}
```
public final boolean isLicensed()
```




**Returns:**
boolean
