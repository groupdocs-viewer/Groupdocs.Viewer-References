---
title: "TimeUnit"
second_title: "GroupDocs.Viewer için Node.js üzerinden Java API Referansı"
description: "Proje süresinin zaman birimi."
type: docs
weight: 47
url: /tr/nodejs-java/com.groupdocs.viewer.options/timeunit/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum TimeUnit extends Enum<TimeUnit>
```

Proje süresinin zaman birimi.

TimeUnit enum'ı, GroupDocs.Viewer bileşeninde bir projenin süresini belirtmek için farklı zaman birimlerini temsil eder. Günler, aylar ve benzeri gibi bir projenin süresini temsil etmek ve hesaplamak için kullanılabilecek önceden tanımlı zaman birimleri sağlar. Ayrıntılar için [documentation][] belgesine bakın.

Örnek kullanım:

```

 HtmlViewOptions pdfViewOptions = HtmlViewOptions.forEmbeddedResources();
 ProjectManagementOptions projectManagementOptions = pdfViewOptions.getProjectManagementOptions();
 projectManagementOptions.setTimeUnit(TimeUnit.MONTHS);

 try (Viewer viewer = new Viewer("document.mpp")) {
     viewer.view(pdfViewOptions);
     // Use the viewer object for further operations
 }
 
```


[documentation]: https://docs.groupdocs.com/viewer/java/render-ms-project-files/#adjust-the-time-unit
## Fields

| Field | Açıklama |
| --- | --- |
| [UNSPECIFIED](#UNSPECIFIED) | Bilinmeyen zaman ölçeği. |
| [DAYS](#DAYS) | Günler zaman ölçeği. |
| [THIRDS_OF_MONTHS](#THIRDS-OF-MONTHS) | Ayların üçte birleri zaman ölçeği. |
| [MONTHS](#MONTHS) | Aylar zaman ölçeği. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
### UNSPECIFIED {#UNSPECIFIED}
```
public static final TimeUnit UNSPECIFIED
```


Bilinmeyen zaman ölçeği. Bu zaman birimi, bilinmeyen veya belirtilmemiş bir zaman ölçeğini temsil eder.

Ayrıntılar için, [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-ms-project-files/#adjust-the-time-unit

### DAYS {#DAYS}
```
public static final TimeUnit DAYS
```


Günler zaman ölçeği. Bu zaman birimi bir günlük aralığı temsil eder.

Ayrıntılar için, [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-ms-project-files/#adjust-the-time-unit

### THIRDS_OF_MONTHS {#THIRDS-OF-MONTHS}
```
public static final TimeUnit THIRDS_OF_MONTHS
```


Ayların üçte birleri zaman ölçeği. Bu zaman birimi bir ayın üçte birini temsil eder.

Ayrıntılar için, [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-ms-project-files/#adjust-the-time-unit

### MONTHS {#MONTHS}
```
public static final TimeUnit MONTHS
```


Aylar zaman ölçeği. Bu zaman birimi bir aylık aralığı temsil eder.

Ayrıntılar için, [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-ms-project-files/#adjust-the-time-unit

### values() {#values--}
```
public static TimeUnit[] values()
```




**Returns:**
com.groupdocs.viewer.options.TimeUnit[]
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static TimeUnit valueOf(String name)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| ad | java.lang.String |  |

**Returns:**
[TimeUnit](../../com.groupdocs.viewer.options/timeunit)
