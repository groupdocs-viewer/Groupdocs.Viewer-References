---
title: "ArchiveViewInfo"
second_title: "GroupDocs.Viewer için Node.js üzerinden Java API Referansı"
description: "Bir arşiv dosyası için görünüm bilgilerini temsil eder."
type: docs
weight: 11
url: /tr/nodejs-java/com.groupdocs.viewer.results/archiveviewinfo/
---
**All Implemented Interfaces:**
[com.groupdocs.viewer.results.ViewInfo](../../com.groupdocs.viewer.results/viewinfo)
```
public interface ArchiveViewInfo extends ViewInfo
```

Bir arşiv dosyası için görünüm bilgilerini temsil eder.

ArchiveViewInfo arayüzü, GroupDocs.Viewer bileşeninde bir arşiv dosyasına özgü görüntü bilgilerini almayı sağlayan sözleşmeyi tanımlar. Sayfa sayısı, boyutlar ve arşiv dosyalarına özgü render seçenekleri gibi ayrıntılara erişim sağlayan yöntemler sunar.

Örnek kullanım:

```

 try (Viewer viewer = new Viewer("document.zip")) {
     ArchiveViewInfo viewInfo = (ArchiveViewInfo) viewer.getViewInfo(ViewInfoOptions.forHtmlView());

     // Use the viewInfo object for further operations
 }
 
```

***Note:** The default implementation of this interface is ArchiveViewInfoImpl.*
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getFolders()](#getFolders--) | Arşiv dosyasında bulunan klasörlerin listesini alır. |
| [setFolders(List<String> folders)](#setFolders-java.util.List-java.lang.String--) | Arşiv dosyasında bulunan klasörlerin listesini ayarlar. |
### getFolders() {#getFolders--}
```
public abstract List<String> getFolders()
```


Arşiv dosyasında bulunan klasörlerin listesini alır.

**Returns:**
java.util.List<java.lang.String> - klasörlerin listesi.
### setFolders(List<String> folders) {#setFolders-java.util.List-java.lang.String--}
```
public abstract void setFolders(List<String> folders)
```


Arşiv dosyasında bulunan klasörlerin listesini ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| klasörler | java.util.List<java.lang.String> | klasörlerin listesi. |

