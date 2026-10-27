---
title: "LotusNotesViewInfo"
second_title: "GroupDocs.Viewer voor Node.js via Java API-referentie"
description: "Stelt weergave-informatie voor Lotus Notes-databaseopslag voor."
type: docs
weight: 19
url: /nl/nodejs-java/com.groupdocs.viewer.results/lotusnotesviewinfo/
---
**All Implemented Interfaces:**
[com.groupdocs.viewer.results.ViewInfo](../../com.groupdocs.viewer.results/viewinfo)
```
public interface LotusNotesViewInfo extends ViewInfo
```

Stelt weergave-informatie voor Lotus Notes-databaseopslag voor.

De LotusNotesViewInfo-interface definieert het contract voor het benaderen en manipuleren van weergave-informatie voor Lotus Notes-databaseopslag in de GroupDocs.Viewer-component. Het biedt methoden om informatie op te halen, zoals het aantal notities, en andere eigenschappen.

Voorbeeldgebruik:

```

 try (Viewer viewer = new Viewer("document.nsf")) {
     final LotusNotesViewInfo viewInfo = (LotusNotesViewInfo) viewer.getViewInfo(ViewInfoOptions.forHtmlView());
     // Use the viewInfo object for further operations
 }
 
```

***Note:** The default implementation of this interface is LotusNotesViewInfoImpl.*
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getNotesCount()](#getNotesCount--) | Haalt het aantal notities in de opslag op. |
| [setNotesCount(int count)](#setNotesCount-int-) | Stelt het aantal notities in de opslag in. |
### getNotesCount() {#getNotesCount--}
```
public abstract int getNotesCount()
```


Haalt het aantal notities in de opslag op.

**Returns:**
int - het aantal notities in de opslag.
### setNotesCount(int count) {#setNotesCount-int-}
```
public abstract void setNotesCount(int count)
```


Stelt het aantal notities in de opslag in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| aantal | int | het aantal notities in de opslag. |

