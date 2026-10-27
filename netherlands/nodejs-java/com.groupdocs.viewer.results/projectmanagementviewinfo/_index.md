---
title: "ProjectManagementViewInfo"
second_title: "GroupDocs.Viewer voor Node.js via Java API-referentie"
description: "Stelt weergave-informatie voor een MS Project-document voor."
type: docs
weight: 23
url: /nl/nodejs-java/com.groupdocs.viewer.results/projectmanagementviewinfo/
---
**All Implemented Interfaces:**
[com.groupdocs.viewer.results.ViewInfo](../../com.groupdocs.viewer.results/viewinfo)
```
public interface ProjectManagementViewInfo extends ViewInfo
```

Stelt weergave-informatie voor een MS Project-document voor.

De ProjectManagementViewInfo interface definieert het contract voor het benaderen en manipuleren van weergave‑informatie voor een MS Project‑document in de GroupDocs.Viewer‑component. Het biedt methoden om informatie op te halen zoals de start‑ en einddatums, en andere eigenschappen.

Voorbeeldgebruik:

```

 try (Viewer viewer = new Viewer("document.mpp")) {
     final ProjectManagementViewInfo viewInfo = (ProjectManagementViewInfo) viewer.getViewInfo(ViewInfoOptions.forPngView());
     // Use the viewInfo object for further operations
 }
 
```

***Note:** The default implementation of this interface is ProjectManagementViewInfoImpl.*
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getStartDate()](#getStartDate--) | Haalt de datum en tijd op waarop het project is gestart. |
| [setStartDate(Date startDate)](#setStartDate-java.util.Date-) | Stelt de startdatum en -tijd voor het project in. |
| [getEndDate()](#getEndDate--) | Haalt de datum en tijd op waarop het project voltooid moet worden. |
| [setEndDate(Date endDate)](#setEndDate-java.util.Date-) | Stelt de einddatum en -tijd voor het project in. |
### getStartDate() {#getStartDate--}
```
public abstract Date getStartDate()
```


Haalt de datum en tijd op waarop het project is gestart.

**Returns:**
java.util.Date - de startdatum en -tijd van het project.
### setStartDate(Date startDate) {#setStartDate-java.util.Date-}
```
public abstract void setStartDate(Date startDate)
```


Stelt de startdatum en -tijd voor het project in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| startDate | java.util.Date | de nieuwe startdatum en -tijd die moet worden ingesteld. |

### getEndDate() {#getEndDate--}
```
public abstract Date getEndDate()
```


Haalt de datum en tijd op waarop het project voltooid moet worden.

**Returns:**
java.util.Date - de einddatum en -tijd van het project.
### setEndDate(Date endDate) {#setEndDate-java.util.Date-}
```
public abstract void setEndDate(Date endDate)
```


Stelt de einddatum en -tijd voor het project in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| endDate | java.util.Date | de nieuwe einddatum en -tijd die moet worden ingesteld. |

