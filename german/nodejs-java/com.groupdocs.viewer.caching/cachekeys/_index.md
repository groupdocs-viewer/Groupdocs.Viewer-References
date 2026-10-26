---
title: "CacheKeys"
second_title: "GroupDocs.Viewer für Node.js über Java API-Referenz"
description: "Stellt Methoden bereit, um die eindeutige Kennung eines Cache‑Eintrags abzurufen."
type: docs
weight: 10
url: /de/nodejs-java/com.groupdocs.viewer.caching/cachekeys/
---
**Inheritance:**
java.lang.Object
```
public class CacheKeys
```

Stellt Methoden bereit, um die eindeutige Kennung eines Cache‑Eintrags abzurufen.

Die Klasse ermöglicht das Erzeugen von Cache‑Schlüsseln basierend auf verschiedenen Parametern, wie dem Dokumentpfad, den Rendering‑Optionen und dem Ressourcennamen. Diese Cache‑Schlüssel können verwendet werden, um zwischengespeicherte Daten für ein effizientes Dokument‑Rendering zu speichern und abzurufen.

Beispielhafte Verwendung:

```

 // Generate a cache key for a file
 String fileKey = CacheKeys.getFileKey("filename.pdf");

 // Generate a cache key for a page
 String pageKey = CacheKeys.getPageKey(pageNumber, FileType.HTML.getExtension());

 // Generate a cache key for a resource
 Resource resource = new Resource("styles.css", false);
 String pageKey = CacheKeys.getResourceKey(pageNumber, resource);
 
```
## Felder

| Feld | Beschreibung |
| --- | --- |
| [PAGE_NUMBER](#PAGE-NUMBER) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getAttachmentsKey()](#getAttachmentsKey--) | Gibt den eindeutigen Bezeichner für den Cache‑Eintrag zurück, der eine Sammlung von [Attachment](../../com.groupdocs.viewer.results/attachment)-Objekten darstellt. |
| [getAttachmentKey(String attachmentId)](#getAttachmentKey-java.lang.String-) | Ruft den eindeutigen Bezeichner für den Cache‑Eintrag ab, der eine Anhangsdatei darstellt. |
| [getViewInfoKey()](#getViewInfoKey--) | Ruft den eindeutigen Bezeichner für den Cache‑Eintrag ab, der ein [ViewInfo](../../com.groupdocs.viewer.results/viewinfo)-Objekt darstellt. |
| [getFileInfoKey()](#getFileInfoKey--) | Ruft den eindeutigen Bezeichner für den Cache‑Eintrag ab, der ein [ViewInfo](../../com.groupdocs.viewer.results/viewinfo)-Objekt darstellt. |
| [getFileKey(String extension)](#getFileKey-java.lang.String-) | Ruft die eindeutige Kennung für den Cache‑Eintrag ab, der eine Datei darstellt. |
| [getPageKey(int pageNumber, String extension)](#getPageKey-int-java.lang.String-) | Ruft die eindeutige Kennung für den Cache‑Eintrag ab, der eine Seiten‑Datei darstellt. |
| [getResourceKey(int pageNumber, Resource resource)](#getResourceKey-int-com.groupdocs.viewer.results.Resource-) | Gibt eine eindeutige Kennung für den Cache‑Eintrag zurück, der ein [Resource](../../com.groupdocs.viewer.results/resource)-Objekt darstellt. |
| [getResourceFilter(int pageNumber)](#getResourceFilter-int-) | Gibt einen Filter‑String zurück, um nach Cache‑Einträgen zu suchen, die [Resource](../../com.groupdocs.viewer.results/resource)-Objekte darstellen. |
### PAGE_NUMBER {#PAGE-NUMBER}
```
public static final String PAGE_NUMBER
```


### getAttachmentsKey() {#getAttachmentsKey--}
```
public static String getAttachmentsKey()
```


Gibt den eindeutigen Bezeichner für den Cache‑Eintrag zurück, der eine Sammlung von [Attachment](../../com.groupdocs.viewer.results/attachment)-Objekten darstellt.

**Returns:**
java.lang.String - die eindeutige Kennung für den Anhänge‑Cache‑Eintrag.
### getAttachmentKey(String attachmentId) {#getAttachmentKey-java.lang.String-}
```
public static String getAttachmentKey(String attachmentId)
```


Ruft den eindeutigen Bezeichner für den Cache‑Eintrag ab, der eine Anhangsdatei darstellt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| attachmentId | java.lang.String | Die eindeutige Kennung des Anhangs (im Kontext einer einzelnen Datei). |

**Returns:**
java.lang.String - die eindeutige Kennung für den Anhang‑Datei‑Cache‑Eintrag.
### getViewInfoKey() {#getViewInfoKey--}
```
public static String getViewInfoKey()
```


Ruft den eindeutigen Bezeichner für den Cache‑Eintrag ab, der ein [ViewInfo](../../com.groupdocs.viewer.results/viewinfo)-Objekt darstellt.

**Returns:**
java.lang.String - die eindeutige Kennung für den Cache‑Eintrag.
### getFileInfoKey() {#getFileInfoKey--}
```
public static String getFileInfoKey()
```


Ruft den eindeutigen Bezeichner für den Cache‑Eintrag ab, der ein [ViewInfo](../../com.groupdocs.viewer.results/viewinfo)-Objekt darstellt.

**Returns:**
java.lang.String - die eindeutige Kennung für den Cache‑Eintrag, der ein [ViewInfo](../../com.groupdocs.viewer.results/viewinfo)-Objekt darstellt.
### getFileKey(String extension) {#getFileKey-java.lang.String-}
```
public static String getFileKey(String extension)
```


Ruft die eindeutige Kennung für den Cache‑Eintrag ab, der eine Datei darstellt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| extension | java.lang.String | Der Dateinamensuffix (einschließlich des Punktes "."), z. B. ".doc". |

**Returns:**
java.lang.String - die eindeutige Kennung für den Cache‑Eintrag, der eine Datei darstellt.
### getPageKey(int pageNumber, String extension) {#getPageKey-int-java.lang.String-}
```
public static String getPageKey(int pageNumber, String extension)
```


Ruft die eindeutige Kennung für den Cache‑Eintrag ab, der eine Seiten‑Datei darstellt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pageNumber | int | Die Nummer der Seite. |
| extension | java.lang.String | Der Dateinamensuffix (einschließlich des Punktes "."), z. B. ".doc". |

**Returns:**
java.lang.String - die eindeutige Kennung für den Cache‑Eintrag, der eine Seiten‑Datei darstellt.
### getResourceKey(int pageNumber, Resource resource) {#getResourceKey-int-com.groupdocs.viewer.results.Resource-}
```
public static String getResourceKey(int pageNumber, Resource resource)
```


Gibt eine eindeutige Kennung für den Cache‑Eintrag zurück, der ein [Resource](../../com.groupdocs.viewer.results/resource)-Objekt darstellt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pageNumber | int | Die Nummer der Seite. |
| resource | [Resource](../../com.groupdocs.viewer.results/resource) | Die HTML‑Resource. |

**Returns:**
java.lang.String - die eindeutige Kennung für den Cache‑Eintrag.
### getResourceFilter(int pageNumber) {#getResourceFilter-int-}
```
public static String getResourceFilter(int pageNumber)
```


Gibt einen Filter‑String zurück, um nach Cache‑Einträgen zu suchen, die [Resource](../../com.groupdocs.viewer.results/resource)-Objekte darstellen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pageNumber | int | Die Nummer der Seite. |

**Returns:**
java.lang.String - der Filter‑String, um nach Cache‑Einträgen zu suchen.
