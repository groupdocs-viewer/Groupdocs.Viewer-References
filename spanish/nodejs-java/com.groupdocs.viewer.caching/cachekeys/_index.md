---
title: "CacheKeys"
second_title: "Referencia de API de GroupDocs.Viewer para Node.js vía Java"
description: "Proporciona métodos para obtener el identificador único de una entrada de caché."
type: docs
weight: 10
url: /es/nodejs-java/com.groupdocs.viewer.caching/cachekeys/
---
**Inheritance:**
java.lang.Object
```
public class CacheKeys
```

Proporciona métodos para obtener el identificador único de una entrada de caché.

La clase le permite generar claves de caché basadas en diferentes parámetros, como la ruta del documento, las opciones de renderizado y el nombre del recurso. Estas claves de caché pueden usarse para almacenar y recuperar datos en caché para un renderizado de documentos eficiente.

Ejemplo de uso:

```

 // Generate a cache key for a file
 String fileKey = CacheKeys.getFileKey("filename.pdf");

 // Generate a cache key for a page
 String pageKey = CacheKeys.getPageKey(pageNumber, FileType.HTML.getExtension());

 // Generate a cache key for a resource
 Resource resource = new Resource("styles.css", false);
 String pageKey = CacheKeys.getResourceKey(pageNumber, resource);
 
```
## Fields

| Field | Descripción |
| --- | --- |
| [PAGE_NUMBER](#PAGE-NUMBER) |  |
## Métodos

| Método | Descripción |
| --- | --- |
| [getAttachmentsKey()](#getAttachmentsKey--) | Devuelve el identificador único para la entrada de caché que representa una colección de objetos [Attachment](../../com.groupdocs.viewer.results/attachment). |
| [getAttachmentKey(String attachmentId)](#getAttachmentKey-java.lang.String-) | Recupera el identificador único para la entrada de caché que representa un archivo adjunto. |
| [getViewInfoKey()](#getViewInfoKey--) | Recupera el identificador único para la entrada de caché que representa un objeto [ViewInfo](../../com.groupdocs.viewer.results/viewinfo). |
| [getFileInfoKey()](#getFileInfoKey--) | Recupera el identificador único para la entrada de caché que representa un objeto [ViewInfo](../../com.groupdocs.viewer.results/viewinfo). |
| [getFileKey(String extension)](#getFileKey-java.lang.String-) | Recupera el identificador único de la entrada de caché que representa un archivo. |
| [getPageKey(int pageNumber, String extension)](#getPageKey-int-java.lang.String-) | Recupera el identificador único de la entrada de caché que representa un archivo de página. |
| [getResourceKey(int pageNumber, Resource resource)](#getResourceKey-int-com.groupdocs.viewer.results.Resource-) | Devuelve un identificador único para la entrada de caché que representa un objeto [Resource](../../com.groupdocs.viewer.results/resource). |
| [getResourceFilter(int pageNumber)](#getResourceFilter-int-) | Devuelve una cadena de filtro para buscar entradas de caché que representan objetos [Resource](../../com.groupdocs.viewer.results/resource). |
### PAGE_NUMBER {#PAGE-NUMBER}
```
public static final String PAGE_NUMBER
```


### getAttachmentsKey() {#getAttachmentsKey--}
```
public static String getAttachmentsKey()
```


Devuelve el identificador único para la entrada de caché que representa una colección de objetos [Attachment](../../com.groupdocs.viewer.results/attachment).

**Returns:**
java.lang.String - el identificador único para la entrada de caché de los adjuntos.
### getAttachmentKey(String attachmentId) {#getAttachmentKey-java.lang.String-}
```
public static String getAttachmentKey(String attachmentId)
```


Recupera el identificador único para la entrada de caché que representa un archivo adjunto.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| attachmentId | java.lang.String | El identificador único del adjunto (en el contexto de un solo archivo). |

**Returns:**
java.lang.String - el identificador único para la entrada de caché del archivo adjunto.
### getViewInfoKey() {#getViewInfoKey--}
```
public static String getViewInfoKey()
```


Recupera el identificador único para la entrada de caché que representa un objeto [ViewInfo](../../com.groupdocs.viewer.results/viewinfo).

**Returns:**
java.lang.String - el identificador único para la entrada de caché.
### getFileInfoKey() {#getFileInfoKey--}
```
public static String getFileInfoKey()
```


Recupera el identificador único para la entrada de caché que representa un objeto [ViewInfo](../../com.groupdocs.viewer.results/viewinfo).

**Returns:**
java.lang.String - el identificador único para la entrada de caché que representa un objeto [ViewInfo](../../com.groupdocs.viewer.results/viewinfo).
### getFileKey(String extension) {#getFileKey-java.lang.String-}
```
public static String getFileKey(String extension)
```


Recupera el identificador único de la entrada de caché que representa un archivo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| extension | java.lang.String | El sufijo del nombre de archivo (incluyendo el punto \".\") p. ej. \".doc\". |

**Returns:**
java.lang.String - el identificador único para la entrada de caché que representa un archivo.
### getPageKey(int pageNumber, String extension) {#getPageKey-int-java.lang.String-}
```
public static String getPageKey(int pageNumber, String extension)
```


Recupera el identificador único de la entrada de caché que representa un archivo de página.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pageNumber | int | El número de la página. |
| extension | java.lang.String | El sufijo del nombre de archivo (incluyendo el punto \".\") p. ej. \".doc\". |

**Returns:**
java.lang.String - el identificador único para la entrada de caché que representa un archivo de página.
### getResourceKey(int pageNumber, Resource resource) {#getResourceKey-int-com.groupdocs.viewer.results.Resource-}
```
public static String getResourceKey(int pageNumber, Resource resource)
```


Devuelve un identificador único para la entrada de caché que representa un objeto [Resource](../../com.groupdocs.viewer.results/resource).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pageNumber | int | El número de la página. |
| resource | [Resource](../../com.groupdocs.viewer.results/resource) | El recurso HTML. |

**Returns:**
java.lang.String - el identificador único para la entrada de caché.
### getResourceFilter(int pageNumber) {#getResourceFilter-int-}
```
public static String getResourceFilter(int pageNumber)
```


Devuelve una cadena de filtro para buscar entradas de caché que representan objetos [Resource](../../com.groupdocs.viewer.results/resource).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pageNumber | int | El número de la página. |

**Returns:**
java.lang.String - la cadena de filtro para buscar entradas de caché.
