---
title: "ProjectManagementOptions"
second_title: "GroupDocs.Viewer Java için API Referansı"
description: "Proje yönetimi dosyalarını işlemek için seçenekler sağlar."
type: docs
weight: 27
url: /tr/java/com.groupdocs.viewer.options/projectmanagementoptions/
---
**Inheritance:**
java.lang.Object
```
public class ProjectManagementOptions
```

Proje yönetimi dosyalarını işlemek için seçenekler sağlar.


ProjectManagementOptions sınıfı, kullanılabilecek çeşitli ayarları ve parametreleri kapsar
proje yönetimi dosyalarının (örneğin Microsoft Project veya benzeri) işlenmesini kontrol etmek için
GroupDocs.Viewer bileşeninde.
Ayrıntılar için, [belgelendirme](../https://docs.groupdocs.com/viewer/java/render-ms-project-files/) adresine bakın.


Örnek kullanım:

````

 PngViewOptions pngViewOptions = new PngViewOptions();
 ProjectManagementOptions projectManagementOptions = pngViewOptions.getProjectManagementOptions();
 projectManagementOptions.setPageSize(PageSize.A4);
 projectManagementOptions.setStartDate(new Date(2021, 11, 23));

 try (Viewer viewer = new Viewer("document.docx")) {
     viewer.view(pngViewOptions);
     // Use the viewer object for further operations
 }
 
````


## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
|  | [ProjectManagementOptions()](#ProjectManagementOptions--) | Yeni bir örnek başlatır |
ProjectManagementOptions
sınıf.
|
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getPageSize()](#getPageSize--) | Çıktı sayfa boyutunu alır. |
|
|  | [setPageSize(PageSize value)](#setPageSize-com.groupdocs.viewer.options.PageSize-) | Çıktı sayfa boyutunu ayarlar. |
|
|  | [getTimeUnit()](#getTimeUnit--) | Zaman birimini alır. |
|
|  | [setTimeUnit(TimeUnit value)](#setTimeUnit-com.groupdocs.viewer.options.TimeUnit-) | Zaman birimini alır. |
|
|  | [getStartDate()](#getStartDate--) | Çıktıya dahil edilecek Gantt Şeması Görünümü'nün başlangıç tarihini alır. |
|
|  | [setStartDate(Date value)](#setStartDate-java.util.Date-) | Çıktıya dahil edilecek Gantt Şeması Görünümü'nün başlangıç tarihini ayarlar. |
|
|  | [getEndDate()](#getEndDate--) | Çıktıya dahil edilecek Gantt Şeması Görünümü'nün bitiş tarihini alır. |
|
|  | [setEndDate(Date value)](#setEndDate-java.util.Date-) | Çıktıya dahil edilecek Gantt Şeması Görünümü'nün bitiş tarihini ayarlar. |
|
### ProjectManagementOptions() {#ProjectManagementOptions--}
```
public ProjectManagementOptions()
```


Yeni bir örnek başlatır
ProjectManagementOptions
sınıf.


### getPageSize() {#getPageSize--}
```
public final PageSize getPageSize()
```


Çıktı sayfa boyutunu alır.


Kod örneği için, [belgelendirmeye](../https://docs.groupdocs.com/viewer/java/render-ms-project-files/#specify-the-output-page-size) bakın.


**Returns:**
[PageSize](../../com.groupdocs.viewer.options/pagesize) - the output page size.

### setPageSize(PageSize value) {#setPageSize-com.groupdocs.viewer.options.PageSize-}
```
public final void setPageSize(PageSize value)
```


Çıktı sayfa boyutunu ayarlar.


Kod örneği için, [belgelendirmeye](../https://docs.groupdocs.com/viewer/java/render-ms-project-files/#specify-the-output-page-size) bakın.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | value | [PageSize](../../com.groupdocs.viewer.options/pagesize) | Çıktı sayfa boyutu. |
|

### getTimeUnit() {#getTimeUnit--}
```
public final TimeUnit getTimeUnit()
```


Zaman birimini alır.


Kod örneği için, [belgelendirmeye](../https://docs.groupdocs.com/viewer/java/render-ms-project-files/#adjust-the-time-unit) bakın.


**Returns:**
[TimeUnit](../../com.groupdocs.viewer.options/timeunit) - the time unit.

### setTimeUnit(TimeUnit value) {#setTimeUnit-com.groupdocs.viewer.options.TimeUnit-}
```
public final void setTimeUnit(TimeUnit value)
```


Zaman birimini alır.


Kod örneği için, [belgelendirmeye](../https://docs.groupdocs.com/viewer/java/render-ms-project-files/#adjust-the-time-unit) bakın.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | value | [TimeUnit](../../com.groupdocs.viewer.options/timeunit) | Zaman birimi. |
|

### getStartDate() {#getStartDate--}
```
public final Date getStartDate()
```


Çıktıya dahil edilecek Gantt Şeması Görünümü'nün başlangıç tarihini alır.


***Note:** Use this option when you need to render a specific time interval of the project within the Gantt Chart View.*
Kod örneği için, [belgelendirmeye](../https://docs.groupdocs.com/viewer/java/render-ms-project-files/#render-specific-dates) bakın.


**Returns:**
java.util.Date - Gantt Chart View başlangıç tarihi.

### setStartDate(Date value) {#setStartDate-java.util.Date-}
```
public final void setStartDate(Date value)
```


Çıktıya dahil edilecek Gantt Şeması Görünümü'nün başlangıç tarihini ayarlar.


***Note:** Use this option when you need to render a specific time interval of the project within the Gantt Chart View.*
Kod örneği için, [belgelendirmeye](../https://docs.groupdocs.com/viewer/java/render-ms-project-files/#render-specific-dates) bakın.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | value | java.util.Date | Gantt Chart View başlangıç tarihi. |
|

### getEndDate() {#getEndDate--}
```
public final Date getEndDate()
```


Çıktıya dahil edilecek Gantt Şeması Görünümü'nün bitiş tarihini alır.


***Note:** Use this option when you need to render a specific time interval of the project within the Gantt Chart View.*
Kod örneği için, [belgelendirmeye](../https://docs.groupdocs.com/viewer/java/render-ms-project-files/#render-specific-dates) bakın.


**Returns:**
java.util.Date - Gantt Chart View bitiş tarihi.

### setEndDate(Date value) {#setEndDate-java.util.Date-}
```
public final void setEndDate(Date value)
```


Çıktıya dahil edilecek Gantt Şeması Görünümü'nün bitiş tarihini ayarlar.


***Note:** Use this option when you need to render a specific time interval of the project within the Gantt Chart View.*
Kod örneği için, [belgelendirmeye](../https://docs.groupdocs.com/viewer/java/render-ms-project-files/#render-specific-dates) bakın.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | value | java.util.Date | Gantt Chart View bitiş tarihi. |
|

