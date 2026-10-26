---
title: "PathUtils"
second_title: "GroupDocs.Viewer für Node.js über Java API-Referenz"
description: "Die Klasse PathUtils stellt Dienstprogrammmethoden zum Arbeiten mit Dateipfaden bereit."
type: docs
weight: 11
url: /de/nodejs-java/com.groupdocs.viewer.utils/pathutils/
---
**Inheritance:**
java.lang.Object
```
public class PathUtils
```

Die Klasse PathUtils stellt Dienstprogrammmethoden zum Arbeiten mit Dateipfaden bereit.

Die Klasse PathUtils enthält statische Methoden, die es Ihnen ermöglichen, verschiedene Operationen mit Dateipfaden in der GroupDocs.Viewer-Komponente durchzuführen.

Beispielhafte Verwendung:

```

 String combinedPath = PathUtils.combine("part", "of", "path");
 String fileName = PathUtils.getFileName("/path/to/file.txt");
 
```
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [combine(String[] params)](#combine-java.lang.String...-) | Kombiniert Pfadteile mithilfe eines Trennzeichens. |
| [getFileName(String path)](#getFileName-java.lang.String-) | Ermittelt den Dateinamen. |
### combine(String[] params) {#combine-java.lang.String...-}
```
public static String combine(String[] params)
```


Kombiniert Pfadteile mithilfe eines Trennzeichens.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| params | java.lang.String[] | die Pfadteile |

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
| Pfad | java.lang.String | der Pfad |

**Returns:**
java.lang.String - der Dateiname
