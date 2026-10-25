---
title: "ArchiveViewInfo"
second_title: "GroupDocs.Viewer Java için API Referansı"
description: "Arşiv dosyası için görünüm bilgilerini temsil eder."
type: docs
weight: 11
url: /tr/java/com.groupdocs.viewer.results/archiveviewinfo/
---
**All Implemented Interfaces:**
[com.groupdocs.viewer.results.ViewInfo](../../com.groupdocs.viewer.results/viewinfo)
```
public interface ArchiveViewInfo extends ViewInfo
```

Arşiv dosyası için görünüm bilgilerini temsil eder.


ArchiveViewInfo arabirimi, arşiv dosyasına özgü görüntü bilgilerini almayı sağlayan sözleşmeyi tanımlar
GroupDocs.Viewer bileşeninde. Sayfa sayısı, boyutlar ve render seçenekleri gibi ayrıntılara erişim sağlayan yöntemler sunar
arşiv dosyalarına özgü.


Örnek kullanım:

````

 try (Viewer viewer = new Viewer("document.zip")) {
     ArchiveViewInfo viewInfo = (ArchiveViewInfo) viewer.getViewInfo(ViewInfoOptions.forHtmlView());

     // Use the viewInfo object for further operations
 }
 
````


***Note:** The default implementation of this interface is ArchiveViewInfoImpl.*

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getFolders()](#getFolders--) | Arşiv dosyası içinde bulunan klasörlerin listesini alır. |
|
|  | [setFolders(List<String> folders)](#setFolders-java.util.List-java.lang.String--) | Arşiv dosyası içinde bulunan klasörlerin listesini ayarlar. |
|
### getFolders() {#getFolders--}
```
public abstract List<String> getFolders()
```


Arşiv dosyası içinde bulunan klasörlerin listesini alır.


**Returns:**
java.util.List<java.lang.String> - klasörlerin listesi.

### setFolders(List<String> folders) {#setFolders-java.util.List-java.lang.String--}
```
public abstract void setFolders(List<String> folders)
```


Arşiv dosyası içinde bulunan klasörlerin listesini ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | klasörler | java.util.List<java.lang.String> | klasörlerin listesi. |
|

