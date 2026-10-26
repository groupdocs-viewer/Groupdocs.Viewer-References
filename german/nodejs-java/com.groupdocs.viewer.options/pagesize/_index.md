---
title: "PageSize"
second_title: "GroupDocs.Viewer für Node.js über Java API-Referenz"
description: "Die Größe der Seite."
type: docs
weight: 42
url: /de/nodejs-java/com.groupdocs.viewer.options/pagesize/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum PageSize extends Enum<PageSize>
```

Die Größe der Seite.

Das PageSize-Enum repräsentiert verschiedene Seitengrößen in der GroupDocs.Viewer-Komponente. Es bietet eine Reihe vordefinierter Seitengrößen, die verwendet werden können, um die Abmessungen einer Seite in verschiedenen Dokumentdarstellungs‑Szenarien anzugeben.

Beispielhafte Verwendung:

```

 HtmlViewOptions htmlViewOptions = HtmlViewOptions.forEmbeddedResources();
 ProjectManagementOptions projectManagementOptions = htmlViewOptions.getProjectManagementOptions();
 projectManagementOptions.setPageSize(PageSize.A4);

 try (Viewer viewer = new Viewer("document.mpp")) {
     viewer.view(htmlViewOptions);
     // Use the viewer object for further operations
 }
 
```
## Felder

| Feld | Beschreibung |
| --- | --- |
| [UNSPECIFIED](#UNSPECIFIED) | Die Standard‑, nicht spezifizierte Seitengröße. |
| [LETTER](#LETTER) | Die Größe der Letter-Seite in Punkten beträgt 792 x 612. |
| [LEDGER](#LEDGER) | Die Größe der A0-Seite in Punkten beträgt 3371 x 2384. |
| [A0](#A0) | Die Größe der A1-Seite in Punkten beträgt 2384 x 1685. |
| [A1](#A1) | Die Größe der A2-Seite in Punkten beträgt 1684 x 1190. |
| [A2](#A2) | Die Größe der A3-Seite in Punkten beträgt 1190 x 842. |
| [A3](#A3) | Die Größe der A3-Seite in Punkten beträgt 1190 x 842. |
| [A4](#A4) | Die Größe der A4-Seite in Punkten beträgt 842 x 595. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
### UNSPECIFIED {#UNSPECIFIED}
```
public static final PageSize UNSPECIFIED
```


Die Standard‑, nicht angegebene Seitengröße. Diese Größe wird verwendet, wenn keine bestimmte Seitengröße angegeben ist.

### LETTER {#LETTER}
```
public static final PageSize LETTER
```


Die Größe der Letter-Seite in Punkten beträgt 792 x 612. Diese Seitengröße wird in Nordamerika häufig für Briefe und Dokumente verwendet.

### LEDGER {#LEDGER}
```
public static final PageSize LEDGER
```


Die Größe der A0-Seite in Punkten beträgt 3371 x 2384. Diese große Seitengröße ist Teil des internationalen Standards ISO 216.

### A0 {#A0}
```
public static final PageSize A0
```


Die Größe der A1-Seite in Punkten beträgt 2384 x 1685. Diese Seitengröße ist Teil des internationalen Standards ISO 216.

### A1 {#A1}
```
public static final PageSize A1
```


Die Größe der A2-Seite in Punkten beträgt 1684 x 1190. Diese Seitengröße ist Teil des internationalen Standards ISO 216.

### A2 {#A2}
```
public static final PageSize A2
```


Die Größe der A3-Seite in Punkten beträgt 1190 x 842. Diese Seitengröße ist Teil des internationalen Standards ISO 216.

### A3 {#A3}
```
public static final PageSize A3
```


Die Größe der A3-Seite in Punkten beträgt 1190 x 842. Diese Seitengröße ist Teil des internationalen Standards ISO 216.

### A4 {#A4}
```
public static final PageSize A4
```


Die Größe der A4-Seite in Punkten beträgt 842 x 595. Diese Seitengröße ist Teil des internationalen Standards ISO 216.

### values() {#values--}
```
public static PageSize[] values()
```




**Returns:**
com.groupdocs.viewer.options.PageSize[]
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static PageSize valueOf(String name)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Name | java.lang.String |  |

**Returns:**
[PageSize](../../com.groupdocs.viewer.options/pagesize)
