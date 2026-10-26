---
title: "SearchOption"
second_title: "GroupDocs.Viewer per Node.js via Java Riferimento API"
description: "Specifica se cercare la cartella corrente o la cartella corrente e tutte le sottocartelle."
type: docs
weight: 21
url: /it/nodejs-java/com.groupdocs.viewer.fonts/searchoption/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum SearchOption extends Enum<SearchOption>
```

Specifica se cercare nella cartella corrente, o nella cartella corrente e in tutte le sottocartelle.

L'enumerazione SearchOption viene utilizzata per specificare l'ambito dell'operazione di ricerca dei font nell'API GroupDocs.Viewer.

Esempio di utilizzo:

```

 FontSettings.setFontSources(new FolderFontSource("/path/to/fonts/folder", SearchOption.ALL_FOLDERS));
 
```

***Note:** This enum is typically used to specify strategy of searching fonts in provided directory.*
## Campi

| Campo | Descrizione |
| --- | --- |
| [TOP_FOLDER_ONLY](#TOP-FOLDER-ONLY) | Include solo la cartella corrente in una ricerca. |
| [ALL_FOLDERS](#ALL-FOLDERS) | Include la cartella corrente e tutte le sottocartelle in una ricerca. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
### TOP_FOLDER_ONLY {#TOP-FOLDER-ONLY}
```
public static final SearchOption TOP_FOLDER_ONLY
```


Include solo la cartella corrente in una ricerca.

### ALL_FOLDERS {#ALL-FOLDERS}
```
public static final SearchOption ALL_FOLDERS
```


Include la cartella corrente e tutte le sottocartelle in una ricerca.

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
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| nome | java.lang.String |  |

**Returns:**
[SearchOption](../../com.groupdocs.viewer.fonts/searchoption)
