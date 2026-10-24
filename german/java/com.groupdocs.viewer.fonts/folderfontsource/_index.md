---
title: "FolderFontSource"
second_title: "GroupDocs.Viewer für Java API-Referenz"
description: "Stellt einen Ordner dar, der TrueType-Schriftarten enthält."
type: docs
weight: 10
url: /de/java/com.groupdocs.viewer.fonts/folderfontsource/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.viewer.fonts.FontSource](../../com.groupdocs.viewer.fonts/fontsource), com.aspose.ms.System.IEquatable
```
public final class FolderFontSource implements FontSource, System.IEquatable<FolderFontSource>
```

Stellt einen Ordner dar, der TrueType-Schriftarten enthält.


Die Klasse FolderFontSource wird verwendet, um einen Ordnerpfad anzugeben, der TrueType-Schriften enthält.
Sie ermöglicht der GroupDocs.Viewer API den Zugriff auf die im angegebenen Ordner gespeicherten Schriften für die Dokumentendarstellung.


Beispielverwendung:

````

 FontSettings.setFontSources(new FolderFontSource("/path/to/fonts/folder", SearchOption.ALL_FOLDERS));
 
````


## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
|  | [FolderFontSource(String folderPath, SearchOption searchOption)](#FolderFontSource-java.lang.String-com.groupdocs.viewer.fonts.SearchOption-) | Initialisiert eine neue Instanz von |
FolderFontSource
Klasse.
|
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [isEqualTo(FolderFontSource left, FolderFontSource right)](#isEqualTo-com.groupdocs.viewer.fonts.FolderFontSource-com.groupdocs.viewer.fonts.FolderFontSource-) | Bestimmt, ob zwei |
FolderFontSource
Objekte gleich sind.
|
|  | [isNotEqualTo(FolderFontSource left, FolderFontSource right)](#isNotEqualTo-com.groupdocs.viewer.fonts.FolderFontSource-com.groupdocs.viewer.fonts.FolderFontSource-) | Bestimmt, ob zwei |
FolderFontSource
Objekte nicht gleich sind.
|
|  | [getFolderPath()](#getFolderPath--) | Liefert den Pfad zum Ordner, der TrueType-Schriften enthält. |
|
|  | [getSearchOption()](#getSearchOption--) | Liefert die Suchoption, die angibt, ob nur der aktuelle Ordner oder der aktuelle Ordner und alle Unterordner durchsucht werden sollen. |
|
|  | [isRecursive()](#isRecursive--) | Prüft, ob die Schriften rekursiv durchsucht würden. |
|
|  | [equals(FolderFontSource other)](#equals-com.groupdocs.viewer.fonts.FolderFontSource-) | Bestimmt, ob das aktuelle |
FolderFontSource
mit dem angegebenen übereinstimmt
FolderFontSource
Objekt.
|
|  | [equals(Object o)](#equals-java.lang.Object-) | Bestimmt, ob das aktuelle |
FolderFontSource
ist dasselbe wie das angegebene Objekt.
|
|  | [hashCode()](#hashCode--) | Gibt den Hashcode für das aktuelle |
FolderFontSource
Objekt.
|
|  | [toString()](#toString--) | Gibt eine Zeichenkette zurück, die das aktuelle Objekt darstellt. |
|
### FolderFontSource(String folderPath, SearchOption searchOption) {#FolderFontSource-java.lang.String-com.groupdocs.viewer.fonts.SearchOption-}
```
public FolderFontSource(String folderPath, SearchOption searchOption)
```


Initialisiert eine neue Instanz von
FolderFontSource
Klasse.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | folderPath | java.lang.String | Pfad zum Ordner, der TrueType-Schriften enthält. |
|
|  | searchOption | [SearchOption](../../com.groupdocs.viewer.fonts/searchoption) | Gibt an, ob der aktuelle Ordner oder der aktuelle Ordner und alle Unterordner durchsucht werden sollen. |
|

### isEqualTo(FolderFontSource left, FolderFontSource right) {#isEqualTo-com.groupdocs.viewer.fonts.FolderFontSource-com.groupdocs.viewer.fonts.FolderFontSource-}
```
public static boolean isEqualTo(FolderFontSource left, FolderFontSource right)
```


Bestimmt, ob zwei
FolderFontSource
Objekte gleich sind.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | left | [FolderFontSource](../../com.groupdocs.viewer.fonts/folderfontsource) | Das linke  FolderFontSource  Objekt. |
|
|  | right | [FolderFontSource](../../com.groupdocs.viewer.fonts/folderfontsource) | Das rechte  FolderFontSource  Objekt. |
|

**Returns:**
boolean -  true  wenn beide  FolderFontSource  Objekte identisch sind; andernfalls  false .

### isNotEqualTo(FolderFontSource left, FolderFontSource right) {#isNotEqualTo-com.groupdocs.viewer.fonts.FolderFontSource-com.groupdocs.viewer.fonts.FolderFontSource-}
```
public static boolean isNotEqualTo(FolderFontSource left, FolderFontSource right)
```


Bestimmt, ob zwei
FolderFontSource
Objekte nicht gleich sind.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | left | [FolderFontSource](../../com.groupdocs.viewer.fonts/folderfontsource) | Das linke  FolderFontSource  Objekt. |
|
|  | right | [FolderFontSource](../../com.groupdocs.viewer.fonts/folderfontsource) | Das rechte  FolderFontSource  Objekt. |
|

**Returns:**
boolean -  true  wenn beide  FolderFontSource  Objekte nicht identisch sind; andernfalls  false .

### getFolderPath() {#getFolderPath--}
```
public String getFolderPath()
```


Liefert den Pfad zum Ordner, der TrueType-Schriften enthält.


**Returns:**
java.lang.String - der Pfad zum Ordner, der TrueType-Schriften enthält.

### getSearchOption() {#getSearchOption--}
```
public SearchOption getSearchOption()
```


Liefert die Suchoption, die angibt, ob nur der aktuelle Ordner oder der aktuelle Ordner und alle Unterordner durchsucht werden sollen.


**Returns:**
[SearchOption](../../com.groupdocs.viewer.fonts/searchoption) - the search option.

### isRecursive() {#isRecursive--}
```
public boolean isRecursive()
```


Prüft, ob die Schriften rekursiv durchsucht würden.


**Returns:**
boolean -  true  wenn die Schriften rekursiv durchsucht würden,  false  andernfalls.

### equals(FolderFontSource other) {#equals-com.groupdocs.viewer.fonts.FolderFontSource-}
```
public boolean equals(FolderFontSource other)
```


Bestimmt, ob das aktuelle
FolderFontSource
mit dem angegebenen übereinstimmt
FolderFontSource
Objekt.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | other | [FolderFontSource](../../com.groupdocs.viewer.fonts/folderfontsource) | Das Objekt, das mit dem aktuellen  FolderFontSource  Objekt verglichen wird. |
|

**Returns:**
boolean -  true  wenn beide  FolderFontSource  Objekte identisch sind; andernfalls  false

### equals(Object o) {#equals-java.lang.Object-}
```
public boolean equals(Object o)
```


Bestimmt, ob das aktuelle
FolderFontSource
ist dasselbe wie das angegebene Objekt.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | o | java.lang.Object | Das Objekt, das mit dem aktuellen  FolderFontSource  Objekt verglichen wird. |
|

**Returns:**
boolean -  true  wenn der  obj  Parameter vom Typ  FolderFontSource  ist und mit dem aktuellen  FolderFontSource  Objekt identisch ist; andernfalls  false

### hashCode() {#hashCode--}
```
public int hashCode()
```


Gibt den Hashcode für das aktuelle
FolderFontSource
Objekt.


**Returns:**
int - ein Hashcode für das aktuelle  FolderFontSource  Objekt.

### toString() {#toString--}
```
public String toString()
```


Gibt eine Zeichenkette zurück, die das aktuelle Objekt darstellt.


**Returns:**
java.lang.String - eine Zeichenkette, die das aktuelle Objekt darstellt.

