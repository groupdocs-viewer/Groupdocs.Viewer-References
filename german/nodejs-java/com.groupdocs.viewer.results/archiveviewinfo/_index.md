---
title: "ArchiveViewInfo"
second_title: "GroupDocs.Viewer für Node.js über Java API-Referenz"
description: "Stellt Ansichtsinformationen für eine Archivdatei dar."
type: docs
weight: 11
url: /de/nodejs-java/com.groupdocs.viewer.results/archiveviewinfo/
---
**All Implemented Interfaces:**
[com.groupdocs.viewer.results.ViewInfo](../../com.groupdocs.viewer.results/viewinfo)
```
public interface ArchiveViewInfo extends ViewInfo
```

Stellt Ansichtsinformationen für eine Archivdatei dar.

Das ArchiveViewInfo-Interface definiert den Vertrag zur Ermittlung von Ansichtsinformationen, die spezifisch für eine Archivdatei in der GroupDocs.Viewer-Komponente sind. Es stellt Methoden bereit, um Details wie Seitenanzahl, Abmessungen und Rendering-Optionen, die spezifisch für Archivdateien sind, abzurufen.

Beispielhafte Verwendung:

```

 try (Viewer viewer = new Viewer("document.zip")) {
     ArchiveViewInfo viewInfo = (ArchiveViewInfo) viewer.getViewInfo(ViewInfoOptions.forHtmlView());

     // Use the viewInfo object for further operations
 }
 
```

***Note:** The default implementation of this interface is ArchiveViewInfoImpl.*
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getFolders()](#getFolders--) | Ruft die Liste der Ordner ab, die in der Archivdatei enthalten sind. |
| [setFolders(List<String> folders)](#setFolders-java.util.List-java.lang.String--) | Setzt die Liste der Ordner, die in der Archivdatei enthalten sind. |
### getFolders() {#getFolders--}
```
public abstract List<String> getFolders()
```


Ruft die Liste der Ordner ab, die in der Archivdatei enthalten sind.

**Returns:**
java.util.List<java.lang.String> - die Liste der Ordner.
### setFolders(List<String> folders) {#setFolders-java.util.List-java.lang.String--}
```
public abstract void setFolders(List<String> folders)
```


Setzt die Liste der Ordner, die in der Archivdatei enthalten sind.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| folders | java.util.List<java.lang.String> | die Liste der Ordner. |

