---
title: "LotusNotesViewInfo"
second_title: "GroupDocs.Viewer für Java API-Referenz"
description: "Stellt Ansichtsinformationen für die Lotus‑Notes‑Datenbankspeicherung dar."
type: docs
weight: 19
url: /de/java/com.groupdocs.viewer.results/lotusnotesviewinfo/
---
**All Implemented Interfaces:**
[com.groupdocs.viewer.results.ViewInfo](../../com.groupdocs.viewer.results/viewinfo)
```
public interface LotusNotesViewInfo extends ViewInfo
```

Stellt Ansichtsinformationen für die Lotus‑Notes‑Datenbankspeicherung dar.


Das LotusNotesViewInfo-Interface definiert den Vertrag für den Zugriff auf und die Manipulation von Ansichtsinformationen
für die Lotus Notes-Datenbankspeicherung in der GroupDocs.Viewer-Komponente. Sie bietet Methoden zum Abrufen von Informationen
wie z. B. die Notizanzahl und weitere Eigenschaften.


Beispielverwendung:

````

 try (Viewer viewer = new Viewer("document.nsf")) {
     final LotusNotesViewInfo viewInfo = (LotusNotesViewInfo) viewer.getViewInfo(ViewInfoOptions.forHtmlView());
     // Use the viewInfo object for further operations
 }
 
````


***Note:** The default implementation of this interface is LotusNotesViewInfoImpl.*

## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getNotesCount()](#getNotesCount--) | Ruft die Anzahl der Notizen im Speicher ab. |
|
|  | [setNotesCount(int count)](#setNotesCount-int-) | Setzt die Anzahl der Notizen im Speicher. |
|
### getNotesCount() {#getNotesCount--}
```
public abstract int getNotesCount()
```


Ruft die Anzahl der Notizen im Speicher ab.


**Returns:**
int - die Anzahl der Notizen im Speicher.

### setNotesCount(int count) {#setNotesCount-int-}
```
public abstract void setNotesCount(int count)
```


Setzt die Anzahl der Notizen im Speicher.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Anzahl | int | die Anzahl der Notizen im Speicher. |
|

