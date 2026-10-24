---
title: "CacheKeys"
second_title: "Référence API de GroupDocs.Viewer pour Java"
description: "Fournit des méthodes pour récupérer l'identifiant unique d'une entrée de cache."
type: docs
weight: 10
url: /fr/java/com.groupdocs.viewer.caching/cachekeys/
---
**Inheritance:**
java.lang.Object
```
public class CacheKeys
```

Fournit des méthodes pour récupérer l'identifiant unique d'une entrée de cache.


La classe vous permet de générer des clés de cache basées sur différents paramètres, tels que le chemin du document, les options de rendu et le nom de la ressource.
Ces clés de cache peuvent être utilisées pour stocker et récupérer des données en cache afin d'optimiser le rendu des documents.


Exemple d'utilisation :

````

 // Generate a cache key for a file
 String fileKey = CacheKeys.getFileKey("filename.pdf");

 // Generate a cache key for a page
 String pageKey = CacheKeys.getPageKey(pageNumber, FileType.HTML.getExtension());

 // Generate a cache key for a resource
 Resource resource = new Resource("styles.css", false);
 String pageKey = CacheKeys.getResourceKey(pageNumber, resource);
 
````


## Champs

| Champ | Description |
| --- | --- |
| [PAGE_NUMBER](#PAGE-NUMBER) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getAttachmentsKey()](#getAttachmentsKey--) | Renvoie l'identifiant unique de l'entrée de cache qui représente une collection d'objets [Attachment](../../com.groupdocs.viewer.results/attachment). |
|
|  | [getAttachmentKey(String attachmentId)](#getAttachmentKey-java.lang.String-) | Récupère l'identifiant unique de l'entrée de cache représentant un fichier de pièce jointe. |
|
|  | [getViewInfoKey()](#getViewInfoKey--) | Récupère l'identifiant unique de l'entrée de cache qui représente un objet [ViewInfo](../../com.groupdocs.viewer.results/viewinfo). |
|
|  | [getFileInfoKey()](#getFileInfoKey--) | Récupère l'identifiant unique de l'entrée de cache qui représente un objet [ViewInfo](../../com.groupdocs.viewer.results/viewinfo). |
|
|  | [getFileKey(String extension)](#getFileKey-java.lang.String-) | Récupère l'identifiant unique de l'entrée de cache qui représente un fichier. |
|
|  | [getPageKey(int pageNumber, String extension)](#getPageKey-int-java.lang.String-) | Récupère l'identifiant unique de l'entrée de cache qui représente un fichier de page. |
|
|  | [getResourceKey(int pageNumber, Resource resource)](#getResourceKey-int-com.groupdocs.viewer.results.Resource-) | Renvoie un identifiant unique pour l'entrée de cache qui représente un objet [Resource](../../com.groupdocs.viewer.results/resource). |
|
|  | [getResourceFilter(int pageNumber)](#getResourceFilter-int-) | Renvoie une chaîne de filtre pour rechercher les entrées de cache qui représentent des objets [Resource](../../com.groupdocs.viewer.results/resource). |
|
### PAGE_NUMBER {#PAGE-NUMBER}
```
public static final String PAGE_NUMBER
```


### getAttachmentsKey() {#getAttachmentsKey--}
```
public static String getAttachmentsKey()
```


Renvoie l'identifiant unique de l'entrée de cache qui représente une collection d'objets [Attachment](../../com.groupdocs.viewer.results/attachment).


**Returns:**
java.lang.String - l'identifiant unique de l'entrée de cache des pièces jointes.

### getAttachmentKey(String attachmentId) {#getAttachmentKey-java.lang.String-}
```
public static String getAttachmentKey(String attachmentId)
```


Récupère l'identifiant unique de l'entrée de cache représentant un fichier de pièce jointe.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | attachmentId | java.lang.String | L'identifiant unique de la pièce jointe (dans le contexte d'un seul fichier). |
|

**Returns:**
java.lang.String - l'identifiant unique de l'entrée de cache du fichier de pièce jointe.

### getViewInfoKey() {#getViewInfoKey--}
```
public static String getViewInfoKey()
```


Récupère l'identifiant unique de l'entrée de cache qui représente un objet [ViewInfo](../../com.groupdocs.viewer.results/viewinfo).


**Returns:**
java.lang.String - l'identifiant unique de l'entrée de cache.

### getFileInfoKey() {#getFileInfoKey--}
```
public static String getFileInfoKey()
```


Récupère l'identifiant unique de l'entrée de cache qui représente un objet [ViewInfo](../../com.groupdocs.viewer.results/viewinfo).


**Returns:**
java.lang.String - l'identifiant unique de l'entrée de cache représentant un objet [ViewInfo](../../com.groupdocs.viewer.results/viewinfo).

### getFileKey(String extension) {#getFileKey-java.lang.String-}
```
public static String getFileKey(String extension)
```


Récupère l'identifiant unique de l'entrée de cache qui représente un fichier.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | extension | java.lang.String | Le suffixe du nom de fichier (y compris le point ".") par ex. ".doc". |
|

**Returns:**
java.lang.String - l'identifiant unique pour l'entrée du cache représentant un fichier.

### getPageKey(int pageNumber, String extension) {#getPageKey-int-java.lang.String-}
```
public static String getPageKey(int pageNumber, String extension)
```


Récupère l'identifiant unique de l'entrée de cache qui représente un fichier de page.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | pageNumber | int | Le numéro de la page. |
|
|  | extension | java.lang.String | Le suffixe du nom de fichier (y compris le point ".") par ex. ".doc". |
|

**Returns:**
java.lang.String - l'identifiant unique pour l'entrée du cache représentant un fichier de page.

### getResourceKey(int pageNumber, Resource resource) {#getResourceKey-int-com.groupdocs.viewer.results.Resource-}
```
public static String getResourceKey(int pageNumber, Resource resource)
```


Renvoie un identifiant unique pour l'entrée de cache qui représente un objet [Resource](../../com.groupdocs.viewer.results/resource).


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | pageNumber | int | Le numéro de la page. |
|
|  | resource | [Resource](../../com.groupdocs.viewer.results/resource) | La ressource HTML. |
|

**Returns:**
java.lang.String - l'identifiant unique de l'entrée de cache.

### getResourceFilter(int pageNumber) {#getResourceFilter-int-}
```
public static String getResourceFilter(int pageNumber)
```


Renvoie une chaîne de filtre pour rechercher les entrées de cache qui représentent des objets [Resource](../../com.groupdocs.viewer.results/resource).


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | pageNumber | int | Le numéro de la page. |
|

**Returns:**
java.lang.String - la chaîne de filtre pour rechercher des entrées du cache.

