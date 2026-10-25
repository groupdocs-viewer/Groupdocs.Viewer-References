---
title: "LotusNotesViewInfo"
second_title: "GroupDocs.Viewer Java için API Referansı"
description: "Lotus Notes veritabanı depolaması için görünüm bilgilerini temsil eder."
type: docs
weight: 19
url: /tr/java/com.groupdocs.viewer.results/lotusnotesviewinfo/
---
**All Implemented Interfaces:**
[com.groupdocs.viewer.results.ViewInfo](../../com.groupdocs.viewer.results/viewinfo)
```
public interface LotusNotesViewInfo extends ViewInfo
```

Lotus Notes veritabanı depolaması için görünüm bilgilerini temsil eder.


LotusNotesViewInfo arabirimi, görünüm bilgilerine erişmek ve bunları değiştirmek için sözleşmeyi tanımlar.
GroupDocs.Viewer bileşenindeki Lotus Notes veritabanı depolaması için. Bilgi almak için yöntemler sağlar.
örneğin not sayısı ve diğer özellikler.


Örnek kullanım:

````

 try (Viewer viewer = new Viewer("document.nsf")) {
     final LotusNotesViewInfo viewInfo = (LotusNotesViewInfo) viewer.getViewInfo(ViewInfoOptions.forHtmlView());
     // Use the viewInfo object for further operations
 }
 
````


***Note:** The default implementation of this interface is LotusNotesViewInfoImpl.*

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getNotesCount()](#getNotesCount--) | Depodaki not sayısını alır. |
|
|  | [setNotesCount(int count)](#setNotesCount-int-) | Depodaki not sayısını ayarlar. |
|
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
|  | sayı | int | depodaki not sayısı. |
|

