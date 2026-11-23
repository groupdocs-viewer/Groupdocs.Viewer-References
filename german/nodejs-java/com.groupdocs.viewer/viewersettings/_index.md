---
title: "ViewerSettings"
second_title: "GroupDocs.Viewer für Node.js über Java API-Referenz"
description: "Definiert Einstellungen zur Anpassung des Verhaltens der Viewer-Komponente."
type: docs
weight: 13
url: /de/nodejs-java/com.groupdocs.viewer/viewersettings/
---
**Inheritance:**
java.lang.Object
```
public class ViewerSettings
```

Definiert Einstellungen zur Anpassung des Verhaltens der Viewer-Komponente.

Die ViewerSettings-Klasse bietet Optionen und Eigenschaften, um das Verhalten der GroupDocs.Viewer-Komponente während des Dokumentenrenderings anzupassen. Sie können diese Klasse verwenden, um verschiedene Einstellungen festzulegen, wie Logger, benutzerdefinierte Cache-Implementierung und mehr.

Beispielhafte Verwendung:

```

 final ViewerSettings viewerSettings = new ViewerSettings();
 viewerSettings.setLogger(new ConsoleLogger(false, true));

 try (Viewer viewer = new Viewer("source.pdf", viewerSettings)) {
     // Document processing
 }
 
```
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [ViewerSettings(Cache cache, ILogger logger)](#ViewerSettings-com.groupdocs.viewer.caching.Cache-com.groupdocs.foundation.logging.ILogger-) | Initialisiert eine neue Instanz der ViewerSettings-Klasse. |
| [ViewerSettings(ILogger logger)](#ViewerSettings-com.groupdocs.foundation.logging.ILogger-) | Initialisiert eine neue Instanz der ViewerSettings-Klasse. |
| [ViewerSettings(Cache cache)](#ViewerSettings-com.groupdocs.viewer.caching.Cache-) | Initialisiert eine neue Instanz der ViewerSettings-Klasse. |
| [ViewerSettings()](#ViewerSettings--) | Initialisiert eine neue Instanz der ViewerSettings-Klasse. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getLogger()](#getLogger--) | Ruft die Logger-Implementierung ab, die für das Protokollieren (Fehler, Warnungen, Trace) verwendet wird. |
| [setLogger(ILogger logger)](#setLogger-com.groupdocs.foundation.logging.ILogger-) | Setzt die Logger-Implementierung, die für das Protokollieren (Fehler, Warnungen, Trace) verwendet wird. |
| [getCache()](#getCache--) | Ruft die Cache-Implementierung ab, die zum Speichern von Rendering-Ergebnissen verwendet wird. |
| [setCache(Cache cache)](#setCache-com.groupdocs.viewer.caching.Cache-) | Setzt die Cache-Implementierung, die zum Speichern von Rendering-Ergebnissen verwendet wird. |
### ViewerSettings(Cache cache, ILogger logger) {#ViewerSettings-com.groupdocs.viewer.caching.Cache-com.groupdocs.foundation.logging.ILogger-}
```
public ViewerSettings(Cache cache, ILogger logger)
```


Initialisiert eine neue Instanz der ViewerSettings-Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| cache | [Cache](../../com.groupdocs.viewer.caching/cache) | Der Cache. |
| Logger | com.groupdocs.foundation.logging.ILogger | Der Logger. |

### ViewerSettings(ILogger logger) {#ViewerSettings-com.groupdocs.foundation.logging.ILogger-}
```
public ViewerSettings(ILogger logger)
```


Initialisiert eine neue Instanz der ViewerSettings-Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Logger | com.groupdocs.foundation.logging.ILogger | Der Logger. |

### ViewerSettings(Cache cache) {#ViewerSettings-com.groupdocs.viewer.caching.Cache-}
```
public ViewerSettings(Cache cache)
```


Initialisiert eine neue Instanz der ViewerSettings-Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| cache | [Cache](../../com.groupdocs.viewer.caching/cache) | Der Cache. |

### ViewerSettings() {#ViewerSettings--}
```
public ViewerSettings()
```


Initialisiert eine neue Instanz der ViewerSettings-Klasse.

### getLogger() {#getLogger--}
```
public ILogger getLogger()
```


Ruft die Logger-Implementierung ab, die für das Protokollieren (Fehler, Warnungen, Trace) verwendet wird.

**Returns:**
com.groupdocs.foundation.logging.ILogger - die Logger-Implementierung.
### setLogger(ILogger logger) {#setLogger-com.groupdocs.foundation.logging.ILogger-}
```
public void setLogger(ILogger logger)
```


Setzt die Logger-Implementierung, die für das Protokollieren (Fehler, Warnungen, Trace) verwendet wird.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Logger | com.groupdocs.foundation.logging.ILogger | Die zu setzende Logger-Implementierung. |

### getCache() {#getCache--}
```
public final Cache getCache()
```


Ruft die Cache-Implementierung ab, die zum Speichern von Rendering-Ergebnissen verwendet wird.

**Returns:**
[Cache](../../com.groupdocs.viewer.caching/cache) - the cache implementation.
### setCache(Cache cache) {#setCache-com.groupdocs.viewer.caching.Cache-}
```
public void setCache(Cache cache)
```


Setzt die Cache-Implementierung, die zum Speichern von Rendering-Ergebnissen verwendet wird.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| cache | [Cache](../../com.groupdocs.viewer.caching/cache) | Die Cache-Implementierung. |

