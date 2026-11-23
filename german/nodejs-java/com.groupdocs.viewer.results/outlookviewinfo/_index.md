---
title: "OutlookViewInfo"
second_title: "GroupDocs.Viewer für Node.js über Java API-Referenz"
description: "Stellt Ansichtsinformationen für eine Outlook‑Datendatei dar."
type: docs
weight: 20
url: /de/nodejs-java/com.groupdocs.viewer.results/outlookviewinfo/
---
**All Implemented Interfaces:**
[com.groupdocs.viewer.results.ViewInfo](../../com.groupdocs.viewer.results/viewinfo)
```
public interface OutlookViewInfo extends ViewInfo
```

Stellt Ansichtsinformationen für eine Outlook‑Datendatei dar.

Das OutlookViewInfo-Interface definiert den Vertrag für den Zugriff auf und die Manipulation von Ansichtsinformationen für eine Outlook‑Data‑Datei in der GroupDocs.Viewer‑Komponente. Es bietet Methoden zum Abrufen von Informationen wie einer Liste von Ordnern und anderen Eigenschaften.

Beispielhafte Verwendung:

```

 try (Viewer viewer = new Viewer("document.pst")) {
     final OutlookViewInfo viewInfo = (OutlookViewInfo) viewer.getViewInfo(ViewInfoOptions.forHtmlView());
     // Use the viewInfo object for further operations
 }
 
```

***Note:** The default implementation of this interface is OutlookViewInfoImpl.*
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getFolders()](#getFolders--) | Ruft die Liste der im Outlook‑Data‑Datei enthaltenen Ordner ab. |
| [setFolders(List<String> list)](#setFolders-java.util.List-java.lang.String--) | Setzt die Liste der im Outlook‑Data‑Datei enthaltenen Ordner. |
### getFolders() {#getFolders--}
```
public abstract List<String> getFolders()
```


Ruft die Liste der im Outlook‑Data‑Datei enthaltenen Ordner ab.

**Returns:**
java.util.List<java.lang.String> - die Liste der Ordner.
### setFolders(List<String> list) {#setFolders-java.util.List-java.lang.String--}
```
public abstract void setFolders(List<String> list)
```


Setzt die Liste der im Outlook‑Data‑Datei enthaltenen Ordner.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Liste | java.util.List<java.lang.String> | die Liste der Ordner. |

