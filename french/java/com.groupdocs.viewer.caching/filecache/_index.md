---
title: "FileCache"
second_title: "Référence API de GroupDocs.Viewer pour Java"
description: "Représente un cache local sur disque."
type: docs
weight: 11
url: /fr/java/com.groupdocs.viewer.caching/filecache/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.viewer.caching.Cache](../../com.groupdocs.viewer.caching/cache)
```
public class FileCache implements Cache
```

Représente un cache local sur disque.


La classe FileCache représente un cache local sur disque dans le composant GroupDocs.Viewer.
Elle fournit des fonctionnalités pour stocker et récupérer les données en cache sur le disque afin d'assurer un rendu efficace des documents.


Exemple d'utilisation :

````

 FileCache fileCache = new FileCache(cachePath, cacheSubFolder);

 final ViewerSettings viewerSettings = new ViewerSettings();
 viewerSettings.setCache(fileCache);

 try (Viewer viewer = new Viewer(documentPath, viewerSettings)) {
     // Use the viewer object for document rendering
 }
 
````


Pour utiliser le FileCache, vous devez créer une instance de cette classe et la transmettre à l'objet ViewerSettings.
L'objet Viewer utilisera alors le FileCache à des fins de mise en cache lors du rendu des documents.


***Note:** The FileCache is just one of the cache implementations provided by GroupDocs.Viewer.
Vous pouvez également implémenter votre propre cache personnalisé en implémentant l'interface Cache.*

## Constructeurs

| Constructeur | Description |
| --- | --- |
|  | [FileCache(String cachePath)](#FileCache-java.lang.String-) | Crée une nouvelle instance de la |
FileCache
classe.
|
|  | [FileCache(Path cachePath)](#FileCache-java.nio.file.Path-) | Crée une nouvelle instance de la |
FileCache
classe.
|
|  | [FileCache(String cachePath, String cacheSubFolder)](#FileCache-java.lang.String-java.lang.String-) | Crée une nouvelle instance de la |
FileCache
classe.
|
|  | [FileCache(Path cachePath, String cacheSubFolder)](#FileCache-java.nio.file.Path-java.lang.String-) | Crée une nouvelle instance de la |
FileCache
classe.
|
## Champs

| Champ | Description |
| --- | --- |
| [CACHE_PATH](#CACHE-PATH) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getCachePath()](#getCachePath--) | Obtient le chemin relatif ou absolu du dossier de cache. |
|
|  | [getCacheSubFolder()](#getCacheSubFolder--) | Le sous-dossier à ajouter au chemin du cache. |
|
|  | [set(String key, Object value)](#set-java.lang.String-java.lang.Object-) | Sérialise les données sur le disque local. |
|
|  | [<T>get(String key, Class<T> clazz)](#-T-get-java.lang.String-java.lang.Class-T--) | Désérialise les données associées à cette clé si elles sont présentes. |
|
|  | [getKeys(String filter)](#getKeys-java.lang.String-) | Renvoie tous les noms de fichiers qui contiennent le filtre dans le nom de fichier. |
|
### FileCache(String cachePath) {#FileCache-java.lang.String-}
```
public FileCache(String cachePath)
```


Crée une nouvelle instance de la
FileCache
classe.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | cachePath | java.lang.String | Le chemin relatif ou absolu où le cache de documents sera stocké. |
|

### FileCache(Path cachePath) {#FileCache-java.nio.file.Path-}
```
public FileCache(Path cachePath)
```


Crée une nouvelle instance de la
FileCache
classe.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | cachePath | java.nio.file.Path | Le chemin relatif ou absolu où le cache de documents sera stocké. |
|

### FileCache(String cachePath, String cacheSubFolder) {#FileCache-java.lang.String-java.lang.String-}
```
public FileCache(String cachePath, String cacheSubFolder)
```


Crée une nouvelle instance de la
FileCache
classe.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | cachePath | java.lang.String | Le chemin relatif ou absolu où le cache de documents sera stocké. |
|
|  | cacheSubFolder | java.lang.String | Le sous-dossier à ajouter à cachePath. |
|

### FileCache(Path cachePath, String cacheSubFolder) {#FileCache-java.nio.file.Path-java.lang.String-}
```
public FileCache(Path cachePath, String cacheSubFolder)
```


Crée une nouvelle instance de la
FileCache
classe.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | cachePath | java.nio.file.Path | Le chemin relatif ou absolu où le cache de documents sera stocké. |
|
|  | cacheSubFolder | java.lang.String | Le sous-dossier à ajouter à cachePath. |
|

### CACHE_PATH {#CACHE-PATH}
```
public static final String CACHE_PATH
```


### getCachePath() {#getCachePath--}
```
public final String getCachePath()
```


Obtient le chemin relatif ou absolu du dossier de cache.


**Returns:**
java.lang.String - Chemin du dossier de cache.

### getCacheSubFolder() {#getCacheSubFolder--}
```
public final String getCacheSubFolder()
```


Le sous-dossier à ajouter au chemin du cache.


**Returns:**
java.lang.String - le sous-dossier à ajouter.

### set(String key, Object value) {#set-java.lang.String-java.lang.Object-}
```
public final void set(String key, Object value)
```


Sérialise les données sur le disque local.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | clé | java.lang.String | L'identifiant unique de l'entrée du cache. |
|
|  | valeur | java.lang.Object | L'objet à sérialiser. |
|

### <T>get(String key, Class<T> clazz) {#-T-get-java.lang.String-java.lang.Class-T--}
```
public final T <T>get(String key, Class<T> clazz)
```


Désérialise les données associées à cette clé si elles sont présentes.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | clé | java.lang.String | Une clé identifiant l'entrée demandée. |
|
|  | clazz | java.lang.Class<T> | La classe de la valeur attendue. |
|

**Returns:**
T - la valeur trouvée ou null.

### getKeys(String filter) {#getKeys-java.lang.String-}
```
public final List<String> getKeys(String filter)
```


Renvoie tous les noms de fichiers qui contiennent le filtre dans le nom de fichier.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | filtre | java.lang.String | Le filtre à utiliser. |
|

**Returns:**
java.util.List<java.lang.String> - Noms de fichiers contenant le filtre dans le nom de fichier.

