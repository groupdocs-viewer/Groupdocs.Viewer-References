---
title: "ProjectManagementOptions"
second_title: "GroupDocs.Viewer för Java API-referens"
description: "Tillhandahåller alternativ för rendering av projektledningsfiler."
type: docs
weight: 27
url: /sv/java/com.groupdocs.viewer.options/projectmanagementoptions/
---
**Inheritance:**
java.lang.Object
```
public class ProjectManagementOptions
```

Tillhandahåller alternativ för rendering av projektledningsfiler.


Klassen ProjectManagementOptions kapslar in olika inställningar och parametrar som kan användas
för att kontrollera rendering av projektledningsfiler (såsom Microsoft Project eller liknande)
i GroupDocs.Viewer-komponenten.
För detaljer, se [dokumentationen](../https://docs.groupdocs.com/viewer/java/render-ms-project-files/).


Exempel på användning:

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


## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
|  | [ProjectManagementOptions()](#ProjectManagementOptions--) | Initierar en ny instans av |
ProjectManagementOptions
klassen.
|
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getPageSize()](#getPageSize--) | Hämtar utskrifts sidstorlek. |
|
|  | [setPageSize(PageSize value)](#setPageSize-com.groupdocs.viewer.options.PageSize-) | Ställer in utskrifts sidstorlek. |
|
|  | [getTimeUnit()](#getTimeUnit--) | Hämtar tidsenheten. |
|
|  | [setTimeUnit(TimeUnit value)](#setTimeUnit-com.groupdocs.viewer.options.TimeUnit-) | Hämtar tidsenheten. |
|
|  | [getStartDate()](#getStartDate--) | Hämtar startdatumet för Gantt-diagramvyn som ska inkluderas i utskriften. |
|
|  | [setStartDate(Date value)](#setStartDate-java.util.Date-) | Ställer in startdatumet för Gantt-diagramvyn som ska inkluderas i utskriften. |
|
|  | [getEndDate()](#getEndDate--) | Hämtar slutdatumet för Gantt-diagramvyn som ska inkluderas i utskriften. |
|
|  | [setEndDate(Date value)](#setEndDate-java.util.Date-) | Ställer in slutdatumet för Gantt-diagramvyn som ska inkluderas i utskriften. |
|
### ProjectManagementOptions() {#ProjectManagementOptions--}
```
public ProjectManagementOptions()
```


Initierar en ny instans av
ProjectManagementOptions
klassen.


### getPageSize() {#getPageSize--}
```
public final PageSize getPageSize()
```


Hämtar utskrifts sidstorlek.


För kodexempel, se [dokumentationen](../https://docs.groupdocs.com/viewer/java/render-ms-project-files/#specify-the-output-page-size).


**Returns:**
[PageSize](../../com.groupdocs.viewer.options/pagesize) - the output page size.

### setPageSize(PageSize value) {#setPageSize-com.groupdocs.viewer.options.PageSize-}
```
public final void setPageSize(PageSize value)
```


Ställer in utskrifts sidstorlek.


För kodexempel, se [dokumentationen](../https://docs.groupdocs.com/viewer/java/render-ms-project-files/#specify-the-output-page-size).


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | value | [PageSize](../../com.groupdocs.viewer.options/pagesize) | Utskrifts sidstorlek. |
|

### getTimeUnit() {#getTimeUnit--}
```
public final TimeUnit getTimeUnit()
```


Hämtar tidsenheten.


För kodexempel, se [dokumentationen](../https://docs.groupdocs.com/viewer/java/render-ms-project-files/#adjust-the-time-unit).


**Returns:**
[TimeUnit](../../com.groupdocs.viewer.options/timeunit) - the time unit.

### setTimeUnit(TimeUnit value) {#setTimeUnit-com.groupdocs.viewer.options.TimeUnit-}
```
public final void setTimeUnit(TimeUnit value)
```


Hämtar tidsenheten.


För kodexempel, se [dokumentationen](../https://docs.groupdocs.com/viewer/java/render-ms-project-files/#adjust-the-time-unit).


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | value | [TimeUnit](../../com.groupdocs.viewer.options/timeunit) | Tidsenheten. |
|

### getStartDate() {#getStartDate--}
```
public final Date getStartDate()
```


Hämtar startdatumet för Gantt-diagramvyn som ska inkluderas i utskriften.


***Note:** Use this option when you need to render a specific time interval of the project within the Gantt Chart View.*
För kodexempel, se [dokumentationen](../https://docs.groupdocs.com/viewer/java/render-ms-project-files/#render-specific-dates).


**Returns:**
java.util.Date - startdatumet för Gantt-diagramvyn.

### setStartDate(Date value) {#setStartDate-java.util.Date-}
```
public final void setStartDate(Date value)
```


Ställer in startdatumet för Gantt-diagramvyn som ska inkluderas i utskriften.


***Note:** Use this option when you need to render a specific time interval of the project within the Gantt Chart View.*
För kodexempel, se [dokumentationen](../https://docs.groupdocs.com/viewer/java/render-ms-project-files/#render-specific-dates).


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | värde | java.util.Date | Startdatumet för Gantt-diagramvyn. |
|

### getEndDate() {#getEndDate--}
```
public final Date getEndDate()
```


Hämtar slutdatumet för Gantt-diagramvyn som ska inkluderas i utskriften.


***Note:** Use this option when you need to render a specific time interval of the project within the Gantt Chart View.*
För kodexempel, se [dokumentationen](../https://docs.groupdocs.com/viewer/java/render-ms-project-files/#render-specific-dates).


**Returns:**
java.util.Date - slutdatumet för Gantt-diagramvyn.

### setEndDate(Date value) {#setEndDate-java.util.Date-}
```
public final void setEndDate(Date value)
```


Ställer in slutdatumet för Gantt-diagramvyn som ska inkluderas i utskriften.


***Note:** Use this option when you need to render a specific time interval of the project within the Gantt Chart View.*
För kodexempel, se [dokumentationen](../https://docs.groupdocs.com/viewer/java/render-ms-project-files/#render-specific-dates).


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | värde | java.util.Date | Slutdatumet för Gantt-diagramvyn. |
|

