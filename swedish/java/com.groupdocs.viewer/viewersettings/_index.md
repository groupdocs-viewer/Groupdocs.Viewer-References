---
title: "ViewerSettings"
second_title: "GroupDocs.Viewer för Java API-referens"
description: "Definierar inställningar för att anpassa beteendet hos Viewer-komponenten."
type: docs
weight: 13
url: /sv/java/com.groupdocs.viewer/viewersettings/
---
**Inheritance:**
java.lang.Object
```
public class ViewerSettings
```

Definierar inställningar för att anpassa beteendet hos Viewer-komponenten.


ViewerSettings-klassen tillhandahåller alternativ och egenskaper för att anpassa beteendet hos GroupDocs.Viewer-komponenten under dokumentrenderingsprocessen.
Du kan använda denna klass för att ange olika inställningar, såsom logger, anpassad cache-implementation och mer.


Exempel på användning:

````

 final ViewerSettings viewerSettings = new ViewerSettings();
 viewerSettings.setLogger(new ConsoleLogger(false, true));

 try (Viewer viewer = new Viewer("source.pdf", viewerSettings)) {
     // Document processing
 }
 
````


## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
|  | [ViewerSettings(Cache cache, ILogger logger)](#ViewerSettings-com.groupdocs.viewer.caching.Cache-com.groupdocs.foundation.logging.ILogger-) | Initierar en ny instans av |
ViewerSettings
klassen.
|
|  | [ViewerSettings(ILogger logger)](#ViewerSettings-com.groupdocs.foundation.logging.ILogger-) | Initierar en ny instans av |
ViewerSettings
klassen.
|
|  | [ViewerSettings(Cache cache)](#ViewerSettings-com.groupdocs.viewer.caching.Cache-) | Initierar en ny instans av |
ViewerSettings
klassen.
|
|  | [ViewerSettings()](#ViewerSettings--) | Initierar en ny instans av |
ViewerSettings
klassen.
|
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getLogger()](#getLogger--) | Hämtar logger-implementationen som används för loggning (Errors, Warnings, Traces). |
|
|  | [setLogger(ILogger logger)](#setLogger-com.groupdocs.foundation.logging.ILogger-) | Ställer in logger-implementationen som används för loggning (Errors, Warnings, Traces). |
|
|  | [getCache()](#getCache--) | Hämtar cache-implementationen som används för att lagra renderingsresultat. |
|
|  | [setCache(Cache cache)](#setCache-com.groupdocs.viewer.caching.Cache-) | Ställer in cache-implementationen som används för att lagra renderingsresultat. |
|
### ViewerSettings(Cache cache, ILogger logger) {#ViewerSettings-com.groupdocs.viewer.caching.Cache-com.groupdocs.foundation.logging.ILogger-}
```
public ViewerSettings(Cache cache, ILogger logger)
```


Initierar en ny instans av
ViewerSettings
klassen.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | cache | [Cache](../../com.groupdocs.viewer.caching/cache) | Cachen. |
|
|  | logger | com.groupdocs.foundation.logging.ILogger | Loggern. |
|

### ViewerSettings(ILogger logger) {#ViewerSettings-com.groupdocs.foundation.logging.ILogger-}
```
public ViewerSettings(ILogger logger)
```


Initierar en ny instans av
ViewerSettings
klassen.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | logger | com.groupdocs.foundation.logging.ILogger | Loggern. |
|

### ViewerSettings(Cache cache) {#ViewerSettings-com.groupdocs.viewer.caching.Cache-}
```
public ViewerSettings(Cache cache)
```


Initierar en ny instans av
ViewerSettings
klassen.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | cache | [Cache](../../com.groupdocs.viewer.caching/cache) | Cachen. |
|

### ViewerSettings() {#ViewerSettings--}
```
public ViewerSettings()
```


Initierar en ny instans av
ViewerSettings
klassen.


### getLogger() {#getLogger--}
```
public ILogger getLogger()
```


Hämtar logger-implementationen som används för loggning (Errors, Warnings, Traces).


**Returns:**
com.groupdocs.foundation.logging.ILogger - logger-implementationen.

### setLogger(ILogger logger) {#setLogger-com.groupdocs.foundation.logging.ILogger-}
```
public void setLogger(ILogger logger)
```


Ställer in logger-implementationen som används för loggning (Errors, Warnings, Traces).


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | logger | com.groupdocs.foundation.logging.ILogger | Logger-implementationen att ställa in. |
|

### getCache() {#getCache--}
```
public final Cache getCache()
```


Hämtar cache-implementationen som används för att lagra renderingsresultat.


**Returns:**
[Cache](../../com.groupdocs.viewer.caching/cache) - the cache implementation.

### setCache(Cache cache) {#setCache-com.groupdocs.viewer.caching.Cache-}
```
public void setCache(Cache cache)
```


Ställer in cache-implementationen som används för att lagra renderingsresultat.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | cache | [Cache](../../com.groupdocs.viewer.caching/cache) | Cache-implementationen. |
|

