---
title: "PdfViewInfo"
second_title: "GroupDocs.Viewer için Node.js üzerinden Java API Referansı"
description: "Bir PDF belgesi için görünüm bilgilerini temsil eder."
type: docs
weight: 22
url: /tr/nodejs-java/com.groupdocs.viewer.results/pdfviewinfo/
---
**All Implemented Interfaces:**
[com.groupdocs.viewer.results.ViewInfo](../../com.groupdocs.viewer.results/viewinfo)
```
public interface PdfViewInfo extends ViewInfo
```

Bir PDF belgesi için görünüm bilgilerini temsil eder.

PdfViewInfo arabirimi, GroupDocs.Viewer bileşeninde bir PDF belgesi için görünüm bilgilerine erişim ve bunları yönetme sözleşmesini tanımlar. Yazdırma izni gibi bilgiler ve diğer özellikler için yöntemler sunar.

Örnek kullanım:

```

 try (Viewer viewer = new Viewer("document.pdf")) {
     final PdfViewInfo viewInfo = (PdfViewInfo) viewer.getViewInfo(ViewInfoOptions.forPngView());
     // Use the viewInfo object for further operations
 }
 
```

***Note:** The default implementation of this interface is PdfViewInfoImpl.*
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [isPrintingAllowed()](#isPrintingAllowed--) | Belgenin yazdırılmasının izinli olup olmadığını kontrol eder. |
| [setPrintingAllowed(boolean allowPrinting)](#setPrintingAllowed-boolean-) | Belgenin yazdırılmasının izinli olup olmadığını ayarlar. |
### isPrintingAllowed() {#isPrintingAllowed--}
```
public abstract boolean isPrintingAllowed()
```


Belgenin yazdırılmasının izinli olup olmadığını kontrol eder.

**Returns:**
boolean -  true  eğer yazdırma izinliyse,  false  aksi takdirde.
### setPrintingAllowed(boolean allowPrinting) {#setPrintingAllowed-boolean-}
```
public abstract void setPrintingAllowed(boolean allowPrinting)
```


Belgenin yazdırılmasının izinli olup olmadığını ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| allowPrinting | boolean | true  yazdırmaya izin vermek için,  false  aksi takdirde. |

