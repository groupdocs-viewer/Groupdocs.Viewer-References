---
title: "ArchiveViewInfo"
second_title: "GroupDocs.Viewer for Java API-referentie"
description: "Stelt weergave‑informatie voor een archiefbestand."
type: docs
weight: 11
url: /nl/java/com.groupdocs.viewer.results/archiveviewinfo/
---
**All Implemented Interfaces:**
[com.groupdocs.viewer.results.ViewInfo](../../com.groupdocs.viewer.results/viewinfo)
```
public interface ArchiveViewInfo extends ViewInfo
```

Stelt weergave‑informatie voor een archiefbestand.


De ArchiveViewInfo-interface definieert het contract voor het ophalen van weergave-informatie specifiek voor een archiefbestand
in de GroupDocs.Viewer-component. Het biedt methoden om details te benaderen, zoals paginatelling, afmetingen en renderopties
specifiek voor archiefbestanden.


Voorbeeldgebruik:

````

 try (Viewer viewer = new Viewer("document.zip")) {
     ArchiveViewInfo viewInfo = (ArchiveViewInfo) viewer.getViewInfo(ViewInfoOptions.forHtmlView());

     // Use the viewInfo object for further operations
 }
 
````


***Note:** The default implementation of this interface is ArchiveViewInfoImpl.*

## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getFolders()](#getFolders--) | Haalt de lijst met mappen op die zich in het archiefbestand bevinden. |
|
|  | [setFolders(List<String> folders)](#setFolders-java.util.List-java.lang.String--) | Stelt de lijst met mappen in die zich in het archiefbestand bevinden. |
|
### getFolders() {#getFolders--}
```
public abstract List<String> getFolders()
```


Haalt de lijst met mappen op die zich in het archiefbestand bevinden.


**Returns:**
java.util.List<java.lang.String> - de lijst met mappen.

### setFolders(List<String> folders) {#setFolders-java.util.List-java.lang.String--}
```
public abstract void setFolders(List<String> folders)
```


Stelt de lijst met mappen in die zich in het archiefbestand bevinden.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | mappen | java.util.List<java.lang.String> | de lijst met mappen. |
|

