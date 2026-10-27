---
title: "SearchOption"
second_title: "GroupDocs.Viewer för Node.js via Java API-referens"
description: "Anger om den aktuella mappen eller den aktuella mappen och alla undermappar ska sökas."
type: docs
weight: 21
url: /sv/nodejs-java/com.groupdocs.viewer.fonts/searchoption/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum SearchOption extends Enum<SearchOption>
```

Anger om den aktuella mappen ska sökas, eller den aktuella mappen och alla undermappar.

The SearchOption‑enumet används för att specificera omfattningen av teckensnittssökoperationen i GroupDocs.Viewer API.

Exempel på användning:

```

 FontSettings.setFontSources(new FolderFontSource("/path/to/fonts/folder", SearchOption.ALL_FOLDERS));
 
```

***Note:** This enum is typically used to specify strategy of searching fonts in provided directory.*
## Fält

| Fält | Beskrivning |
| --- | --- |
| [TOP_FOLDER_ONLY](#TOP-FOLDER-ONLY) | Inkluderar endast den aktuella mappen i en sökning. |
| [ALL_FOLDERS](#ALL-FOLDERS) | Inkluderar den aktuella mappen och alla undermappar i en sökning. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
### TOP_FOLDER_ONLY {#TOP-FOLDER-ONLY}
```
public static final SearchOption TOP_FOLDER_ONLY
```


Inkluderar endast den aktuella mappen i en sökning.

### ALL_FOLDERS {#ALL-FOLDERS}
```
public static final SearchOption ALL_FOLDERS
```


Inkluderar den aktuella mappen och alla undermappar i en sökning.

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
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| namn | java.lang.String |  |

**Returns:**
[SearchOption](../../com.groupdocs.viewer.fonts/searchoption)
