---
title: "PathUtils"
second_title: "GroupDocs.Viewer für Java API-Referenz"
description: "Die Klasse PathUtils stellt Hilfsmethoden für die Arbeit mit Dateipfaden bereit."
type: docs
weight: 13
url: /de/java/com.groupdocs.viewer.utils/pathutils/
---
**Inheritance:**
java.lang.Object
```
public class PathUtils
```

Die Klasse PathUtils stellt Hilfsmethoden für die Arbeit mit Dateipfaden bereit.


Die PathUtils-Klasse enthält statische Methoden, die es Ihnen ermöglichen, verschiedene Vorgänge auszuführen
auf Dateipfaden im GroupDocs.Viewer‑Komponente.


Beispielverwendung:

````

 String combinedPath = PathUtils.combine("part", "of", "path");
 String fileName = PathUtils.getFileName("/path/to/file.txt");
 
````


## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [combine(String[] params)](#combine-java.lang.String...-) | Kombiniert Pfadteile mithilfe des Trennzeichens. |
|
|  | [getFileName(String path)](#getFileName-java.lang.String-) | Ermittelt den Dateinamen. |
|
### combine(String[] params) {#combine-java.lang.String...-}
```
public static String combine(String[] params)
```


Kombiniert Pfadteile mithilfe des Trennzeichens.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Parameter | java.lang.String[] | die Pfadteile |
|

**Returns:**
java.lang.String - der Ergebnis-Pfad

### getFileName(String path) {#getFileName-java.lang.String-}
```
public static String getFileName(String path)
```


Ermittelt den Dateinamen.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Pfad | java.lang.String | der Pfad |
|

**Returns:**
java.lang.String - der Dateiname

