---
title: "ProjectManagementOptions"
second_title: "GroupDocs.Viewer için Node.js üzerinden Java API Referansı"
description: "Proje yönetimi dosyalarını renderleme seçenekleri sağlar."
type: docs
weight: 27
url: /tr/nodejs-java/com.groupdocs.viewer.options/projectmanagementoptions/
---
**Inheritance:**
java.lang.Object
```
public class ProjectManagementOptions
```

Proje yönetimi dosyalarını renderleme seçenekleri sağlar.

ProjectManagementOptions sınıfı, GroupDocs.Viewer bileşeninde proje yönetimi dosyalarının (örneğin Microsoft Project veya benzeri) işlenmesini kontrol etmek için kullanılabilecek çeşitli ayar ve parametreleri kapsüller. Ayrıntılar için [documentation][] sayfasına bakın.

Örnek kullanım:

```

 PngViewOptions pngViewOptions = new PngViewOptions();
 ProjectManagementOptions projectManagementOptions = pngViewOptions.getProjectManagementOptions();
 projectManagementOptions.setPageSize(PageSize.A4);
 projectManagementOptions.setStartDate(new Date(2021, 11, 23));

 try (Viewer viewer = new Viewer("document.docx")) {
     viewer.view(pngViewOptions);
     // Use the viewer object for further operations
 }
 
```


[documentation]: https://docs.groupdocs.com/viewer/java/render-ms-project-files/
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [ProjectManagementOptions()](#ProjectManagementOptions--) | ProjectManagementOptions sınıfının yeni bir örneğini başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getPageSize()](#getPageSize--) | Çıktı sayfa boyutunu alır. |
| [setPageSize(PageSize value)](#setPageSize-com.groupdocs.viewer.options.PageSize-) | Çıktı sayfa boyutunu ayarlar. |
| [getTimeUnit()](#getTimeUnit--) | Zaman birimini alır. |
| [setTimeUnit(TimeUnit value)](#setTimeUnit-com.groupdocs.viewer.options.TimeUnit-) | Zaman birimini alır. |
| [getStartDate()](#getStartDate--) | Çıktıya dahil edilecek Gantt Chart View'un başlangıç tarihini alır. |
| [setStartDate(Date value)](#setStartDate-java.util.Date-) | Çıktıya dahil edilecek Gantt Chart View'un başlangıç tarihini ayarlar. |
| [getEndDate()](#getEndDate--) | Çıktıya dahil edilecek Gantt Chart View'un bitiş tarihini alır. |
| [setEndDate(Date value)](#setEndDate-java.util.Date-) | Çıktıya dahil edilecek Gantt Chart View'un bitiş tarihini ayarlar. |
### ProjectManagementOptions() {#ProjectManagementOptions--}
```
public ProjectManagementOptions()
```


ProjectManagementOptions sınıfının yeni bir örneğini başlatır.

### getPageSize() {#getPageSize--}
```
public final PageSize getPageSize()
```


Çıktı sayfa boyutunu alır.

Kod örneği için, [documentation][] sayfasına bakın.


[documentation]: https://docs.groupdocs.com/viewer/java/render-ms-project-files/#specify-the-output-page-size

**Returns:**
[PageSize](../../com.groupdocs.viewer.options/pagesize) - the output page size.
### setPageSize(PageSize value) {#setPageSize-com.groupdocs.viewer.options.PageSize-}
```
public final void setPageSize(PageSize value)
```


Çıktı sayfa boyutunu ayarlar.

Kod örneği için, [documentation][] sayfasına bakın.


[documentation]: https://docs.groupdocs.com/viewer/java/render-ms-project-files/#specify-the-output-page-size

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [PageSize](../../com.groupdocs.viewer.options/pagesize) | Çıktı sayfa boyutu. |

### getTimeUnit() {#getTimeUnit--}
```
public final TimeUnit getTimeUnit()
```


Zaman birimini alır.

Kod örneği için, [documentation][] sayfasına bakın.


[documentation]: https://docs.groupdocs.com/viewer/java/render-ms-project-files/#adjust-the-time-unit

**Returns:**
[TimeUnit](../../com.groupdocs.viewer.options/timeunit) - the time unit.
### setTimeUnit(TimeUnit value) {#setTimeUnit-com.groupdocs.viewer.options.TimeUnit-}
```
public final void setTimeUnit(TimeUnit value)
```


Zaman birimini alır.

Kod örneği için, [documentation][] sayfasına bakın.


[documentation]: https://docs.groupdocs.com/viewer/java/render-ms-project-files/#adjust-the-time-unit

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [TimeUnit](../../com.groupdocs.viewer.options/timeunit) | Zaman birimi. |

### getStartDate() {#getStartDate--}
```
public final Date getStartDate()
```


Çıktıya dahil edilecek Gantt Chart View'un başlangıç tarihini alır.

***Note:** Use this option when you need to render a specific time interval of the project within the Gantt Chart View.* For code sample, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-ms-project-files/#render-specific-dates

**Returns:**
java.util.Date - Gantt Chart View'un başlangıç tarihi.
### setStartDate(Date value) {#setStartDate-java.util.Date-}
```
public final void setStartDate(Date value)
```


Çıktıya dahil edilecek Gantt Chart View'un başlangıç tarihini ayarlar.

***Note:** Use this option when you need to render a specific time interval of the project within the Gantt Chart View.* For code sample, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-ms-project-files/#render-specific-dates

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.util.Date | Gantt Chart View'un başlangıç tarihi. |

### getEndDate() {#getEndDate--}
```
public final Date getEndDate()
```


Çıktıya dahil edilecek Gantt Chart View'un bitiş tarihini alır.

***Note:** Use this option when you need to render a specific time interval of the project within the Gantt Chart View.* For code sample, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-ms-project-files/#render-specific-dates

**Returns:**
java.util.Date - Gantt Chart View'un bitiş tarihi.
### setEndDate(Date value) {#setEndDate-java.util.Date-}
```
public final void setEndDate(Date value)
```


Çıktıya dahil edilecek Gantt Chart View'un bitiş tarihini ayarlar.

***Note:** Use this option when you need to render a specific time interval of the project within the Gantt Chart View.* For code sample, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-ms-project-files/#render-specific-dates

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.util.Date | Gantt Chart View'un bitiş tarihi. |

