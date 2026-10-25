---
title: "FolderFontSource"
second_title: "GroupDocs.Viewer for Java API-referentie"
description: "Stelt een map voor die TrueType-lettertypen bevat."
type: docs
weight: 10
url: /nl/java/com.groupdocs.viewer.fonts/folderfontsource/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.viewer.fonts.FontSource](../../com.groupdocs.viewer.fonts/fontsource), com.aspose.ms.System.IEquatable
```
public final class FolderFontSource implements FontSource, System.IEquatable<FolderFontSource>
```

Stelt een map voor die TrueType-lettertypen bevat.


De FolderFontSource‑klasse wordt gebruikt om een maplocatie op te geven die TrueType‑lettertypen bevat.
Het stelt de GroupDocs.Viewer‑API in staat om toegang te krijgen tot de lettertypen die in de opgegeven map zijn opgeslagen voor documentrendering.


Voorbeeldgebruik:

````

 FontSettings.setFontSources(new FolderFontSource("/path/to/fonts/folder", SearchOption.ALL_FOLDERS));
 
````


## Constructors

| Constructor | Beschrijving |
| --- | --- |
|  | [FolderFontSource(String folderPath, SearchOption searchOption)](#FolderFontSource-java.lang.String-com.groupdocs.viewer.fonts.SearchOption-) | Initialiseert een nieuw exemplaar van de |
FolderFontSource
klasse.
|
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [isEqualTo(FolderFontSource left, FolderFontSource right)](#isEqualTo-com.groupdocs.viewer.fonts.FolderFontSource-com.groupdocs.viewer.fonts.FolderFontSource-) | Bepaalt of twee |
FolderFontSource
objecten hetzelfde zijn.
|
|  | [isNotEqualTo(FolderFontSource left, FolderFontSource right)](#isNotEqualTo-com.groupdocs.viewer.fonts.FolderFontSource-com.groupdocs.viewer.fonts.FolderFontSource-) | Bepaalt of twee |
FolderFontSource
objecten niet hetzelfde zijn.
|
|  | [getFolderPath()](#getFolderPath--) | Haalt het pad op naar de map die TrueType‑lettertypen bevat. |
|
|  | [getSearchOption()](#getSearchOption--) | Haalt de zoekoptie op die aangeeft of er gezocht moet worden in de huidige map, of in de huidige map en alle submappen. |
|
|  | [isRecursive()](#isRecursive--) | Controleert of de lettertypen recursief zouden worden doorzocht. |
|
|  | [equals(FolderFontSource other)](#equals-com.groupdocs.viewer.fonts.FolderFontSource-) | Bepaalt of de huidige |
FolderFontSource
is hetzelfde als de opgegeven
FolderFontSource
object.
|
|  | [equals(Object o)](#equals-java.lang.Object-) | Bepaalt of de huidige |
FolderFontSource
is hetzelfde als het opgegeven object.
|
|  | [hashCode()](#hashCode--) | Retourneert de hashcode voor de huidige |
FolderFontSource
object.
|
|  | [toString()](#toString--) | Retourneert een string die het huidige object vertegenwoordigt. |
|
### FolderFontSource(String folderPath, SearchOption searchOption) {#FolderFontSource-java.lang.String-com.groupdocs.viewer.fonts.SearchOption-}
```
public FolderFontSource(String folderPath, SearchOption searchOption)
```


Initialiseert een nieuw exemplaar van de
FolderFontSource
klasse.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | folderPath | java.lang.String | Pad naar de map die TrueType-lettertypen bevat. |
|
|  | searchOption | [SearchOption](../../com.groupdocs.viewer.fonts/searchoption) | Specificeert of de huidige map moet worden doorzocht, of de huidige map en alle submappen. |
|

### isEqualTo(FolderFontSource left, FolderFontSource right) {#isEqualTo-com.groupdocs.viewer.fonts.FolderFontSource-com.groupdocs.viewer.fonts.FolderFontSource-}
```
public static boolean isEqualTo(FolderFontSource left, FolderFontSource right)
```


Bepaalt of twee
FolderFontSource
objecten hetzelfde zijn.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | left | [FolderFontSource](../../com.groupdocs.viewer.fonts/folderfontsource) | Het linker  FolderFontSource  object. |
|
|  | right | [FolderFontSource](../../com.groupdocs.viewer.fonts/folderfontsource) | Het rechter  FolderFontSource  object. |
|

**Returns:**
boolean -  true  als beide  FolderFontSource  objecten hetzelfde zijn; anders,  false .

### isNotEqualTo(FolderFontSource left, FolderFontSource right) {#isNotEqualTo-com.groupdocs.viewer.fonts.FolderFontSource-com.groupdocs.viewer.fonts.FolderFontSource-}
```
public static boolean isNotEqualTo(FolderFontSource left, FolderFontSource right)
```


Bepaalt of twee
FolderFontSource
objecten niet hetzelfde zijn.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | left | [FolderFontSource](../../com.groupdocs.viewer.fonts/folderfontsource) | Het linker  FolderFontSource  object. |
|
|  | right | [FolderFontSource](../../com.groupdocs.viewer.fonts/folderfontsource) | Het rechter  FolderFontSource  object. |
|

**Returns:**
boolean -  true  als beide  FolderFontSource  objecten niet hetzelfde zijn; anders,  false .

### getFolderPath() {#getFolderPath--}
```
public String getFolderPath()
```


Haalt het pad op naar de map die TrueType‑lettertypen bevat.


**Returns:**
java.lang.String - het pad naar de map die TrueType-lettertypen bevat.

### getSearchOption() {#getSearchOption--}
```
public SearchOption getSearchOption()
```


Haalt de zoekoptie op die aangeeft of er gezocht moet worden in de huidige map, of in de huidige map en alle submappen.


**Returns:**
[SearchOption](../../com.groupdocs.viewer.fonts/searchoption) - the search option.

### isRecursive() {#isRecursive--}
```
public boolean isRecursive()
```


Controleert of de lettertypen recursief zouden worden doorzocht.


**Returns:**
boolean -  true  als de lettertypen recursief zouden worden doorzocht,  false  anders.

### equals(FolderFontSource other) {#equals-com.groupdocs.viewer.fonts.FolderFontSource-}
```
public boolean equals(FolderFontSource other)
```


Bepaalt of de huidige
FolderFontSource
is hetzelfde als de opgegeven
FolderFontSource
object.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | other | [FolderFontSource](../../com.groupdocs.viewer.fonts/folderfontsource) | Het object om te vergelijken met het huidige  FolderFontSource  object. |
|

**Returns:**
boolean -  true  als beide  FolderFontSource  objecten hetzelfde zijn; anders,  false

### equals(Object o) {#equals-java.lang.Object-}
```
public boolean equals(Object o)
```


Bepaalt of de huidige
FolderFontSource
is hetzelfde als het opgegeven object.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | o | java.lang.Object | Het object om te vergelijken met het huidige  FolderFontSource  object. |
|

**Returns:**
boolean -  true  als de  obj  parameter van het type  FolderFontSource  is en hetzelfde is als het huidige  FolderFontSource  object; anders,  false

### hashCode() {#hashCode--}
```
public int hashCode()
```


Retourneert de hashcode voor de huidige
FolderFontSource
object.


**Returns:**
int - een hashcode voor het huidige  FolderFontSource  object.

### toString() {#toString--}
```
public String toString()
```


Retourneert een string die het huidige object vertegenwoordigt.


**Returns:**
java.lang.String - een string die het huidige object vertegenwoordigt.

