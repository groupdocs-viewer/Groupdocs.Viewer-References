---
title: "FolderFontSource"
second_title: "GroupDocs.Viewer för Node.js via Java API-referens"
description: "Representerar en mapp som innehåller TrueType-typsnitt."
type: docs
weight: 10
url: /sv/nodejs-java/com.groupdocs.viewer.fonts/folderfontsource/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.viewer.fonts.FontSource](../../com.groupdocs.viewer.fonts/fontsource), com.aspose.ms.System.IEquatable
```
public final class FolderFontSource implements FontSource, System.IEquatable<FolderFontSource>
```

Representerar en mapp som innehåller TrueType-typsnitt.

Klassen FolderFontSource används för att ange en mappplats som innehåller TrueType-teckensnitt. Den möjliggör för GroupDocs.Viewer API att komma åt teckensnitten som lagras i den angivna mappen för dokumentrenderingsändamål.

Exempel på användning:

```

 FontSettings.setFontSources(new FolderFontSource("/path/to/fonts/folder", SearchOption.ALL_FOLDERS));
 
```
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [FolderFontSource(String folderPath, SearchOption searchOption)](#FolderFontSource-java.lang.String-com.groupdocs.viewer.fonts.SearchOption-) | Initierar en ny instans av klassen  FolderFontSource . |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [isEqualTo(FolderFontSource left, FolderFontSource right)](#isEqualTo-com.groupdocs.viewer.fonts.FolderFontSource-com.groupdocs.viewer.fonts.FolderFontSource-) | Bestämmer om två  FolderFontSource  objekt är desamma. |
| [isNotEqualTo(FolderFontSource left, FolderFontSource right)](#isNotEqualTo-com.groupdocs.viewer.fonts.FolderFontSource-com.groupdocs.viewer.fonts.FolderFontSource-) | Bestämmer om två  FolderFontSource  objekt inte är desamma. |
| [getFolderPath()](#getFolderPath--) | Hämtar sökvägen till mappen som innehåller TrueType-teckensnitt. |
| [getSearchOption()](#getSearchOption--) | Hämtar sökalternativet som anger om den aktuella mappen eller den aktuella mappen och alla undermappar ska sökas. |
| [isRecursive()](#isRecursive--) | Kontrollerar om teckensnitten skulle sökas rekursivt. |
| [equals(FolderFontSource other)](#equals-com.groupdocs.viewer.fonts.FolderFontSource-) | Bestämmer om den aktuella  FolderFontSource  är densamma som det angivna  FolderFontSource  objektet. |
| [equals(Object o)](#equals-java.lang.Object-) | Bestämmer om den aktuella  FolderFontSource  är densamma som det angivna objektet. |
| [hashCode()](#hashCode--) | Returnerar hashkoden för det aktuella  FolderFontSource  objektet. |
| [toString()](#toString--) | Returnerar en sträng som representerar det aktuella objektet. |
### FolderFontSource(String folderPath, SearchOption searchOption) {#FolderFontSource-java.lang.String-com.groupdocs.viewer.fonts.SearchOption-}
```
public FolderFontSource(String folderPath, SearchOption searchOption)
```


Initierar en ny instans av klassen  FolderFontSource .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| folderPath | java.lang.String | Sökväg till mappen som innehåller TrueType-teckensnitt. |
| searchOption | [SearchOption](../../com.groupdocs.viewer.fonts/searchoption) | Anger om den aktuella mappen eller den aktuella mappen och alla undermappar ska sökas. |

### isEqualTo(FolderFontSource left, FolderFontSource right) {#isEqualTo-com.groupdocs.viewer.fonts.FolderFontSource-com.groupdocs.viewer.fonts.FolderFontSource-}
```
public static boolean isEqualTo(FolderFontSource left, FolderFontSource right)
```


Bestämmer om två  FolderFontSource  objekt är desamma.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| left | [FolderFontSource](../../com.groupdocs.viewer.fonts/folderfontsource) | Det vänstra  FolderFontSource  objektet. |
| right | [FolderFontSource](../../com.groupdocs.viewer.fonts/folderfontsource) | Det högra  FolderFontSource  objektet. |

**Returns:**
boolean -  true  om båda  FolderFontSource  objekten är desamma; annars,  false .
### isNotEqualTo(FolderFontSource left, FolderFontSource right) {#isNotEqualTo-com.groupdocs.viewer.fonts.FolderFontSource-com.groupdocs.viewer.fonts.FolderFontSource-}
```
public static boolean isNotEqualTo(FolderFontSource left, FolderFontSource right)
```


Bestämmer om två  FolderFontSource  objekt inte är desamma.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| left | [FolderFontSource](../../com.groupdocs.viewer.fonts/folderfontsource) | Det vänstra  FolderFontSource  objektet. |
| right | [FolderFontSource](../../com.groupdocs.viewer.fonts/folderfontsource) | Det högra  FolderFontSource  objektet. |

**Returns:**
boolean -  true  om båda  FolderFontSource  objekten inte är desamma; annars,  false .
### getFolderPath() {#getFolderPath--}
```
public String getFolderPath()
```


Hämtar sökvägen till mappen som innehåller TrueType-teckensnitt.

**Returns:**
java.lang.String - sökvägen till mappen som innehåller TrueType-teckensnitt.
### getSearchOption() {#getSearchOption--}
```
public SearchOption getSearchOption()
```


Hämtar sökalternativet som anger om den aktuella mappen eller den aktuella mappen och alla undermappar ska sökas.

**Returns:**
[SearchOption](../../com.groupdocs.viewer.fonts/searchoption) - the search option.
### isRecursive() {#isRecursive--}
```
public boolean isRecursive()
```


Kontrollerar om teckensnitten skulle sökas rekursivt.

**Returns:**
boolean -  true  om teckensnitten skulle sökas rekursivt,  false  annars.
### equals(FolderFontSource other) {#equals-com.groupdocs.viewer.fonts.FolderFontSource-}
```
public boolean equals(FolderFontSource other)
```


Bestämmer om den aktuella  FolderFontSource  är densamma som det angivna  FolderFontSource  objektet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| other | [FolderFontSource](../../com.groupdocs.viewer.fonts/folderfontsource) | Objektet att jämföra med det aktuella  FolderFontSource  objektet. |

**Returns:**
boolean -  true  om båda  FolderFontSource  objekten är desamma; annars,  false
### equals(Object o) {#equals-java.lang.Object-}
```
public boolean equals(Object o)
```


Bestämmer om den aktuella  FolderFontSource  är densamma som det angivna objektet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| o | java.lang.Object | Objektet att jämföra med det aktuella  FolderFontSource  objektet. |

**Returns:**
boolean -  true  om parametern  obj  är av typen  FolderFontSource  och är densamma som det aktuella  FolderFontSource  objektet; annars,  false
### hashCode() {#hashCode--}
```
public int hashCode()
```


Returnerar hashkoden för det aktuella  FolderFontSource  objektet.

**Returns:**
int - en hashkod för det aktuella  FolderFontSource  objektet.
### toString() {#toString--}
```
public String toString()
```


Returnerar en sträng som representerar det aktuella objektet.

**Returns:**
java.lang.String - en sträng som representerar det aktuella objektet.
