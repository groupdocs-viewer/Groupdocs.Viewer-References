---
title: "ViewerSettings"
second_title: "GroupDocs.Viewer für Java API-Referenz"
description: "Definiert Einstellungen zur Anpassung des Verhaltens der Viewer-Komponente."
type: docs
weight: 13
url: /de/java/com.groupdocs.viewer/viewersettings/
---
**Inheritance:**
java.lang.Object
```
public class ViewerSettings
```

Definiert Einstellungen zur Anpassung des Verhaltens der Viewer-Komponente.


Die ViewerSettings-Klasse bietet Optionen und Eigenschaften, um das Verhalten der GroupDocs.Viewer-Komponente während des Dokumentenrenderings anzupassen.
Sie können diese Klasse verwenden, um verschiedene Einstellungen festzulegen, wie z.B. Logger, benutzerdefinierte Cache-Implementierung und mehr.


Beispielverwendung:

````

 final ViewerSettings viewerSettings = new ViewerSettings();
 viewerSettings.setLogger(new ConsoleLogger(false, true));

 try (Viewer viewer = new Viewer("source.pdf", viewerSettings)) {
     // Document processing
 }
 
````


## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
|  | [ViewerSettings(Cache cache, ILogger logger)](#ViewerSettings-com.groupdocs.viewer.caching.Cache-com.groupdocs.foundation.logging.ILogger-) | Initialisiert eine neue Instanz von |
ViewerSettings
Klasse.
|
|  | [ViewerSettings(ILogger logger)](#ViewerSettings-com.groupdocs.foundation.logging.ILogger-) | Initialisiert eine neue Instanz von |
ViewerSettings
Klasse.
|
|  | [ViewerSettings(Cache cache)](#ViewerSettings-com.groupdocs.viewer.caching.Cache-) | Initialisiert eine neue Instanz von |
ViewerSettings
Klasse.
|
|  | [ViewerSettings()](#ViewerSettings--) | Initialisiert eine neue Instanz von |
ViewerSettings
Klasse.
|
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getLogger()](#getLogger--) | Ruft die Logger-Implementierung ab, die für die Protokollierung (Fehler, Warnungen, Traces) verwendet wird. |
|
|  | [setLogger(ILogger logger)](#setLogger-com.groupdocs.foundation.logging.ILogger-) | Legt die Logger-Implementierung fest, die für die Protokollierung (Fehler, Warnungen, Traces) verwendet wird. |
|
|  | [getCache()](#getCache--) | Ruft die Cache-Implementierung ab, die zum Speichern von Rendering-Ergebnissen verwendet wird. |
|
|  | [setCache(Cache cache)](#setCache-com.groupdocs.viewer.caching.Cache-) | Legt die Cache-Implementierung fest, die zum Speichern von Rendering-Ergebnissen verwendet wird. |
|
### ViewerSettings(Cache cache, ILogger logger) {#ViewerSettings-com.groupdocs.viewer.caching.Cache-com.groupdocs.foundation.logging.ILogger-}
```
public ViewerSettings(Cache cache, ILogger logger)
```


Initialisiert eine neue Instanz von
ViewerSettings
Klasse.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | cache | [Cache](../../com.groupdocs.viewer.caching/cache) | Der Cache. |
|
|  | Logger | com.groupdocs.foundation.logging.ILogger | Der Logger. |
|

### ViewerSettings(ILogger logger) {#ViewerSettings-com.groupdocs.foundation.logging.ILogger-}
```
public ViewerSettings(ILogger logger)
```


Initialisiert eine neue Instanz von
ViewerSettings
Klasse.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Logger | com.groupdocs.foundation.logging.ILogger | Der Logger. |
|

### ViewerSettings(Cache cache) {#ViewerSettings-com.groupdocs.viewer.caching.Cache-}
```
public ViewerSettings(Cache cache)
```


Initialisiert eine neue Instanz von
ViewerSettings
Klasse.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | cache | [Cache](../../com.groupdocs.viewer.caching/cache) | Der Cache. |
|

### ViewerSettings() {#ViewerSettings--}
```
public ViewerSettings()
```


Initialisiert eine neue Instanz von
ViewerSettings
Klasse.


### getLogger() {#getLogger--}
```
public ILogger getLogger()
```


Ruft die Logger-Implementierung ab, die für die Protokollierung (Fehler, Warnungen, Traces) verwendet wird.


**Returns:**
com.groupdocs.foundation.logging.ILogger – die Logger-Implementierung.

### setLogger(ILogger logger) {#setLogger-com.groupdocs.foundation.logging.ILogger-}
```
public void setLogger(ILogger logger)
```


Legt die Logger-Implementierung fest, die für die Protokollierung (Fehler, Warnungen, Traces) verwendet wird.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Logger | com.groupdocs.foundation.logging.ILogger | Die festzulegende Logger-Implementierung. |
|

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


Legt die Cache-Implementierung fest, die zum Speichern von Rendering-Ergebnissen verwendet wird.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | cache | [Cache](../../com.groupdocs.viewer.caching/cache) | Die Cache-Implementierung. |
|

