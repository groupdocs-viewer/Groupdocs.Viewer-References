---
title: "ProjectManagementOptions"
second_title: "GroupDocs.Viewer for Java API-referentie"
description: "Biedt opties voor het renderen van projectmanagementbestanden."
type: docs
weight: 27
url: /nl/java/com.groupdocs.viewer.options/projectmanagementoptions/
---
**Inheritance:**
java.lang.Object
```
public class ProjectManagementOptions
```

Biedt opties voor het renderen van projectmanagementbestanden.


De ProjectManagementOptions-klasse omvat verschillende instellingen en parameters die kunnen worden gebruikt
om de weergave van projectmanagementbestanden te beheersen (zoals Microsoft Project of vergelijkbaar)
in de GroupDocs.Viewer-component.
Voor details, zie de [documentatie](../https://docs.groupdocs.com/viewer/java/render-ms-project-files/).


Voorbeeldgebruik:

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


## Constructors

| Constructor | Beschrijving |
| --- | --- |
|  | [ProjectManagementOptions()](#ProjectManagementOptions--) | Initialiseert een nieuw exemplaar van de |
ProjectManagementOptions
klasse.
|
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getPageSize()](#getPageSize--) | Haalt de paginagrootte van de uitvoer op. |
|
|  | [setPageSize(PageSize value)](#setPageSize-com.groupdocs.viewer.options.PageSize-) | Stelt de paginagrootte van de uitvoer in. |
|
|  | [getTimeUnit()](#getTimeUnit--) | Haalt de tijdseenheid op. |
|
|  | [setTimeUnit(TimeUnit value)](#setTimeUnit-com.groupdocs.viewer.options.TimeUnit-) | Haalt de tijdseenheid op. |
|
|  | [getStartDate()](#getStartDate--) | Haalt de begindatum van de Gantt-diagramweergave op die in de uitvoer moet worden opgenomen. |
|
|  | [setStartDate(Date value)](#setStartDate-java.util.Date-) | Stelt de begindatum van de Gantt-diagramweergave in die in de uitvoer moet worden opgenomen. |
|
|  | [getEndDate()](#getEndDate--) | Haalt de einddatum van de Gantt-diagramweergave op die in de uitvoer moet worden opgenomen. |
|
|  | [setEndDate(Date value)](#setEndDate-java.util.Date-) | Stelt de einddatum van de Gantt-diagramweergave in die in de uitvoer moet worden opgenomen. |
|
### ProjectManagementOptions() {#ProjectManagementOptions--}
```
public ProjectManagementOptions()
```


Initialiseert een nieuw exemplaar van de
ProjectManagementOptions
klasse.


### getPageSize() {#getPageSize--}
```
public final PageSize getPageSize()
```


Haalt de paginagrootte van de uitvoer op.


Voor een codevoorbeeld, zie de [documentatie](../https://docs.groupdocs.com/viewer/java/render-ms-project-files/#specify-the-output-page-size).


**Returns:**
[PageSize](../../com.groupdocs.viewer.options/pagesize) - the output page size.

### setPageSize(PageSize value) {#setPageSize-com.groupdocs.viewer.options.PageSize-}
```
public final void setPageSize(PageSize value)
```


Stelt de paginagrootte van de uitvoer in.


Voor een codevoorbeeld, zie de [documentatie](../https://docs.groupdocs.com/viewer/java/render-ms-project-files/#specify-the-output-page-size).


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | value | [PageSize](../../com.groupdocs.viewer.options/pagesize) | De paginagrootte van de uitvoer. |
|

### getTimeUnit() {#getTimeUnit--}
```
public final TimeUnit getTimeUnit()
```


Haalt de tijdseenheid op.


Voor een codevoorbeeld, zie de [documentatie](../https://docs.groupdocs.com/viewer/java/render-ms-project-files/#adjust-the-time-unit).


**Returns:**
[TimeUnit](../../com.groupdocs.viewer.options/timeunit) - the time unit.

### setTimeUnit(TimeUnit value) {#setTimeUnit-com.groupdocs.viewer.options.TimeUnit-}
```
public final void setTimeUnit(TimeUnit value)
```


Haalt de tijdseenheid op.


Voor een codevoorbeeld, zie de [documentatie](../https://docs.groupdocs.com/viewer/java/render-ms-project-files/#adjust-the-time-unit).


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | value | [TimeUnit](../../com.groupdocs.viewer.options/timeunit) | De tijdseenheid. |
|

### getStartDate() {#getStartDate--}
```
public final Date getStartDate()
```


Haalt de begindatum van de Gantt-diagramweergave op die in de uitvoer moet worden opgenomen.


***Note:** Use this option when you need to render a specific time interval of the project within the Gantt Chart View.*
Voor een codevoorbeeld, zie de [documentatie](../https://docs.groupdocs.com/viewer/java/render-ms-project-files/#render-specific-dates).


**Returns:**
java.util.Date - de begindatum van de Gantt-diagramweergave.

### setStartDate(Date value) {#setStartDate-java.util.Date-}
```
public final void setStartDate(Date value)
```


Stelt de begindatum van de Gantt-diagramweergave in die in de uitvoer moet worden opgenomen.


***Note:** Use this option when you need to render a specific time interval of the project within the Gantt Chart View.*
Voor een codevoorbeeld, zie de [documentatie](../https://docs.groupdocs.com/viewer/java/render-ms-project-files/#render-specific-dates).


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | waarde | java.util.Date | De begindatum van de Gantt-diagramweergave. |
|

### getEndDate() {#getEndDate--}
```
public final Date getEndDate()
```


Haalt de einddatum van de Gantt-diagramweergave op die in de uitvoer moet worden opgenomen.


***Note:** Use this option when you need to render a specific time interval of the project within the Gantt Chart View.*
Voor een codevoorbeeld, zie de [documentatie](../https://docs.groupdocs.com/viewer/java/render-ms-project-files/#render-specific-dates).


**Returns:**
java.util.Date - de einddatum van de Gantt-diagramweergave.

### setEndDate(Date value) {#setEndDate-java.util.Date-}
```
public final void setEndDate(Date value)
```


Stelt de einddatum van de Gantt-diagramweergave in die in de uitvoer moet worden opgenomen.


***Note:** Use this option when you need to render a specific time interval of the project within the Gantt Chart View.*
Voor een codevoorbeeld, zie de [documentatie](../https://docs.groupdocs.com/viewer/java/render-ms-project-files/#render-specific-dates).


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | waarde | java.util.Date | De einddatum van de Gantt-diagramweergave. |
|

