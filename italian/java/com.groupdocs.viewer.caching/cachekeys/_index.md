---
title: "CacheKeys"
second_title: "Riferimento API di GroupDocs.Viewer per Java"
description: "Fornisce metodi per recuperare l'identificatore univoco di una voce della cache."
type: docs
weight: 10
url: /it/java/com.groupdocs.viewer.caching/cachekeys/
---
**Inheritance:**
java.lang.Object
```
public class CacheKeys
```

Fornisce metodi per recuperare l'identificatore univoco di una voce della cache.


La classe consente di generare chiavi di cache basate su diversi parametri, come il percorso del documento, le opzioni di rendering e il nome della risorsa.
Queste chiavi di cache possono essere utilizzate per memorizzare e recuperare dati nella cache per un rendering efficiente dei documenti.


Esempio di utilizzo:

````

 // Generate a cache key for a file
 String fileKey = CacheKeys.getFileKey("filename.pdf");

 // Generate a cache key for a page
 String pageKey = CacheKeys.getPageKey(pageNumber, FileType.HTML.getExtension());

 // Generate a cache key for a resource
 Resource resource = new Resource("styles.css", false);
 String pageKey = CacheKeys.getResourceKey(pageNumber, resource);
 
````


## Campi

| Campo | Descrizione |
| --- | --- |
| [PAGE_NUMBER](#PAGE-NUMBER) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [getAttachmentsKey()](#getAttachmentsKey--) | Restituisce l'identificatore univoco per la voce di cache che rappresenta una collezione di oggetti [Attachment](../../com.groupdocs.viewer.results/attachment). |
|
|  | [getAttachmentKey(String attachmentId)](#getAttachmentKey-java.lang.String-) | Recupera l'identificatore univoco per la voce di cache che rappresenta un file di allegato. |
|
|  | [getViewInfoKey()](#getViewInfoKey--) | Recupera l'identificatore univoco per la voce di cache che rappresenta un oggetto [ViewInfo](../../com.groupdocs.viewer.results/viewinfo). |
|
|  | [getFileInfoKey()](#getFileInfoKey--) | Recupera l'identificatore univoco per la voce di cache che rappresenta un oggetto [ViewInfo](../../com.groupdocs.viewer.results/viewinfo). |
|
|  | [getFileKey(String extension)](#getFileKey-java.lang.String-) | Recupera l'identificatore univoco per la voce di cache che rappresenta un file. |
|
|  | [getPageKey(int pageNumber, String extension)](#getPageKey-int-java.lang.String-) | Recupera l'identificatore univoco per la voce di cache che rappresenta un file di pagina. |
|
|  | [getResourceKey(int pageNumber, Resource resource)](#getResourceKey-int-com.groupdocs.viewer.results.Resource-) | Restituisce un identificatore univoco per la voce di cache che rappresenta un oggetto [Resource](../../com.groupdocs.viewer.results/resource). |
|
|  | [getResourceFilter(int pageNumber)](#getResourceFilter-int-) | Restituisce una stringa di filtro per cercare le voci di cache che rappresentano oggetti [Resource](../../com.groupdocs.viewer.results/resource). |
|
### PAGE_NUMBER {#PAGE-NUMBER}
```
public static final String PAGE_NUMBER
```


### getAttachmentsKey() {#getAttachmentsKey--}
```
public static String getAttachmentsKey()
```


Restituisce l'identificatore univoco per la voce di cache che rappresenta una collezione di oggetti [Attachment](../../com.groupdocs.viewer.results/attachment).


**Returns:**
java.lang.String - l'identificatore univoco per la voce di cache degli allegati.

### getAttachmentKey(String attachmentId) {#getAttachmentKey-java.lang.String-}
```
public static String getAttachmentKey(String attachmentId)
```


Recupera l'identificatore univoco per la voce di cache che rappresenta un file di allegato.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | attachmentId | java.lang.String | L'identificatore univoco dell'allegato (nel contesto di un singolo file). |
|

**Returns:**
java.lang.String - l'identificatore univoco per la voce di cache del file di allegato.

### getViewInfoKey() {#getViewInfoKey--}
```
public static String getViewInfoKey()
```


Recupera l'identificatore univoco per la voce di cache che rappresenta un oggetto [ViewInfo](../../com.groupdocs.viewer.results/viewinfo).


**Returns:**
java.lang.String - l'identificatore univoco per la voce di cache.

### getFileInfoKey() {#getFileInfoKey--}
```
public static String getFileInfoKey()
```


Recupera l'identificatore univoco per la voce di cache che rappresenta un oggetto [ViewInfo](../../com.groupdocs.viewer.results/viewinfo).


**Returns:**
java.lang.String - l'identificatore univoco per la voce di cache che rappresenta un oggetto [ViewInfo](../../com.groupdocs.viewer.results/viewinfo).

### getFileKey(String extension) {#getFileKey-java.lang.String-}
```
public static String getFileKey(String extension)
```


Recupera l'identificatore univoco per la voce di cache che rappresenta un file.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | estensione | java.lang.String | Il suffisso del nome file (incluso il punto ".") es. ".doc". |
|

**Returns:**
java.lang.String - l'identificatore univoco per la voce della cache che rappresenta un file.

### getPageKey(int pageNumber, String extension) {#getPageKey-int-java.lang.String-}
```
public static String getPageKey(int pageNumber, String extension)
```


Recupera l'identificatore univoco per la voce di cache che rappresenta un file di pagina.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | pageNumber | int | Il numero della pagina. |
|
|  | estensione | java.lang.String | Il suffisso del nome file (incluso il punto ".") es. ".doc". |
|

**Returns:**
java.lang.String - l'identificatore univoco per la voce della cache che rappresenta un file di pagina.

### getResourceKey(int pageNumber, Resource resource) {#getResourceKey-int-com.groupdocs.viewer.results.Resource-}
```
public static String getResourceKey(int pageNumber, Resource resource)
```


Restituisce un identificatore univoco per la voce di cache che rappresenta un oggetto [Resource](../../com.groupdocs.viewer.results/resource).


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | pageNumber | int | Il numero della pagina. |
|
|  | resource | [Resource](../../com.groupdocs.viewer.results/resource) | La risorsa HTML. |
|

**Returns:**
java.lang.String - l'identificatore univoco per la voce di cache.

### getResourceFilter(int pageNumber) {#getResourceFilter-int-}
```
public static String getResourceFilter(int pageNumber)
```


Restituisce una stringa di filtro per cercare le voci di cache che rappresentano oggetti [Resource](../../com.groupdocs.viewer.results/resource).


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | pageNumber | int | Il numero della pagina. |
|

**Returns:**
java.lang.String - la stringa di filtro per cercare le voci della cache.

