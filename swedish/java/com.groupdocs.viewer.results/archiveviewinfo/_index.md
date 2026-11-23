---
title: "ArchiveViewInfo"
second_title: "GroupDocs.Viewer för Java API-referens"
description: "Representerar vyinformation för en arkivfil."
type: docs
weight: 11
url: /sv/java/com.groupdocs.viewer.results/archiveviewinfo/
---
**All Implemented Interfaces:**
[com.groupdocs.viewer.results.ViewInfo](../../com.groupdocs.viewer.results/viewinfo)
```
public interface ArchiveViewInfo extends ViewInfo
```

Representerar vyinformation för en arkivfil.


ArchiveViewInfo‑gränssnittet definierar kontraktet för att hämta vyinformation som är specifik för en arkivfil
i GroupDocs.Viewer‑komponenten. Den tillhandahåller metoder för att komma åt detaljer såsom sidantal, dimensioner och renderingsalternativ
specifik för arkivfiler.


Exempel på användning:

````

 try (Viewer viewer = new Viewer("document.zip")) {
     ArchiveViewInfo viewInfo = (ArchiveViewInfo) viewer.getViewInfo(ViewInfoOptions.forHtmlView());

     // Use the viewInfo object for further operations
 }
 
````


***Note:** The default implementation of this interface is ArchiveViewInfoImpl.*

## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getFolders()](#getFolders--) | Hämtar listan över mappar som finns i arkivfilen. |
|
|  | [setFolders(List<String> folders)](#setFolders-java.util.List-java.lang.String--) | Ställer in listan över mappar som finns i arkivfilen. |
|
### getFolders() {#getFolders--}
```
public abstract List<String> getFolders()
```


Hämtar listan över mappar som finns i arkivfilen.


**Returns:**
java.util.List<java.lang.String> - listan över mappar.

### setFolders(List<String> folders) {#setFolders-java.util.List-java.lang.String--}
```
public abstract void setFolders(List<String> folders)
```


Ställer in listan över mappar som finns i arkivfilen.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | mappar | java.util.List<java.lang.String> | listan över mappar. |
|

