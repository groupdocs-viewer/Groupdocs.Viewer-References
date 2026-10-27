---
title: "LotusNotesViewInfo"
second_title: "GroupDocs.Viewer för Node.js via Java API-referens"
description: "Representerar vyinformation för Lotus Notes-databaslagring."
type: docs
weight: 19
url: /sv/nodejs-java/com.groupdocs.viewer.results/lotusnotesviewinfo/
---
**All Implemented Interfaces:**
[com.groupdocs.viewer.results.ViewInfo](../../com.groupdocs.viewer.results/viewinfo)
```
public interface LotusNotesViewInfo extends ViewInfo
```

Representerar vyinformation för Lotus Notes-databaslagring.

LotusNotesViewInfo-gränssnittet definierar kontraktet för att komma åt och manipulera vyinformation för Lotus Notes-databaslagring i GroupDocs.Viewer-komponenten. Det tillhandahåller metoder för att hämta information såsom antal anteckningar och andra egenskaper.

Exempel på användning:

```

 try (Viewer viewer = new Viewer("document.nsf")) {
     final LotusNotesViewInfo viewInfo = (LotusNotesViewInfo) viewer.getViewInfo(ViewInfoOptions.forHtmlView());
     // Use the viewInfo object for further operations
 }
 
```

***Note:** The default implementation of this interface is LotusNotesViewInfoImpl.*
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getNotesCount()](#getNotesCount--) | Hämtar antalet anteckningar i lagringen. |
| [setNotesCount(int count)](#setNotesCount-int-) | Ställer in antalet anteckningar i lagringen. |
### getNotesCount() {#getNotesCount--}
```
public abstract int getNotesCount()
```


Hämtar antalet anteckningar i lagringen.

**Returns:**
int - antalet anteckningar i lagringen.
### setNotesCount(int count) {#setNotesCount-int-}
```
public abstract void setNotesCount(int count)
```


Ställer in antalet anteckningar i lagringen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| antal | int | antalet anteckningar i lagringen. |

