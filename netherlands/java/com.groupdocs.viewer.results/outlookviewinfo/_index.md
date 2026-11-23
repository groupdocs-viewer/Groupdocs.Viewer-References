---
title: "OutlookViewInfo"
second_title: "GroupDocs.Viewer for Java API-referentie"
description: "Stelt weergave‑informatie voor een Outlook‑gegevensbestand voor."
type: docs
weight: 22
url: /nl/java/com.groupdocs.viewer.results/outlookviewinfo/
---
**All Implemented Interfaces:**
[com.groupdocs.viewer.results.ViewInfo](../../com.groupdocs.viewer.results/viewinfo)
```
public interface OutlookViewInfo extends ViewInfo
```

Stelt weergave‑informatie voor een Outlook‑gegevensbestand voor.


De OutlookViewInfo interface definieert het contract voor het benaderen en manipuleren van weergave-informatie
voor een Outlook-gegevensbestand in de GroupDocs.Viewer component. Het biedt methoden om informatie op te halen
zoals een lijst met mappen, en andere eigenschappen.


Voorbeeldgebruik:

````

 try (Viewer viewer = new Viewer("document.pst")) {
     final OutlookViewInfo viewInfo = (OutlookViewInfo) viewer.getViewInfo(ViewInfoOptions.forHtmlView());
     // Use the viewInfo object for further operations
 }
 
````


***Note:** The default implementation of this interface is OutlookViewInfoImpl.*

## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getFolders()](#getFolders--) | Haalt de lijst met mappen op die in het Outlook-gegevensbestand zijn opgenomen. |
|
|  | [setFolders(List<String> list)](#setFolders-java.util.List-java.lang.String--) | Stelt de lijst met mappen in die in het Outlook-gegevensbestand zijn opgenomen. |
|
### getFolders() {#getFolders--}
```
public abstract List<String> getFolders()
```


Haalt de lijst met mappen op die in het Outlook-gegevensbestand zijn opgenomen.


**Returns:**
java.util.List<java.lang.String> - de lijst met mappen.

### setFolders(List<String> list) {#setFolders-java.util.List-java.lang.String--}
```
public abstract void setFolders(List<String> list)
```


Stelt de lijst met mappen in die in het Outlook-gegevensbestand zijn opgenomen.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | list | java.util.List<java.lang.String> | de lijst met mappen. |
|

