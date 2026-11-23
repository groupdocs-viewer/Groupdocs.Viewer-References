---
title: "SearchOption"
second_title: "Référence API de GroupDocs.Viewer pour Node.js via Java"
description: "Spécifie s'il faut rechercher le dossier actuel ou le dossier actuel et tous les sous‑dossiers."
type: docs
weight: 21
url: /fr/nodejs-java/com.groupdocs.viewer.fonts/searchoption/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum SearchOption extends Enum<SearchOption>
```

Spécifie s'il faut rechercher dans le dossier actuel, ou dans le dossier actuel et tous ses sous-dossiers.

L'énumération SearchOption est utilisée pour spécifier la portée de l'opération de recherche de polices dans l'API GroupDocs.Viewer.

Exemple d'utilisation :

```

 FontSettings.setFontSources(new FolderFontSource("/path/to/fonts/folder", SearchOption.ALL_FOLDERS));
 
```

***Note:** This enum is typically used to specify strategy of searching fonts in provided directory.*
## Champs

| Champ | Description |
| --- | --- |
| [TOP_FOLDER_ONLY](#TOP-FOLDER-ONLY) | Inclut uniquement le dossier actuel dans une recherche. |
| [ALL_FOLDERS](#ALL-FOLDERS) | Inclut le dossier actuel et tous les sous‑dossiers dans une recherche. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
### TOP_FOLDER_ONLY {#TOP-FOLDER-ONLY}
```
public static final SearchOption TOP_FOLDER_ONLY
```


Inclut uniquement le dossier actuel dans une recherche.

### ALL_FOLDERS {#ALL-FOLDERS}
```
public static final SearchOption ALL_FOLDERS
```


Inclut le dossier actuel et tous les sous‑dossiers dans une recherche.

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
| Paramètre | Type | Description |
| --- | --- | --- |
| nom | java.lang.String |  |

**Returns:**
[SearchOption](../../com.groupdocs.viewer.fonts/searchoption)
