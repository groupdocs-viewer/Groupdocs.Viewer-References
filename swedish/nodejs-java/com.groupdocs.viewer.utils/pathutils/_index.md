---
title: "PathUtils"
second_title: "GroupDocs.Viewer för Node.js via Java API-referens"
description: "PathUtils-klassen tillhandahåller hjälpfunktioner för att arbeta med filsökvägar."
type: docs
weight: 11
url: /sv/nodejs-java/com.groupdocs.viewer.utils/pathutils/
---
**Inheritance:**
java.lang.Object
```
public class PathUtils
```

PathUtils-klassen tillhandahåller hjälpfunktioner för att arbeta med filsökvägar.

PathUtils‑klassen innehåller statiska metoder som låter dig utföra olika operationer på filsökvägar i GroupDocs.Viewer‑komponenten.

Exempel på användning:

```

 String combinedPath = PathUtils.combine("part", "of", "path");
 String fileName = PathUtils.getFileName("/path/to/file.txt");
 
```
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [combine(String[] params)](#combine-java.lang.String...-) | Kombinera sökvägsdelar med separator. |
| [getFileName(String path)](#getFileName-java.lang.String-) | Hämtar filnamn. |
### combine(String[] params) {#combine-java.lang.String...-}
```
public static String combine(String[] params)
```


Kombinera sökvägsdelar med separator.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| parametrar | java.lang.String[] | sökvägsdelarna |

**Returns:**
java.lang.String - resultatsökvägen
### getFileName(String path) {#getFileName-java.lang.String-}
```
public static String getFileName(String path)
```


Hämtar filnamn.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sökväg | java.lang.String | sökvägen |

**Returns:**
java.lang.String - filnamnet
