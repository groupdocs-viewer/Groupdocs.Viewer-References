---
title: "ArchiveViewInfo"
second_title: "GroupDocs.Viewer für Java API-Referenz"
description: "Stellt Ansichtsinformationen für eine Archivdatei dar."
type: docs
weight: 11
url: /de/java/com.groupdocs.viewer.results/archiveviewinfo/
---
**All Implemented Interfaces:**
[com.groupdocs.viewer.results.ViewInfo](../../com.groupdocs.viewer.results/viewinfo)
```
public interface ArchiveViewInfo extends ViewInfo
```

Stellt Ansichtsinformationen für eine Archivdatei dar.


Das ArchiveViewInfo-Interface definiert den Vertrag für das Abrufen von Ansichtsinformationen, die spezifisch für eine Archivdatei sind
im GroupDocs.Viewer‑Komponente. Es bietet Methoden zum Zugriff auf Details wie Seitenanzahl, Abmessungen und Rendering‑Optionen
spezifisch für Archivdateien.


Beispielverwendung:

````

 try (Viewer viewer = new Viewer("document.zip")) {
     ArchiveViewInfo viewInfo = (ArchiveViewInfo) viewer.getViewInfo(ViewInfoOptions.forHtmlView());

     // Use the viewInfo object for further operations
 }
 
````


***Note:** The default implementation of this interface is ArchiveViewInfoImpl.*

## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getFolders()](#getFolders--) | Ruft die Liste der im Archivdatei enthaltenen Ordner ab. |
|
|  | [setFolders(List<String> folders)](#setFolders-java.util.List-java.lang.String--) | Setzt die Liste der im Archivdatei enthaltenen Ordner. |
|
### getFolders() {#getFolders--}
```
public abstract List<String> getFolders()
```


Ruft die Liste der im Archivdatei enthaltenen Ordner ab.


**Returns:**
java.util.List<java.lang.String> - die Liste der Ordner.

### setFolders(List<String> folders) {#setFolders-java.util.List-java.lang.String--}
```
public abstract void setFolders(List<String> folders)
```


Setzt die Liste der im Archivdatei enthaltenen Ordner.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Ordner | java.util.List<java.lang.String> | die Liste der Ordner. |
|

