---
title: "CacheKeys"
second_title: "GroupDocs.Viewer for Java API-referentie"
description: "Biedt methoden om de unieke identifier voor een cache‑item op te halen."
type: docs
weight: 10
url: /nl/java/com.groupdocs.viewer.caching/cachekeys/
---
**Inheritance:**
java.lang.Object
```
public class CacheKeys
```

Biedt methoden om de unieke identifier voor een cache‑item op te halen.


De klasse stelt je in staat cache‑sleutels te genereren op basis van verschillende parameters, zoals het documentpad, renderopties en de resource‑naam.
Deze cache‑sleutels kunnen worden gebruikt om gecachte gegevens op te slaan en op te halen voor efficiënte documentrendering.


Voorbeeldgebruik:

````

 // Generate a cache key for a file
 String fileKey = CacheKeys.getFileKey("filename.pdf");

 // Generate a cache key for a page
 String pageKey = CacheKeys.getPageKey(pageNumber, FileType.HTML.getExtension());

 // Generate a cache key for a resource
 Resource resource = new Resource("styles.css", false);
 String pageKey = CacheKeys.getResourceKey(pageNumber, resource);
 
````


## Velden

| Veld | Beschrijving |
| --- | --- |
| [PAGE_NUMBER](#PAGE-NUMBER) |  |
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getAttachmentsKey()](#getAttachmentsKey--) | Retourneert de unieke identifier voor de cache‑entry die een collectie van [Attachment](../../com.groupdocs.viewer.results/attachment) objecten vertegenwoordigt. |
|
|  | [getAttachmentKey(String attachmentId)](#getAttachmentKey-java.lang.String-) | Haalt de unieke identifier op voor de cache‑entry die een bijlagebestand vertegenwoordigt. |
|
|  | [getViewInfoKey()](#getViewInfoKey--) | Haalt de unieke identifier op voor de cache‑entry die een [ViewInfo](../../com.groupdocs.viewer.results/viewinfo) object vertegenwoordigt. |
|
|  | [getFileInfoKey()](#getFileInfoKey--) | Haalt de unieke identifier op voor de cache‑entry die een [ViewInfo](../../com.groupdocs.viewer.results/viewinfo) object vertegenwoordigt. |
|
|  | [getFileKey(String extension)](#getFileKey-java.lang.String-) | Haalt de unieke identifier op voor de cache‑entry die een bestand vertegenwoordigt. |
|
|  | [getPageKey(int pageNumber, String extension)](#getPageKey-int-java.lang.String-) | Haalt de unieke identifier op voor de cache‑entry die een paginabestand vertegenwoordigt. |
|
|  | [getResourceKey(int pageNumber, Resource resource)](#getResourceKey-int-com.groupdocs.viewer.results.Resource-) | Retourneert een unieke identifier voor de cache‑entry die een [Resource](../../com.groupdocs.viewer.results/resource) object vertegenwoordigt. |
|
|  | [getResourceFilter(int pageNumber)](#getResourceFilter-int-) | Retourneert een filter‑string om te zoeken naar cache‑entries die [Resource](../../com.groupdocs.viewer.results/resource) objecten vertegenwoordigen. |
|
### PAGE_NUMBER {#PAGE-NUMBER}
```
public static final String PAGE_NUMBER
```


### getAttachmentsKey() {#getAttachmentsKey--}
```
public static String getAttachmentsKey()
```


Retourneert de unieke identifier voor de cache‑entry die een collectie van [Attachment](../../com.groupdocs.viewer.results/attachment) objecten vertegenwoordigt.


**Returns:**
java.lang.String - de unieke identifier voor de bijlagen‑cache‑entry.

### getAttachmentKey(String attachmentId) {#getAttachmentKey-java.lang.String-}
```
public static String getAttachmentKey(String attachmentId)
```


Haalt de unieke identifier op voor de cache‑entry die een bijlagebestand vertegenwoordigt.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | attachmentId | java.lang.String | De unieke identifier van de bijlage (in de context van één enkel bestand). |
|

**Returns:**
java.lang.String - de unieke identifier voor de bijlage‑bestand‑cache‑entry.

### getViewInfoKey() {#getViewInfoKey--}
```
public static String getViewInfoKey()
```


Haalt de unieke identifier op voor de cache‑entry die een [ViewInfo](../../com.groupdocs.viewer.results/viewinfo) object vertegenwoordigt.


**Returns:**
java.lang.String - de unieke identifier voor de cache‑entry.

### getFileInfoKey() {#getFileInfoKey--}
```
public static String getFileInfoKey()
```


Haalt de unieke identifier op voor de cache‑entry die een [ViewInfo](../../com.groupdocs.viewer.results/viewinfo) object vertegenwoordigt.


**Returns:**
java.lang.String - de unieke identifier voor de cache‑entry die een [ViewInfo](../../com.groupdocs.viewer.results/viewinfo) object vertegenwoordigt.

### getFileKey(String extension) {#getFileKey-java.lang.String-}
```
public static String getFileKey(String extension)
```


Haalt de unieke identifier op voor de cache‑entry die een bestand vertegenwoordigt.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | extensie | java.lang.String | De bestandsextensie (inclusief de punt ".") bijv. ".doc". |
|

**Returns:**
java.lang.String - de unieke identificatie voor de cache‑entry die een bestand vertegenwoordigt.

### getPageKey(int pageNumber, String extension) {#getPageKey-int-java.lang.String-}
```
public static String getPageKey(int pageNumber, String extension)
```


Haalt de unieke identifier op voor de cache‑entry die een paginabestand vertegenwoordigt.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | pageNumber | int | Het paginanummer. |
|
|  | extensie | java.lang.String | De bestandsextensie (inclusief de punt ".") bijv. ".doc". |
|

**Returns:**
java.lang.String - de unieke identificatie voor de cache‑entry die een paginabestand vertegenwoordigt.

### getResourceKey(int pageNumber, Resource resource) {#getResourceKey-int-com.groupdocs.viewer.results.Resource-}
```
public static String getResourceKey(int pageNumber, Resource resource)
```


Retourneert een unieke identifier voor de cache‑entry die een [Resource](../../com.groupdocs.viewer.results/resource) object vertegenwoordigt.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | pageNumber | int | Het paginanummer. |
|
|  | resource | [Resource](../../com.groupdocs.viewer.results/resource) | De HTML‑resource. |
|

**Returns:**
java.lang.String - de unieke identifier voor de cache‑entry.

### getResourceFilter(int pageNumber) {#getResourceFilter-int-}
```
public static String getResourceFilter(int pageNumber)
```


Retourneert een filter‑string om te zoeken naar cache‑entries die [Resource](../../com.groupdocs.viewer.results/resource) objecten vertegenwoordigen.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | pageNumber | int | Het paginanummer. |
|

**Returns:**
java.lang.String - de filter‑string om te zoeken naar cache‑entries.

