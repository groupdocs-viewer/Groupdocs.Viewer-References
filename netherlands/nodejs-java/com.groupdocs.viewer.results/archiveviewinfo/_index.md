---
title: "ArchiveViewInfo"
second_title: "GroupDocs.Viewer voor Node.js via Java API-referentie"
description: "Stelt weergave-informatie voor een archiefbestand voor."
type: docs
weight: 11
url: /nl/nodejs-java/com.groupdocs.viewer.results/archiveviewinfo/
---
**All Implemented Interfaces:**
[com.groupdocs.viewer.results.ViewInfo](../../com.groupdocs.viewer.results/viewinfo)
```
public interface ArchiveViewInfo extends ViewInfo
```

Stelt weergave-informatie voor een archiefbestand voor.

De ArchiveViewInfo-interface definieert het contract voor het ophalen van weergave-informatie die specifiek is voor een archiefbestand in de GroupDocs.Viewer-component. Het biedt methoden om details zoals paginatelling, afmetingen en renderopties die specifiek zijn voor archiefbestanden te benaderen.

Voorbeeldgebruik:

```

 try (Viewer viewer = new Viewer("document.zip")) {
     ArchiveViewInfo viewInfo = (ArchiveViewInfo) viewer.getViewInfo(ViewInfoOptions.forHtmlView());

     // Use the viewInfo object for further operations
 }
 
```

***Note:** The default implementation of this interface is ArchiveViewInfoImpl.*
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getFolders()](#getFolders--) | Haalt de lijst met mappen op die zich in het archiefbestand bevinden. |
| [setFolders(List<String> folders)](#setFolders-java.util.List-java.lang.String--) | Stelt de lijst met mappen in die zich in het archiefbestand bevinden. |
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
| mappen | java.util.List<java.lang.String> | de lijst met mappen. |

