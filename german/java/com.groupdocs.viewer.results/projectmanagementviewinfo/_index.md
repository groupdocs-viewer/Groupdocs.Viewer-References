---
title: "ProjectManagementViewInfo"
second_title: "GroupDocs.Viewer für Java API-Referenz"
description: "Stellt Ansichtsinformationen für ein MS‑Project‑Dokument dar."
type: docs
weight: 25
url: /de/java/com.groupdocs.viewer.results/projectmanagementviewinfo/
---
**All Implemented Interfaces:**
[com.groupdocs.viewer.results.ViewInfo](../../com.groupdocs.viewer.results/viewinfo)
```
public interface ProjectManagementViewInfo extends ViewInfo
```

Stellt Ansichtsinformationen für ein MS‑Project‑Dokument dar.


Das ProjectManagementViewInfo-Interface definiert den Vertrag für den Zugriff auf und die Manipulation von Ansichtsinformationen
für ein MS Project-Dokument in der GroupDocs.Viewer-Komponente. Es bietet Methoden zum Abrufen von Informationen
wie Start- und Enddaten sowie weitere Eigenschaften.


Beispielverwendung:

````

 try (Viewer viewer = new Viewer("document.mpp")) {
     final ProjectManagementViewInfo viewInfo = (ProjectManagementViewInfo) viewer.getViewInfo(ViewInfoOptions.forPngView());
     // Use the viewInfo object for further operations
 }
 
````


***Note:** The default implementation of this interface is ProjectManagementViewInfoImpl.*

## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getStartDate()](#getStartDate--) | Ruft das Datum und die Uhrzeit ab, zu der das Projekt gestartet wurde. |
|
|  | [setStartDate(Date startDate)](#setStartDate-java.util.Date-) | Legt das Startdatum und die Startzeit für das Projekt fest. |
|
|  | [getEndDate()](#getEndDate--) | Ruft das Datum und die Uhrzeit ab, zu der das Projekt abgeschlossen sein soll. |
|
|  | [setEndDate(Date endDate)](#setEndDate-java.util.Date-) | Legt das Enddatum und die Endzeit für das Projekt fest. |
|
### getStartDate() {#getStartDate--}
```
public abstract Date getStartDate()
```


Ruft das Datum und die Uhrzeit ab, zu der das Projekt gestartet wurde.


**Returns:**
java.util.Date - das Startdatum und die Startzeit des Projekts.

### setStartDate(Date startDate) {#setStartDate-java.util.Date-}
```
public abstract void setStartDate(Date startDate)
```


Legt das Startdatum und die Startzeit für das Projekt fest.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | startDate | java.util.Date | das neue Startdatum und die neue Startzeit, die festgelegt werden sollen. |
|

### getEndDate() {#getEndDate--}
```
public abstract Date getEndDate()
```


Ruft das Datum und die Uhrzeit ab, zu der das Projekt abgeschlossen sein soll.


**Returns:**
java.util.Date - das Enddatum und die Endzeit des Projekts.

### setEndDate(Date endDate) {#setEndDate-java.util.Date-}
```
public abstract void setEndDate(Date endDate)
```


Legt das Enddatum und die Endzeit für das Projekt fest.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | endDate | java.util.Date | das neue Enddatum und die neue Endzeit, die festgelegt werden sollen. |
|

