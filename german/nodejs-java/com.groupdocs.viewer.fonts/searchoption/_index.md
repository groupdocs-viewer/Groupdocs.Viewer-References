---
title: "SearchOption"
second_title: "GroupDocs.Viewer für Node.js über Java API-Referenz"
description: "Gibt an, ob im aktuellen Ordner oder im aktuellen Ordner und allen Unterordnern gesucht werden soll."
type: docs
weight: 21
url: /de/nodejs-java/com.groupdocs.viewer.fonts/searchoption/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum SearchOption extends Enum<SearchOption>
```

Gibt an, ob im aktuellen Ordner oder im aktuellen Ordner und allen Unterordnern gesucht werden soll.

Das SearchOption‑Enum wird verwendet, um den Umfang der Schriftsuchoperation in der GroupDocs.Viewer‑API anzugeben.

Beispielhafte Verwendung:

```

 FontSettings.setFontSources(new FolderFontSource("/path/to/fonts/folder", SearchOption.ALL_FOLDERS));
 
```

***Note:** This enum is typically used to specify strategy of searching fonts in provided directory.*
## Felder

| Feld | Beschreibung |
| --- | --- |
| [TOP_FOLDER_ONLY](#TOP-FOLDER-ONLY) | Bezieht nur den aktuellen Ordner in die Suche ein. |
| [ALL_FOLDERS](#ALL-FOLDERS) | Schließt den aktuellen Ordner und alle Unterordner in die Suche ein. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
### TOP_FOLDER_ONLY {#TOP-FOLDER-ONLY}
```
public static final SearchOption TOP_FOLDER_ONLY
```


Bezieht nur den aktuellen Ordner in die Suche ein.

### ALL_FOLDERS {#ALL-FOLDERS}
```
public static final SearchOption ALL_FOLDERS
```


Schließt den aktuellen Ordner und alle Unterordner in die Suche ein.

### values() {#values--}
```
public static SearchOption[] values()
```




**Returns:**
com.groupdocs.viewer.fonts.SearchOption[]
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static SearchOption valueOf(String name)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Name | java.lang.String |  |

**Returns:**
[SearchOption](../../com.groupdocs.viewer.fonts/searchoption)
