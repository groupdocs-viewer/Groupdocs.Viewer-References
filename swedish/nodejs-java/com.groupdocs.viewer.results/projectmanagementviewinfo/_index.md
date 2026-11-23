---
title: "ProjectManagementViewInfo"
second_title: "GroupDocs.Viewer för Node.js via Java API-referens"
description: "Representerar vyinformation för ett MS Project-dokument."
type: docs
weight: 23
url: /sv/nodejs-java/com.groupdocs.viewer.results/projectmanagementviewinfo/
---
**All Implemented Interfaces:**
[com.groupdocs.viewer.results.ViewInfo](../../com.groupdocs.viewer.results/viewinfo)
```
public interface ProjectManagementViewInfo extends ViewInfo
```

Representerar vyinformation för ett MS Project-dokument.

ProjectManagementViewInfo‑gränssnittet definierar kontraktet för åtkomst och manipulering av vyinformation för ett MS Project‑dokument i GroupDocs.Viewer‑komponenten. Det tillhandahåller metoder för att hämta information såsom start‑ och slutdatum samt andra egenskaper.

Exempel på användning:

```

 try (Viewer viewer = new Viewer("document.mpp")) {
     final ProjectManagementViewInfo viewInfo = (ProjectManagementViewInfo) viewer.getViewInfo(ViewInfoOptions.forPngView());
     // Use the viewInfo object for further operations
 }
 
```

***Note:** The default implementation of this interface is ProjectManagementViewInfoImpl.*
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getStartDate()](#getStartDate--) | Hämtar datum och tid då projektet startade. |
| [setStartDate(Date startDate)](#setStartDate-java.util.Date-) | Ställer in startdatum och -tid för projektet. |
| [getEndDate()](#getEndDate--) | Hämtar datum och tid då projektet ska slutföras. |
| [setEndDate(Date endDate)](#setEndDate-java.util.Date-) | Ställer in slutdatum och -tid för projektet. |
### getStartDate() {#getStartDate--}
```
public abstract Date getStartDate()
```


Hämtar datum och tid då projektet startade.

**Returns:**
java.util.Date - projektets startdatum och -tid.
### setStartDate(Date startDate) {#setStartDate-java.util.Date-}
```
public abstract void setStartDate(Date startDate)
```


Ställer in startdatum och -tid för projektet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| startDate | java.util.Date | det nya startdatumet och -tiden som ska sättas. |

### getEndDate() {#getEndDate--}
```
public abstract Date getEndDate()
```


Hämtar datum och tid då projektet ska slutföras.

**Returns:**
java.util.Date - projektets slutdatum och -tid.
### setEndDate(Date endDate) {#setEndDate-java.util.Date-}
```
public abstract void setEndDate(Date endDate)
```


Ställer in slutdatum och -tid för projektet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| endDate | java.util.Date | det nya slutdatumet och -tiden som ska sättas. |

