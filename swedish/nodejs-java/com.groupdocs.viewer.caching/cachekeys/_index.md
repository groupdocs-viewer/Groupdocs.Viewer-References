---
title: "CacheKeys"
second_title: "GroupDocs.Viewer för Node.js via Java API-referens"
description: "Tillhandahåller metoder för att hämta den unika identifieraren för en cachepost."
type: docs
weight: 10
url: /sv/nodejs-java/com.groupdocs.viewer.caching/cachekeys/
---
**Inheritance:**
java.lang.Object
```
public class CacheKeys
```

Tillhandahåller metoder för att hämta den unika identifieraren för en cachepost.

Klassen låter dig generera cache-nycklar baserat på olika parametrar, såsom dokumentets sökväg, renderingsalternativ och resursnamn. Dessa cache-nycklar kan användas för att lagra och hämta cachad data för effektiv dokumentrendering.

Exempel på användning:

```

 // Generate a cache key for a file
 String fileKey = CacheKeys.getFileKey("filename.pdf");

 // Generate a cache key for a page
 String pageKey = CacheKeys.getPageKey(pageNumber, FileType.HTML.getExtension());

 // Generate a cache key for a resource
 Resource resource = new Resource("styles.css", false);
 String pageKey = CacheKeys.getResourceKey(pageNumber, resource);
 
```
## Fält

| Fält | Beskrivning |
| --- | --- |
| [PAGE_NUMBER](#PAGE-NUMBER) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getAttachmentsKey()](#getAttachmentsKey--) | Returnerar den unika identifieraren för cache-posten som representerar en samling av [Attachment](../../com.groupdocs.viewer.results/attachment)-objekt. |
| [getAttachmentKey(String attachmentId)](#getAttachmentKey-java.lang.String-) | Hämtar den unika identifieraren för cache-posten som representerar en bilagefil. |
| [getViewInfoKey()](#getViewInfoKey--) | Hämtar den unika identifieraren för cache-posten som representerar ett [ViewInfo](../../com.groupdocs.viewer.results/viewinfo)-objekt. |
| [getFileInfoKey()](#getFileInfoKey--) | Hämtar den unika identifieraren för cache-posten som representerar ett [ViewInfo](../../com.groupdocs.viewer.results/viewinfo)-objekt. |
| [getFileKey(String extension)](#getFileKey-java.lang.String-) | Hämtar den unika identifieraren för cacheposten som representerar en fil. |
| [getPageKey(int pageNumber, String extension)](#getPageKey-int-java.lang.String-) | Hämtar den unika identifieraren för cacheposten som representerar en sidfil. |
| [getResourceKey(int pageNumber, Resource resource)](#getResourceKey-int-com.groupdocs.viewer.results.Resource-) | Returnerar en unik identifierare för cacheposten som representerar ett [Resource](../../com.groupdocs.viewer.results/resource)-objekt. |
| [getResourceFilter(int pageNumber)](#getResourceFilter-int-) | Returnerar en filtersträng för att söka efter cacheposter som representerar [Resource](../../com.groupdocs.viewer.results/resource)-objekt. |
### PAGE_NUMBER {#PAGE-NUMBER}
```
public static final String PAGE_NUMBER
```


### getAttachmentsKey() {#getAttachmentsKey--}
```
public static String getAttachmentsKey()
```


Returnerar den unika identifieraren för cache-posten som representerar en samling av [Attachment](../../com.groupdocs.viewer.results/attachment)-objekt.

**Returns:**
java.lang.String – den unika identifieraren för bilagornas cachepost.
### getAttachmentKey(String attachmentId) {#getAttachmentKey-java.lang.String-}
```
public static String getAttachmentKey(String attachmentId)
```


Hämtar den unika identifieraren för cache-posten som representerar en bilagefil.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| attachmentId | java.lang.String | Den unika identifieraren för bilagan (i kontexten av en enskild fil). |

**Returns:**
java.lang.String – den unika identifieraren för bilagans filcachepost.
### getViewInfoKey() {#getViewInfoKey--}
```
public static String getViewInfoKey()
```


Hämtar den unika identifieraren för cache-posten som representerar ett [ViewInfo](../../com.groupdocs.viewer.results/viewinfo)-objekt.

**Returns:**
java.lang.String – den unika identifieraren för cacheposten.
### getFileInfoKey() {#getFileInfoKey--}
```
public static String getFileInfoKey()
```


Hämtar den unika identifieraren för cache-posten som representerar ett [ViewInfo](../../com.groupdocs.viewer.results/viewinfo)-objekt.

**Returns:**
java.lang.String – den unika identifieraren för cacheposten som representerar ett [ViewInfo](../../com.groupdocs.viewer.results/viewinfo)-objekt.
### getFileKey(String extension) {#getFileKey-java.lang.String-}
```
public static String getFileKey(String extension)
```


Hämtar den unika identifieraren för cacheposten som representerar en fil.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| extension | java.lang.String | Filnamnstillägget (inklusive punkten \".\") t.ex. \".doc\". |

**Returns:**
java.lang.String – den unika identifieraren för cacheposten som representerar en fil.
### getPageKey(int pageNumber, String extension) {#getPageKey-int-java.lang.String-}
```
public static String getPageKey(int pageNumber, String extension)
```


Hämtar den unika identifieraren för cacheposten som representerar en sidfil.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pageNumber | int | Sidans nummer. |
| extension | java.lang.String | Filnamnstillägget (inklusive punkten \".\") t.ex. \".doc\". |

**Returns:**
java.lang.String – den unika identifieraren för cacheposten som representerar en sidfil.
### getResourceKey(int pageNumber, Resource resource) {#getResourceKey-int-com.groupdocs.viewer.results.Resource-}
```
public static String getResourceKey(int pageNumber, Resource resource)
```


Returnerar en unik identifierare för cacheposten som representerar ett [Resource](../../com.groupdocs.viewer.results/resource)-objekt.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pageNumber | int | Sidans nummer. |
| resource | [Resource](../../com.groupdocs.viewer.results/resource) | HTML-resursen. |

**Returns:**
java.lang.String – den unika identifieraren för cacheposten.
### getResourceFilter(int pageNumber) {#getResourceFilter-int-}
```
public static String getResourceFilter(int pageNumber)
```


Returnerar en filtersträng för att söka efter cacheposter som representerar [Resource](../../com.groupdocs.viewer.results/resource)-objekt.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pageNumber | int | Sidans nummer. |

**Returns:**
java.lang.String – filtersträngen för att söka efter cacheposter.
