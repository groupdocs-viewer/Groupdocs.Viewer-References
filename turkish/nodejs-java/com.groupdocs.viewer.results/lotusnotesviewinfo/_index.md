---
title: "LotusNotesViewInfo"
second_title: "GroupDocs.Viewer için Node.js üzerinden Java API Referansı"
description: "Lotus Notes veritabanı depolaması için görünüm bilgilerini temsil eder."
type: docs
weight: 19
url: /tr/nodejs-java/com.groupdocs.viewer.results/lotusnotesviewinfo/
---
**All Implemented Interfaces:**
[com.groupdocs.viewer.results.ViewInfo](../../com.groupdocs.viewer.results/viewinfo)
```
public interface LotusNotesViewInfo extends ViewInfo
```

Lotus Notes veritabanı depolaması için görünüm bilgilerini temsil eder.

LotusNotesViewInfo arabirimi, GroupDocs.Viewer bileşeninde Lotus Notes veritabanı depolaması için görünüm bilgilerine erişim ve bunları yönetme sözleşmesini tanımlar. Not sayısı ve diğer özellikler gibi bilgileri almak için yöntemler sunar.

Örnek kullanım:

```

 try (Viewer viewer = new Viewer("document.nsf")) {
     final LotusNotesViewInfo viewInfo = (LotusNotesViewInfo) viewer.getViewInfo(ViewInfoOptions.forHtmlView());
     // Use the viewInfo object for further operations
 }
 
```

***Note:** The default implementation of this interface is LotusNotesViewInfoImpl.*
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getNotesCount()](#getNotesCount--) | Depodaki not sayısını alır. |
| [setNotesCount(int count)](#setNotesCount-int-) | Depodaki not sayısını ayarlar. |
### getNotesCount() {#getNotesCount--}
```
public abstract int getNotesCount()
```


Depodaki not sayısını alır.

**Returns:**
int - depodaki not sayısı.
### setNotesCount(int count) {#setNotesCount-int-}
```
public abstract void setNotesCount(int count)
```


Depodaki not sayısını ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| sayı | int | depodaki not sayısı. |

