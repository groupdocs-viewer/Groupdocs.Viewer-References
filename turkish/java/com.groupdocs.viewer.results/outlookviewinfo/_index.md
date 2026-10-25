---
title: "OutlookViewInfo"
second_title: "GroupDocs.Viewer Java için API Referansı"
description: "Bir Outlook Veri dosyası için görünüm bilgilerini temsil eder."
type: docs
weight: 22
url: /tr/java/com.groupdocs.viewer.results/outlookviewinfo/
---
**All Implemented Interfaces:**
[com.groupdocs.viewer.results.ViewInfo](../../com.groupdocs.viewer.results/viewinfo)
```
public interface OutlookViewInfo extends ViewInfo
```

Bir Outlook Veri dosyası için görünüm bilgilerini temsil eder.


OutlookViewInfo arabirimi, görünüm bilgilerine erişmek ve bunları değiştirmek için sözleşmeyi tanımlar.
GroupDocs.Viewer bileşenindeki bir Outlook Veri dosyası için. Bilgi almak için yöntemler sağlar.
klasör listesi ve diğer özellikler gibi.


Örnek kullanım:

````

 try (Viewer viewer = new Viewer("document.pst")) {
     final OutlookViewInfo viewInfo = (OutlookViewInfo) viewer.getViewInfo(ViewInfoOptions.forHtmlView());
     // Use the viewInfo object for further operations
 }
 
````


***Note:** The default implementation of this interface is OutlookViewInfoImpl.*

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getFolders()](#getFolders--) | Outlook Veri dosyasında bulunan klasörlerin listesini alır. |
|
|  | [setFolders(List<String> list)](#setFolders-java.util.List-java.lang.String--) | Outlook Veri dosyasında bulunan klasörlerin listesini ayarlar. |
|
### getFolders() {#getFolders--}
```
public abstract List<String> getFolders()
```


Outlook Veri dosyasında bulunan klasörlerin listesini alır.


**Returns:**
java.util.List<java.lang.String> - klasörlerin listesi.

### setFolders(List<String> list) {#setFolders-java.util.List-java.lang.String--}
```
public abstract void setFolders(List<String> list)
```


Outlook Veri dosyasında bulunan klasörlerin listesini ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | liste | java.util.List<java.lang.String> | klasörlerin listesi. |
|

