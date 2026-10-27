---
title: "ProjectManagementViewInfo"
second_title: "GroupDocs.Viewer için Node.js üzerinden Java API Referansı"
description: "Bir MS Project belgesi için görünüm bilgilerini temsil eder."
type: docs
weight: 23
url: /tr/nodejs-java/com.groupdocs.viewer.results/projectmanagementviewinfo/
---
**All Implemented Interfaces:**
[com.groupdocs.viewer.results.ViewInfo](../../com.groupdocs.viewer.results/viewinfo)
```
public interface ProjectManagementViewInfo extends ViewInfo
```

Bir MS Project belgesi için görünüm bilgilerini temsil eder.

ProjectManagementViewInfo arayüzü, GroupDocs.Viewer bileşeninde bir MS Project belgesi için görünüm bilgilerine erişme ve bu bilgileri değiştirme sözleşmesini tanımlar. Başlangıç ve bitiş tarihleri gibi bilgileri ve diğer özellikleri almak için yöntemler sağlar.

Örnek kullanım:

```

 try (Viewer viewer = new Viewer("document.mpp")) {
     final ProjectManagementViewInfo viewInfo = (ProjectManagementViewInfo) viewer.getViewInfo(ViewInfoOptions.forPngView());
     // Use the viewInfo object for further operations
 }
 
```

***Note:** The default implementation of this interface is ProjectManagementViewInfoImpl.*
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getStartDate()](#getStartDate--) | Projenin başlatıldığı tarih ve saati alır. |
| [setStartDate(Date startDate)](#setStartDate-java.util.Date-) | Proje için başlangıç tarih ve saatini ayarlar. |
| [getEndDate()](#getEndDate--) | Projenin tamamlanacağı tarih ve saati alır. |
| [setEndDate(Date endDate)](#setEndDate-java.util.Date-) | Proje için bitiş tarih ve saatini ayarlar. |
### getStartDate() {#getStartDate--}
```
public abstract Date getStartDate()
```


Projenin başlatıldığı tarih ve saati alır.

**Returns:**
java.util.Date - projenin başlangıç tarih ve saati.
### setStartDate(Date startDate) {#setStartDate-java.util.Date-}
```
public abstract void setStartDate(Date startDate)
```


Proje için başlangıç tarih ve saatini ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| startDate | java.util.Date | ayarlanacak yeni başlangıç tarih ve saati. |

### getEndDate() {#getEndDate--}
```
public abstract Date getEndDate()
```


Projenin tamamlanacağı tarih ve saati alır.

**Returns:**
java.util.Date - projenin bitiş tarih ve saati.
### setEndDate(Date endDate) {#setEndDate-java.util.Date-}
```
public abstract void setEndDate(Date endDate)
```


Proje için bitiş tarih ve saatini ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| endDate | java.util.Date | ayarlanacak yeni bitiş tarih ve saati. |

