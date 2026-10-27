---
title: "OutlookViewInfo"
second_title: "GroupDocs.Viewer için Node.js üzerinden Java API Referansı"
description: "Outlook Veri dosyası için görünüm bilgilerini temsil eder."
type: docs
weight: 20
url: /tr/nodejs-java/com.groupdocs.viewer.results/outlookviewinfo/
---
**All Implemented Interfaces:**
[com.groupdocs.viewer.results.ViewInfo](../../com.groupdocs.viewer.results/viewinfo)
```
public interface OutlookViewInfo extends ViewInfo
```

Outlook Veri dosyası için görünüm bilgilerini temsil eder.

OutlookViewInfo arabirimi, GroupDocs.Viewer bileşeninde bir Outlook Veri dosyası için görünüm bilgilerine erişim ve bunları yönetme sözleşmesini tanımlar. Klasör listesi ve diğer özellikler gibi bilgileri almak için yöntemler sunar.

Örnek kullanım:

```

 try (Viewer viewer = new Viewer("document.pst")) {
     final OutlookViewInfo viewInfo = (OutlookViewInfo) viewer.getViewInfo(ViewInfoOptions.forHtmlView());
     // Use the viewInfo object for further operations
 }
 
```

***Note:** The default implementation of this interface is OutlookViewInfoImpl.*
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getFolders()](#getFolders--) | Outlook Veri dosyasında bulunan klasörlerin listesini alır. |
| [setFolders(List<String> list)](#setFolders-java.util.List-java.lang.String--) | Outlook Veri dosyasında bulunan klasörlerin listesini ayarlar. |
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
| liste | java.util.List<java.lang.String> | klasörlerin listesi. |

