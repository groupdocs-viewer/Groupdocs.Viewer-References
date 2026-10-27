---
title: "PathUtils"
second_title: "GroupDocs.Viewer voor Node.js via Java API-referentie"
description: "De PathUtils-klasse biedt hulpmethoden voor het werken met bestandspaden."
type: docs
weight: 11
url: /nl/nodejs-java/com.groupdocs.viewer.utils/pathutils/
---
**Inheritance:**
java.lang.Object
```
public class PathUtils
```

De PathUtils-klasse biedt hulpmethoden voor het werken met bestandspaden.

De PathUtils‑klasse bevat statische methoden waarmee u verschillende bewerkingen op bestandspaden in de GroupDocs.Viewer‑component kunt uitvoeren.

Voorbeeldgebruik:

```

 String combinedPath = PathUtils.combine("part", "of", "path");
 String fileName = PathUtils.getFileName("/path/to/file.txt");
 
```
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [combine(String[] params)](#combine-java.lang.String...-) | Combineer padonderdelen met behulp van een scheidingsteken. |
| [getFileName(String path)](#getFileName-java.lang.String-) | Haalt bestandsnaam op. |
### combine(String[] params) {#combine-java.lang.String...-}
```
public static String combine(String[] params)
```


Combineer padonderdelen met behulp van een scheidingsteken.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| params | java.lang.String[] | de padonderdelen |

**Returns:**
java.lang.String - het resultaatpad
### getFileName(String path) {#getFileName-java.lang.String-}
```
public static String getFileName(String path)
```


Haalt bestandsnaam op.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| pad | java.lang.String | het pad |

**Returns:**
java.lang.String - de bestandsnaam
