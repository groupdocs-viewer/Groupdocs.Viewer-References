---
title: "Lisans"
second_title: "GroupDocs.Viewer için Node.js üzerinden Java API Referansı"
description: "Bileşeni lisanslamak ve tam işlevselliğini açmak için yöntemler sağlar."
type: docs
weight: 10
url: /tr/nodejs-java/com.groupdocs.viewer/license/
---
**Inheritance:**
java.lang.Object
```
public class License
```

Bileşeni lisanslamak ve tam işlevselliğini açmak için yöntemler sağlar.

Lisans sınıfı, GroupDocs.Viewer bileşenine geçerli bir lisans uygulamanıza olanak tanır, böylece tüm özellikleri kullanabilir ve herhangi bir değerlendirme sınırlamasını kaldırabilirsiniz.

Örnek kullanım:

```

 License license = new License();
 license.setLicense("path/to/license/file.lic");
 
```
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [License()](#License--) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [resetLicense()](#resetLicense--) |  |
| [setLicense(InputStream licenseStream)](#setLicense-java.io.InputStream-) | Bileşeni lisanslar. |
| [setLicense(Path licensePath)](#setLicense-java.nio.file.Path-) | Bileşeni lisanslar. |
| [setLicense(String licensePath)](#setLicense-java.lang.String-) | Bileşeni lisanslar. |
| [setLicense(URL licenseUri)](#setLicense-java.net.URL-) | Bileşeni lisanslar. |
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


Bileşeni lisanslar.

Aşağıdaki örnek, lisans dosyasının InputStream'ini geçirerek bir lisansın nasıl ayarlanacağını gösterir.

Lisanslama hakkında daha fazla bilgi için lütfen [GroupDocs Licensing FAQ][] adresine bakın. Ayrıca GroupDocs.Viewer lisanslamasıyla ilgili ayrıntılı bilgileri [Evaluation Limitations and Licensing][] belgelerinde bulabilirsiniz.

**Example:**

```

 FileInputStream licenseStream = new FileInputStream("LicenseFile.lic");
 License license = new License();
 license.setLicense(licenseStream);
 
```


[GroupDocs Licensing FAQ]: https://purchase.groupdocs.com/faqs/licensing
[Evaluation Limitations and Licensing]: https://docs.groupdocs.com/display/viewernet/Evaluation+Limitations+and+Licensing+of+GroupDocs.Viewer

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| licenseStream | java.io.InputStream | Lisans akışı. |

### setLicense(Path licensePath) {#setLicense-java.nio.file.Path-}
```
public final void setLicense(Path licensePath)
```


Bileşeni lisanslar.

Belirtilen lisans yolu kullanılarak bileşen için lisansı ayarlar.

**Note:** This method should be called before using any functionality of the component.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| licensePath | java.nio.file.Path | Lisans yolu. |

### setLicense(String licensePath) {#setLicense-java.lang.String-}
```
public final void setLicense(String licensePath)
```


Bileşeni lisanslar.

Bu yöntem, herhangi bir işlevsellik kullanılmadan önce çağrılmalıdır.

Örnek kullanım:

```

 String licensePath = "GroupDocs.Viewer.lic";
 License license = new License();
 license.setLicense(licensePath);
 
```

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| licensePath | java.lang.String | Lisans yolu veya URL. |

### setLicense(URL licenseUri) {#setLicense-java.net.URL-}
```
public void setLicense(URL licenseUri)
```


Bileşeni lisanslar.

Bu yöntem, herhangi bir işlevsellik kullanılmadan önce çağrılmalıdır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| licenseUri | java.net.URL | Lisans URI'si. |

### isLicensed() {#isLicensed--}
```
public final boolean isLicensed()
```




**Returns:**
boolean
