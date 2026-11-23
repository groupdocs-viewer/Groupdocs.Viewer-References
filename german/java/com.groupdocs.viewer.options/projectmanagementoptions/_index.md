---
title: "ProjectManagementOptions"
second_title: "GroupDocs.Viewer für Java API-Referenz"
description: "Stellt Optionen zum Rendern von Projektmanagement‑Dateien bereit."
type: docs
weight: 27
url: /de/java/com.groupdocs.viewer.options/projectmanagementoptions/
---
**Inheritance:**
java.lang.Object
```
public class ProjectManagementOptions
```

Stellt Optionen zum Rendern von Projektmanagement‑Dateien bereit.


Die Klasse ProjectManagementOptions kapselt verschiedene Einstellungen und Parameter, die verwendet werden können
um die Darstellung von Projektmanagement-Dateien (wie Microsoft Project oder ähnlichen) zu steuern
in der GroupDocs.Viewer-Komponente.
Für Details siehe die [Dokumentation](../https://docs.groupdocs.com/viewer/java/render-ms-project-files/).


Beispielverwendung:

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


## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
|  | [ProjectManagementOptions()](#ProjectManagementOptions--) | Initialisiert eine neue Instanz von |
ProjectManagementOptions
Klasse.
|
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getPageSize()](#getPageSize--) | Ruft die Größe der Ausgabeseite ab. |
|
|  | [setPageSize(PageSize value)](#setPageSize-com.groupdocs.viewer.options.PageSize-) | Setzt die Größe der Ausgabeseite. |
|
|  | [getTimeUnit()](#getTimeUnit--) | Ruft die Zeiteinheit ab. |
|
|  | [setTimeUnit(TimeUnit value)](#setTimeUnit-com.groupdocs.viewer.options.TimeUnit-) | Ruft die Zeiteinheit ab. |
|
|  | [getStartDate()](#getStartDate--) | Ruft das Startdatum der Gantt-Diagrammansicht ab, das in die Ausgabe aufgenommen werden soll. |
|
|  | [setStartDate(Date value)](#setStartDate-java.util.Date-) | Setzt das Startdatum der Gantt-Diagrammansicht, das in die Ausgabe aufgenommen werden soll. |
|
|  | [getEndDate()](#getEndDate--) | Ruft das Enddatum der Gantt-Diagrammansicht ab, das in die Ausgabe aufgenommen werden soll. |
|
|  | [setEndDate(Date value)](#setEndDate-java.util.Date-) | Setzt das Enddatum der Gantt-Diagrammansicht, das in die Ausgabe aufgenommen werden soll. |
|
### ProjectManagementOptions() {#ProjectManagementOptions--}
```
public ProjectManagementOptions()
```


Initialisiert eine neue Instanz von
ProjectManagementOptions
Klasse.


### getPageSize() {#getPageSize--}
```
public final PageSize getPageSize()
```


Ruft die Größe der Ausgabeseite ab.


Für ein Code‑Beispiel, siehe die [Dokumentation](../https://docs.groupdocs.com/viewer/java/render-ms-project-files/#specify-the-output-page-size).


**Returns:**
[PageSize](../../com.groupdocs.viewer.options/pagesize) - the output page size.

### setPageSize(PageSize value) {#setPageSize-com.groupdocs.viewer.options.PageSize-}
```
public final void setPageSize(PageSize value)
```


Setzt die Größe der Ausgabeseite.


Für ein Code‑Beispiel, siehe die [Dokumentation](../https://docs.groupdocs.com/viewer/java/render-ms-project-files/#specify-the-output-page-size).


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | value | [PageSize](../../com.groupdocs.viewer.options/pagesize) | Die Seitengröße der Ausgabe. |
|

### getTimeUnit() {#getTimeUnit--}
```
public final TimeUnit getTimeUnit()
```


Ruft die Zeiteinheit ab.


Für ein Code‑Beispiel, siehe die [Dokumentation](../https://docs.groupdocs.com/viewer/java/render-ms-project-files/#adjust-the-time-unit).


**Returns:**
[TimeUnit](../../com.groupdocs.viewer.options/timeunit) - the time unit.

### setTimeUnit(TimeUnit value) {#setTimeUnit-com.groupdocs.viewer.options.TimeUnit-}
```
public final void setTimeUnit(TimeUnit value)
```


Ruft die Zeiteinheit ab.


Für ein Code‑Beispiel, siehe die [Dokumentation](../https://docs.groupdocs.com/viewer/java/render-ms-project-files/#adjust-the-time-unit).


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | value | [TimeUnit](../../com.groupdocs.viewer.options/timeunit) | Die Zeiteinheit. |
|

### getStartDate() {#getStartDate--}
```
public final Date getStartDate()
```


Ruft das Startdatum der Gantt-Diagrammansicht ab, das in die Ausgabe aufgenommen werden soll.


***Note:** Use this option when you need to render a specific time interval of the project within the Gantt Chart View.*
Für ein Code‑Beispiel, siehe die [Dokumentation](../https://docs.groupdocs.com/viewer/java/render-ms-project-files/#render-specific-dates).


**Returns:**
java.util.Date - das Startdatum der Gantt‑Diagrammansicht.

### setStartDate(Date value) {#setStartDate-java.util.Date-}
```
public final void setStartDate(Date value)
```


Setzt das Startdatum der Gantt-Diagrammansicht, das in die Ausgabe aufgenommen werden soll.


***Note:** Use this option when you need to render a specific time interval of the project within the Gantt Chart View.*
Für ein Code‑Beispiel, siehe die [Dokumentation](../https://docs.groupdocs.com/viewer/java/render-ms-project-files/#render-specific-dates).


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | value | java.util.Date | Das Startdatum der Gantt‑Diagrammansicht. |
|

### getEndDate() {#getEndDate--}
```
public final Date getEndDate()
```


Ruft das Enddatum der Gantt-Diagrammansicht ab, das in die Ausgabe aufgenommen werden soll.


***Note:** Use this option when you need to render a specific time interval of the project within the Gantt Chart View.*
Für ein Code‑Beispiel, siehe die [Dokumentation](../https://docs.groupdocs.com/viewer/java/render-ms-project-files/#render-specific-dates).


**Returns:**
java.util.Date - das Enddatum der Gantt‑Diagrammansicht.

### setEndDate(Date value) {#setEndDate-java.util.Date-}
```
public final void setEndDate(Date value)
```


Setzt das Enddatum der Gantt-Diagrammansicht, das in die Ausgabe aufgenommen werden soll.


***Note:** Use this option when you need to render a specific time interval of the project within the Gantt Chart View.*
Für ein Code‑Beispiel, siehe die [Dokumentation](../https://docs.groupdocs.com/viewer/java/render-ms-project-files/#render-specific-dates).


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | value | java.util.Date | Das Enddatum der Gantt‑Diagrammansicht. |
|

