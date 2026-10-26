---
title: "FileCache"
second_title: "GroupDocs.Viewer per Node.js via Java Riferimento API"
description: "Rappresenta una cache locale su disco."
type: docs
weight: 11
url: /it/nodejs-java/com.groupdocs.viewer.caching/filecache/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.viewer.caching.Cache](../../com.groupdocs.viewer.caching/cache)
```
public class FileCache implements Cache
```

Rappresenta una cache locale su disco.

La classe FileCache rappresenta una cache locale su disco nel componente GroupDocs.Viewer. Fornisce funzionalità per memorizzare e recuperare dati nella cache sul disco per una resa efficiente dei documenti.

Esempio di utilizzo:

```

 FileCache fileCache = new FileCache(cachePath, cacheSubFolder);

 final ViewerSettings viewerSettings = new ViewerSettings();
 viewerSettings.setCache(fileCache);

 try (Viewer viewer = new Viewer(documentPath, viewerSettings)) {
     // Use the viewer object for document rendering
 }
 
```

Per utilizzare FileCache, è necessario creare un'istanza di questa classe e passarla all'oggetto ViewerSettings. L'oggetto Viewer utilizzerà quindi FileCache per scopi di caching durante il rendering dei documenti.

***Note:** The FileCache is just one of the cache implementations provided by GroupDocs.Viewer. You can also implement your own custom cache by implementing the Cache interface.*
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [FileCache(String cachePath)](#FileCache-java.lang.String-) | Crea una nuova istanza della classe  FileCache  . |
| [FileCache(Path cachePath)](#FileCache-java.nio.file.Path-) | Crea una nuova istanza della classe  FileCache  . |
| [FileCache(String cachePath, String cacheSubFolder)](#FileCache-java.lang.String-java.lang.String-) | Crea una nuova istanza della classe  FileCache  . |
| [FileCache(Path cachePath, String cacheSubFolder)](#FileCache-java.nio.file.Path-java.lang.String-) | Crea una nuova istanza della classe  FileCache  . |
## Campi

| Campo | Descrizione |
| --- | --- |
| [CACHE_PATH](#CACHE-PATH) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getCachePath()](#getCachePath--) | Ottiene il percorso relativo o assoluto della cartella di cache. |
| [getCacheSubFolder()](#getCacheSubFolder--) | La sottocartella da aggiungere al percorso della cache. |
| [set(String key, Object value)](#set-java.lang.String-java.lang.Object-) | Serializza i dati sul disco locale. |
| [<T>get(String key, Class<T> clazz)](#-T-get-java.lang.String-java.lang.Class-T--) | Deserializza i dati associati a questa chiave, se presenti. |
| [getKeys(String filter)](#getKeys-java.lang.String-) | Restituisce tutti i nomi file che contengono il filtro nel nome del file. |
### FileCache(String cachePath) {#FileCache-java.lang.String-}
```
public FileCache(String cachePath)
```


Crea una nuova istanza della classe  FileCache  .

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| cachePath | java.lang.String | Il percorso relativo o assoluto dove verrà memorizzata la cache dei documenti. |

### FileCache(Path cachePath) {#FileCache-java.nio.file.Path-}
```
public FileCache(Path cachePath)
```


Crea una nuova istanza della classe  FileCache  .

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| cachePath | java.nio.file.Path | Il percorso relativo o assoluto dove verrà memorizzata la cache dei documenti. |

### FileCache(String cachePath, String cacheSubFolder) {#FileCache-java.lang.String-java.lang.String-}
```
public FileCache(String cachePath, String cacheSubFolder)
```


Crea una nuova istanza della classe  FileCache  .

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| cachePath | java.lang.String | Il percorso relativo o assoluto dove verrà memorizzata la cache dei documenti. |
| cacheSubFolder | java.lang.String | La sottocartella da aggiungere a cachePath. |

### FileCache(Path cachePath, String cacheSubFolder) {#FileCache-java.nio.file.Path-java.lang.String-}
```
public FileCache(Path cachePath, String cacheSubFolder)
```


Crea una nuova istanza della classe  FileCache  .

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| cachePath | java.nio.file.Path | Il percorso relativo o assoluto dove verrà memorizzata la cache dei documenti. |
| cacheSubFolder | java.lang.String | La sottocartella da aggiungere a cachePath. |

### CACHE_PATH {#CACHE-PATH}
```
public static final String CACHE_PATH
```


### getCachePath() {#getCachePath--}
```
public final String getCachePath()
```


Ottiene il percorso relativo o assoluto della cartella di cache.

**Returns:**
java.lang.String - Percorso della cartella cache.
### getCacheSubFolder() {#getCacheSubFolder--}
```
public final String getCacheSubFolder()
```


La sottocartella da aggiungere al percorso della cache.

**Returns:**
java.lang.String - la sottocartella da aggiungere.
### set(String key, Object value) {#set-java.lang.String-java.lang.Object-}
```
public final void set(String key, Object value)
```


Serializza i dati sul disco locale.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| key | java.lang.String | L'identificatore unico per la voce della cache. |
| value | java.lang.Object | L'oggetto da serializzare. |

### <T>get(String key, Class<T> clazz) {#-T-get-java.lang.String-java.lang.Class-T--}
```
public final T <T>get(String key, Class<T> clazz)
```


Deserializza i dati associati a questa chiave, se presenti.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| key | java.lang.String | Una chiave che identifica la voce richiesta. |
| clazz | java.lang.Class<T> | La classe del valore atteso. |

**Returns:**
T - il valore trovato o null.
### getKeys(String filter) {#getKeys-java.lang.String-}
```
public final List<String> getKeys(String filter)
```


Restituisce tutti i nomi file che contengono il filtro nel nome del file.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| filter | java.lang.String | Il filtro da utilizzare. |

**Returns:**
java.util.List<java.lang.String> - Nomi file che contengono il filtro nel nome del file.
