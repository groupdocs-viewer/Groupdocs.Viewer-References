---
title: "FileCache"
second_title: "Referencia de API de GroupDocs.Viewer para Node.js vía Java"
description: "Representa una caché local en disco."
type: docs
weight: 11
url: /es/nodejs-java/com.groupdocs.viewer.caching/filecache/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.viewer.caching.Cache](../../com.groupdocs.viewer.caching/cache)
```
public class FileCache implements Cache
```

Representa una caché local en disco.

La clase FileCache representa una caché local en disco en el componente GroupDocs.Viewer. Proporciona funcionalidad para almacenar y recuperar datos en caché en el disco para una renderización eficiente de documentos.

Ejemplo de uso:

```

 FileCache fileCache = new FileCache(cachePath, cacheSubFolder);

 final ViewerSettings viewerSettings = new ViewerSettings();
 viewerSettings.setCache(fileCache);

 try (Viewer viewer = new Viewer(documentPath, viewerSettings)) {
     // Use the viewer object for document rendering
 }
 
```

Para usar FileCache, debe crear una instancia de esta clase y pasarla al objeto ViewerSettings. El objeto Viewer utilizará entonces FileCache con fines de caché mientras renderiza los documentos.

***Note:** The FileCache is just one of the cache implementations provided by GroupDocs.Viewer. You can also implement your own custom cache by implementing the Cache interface.*
## Constructores

| Constructor | Descripción |
| --- | --- |
| [FileCache(String cachePath)](#FileCache-java.lang.String-) | Crea una nueva instancia de la clase  FileCache . |
| [FileCache(Path cachePath)](#FileCache-java.nio.file.Path-) | Crea una nueva instancia de la clase  FileCache . |
| [FileCache(String cachePath, String cacheSubFolder)](#FileCache-java.lang.String-java.lang.String-) | Crea una nueva instancia de la clase  FileCache . |
| [FileCache(Path cachePath, String cacheSubFolder)](#FileCache-java.nio.file.Path-java.lang.String-) | Crea una nueva instancia de la clase  FileCache . |
## Fields

| Field | Descripción |
| --- | --- |
| [CACHE_PATH](#CACHE-PATH) |  |
## Métodos

| Método | Descripción |
| --- | --- |
| [getCachePath()](#getCachePath--) | Obtiene la ruta relativa o absoluta a la carpeta de caché. |
| [getCacheSubFolder()](#getCacheSubFolder--) | La subcarpeta que se añadirá a la ruta de la caché. |
| [set(String key, Object value)](#set-java.lang.String-java.lang.Object-) | Serializa datos al disco local. |
| [<T>get(String key, Class<T> clazz)](#-T-get-java.lang.String-java.lang.Class-T--) | Deserializa los datos asociados con esta clave si están presentes. |
| [getKeys(String filter)](#getKeys-java.lang.String-) | Devuelve todos los nombres de archivo que contienen el filtro en el nombre del archivo. |
### FileCache(String cachePath) {#FileCache-java.lang.String-}
```
public FileCache(String cachePath)
```


Crea una nueva instancia de la clase  FileCache .

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| cachePath | java.lang.String | La ruta relativa o absoluta donde se almacenará la caché del documento. |

### FileCache(Path cachePath) {#FileCache-java.nio.file.Path-}
```
public FileCache(Path cachePath)
```


Crea una nueva instancia de la clase  FileCache .

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| cachePath | java.nio.file.Path | La ruta relativa o absoluta donde se almacenará la caché del documento. |

### FileCache(String cachePath, String cacheSubFolder) {#FileCache-java.lang.String-java.lang.String-}
```
public FileCache(String cachePath, String cacheSubFolder)
```


Crea una nueva instancia de la clase  FileCache .

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| cachePath | java.lang.String | La ruta relativa o absoluta donde se almacenará la caché del documento. |
| cacheSubFolder | java.lang.String | La subcarpeta que se añadirá a  cachePath . |

### FileCache(Path cachePath, String cacheSubFolder) {#FileCache-java.nio.file.Path-java.lang.String-}
```
public FileCache(Path cachePath, String cacheSubFolder)
```


Crea una nueva instancia de la clase  FileCache .

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| cachePath | java.nio.file.Path | La ruta relativa o absoluta donde se almacenará la caché del documento. |
| cacheSubFolder | java.lang.String | La subcarpeta que se añadirá a  cachePath . |

### CACHE_PATH {#CACHE-PATH}
```
public static final String CACHE_PATH
```


### getCachePath() {#getCachePath--}
```
public final String getCachePath()
```


Obtiene la ruta relativa o absoluta a la carpeta de caché.

**Returns:**
java.lang.String - Ruta a la carpeta de caché.
### getCacheSubFolder() {#getCacheSubFolder--}
```
public final String getCacheSubFolder()
```


La subcarpeta que se añadirá a la ruta de la caché.

**Returns:**
java.lang.String - la subcarpeta que se añadirá.
### set(String key, Object value) {#set-java.lang.String-java.lang.Object-}
```
public final void set(String key, Object value)
```


Serializa datos al disco local.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| key | java.lang.String | El identificador único para la entrada de caché. |
| value | java.lang.Object | El objeto a serializar. |

### <T>get(String key, Class<T> clazz) {#-T-get-java.lang.String-java.lang.Class-T--}
```
public final T <T>get(String key, Class<T> clazz)
```


Deserializa los datos asociados con esta clave si están presentes.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| key | java.lang.String | Una clave que identifica la entrada solicitada. |
| clazz | java.lang.Class<T> | La clase del valor esperado. |

**Returns:**
T - el valor localizado o null.
### getKeys(String filter) {#getKeys-java.lang.String-}
```
public final List<String> getKeys(String filter)
```


Devuelve todos los nombres de archivo que contienen el filtro en el nombre del archivo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| filter | java.lang.String | El filtro a usar. |

**Returns:**
java.util.List<java.lang.String> - Nombres de archivo que contienen el filtro en el nombre del archivo.
