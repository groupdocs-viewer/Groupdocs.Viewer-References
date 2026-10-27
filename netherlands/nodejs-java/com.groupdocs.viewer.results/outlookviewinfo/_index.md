---
title: "OutlookViewInfo"
second_title: "GroupDocs.Viewer voor Node.js via Java API-referentie"
description: "Stelt weergave-informatie voor een Outlook-gegevensbestand voor."
type: docs
weight: 20
url: /nl/nodejs-java/com.groupdocs.viewer.results/outlookviewinfo/
---
**All Implemented Interfaces:**
[com.groupdocs.viewer.results.ViewInfo](../../com.groupdocs.viewer.results/viewinfo)
```
public interface OutlookViewInfo extends ViewInfo
```

Stelt weergave-informatie voor een Outlook-gegevensbestand voor.

De OutlookViewInfo-interface definieert het contract voor het benaderen en manipuleren van weergave-informatie voor een Outlook-gegevensbestand in de GroupDocs.Viewer-component. Het biedt methoden om informatie op te halen, zoals een lijst met mappen, en andere eigenschappen.

Voorbeeldgebruik:

```

 try (Viewer viewer = new Viewer("document.pst")) {
     final OutlookViewInfo viewInfo = (OutlookViewInfo) viewer.getViewInfo(ViewInfoOptions.forHtmlView());
     // Use the viewInfo object for further operations
 }
 
```

***Note:** The default implementation of this interface is OutlookViewInfoImpl.*
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getFolders()](#getFolders--) | Haalt de lijst met mappen op die zich in het Outlook-gegevensbestand bevinden. |
| [setFolders(List<String> list)](#setFolders-java.util.List-java.lang.String--) | Stelt de lijst met mappen in die zich in het Outlook-gegevensbestand bevinden. |
### getFolders() {#getFolders--}
```
public abstract List<String> getFolders()
```


Haalt de lijst met mappen op die zich in het Outlook-gegevensbestand bevinden.

**Returns:**
java.util.List<java.lang.String> - de lijst met mappen.
### setFolders(List<String> list) {#setFolders-java.util.List-java.lang.String--}
```
public abstract void setFolders(List<String> list)
```


Stelt de lijst met mappen in die zich in het Outlook-gegevensbestand bevinden.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| lijst | java.util.List<java.lang.String> | de lijst met mappen. |

