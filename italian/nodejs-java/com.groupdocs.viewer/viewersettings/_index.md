---
title: "ViewerSettings"
second_title: "GroupDocs.Viewer per Node.js via Java Riferimento API"
description: "Definisce le impostazioni per personalizzare il comportamento del componente Viewer."
type: docs
weight: 13
url: /it/nodejs-java/com.groupdocs.viewer/viewersettings/
---
**Inheritance:**
java.lang.Object
```
public class ViewerSettings
```

Definisce le impostazioni per personalizzare il comportamento del componente Viewer.

La classe ViewerSettings fornisce opzioni e proprietà per personalizzare il comportamento del componente GroupDocs.Viewer durante il processo di rendering del documento. È possibile utilizzare questa classe per specificare varie impostazioni, come il logger, un'implementazione di cache personalizzata e altro.

Esempio di utilizzo:

```

 final ViewerSettings viewerSettings = new ViewerSettings();
 viewerSettings.setLogger(new ConsoleLogger(false, true));

 try (Viewer viewer = new Viewer("source.pdf", viewerSettings)) {
     // Document processing
 }
 
```
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [ViewerSettings(Cache cache, ILogger logger)](#ViewerSettings-com.groupdocs.viewer.caching.Cache-com.groupdocs.foundation.logging.ILogger-) | Inizializza una nuova istanza della classe ViewerSettings. |
| [ViewerSettings(ILogger logger)](#ViewerSettings-com.groupdocs.foundation.logging.ILogger-) | Inizializza una nuova istanza della classe ViewerSettings. |
| [ViewerSettings(Cache cache)](#ViewerSettings-com.groupdocs.viewer.caching.Cache-) | Inizializza una nuova istanza della classe ViewerSettings. |
| [ViewerSettings()](#ViewerSettings--) | Inizializza una nuova istanza della classe ViewerSettings. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getLogger()](#getLogger--) | Ottiene l'implementazione del logger utilizzata per il logging (Errori, Avvisi, Tracce). |
| [setLogger(ILogger logger)](#setLogger-com.groupdocs.foundation.logging.ILogger-) | Imposta l'implementazione del logger utilizzata per il logging (Errori, Avvisi, Tracce). |
| [getCache()](#getCache--) | Ottiene l'implementazione della cache utilizzata per memorizzare i risultati del rendering. |
| [setCache(Cache cache)](#setCache-com.groupdocs.viewer.caching.Cache-) | Imposta l'implementazione della cache utilizzata per memorizzare i risultati del rendering. |
### ViewerSettings(Cache cache, ILogger logger) {#ViewerSettings-com.groupdocs.viewer.caching.Cache-com.groupdocs.foundation.logging.ILogger-}
```
public ViewerSettings(Cache cache, ILogger logger)
```


Inizializza una nuova istanza della classe ViewerSettings.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| cache | [Cache](../../com.groupdocs.viewer.caching/cache) | La cache. |
| logger | com.groupdocs.foundation.logging.ILogger | Il logger. |

### ViewerSettings(ILogger logger) {#ViewerSettings-com.groupdocs.foundation.logging.ILogger-}
```
public ViewerSettings(ILogger logger)
```


Inizializza una nuova istanza della classe ViewerSettings.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| logger | com.groupdocs.foundation.logging.ILogger | Il logger. |

### ViewerSettings(Cache cache) {#ViewerSettings-com.groupdocs.viewer.caching.Cache-}
```
public ViewerSettings(Cache cache)
```


Inizializza una nuova istanza della classe ViewerSettings.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| cache | [Cache](../../com.groupdocs.viewer.caching/cache) | La cache. |

### ViewerSettings() {#ViewerSettings--}
```
public ViewerSettings()
```


Inizializza una nuova istanza della classe ViewerSettings.

### getLogger() {#getLogger--}
```
public ILogger getLogger()
```


Ottiene l'implementazione del logger utilizzata per il logging (Errori, Avvisi, Tracce).

**Returns:**
com.groupdocs.foundation.logging.ILogger - l'implementazione del logger.
### setLogger(ILogger logger) {#setLogger-com.groupdocs.foundation.logging.ILogger-}
```
public void setLogger(ILogger logger)
```


Imposta l'implementazione del logger utilizzata per il logging (Errori, Avvisi, Tracce).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| logger | com.groupdocs.foundation.logging.ILogger | L'implementazione del logger da impostare. |

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
| cache | [Cache](../../com.groupdocs.viewer.caching/cache) | L'implementazione della cache. |

