---
title: "ProjectManagementViewInfo"
second_title: "GroupDocs.Viewer för Java API-referens"
description: "Representerar vyinformation för ett MS Project‑dokument."
type: docs
weight: 25
url: /sv/java/com.groupdocs.viewer.results/projectmanagementviewinfo/
---
**All Implemented Interfaces:**
[com.groupdocs.viewer.results.ViewInfo](../../com.groupdocs.viewer.results/viewinfo)
```
public interface ProjectManagementViewInfo extends ViewInfo
```

Representerar vyinformation för ett MS Project‑dokument.


ProjectManagementViewInfo‑gränssnittet definierar kontraktet för åtkomst till och manipulering av vyinformation
för ett MS Project-dokument i GroupDocs.Viewer‑komponenten. Den tillhandahåller metoder för att hämta information
såsom start- och slutdatum samt andra egenskaper.


Exempel på användning:

````

 try (Viewer viewer = new Viewer("document.mpp")) {
     final ProjectManagementViewInfo viewInfo = (ProjectManagementViewInfo) viewer.getViewInfo(ViewInfoOptions.forPngView());
     // Use the viewInfo object for further operations
 }
 
````


***Note:** The default implementation of this interface is ProjectManagementViewInfoImpl.*

## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getStartDate()](#getStartDate--) | Hämtar datum och tid då projektet startade. |
|
|  | [setStartDate(Date startDate)](#setStartDate-java.util.Date-) | Sätter startdatum och tid för projektet. |
|
|  | [getEndDate()](#getEndDate--) | Hämtar datum och tid då projektet ska slutföras. |
|
|  | [setEndDate(Date endDate)](#setEndDate-java.util.Date-) | Sätter slutdatum och tid för projektet. |
|
### getStartDate() {#getStartDate--}
```
public abstract Date getStartDate()
```


Hämtar datum och tid då projektet startade.


**Returns:**
java.util.Date - startdatum och tid för projektet.

### setStartDate(Date startDate) {#setStartDate-java.util.Date-}
```
public abstract void setStartDate(Date startDate)
```


Sätter startdatum och tid för projektet.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | startDate | java.util.Date | det nya startdatumet och tiden som ska sättas. |
|

### getEndDate() {#getEndDate--}
```
public abstract Date getEndDate()
```


Hämtar datum och tid då projektet ska slutföras.


**Returns:**
java.util.Date - slutdatum och tid för projektet.

### setEndDate(Date endDate) {#setEndDate-java.util.Date-}
```
public abstract void setEndDate(Date endDate)
```


Sätter slutdatum och tid för projektet.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | endDate | java.util.Date | det nya slutdatumet och tiden som ska sättas. |
|

