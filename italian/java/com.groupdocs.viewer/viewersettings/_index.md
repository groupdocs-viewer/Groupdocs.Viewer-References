---
title: "ViewerSettings"
second_title: "Riferimento API di GroupDocs.Viewer per Java"
description: "Definisce le impostazioni per personalizzare il comportamento del componente Viewer."
type: docs
weight: 13
url: /it/java/com.groupdocs.viewer/viewersettings/
---
**Inheritance:**
java.lang.Object
```
public class ViewerSettings
```

Definisce le impostazioni per personalizzare il comportamento del componente Viewer.


La classe ViewerSettings fornisce opzioni e proprietà per personalizzare il comportamento del componente GroupDocs.Viewer durante il processo di rendering del documento.
È possibile utilizzare questa classe per specificare varie impostazioni, come il logger, un'implementazione di cache personalizzata e altro.


Esempio di utilizzo:

````

 final ViewerSettings viewerSettings = new ViewerSettings();
 viewerSettings.setLogger(new ConsoleLogger(false, true));

 try (Viewer viewer = new Viewer("source.pdf", viewerSettings)) {
     // Document processing
 }
 
````


## Costruttori

| Costruttore | Descrizione |
| --- | --- |
|  | [ViewerSettings(Cache cache, ILogger logger)](#ViewerSettings-com.groupdocs.viewer.caching.Cache-com.groupdocs.foundation.logging.ILogger-) | Inizializza una nuova istanza di |
ViewerSettings
classe.
|
|  | [ViewerSettings(ILogger logger)](#ViewerSettings-com.groupdocs.foundation.logging.ILogger-) | Inizializza una nuova istanza di |
ViewerSettings
classe.
|
|  | [ViewerSettings(Cache cache)](#ViewerSettings-com.groupdocs.viewer.caching.Cache-) | Inizializza una nuova istanza di |
ViewerSettings
classe.
|
|  | [ViewerSettings()](#ViewerSettings--) | Inizializza una nuova istanza di |
ViewerSettings
classe.
|
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [getLogger()](#getLogger--) | Ottiene l'implementazione del logger utilizzata per il logging (Errori, Avvisi, Traces). |
|
|  | [setLogger(ILogger logger)](#setLogger-com.groupdocs.foundation.logging.ILogger-) | Imposta l'implementazione del logger utilizzata per il logging (Errori, Avvisi, Traces). |
|
|  | [getCache()](#getCache--) | Ottiene l'implementazione della cache utilizzata per memorizzare i risultati del rendering. |
|
|  | [setCache(Cache cache)](#setCache-com.groupdocs.viewer.caching.Cache-) | Imposta l'implementazione della cache utilizzata per memorizzare i risultati del rendering. |
|
### ViewerSettings(Cache cache, ILogger logger) {#ViewerSettings-com.groupdocs.viewer.caching.Cache-com.groupdocs.foundation.logging.ILogger-}
```
public ViewerSettings(Cache cache, ILogger logger)
```


Inizializza una nuova istanza di
ViewerSettings
classe.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | cache | [Cache](../../com.groupdocs.viewer.caching/cache) | La cache. |
|
|  | logger | com.groupdocs.foundation.logging.ILogger | Il logger. |
|

### ViewerSettings(ILogger logger) {#ViewerSettings-com.groupdocs.foundation.logging.ILogger-}
```
public ViewerSettings(ILogger logger)
```


Inizializza una nuova istanza di
ViewerSettings
classe.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | logger | com.groupdocs.foundation.logging.ILogger | Il logger. |
|

### ViewerSettings(Cache cache) {#ViewerSettings-com.groupdocs.viewer.caching.Cache-}
```
public ViewerSettings(Cache cache)
```


Inizializza una nuova istanza di
ViewerSettings
classe.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | cache | [Cache](../../com.groupdocs.viewer.caching/cache) | La cache. |
|

### ViewerSettings() {#ViewerSettings--}
```
public ViewerSettings()
```


Inizializza una nuova istanza di
ViewerSettings
classe.


### getLogger() {#getLogger--}
```
public ILogger getLogger()
```


Ottiene l'implementazione del logger utilizzata per il logging (Errori, Avvisi, Traces).


**Returns:**
com.groupdocs.foundation.logging.ILogger - l'implementazione del logger.

### setLogger(ILogger logger) {#setLogger-com.groupdocs.foundation.logging.ILogger-}
```
public void setLogger(ILogger logger)
```


Imposta l'implementazione del logger utilizzata per il logging (Errori, Avvisi, Traces).


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | logger | com.groupdocs.foundation.logging.ILogger | L'implementazione del logger da impostare. |
|

### getCache() {#getCache--}
```
public final Cache getCache()
```


Ottiene l'implementazione della cache utilizzata per memorizzare i risultati del rendering.


**Returns:**
[Cache](../../com.groupdocs.viewer.caching/cache) - the cache implementation.

### setCache(Cache cache) {#setCache-com.groupdocs.viewer.caching.Cache-}
```
public void setCache(Cache cache)
```


Imposta l'implementazione della cache utilizzata per memorizzare i risultati del rendering.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | cache | [Cache](../../com.groupdocs.viewer.caching/cache) | L'implementazione della cache. |
|

