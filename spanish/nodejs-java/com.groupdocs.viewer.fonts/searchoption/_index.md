---
title: "SearchOption"
second_title: "Referencia de API de GroupDocs.Viewer para Node.js vía Java"
description: "Especifica si buscar en la carpeta actual o en la carpeta actual y todas sus subcarpetas."
type: docs
weight: 21
url: /es/nodejs-java/com.groupdocs.viewer.fonts/searchoption/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum SearchOption extends Enum<SearchOption>
```

Especifica si buscar en la carpeta actual, o en la carpeta actual y todas sus subcarpetas.

El enum SearchOption se utiliza para especificar el alcance de la operación de búsqueda de fuentes en la API de GroupDocs.Viewer.

Ejemplo de uso:

```

 FontSettings.setFontSources(new FolderFontSource("/path/to/fonts/folder", SearchOption.ALL_FOLDERS));
 
```

***Note:** This enum is typically used to specify strategy of searching fonts in provided directory.*
## Fields

| Field | Descripción |
| --- | --- |
| [TOP_FOLDER_ONLY](#TOP-FOLDER-ONLY) | Incluye solo la carpeta actual en una búsqueda. |
| [ALL_FOLDERS](#ALL-FOLDERS) | Incluye la carpeta actual y todas las subcarpetas en una búsqueda. |
## Métodos

| Método | Descripción |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
### TOP_FOLDER_ONLY {#TOP-FOLDER-ONLY}
```
public static final SearchOption TOP_FOLDER_ONLY
```


Incluye solo la carpeta actual en una búsqueda.

### ALL_FOLDERS {#ALL-FOLDERS}
```
public static final SearchOption ALL_FOLDERS
```


Incluye la carpeta actual y todas las subcarpetas en una búsqueda.

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
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| nombre | java.lang.String |  |

**Returns:**
[SearchOption](../../com.groupdocs.viewer.fonts/searchoption)
