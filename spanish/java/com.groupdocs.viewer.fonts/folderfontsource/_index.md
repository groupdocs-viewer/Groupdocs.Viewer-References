---
title: "FolderFontSource"
second_title: "GroupDocs.Viewer for Java Referencia de API"
description: "Representa una carpeta que contiene fuentes TrueType."
type: docs
weight: 10
url: /es/java/com.groupdocs.viewer.fonts/folderfontsource/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.viewer.fonts.FontSource](../../com.groupdocs.viewer.fonts/fontsource), com.aspose.ms.System.IEquatable
```
public final class FolderFontSource implements FontSource, System.IEquatable<FolderFontSource>
```

Representa una carpeta que contiene fuentes TrueType.


La clase FolderFontSource se usa para especificar una ubicación de carpeta que contiene fuentes TrueType.
Permite que la API GroupDocs.Viewer acceda a las fuentes almacenadas en la carpeta especificada para propósitos de renderizado de documentos.


Ejemplo de uso:

````

 FontSettings.setFontSources(new FolderFontSource("/path/to/fonts/folder", SearchOption.ALL_FOLDERS));
 
````


## Constructores

| Constructor | Descripción |
| --- | --- |
|  | [FolderFontSource(String folderPath, SearchOption searchOption)](#FolderFontSource-java.lang.String-com.groupdocs.viewer.fonts.SearchOption-) | Inicializa una nueva instancia de la |
FolderFontSource
clase.
|
## Métodos

| Método | Descripción |
| --- | --- |
|  | [isEqualTo(FolderFontSource left, FolderFontSource right)](#isEqualTo-com.groupdocs.viewer.fonts.FolderFontSource-com.groupdocs.viewer.fonts.FolderFontSource-) | Determina si dos |
FolderFontSource
objetos son los mismos.
|
|  | [isNotEqualTo(FolderFontSource left, FolderFontSource right)](#isNotEqualTo-com.groupdocs.viewer.fonts.FolderFontSource-com.groupdocs.viewer.fonts.FolderFontSource-) | Determina si dos |
FolderFontSource
objetos no son los mismos.
|
|  | [getFolderPath()](#getFolderPath--) | Obtiene la ruta a la carpeta que contiene fuentes TrueType. |
|
|  | [getSearchOption()](#getSearchOption--) | Obtiene la opción de búsqueda que especifica si buscar en la carpeta actual, o en la carpeta actual y todas sus subcarpetas. |
|
|  | [isRecursive()](#isRecursive--) | Comprueba si las fuentes se buscarían de forma recursiva. |
|
|  | [equals(FolderFontSource other)](#equals-com.groupdocs.viewer.fonts.FolderFontSource-) | Determina si el actual |
FolderFontSource
es el mismo que el especificado
FolderFontSource
objeto.
|
|  | [equals(Object o)](#equals-java.lang.Object-) | Determina si el actual |
FolderFontSource
es el mismo que el objeto especificado.
|
|  | [hashCode()](#hashCode--) | Devuelve el código hash para el actual |
FolderFontSource
objeto.
|
|  | [toString()](#toString--) | Devuelve una cadena que representa el objeto actual. |
|
### FolderFontSource(String folderPath, SearchOption searchOption) {#FolderFontSource-java.lang.String-com.groupdocs.viewer.fonts.SearchOption-}
```
public FolderFontSource(String folderPath, SearchOption searchOption)
```


Inicializa una nueva instancia de la
FolderFontSource
clase.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | folderPath | java.lang.String | Ruta a la carpeta que contiene fuentes TrueType. |
|
|  | searchOption | [SearchOption](../../com.groupdocs.viewer.fonts/searchoption) | Especifica si buscar en la carpeta actual, o en la carpeta actual y todas sus subcarpetas. |
|

### isEqualTo(FolderFontSource left, FolderFontSource right) {#isEqualTo-com.groupdocs.viewer.fonts.FolderFontSource-com.groupdocs.viewer.fonts.FolderFontSource-}
```
public static boolean isEqualTo(FolderFontSource left, FolderFontSource right)
```


Determina si dos
FolderFontSource
objetos son los mismos.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | left | [FolderFontSource](../../com.groupdocs.viewer.fonts/folderfontsource) | El objeto  FolderFontSource  de la izquierda. |
|
|  | right | [FolderFontSource](../../com.groupdocs.viewer.fonts/folderfontsource) | El objeto  FolderFontSource  de la derecha. |
|

**Returns:**
boolean -  true  si ambos objetos  FolderFontSource  son iguales; de lo contrario,  false .

### isNotEqualTo(FolderFontSource left, FolderFontSource right) {#isNotEqualTo-com.groupdocs.viewer.fonts.FolderFontSource-com.groupdocs.viewer.fonts.FolderFontSource-}
```
public static boolean isNotEqualTo(FolderFontSource left, FolderFontSource right)
```


Determina si dos
FolderFontSource
objetos no son los mismos.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | left | [FolderFontSource](../../com.groupdocs.viewer.fonts/folderfontsource) | El objeto  FolderFontSource  de la izquierda. |
|
|  | right | [FolderFontSource](../../com.groupdocs.viewer.fonts/folderfontsource) | El objeto  FolderFontSource  de la derecha. |
|

**Returns:**
boolean -  true  si ambos objetos  FolderFontSource  no son iguales; de lo contrario,  false .

### getFolderPath() {#getFolderPath--}
```
public String getFolderPath()
```


Obtiene la ruta a la carpeta que contiene fuentes TrueType.


**Returns:**
java.lang.String - la ruta a la carpeta que contiene fuentes TrueType.

### getSearchOption() {#getSearchOption--}
```
public SearchOption getSearchOption()
```


Obtiene la opción de búsqueda que especifica si buscar en la carpeta actual, o en la carpeta actual y todas sus subcarpetas.


**Returns:**
[SearchOption](../../com.groupdocs.viewer.fonts/searchoption) - the search option.

### isRecursive() {#isRecursive--}
```
public boolean isRecursive()
```


Comprueba si las fuentes se buscarían de forma recursiva.


**Returns:**
boolean -  true  si las fuentes se buscarían de forma recursiva,  false  de lo contrario.

### equals(FolderFontSource other) {#equals-com.groupdocs.viewer.fonts.FolderFontSource-}
```
public boolean equals(FolderFontSource other)
```


Determina si el actual
FolderFontSource
es el mismo que el especificado
FolderFontSource
objeto.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | other | [FolderFontSource](../../com.groupdocs.viewer.fonts/folderfontsource) | El objeto a comparar con el actual objeto  FolderFontSource . |
|

**Returns:**
boolean -  true  si ambos objetos  FolderFontSource  son iguales; de lo contrario,  false

### equals(Object o) {#equals-java.lang.Object-}
```
public boolean equals(Object o)
```


Determina si el actual
FolderFontSource
es el mismo que el objeto especificado.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | o | java.lang.Object | El objeto a comparar con el actual objeto  FolderFontSource . |
|

**Returns:**
boolean -  true  si el parámetro  obj  es de tipo  FolderFontSource  y es el mismo que el actual objeto  FolderFontSource ; de lo contrario,  false

### hashCode() {#hashCode--}
```
public int hashCode()
```


Devuelve el código hash para el actual
FolderFontSource
objeto.


**Returns:**
int - un código hash para el actual objeto  FolderFontSource .

### toString() {#toString--}
```
public String toString()
```


Devuelve una cadena que representa el objeto actual.


**Returns:**
java.lang.String - una cadena que representa el objeto actual.

