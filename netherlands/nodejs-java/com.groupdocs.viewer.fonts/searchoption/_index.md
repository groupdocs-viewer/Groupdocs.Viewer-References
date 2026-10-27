---
title: "SearchOption"
second_title: "GroupDocs.Viewer voor Node.js via Java API-referentie"
description: "Specificeert of er gezocht moet worden in de huidige map of in de huidige map en alle submappen."
type: docs
weight: 21
url: /nl/nodejs-java/com.groupdocs.viewer.fonts/searchoption/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum SearchOption extends Enum<SearchOption>
```

Specificeert of de huidige map moet worden doorzocht, of de huidige map en alle submappen.

De SearchOption enum wordt gebruikt om de reikwijdte van de lettertypezoekbewerking in de GroupDocs.Viewer API te specificeren.

Voorbeeldgebruik:

```

 FontSettings.setFontSources(new FolderFontSource("/path/to/fonts/folder", SearchOption.ALL_FOLDERS));
 
```

***Note:** This enum is typically used to specify strategy of searching fonts in provided directory.*
## Velden

| Veld | Beschrijving |
| --- | --- |
| [TOP_FOLDER_ONLY](#TOP-FOLDER-ONLY) | Bevat alleen de huidige map in een zoekopdracht. |
| [ALL_FOLDERS](#ALL-FOLDERS) | Bevat de huidige map en alle submappen in een zoekopdracht. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
### TOP_FOLDER_ONLY {#TOP-FOLDER-ONLY}
```
public static final SearchOption TOP_FOLDER_ONLY
```


Bevat alleen de huidige map in een zoekopdracht.

### ALL_FOLDERS {#ALL-FOLDERS}
```
public static final SearchOption ALL_FOLDERS
```


Bevat de huidige map en alle submappen in een zoekopdracht.

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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| naam | java.lang.String |  |

**Returns:**
[SearchOption](../../com.groupdocs.viewer.fonts/searchoption)
