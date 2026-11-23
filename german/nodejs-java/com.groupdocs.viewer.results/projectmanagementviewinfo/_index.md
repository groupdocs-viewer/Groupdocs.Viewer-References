---
title: "ProjectManagementViewInfo"
second_title: "GroupDocs.Viewer für Node.js über Java API-Referenz"
description: "Stellt Ansichtsinformationen für ein MS‑Project‑Dokument dar."
type: docs
weight: 23
url: /de/nodejs-java/com.groupdocs.viewer.results/projectmanagementviewinfo/
---
**All Implemented Interfaces:**
[com.groupdocs.viewer.results.ViewInfo](../../com.groupdocs.viewer.results/viewinfo)
```
public interface ProjectManagementViewInfo extends ViewInfo
```

Stellt Ansichtsinformationen für ein MS‑Project‑Dokument dar.

Das ProjectManagementViewInfo‑Interface definiert den Vertrag für den Zugriff auf und die Manipulation von Ansichtsinformationen für ein MS‑Project‑Dokument in der GroupDocs.Viewer‑Komponente. Es stellt Methoden bereit, um Informationen wie Start‑ und Enddaten sowie weitere Eigenschaften abzurufen.

Beispielhafte Verwendung:

```

 try (Viewer viewer = new Viewer("document.mpp")) {
     final ProjectManagementViewInfo viewInfo = (ProjectManagementViewInfo) viewer.getViewInfo(ViewInfoOptions.forPngView());
     // Use the viewInfo object for further operations
 }
 
```

***Note:** The default implementation of this interface is ProjectManagementViewInfoImpl.*
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getStartDate()](#getStartDate--) | Ruft das Datum und die Uhrzeit ab, zu dem das Projekt gestartet wurde. |
| [setStartDate(Date startDate)](#setStartDate-java.util.Date-) | Setzt das Startdatum und die Startzeit für das Projekt. |
| [getEndDate()](#getEndDate--) | Ruft das Datum und die Uhrzeit ab, zu dem das Projekt abgeschlossen werden soll. |
| [setEndDate(Date endDate)](#setEndDate-java.util.Date-) | Setzt das Enddatum und die Endzeit für das Projekt. |
### getStartDate() {#getStartDate--}
```
public abstract Date getStartDate()
```


Ruft das Datum und die Uhrzeit ab, zu dem das Projekt gestartet wurde.

**Returns:**
java.util.Date - das Startdatum und die Startzeit des Projekts.
### setStartDate(Date startDate) {#setStartDate-java.util.Date-}
```
public abstract void setStartDate(Date startDate)
```


Setzt das Startdatum und die Startzeit für das Projekt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| startDate | java.util.Date | das neue Startdatum und die neue Startzeit, die festgelegt werden soll. |

### getEndDate() {#getEndDate--}
```
public abstract Date getEndDate()
```


Ruft das Datum und die Uhrzeit ab, zu dem das Projekt abgeschlossen werden soll.

**Returns:**
java.util.Date - das Enddatum und die Endzeit des Projekts.
### setEndDate(Date endDate) {#setEndDate-java.util.Date-}
```
public abstract void setEndDate(Date endDate)
```


Setzt das Enddatum und die Endzeit für das Projekt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| endDate | java.util.Date | das neue Enddatum und die neue Endzeit, die festgelegt werden soll. |

