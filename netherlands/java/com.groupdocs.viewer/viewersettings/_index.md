---
title: "ViewerSettings"
second_title: "GroupDocs.Viewer for Java API-referentie"
description: "Definieert instellingen voor het aanpassen van het gedrag van de Viewer-component."
type: docs
weight: 13
url: /nl/java/com.groupdocs.viewer/viewersettings/
---
**Inheritance:**
java.lang.Object
```
public class ViewerSettings
```

Definieert instellingen voor het aanpassen van het gedrag van de Viewer-component.


De ViewerSettings‑klasse biedt opties en eigenschappen om het gedrag van de GroupDocs.Viewer‑component aan te passen tijdens het documentrenderproces.
U kunt deze klasse gebruiken om verschillende instellingen op te geven, zoals logger, aangepaste cache‑implementatie en meer.


Voorbeeldgebruik:

````

 final ViewerSettings viewerSettings = new ViewerSettings();
 viewerSettings.setLogger(new ConsoleLogger(false, true));

 try (Viewer viewer = new Viewer("source.pdf", viewerSettings)) {
     // Document processing
 }
 
````


## Constructors

| Constructor | Beschrijving |
| --- | --- |
|  | [ViewerSettings(Cache cache, ILogger logger)](#ViewerSettings-com.groupdocs.viewer.caching.Cache-com.groupdocs.foundation.logging.ILogger-) | Initialiseert een nieuw exemplaar van de |
ViewerSettings
klasse.
|
|  | [ViewerSettings(ILogger logger)](#ViewerSettings-com.groupdocs.foundation.logging.ILogger-) | Initialiseert een nieuw exemplaar van de |
ViewerSettings
klasse.
|
|  | [ViewerSettings(Cache cache)](#ViewerSettings-com.groupdocs.viewer.caching.Cache-) | Initialiseert een nieuw exemplaar van de |
ViewerSettings
klasse.
|
|  | [ViewerSettings()](#ViewerSettings--) | Initialiseert een nieuw exemplaar van de |
ViewerSettings
klasse.
|
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getLogger()](#getLogger--) | Haalt de logger‑implementatie op die wordt gebruikt voor logging (Fouten, Waarschuwingen, Traces). |
|
|  | [setLogger(ILogger logger)](#setLogger-com.groupdocs.foundation.logging.ILogger-) | Stelt de logger‑implementatie in die wordt gebruikt voor logging (Fouten, Waarschuwingen, Traces). |
|
|  | [getCache()](#getCache--) | Haalt de cache‑implementatie op die wordt gebruikt voor het opslaan van renderresultaten. |
|
|  | [setCache(Cache cache)](#setCache-com.groupdocs.viewer.caching.Cache-) | Stelt de cache‑implementatie in die wordt gebruikt voor het opslaan van renderresultaten. |
|
### ViewerSettings(Cache cache, ILogger logger) {#ViewerSettings-com.groupdocs.viewer.caching.Cache-com.groupdocs.foundation.logging.ILogger-}
```
public ViewerSettings(Cache cache, ILogger logger)
```


Initialiseert een nieuw exemplaar van de
ViewerSettings
klasse.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | cache | [Cache](../../com.groupdocs.viewer.caching/cache) | De cache. |
|
|  | logger | com.groupdocs.foundation.logging.ILogger | De logger. |
|

### ViewerSettings(ILogger logger) {#ViewerSettings-com.groupdocs.foundation.logging.ILogger-}
```
public ViewerSettings(ILogger logger)
```


Initialiseert een nieuw exemplaar van de
ViewerSettings
klasse.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | logger | com.groupdocs.foundation.logging.ILogger | De logger. |
|

### ViewerSettings(Cache cache) {#ViewerSettings-com.groupdocs.viewer.caching.Cache-}
```
public ViewerSettings(Cache cache)
```


Initialiseert een nieuw exemplaar van de
ViewerSettings
klasse.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | cache | [Cache](../../com.groupdocs.viewer.caching/cache) | De cache. |
|

### ViewerSettings() {#ViewerSettings--}
```
public ViewerSettings()
```


Initialiseert een nieuw exemplaar van de
ViewerSettings
klasse.


### getLogger() {#getLogger--}
```
public ILogger getLogger()
```


Haalt de logger‑implementatie op die wordt gebruikt voor logging (Fouten, Waarschuwingen, Traces).


**Returns:**
com.groupdocs.foundation.logging.ILogger - de logger‑implementatie.

### setLogger(ILogger logger) {#setLogger-com.groupdocs.foundation.logging.ILogger-}
```
public void setLogger(ILogger logger)
```


Stelt de logger‑implementatie in die wordt gebruikt voor logging (Fouten, Waarschuwingen, Traces).


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | logger | com.groupdocs.foundation.logging.ILogger | De logger‑implementatie om in te stellen. |
|

### getCache() {#getCache--}
```
public final Cache getCache()
```


Haalt de cache‑implementatie op die wordt gebruikt voor het opslaan van renderresultaten.


**Returns:**
[Cache](../../com.groupdocs.viewer.caching/cache) - the cache implementation.

### setCache(Cache cache) {#setCache-com.groupdocs.viewer.caching.Cache-}
```
public void setCache(Cache cache)
```


Stelt de cache‑implementatie in die wordt gebruikt voor het opslaan van renderresultaten.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | cache | [Cache](../../com.groupdocs.viewer.caching/cache) | De cache-implementatie. |
|

