---
title: "ViewerSettings"
second_title: "Référence API de GroupDocs.Viewer pour Java"
description: "Définit les paramètres permettant de personnaliser le comportement du composant Viewer."
type: docs
weight: 13
url: /fr/java/com.groupdocs.viewer/viewersettings/
---
**Inheritance:**
java.lang.Object
```
public class ViewerSettings
```

Définit les paramètres permettant de personnaliser le comportement du composant Viewer.


La classe ViewerSettings fournit des options et des propriétés pour personnaliser le comportement du composant GroupDocs.Viewer pendant le processus de rendu du document.
Vous pouvez utiliser cette classe pour spécifier divers paramètres, tels que le journaliseur, une implémentation de cache personnalisée, et plus encore.


Exemple d'utilisation :

````

 final ViewerSettings viewerSettings = new ViewerSettings();
 viewerSettings.setLogger(new ConsoleLogger(false, true));

 try (Viewer viewer = new Viewer("source.pdf", viewerSettings)) {
     // Document processing
 }
 
````


## Constructeurs

| Constructeur | Description |
| --- | --- |
|  | [ViewerSettings(Cache cache, ILogger logger)](#ViewerSettings-com.groupdocs.viewer.caching.Cache-com.groupdocs.foundation.logging.ILogger-) | Initialise une nouvelle instance de |
ViewerSettings
classe.
|
|  | [ViewerSettings(ILogger logger)](#ViewerSettings-com.groupdocs.foundation.logging.ILogger-) | Initialise une nouvelle instance de |
ViewerSettings
classe.
|
|  | [ViewerSettings(Cache cache)](#ViewerSettings-com.groupdocs.viewer.caching.Cache-) | Initialise une nouvelle instance de |
ViewerSettings
classe.
|
|  | [ViewerSettings()](#ViewerSettings--) | Initialise une nouvelle instance de |
ViewerSettings
classe.
|
## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getLogger()](#getLogger--) | Obtient l'implémentation du journaliseur utilisée pour la journalisation (Erreurs, Avertissements, Traces). |
|
|  | [setLogger(ILogger logger)](#setLogger-com.groupdocs.foundation.logging.ILogger-) | Définit l'implémentation du journaliseur utilisée pour la journalisation (Erreurs, Avertissements, Traces). |
|
|  | [getCache()](#getCache--) | Obtient l'implémentation du cache utilisée pour stocker les résultats du rendu. |
|
|  | [setCache(Cache cache)](#setCache-com.groupdocs.viewer.caching.Cache-) | Définit l'implémentation du cache utilisée pour stocker les résultats du rendu. |
|
### ViewerSettings(Cache cache, ILogger logger) {#ViewerSettings-com.groupdocs.viewer.caching.Cache-com.groupdocs.foundation.logging.ILogger-}
```
public ViewerSettings(Cache cache, ILogger logger)
```


Initialise une nouvelle instance de
ViewerSettings
classe.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | cache | [Cache](../../com.groupdocs.viewer.caching/cache) | Le cache. |
|
|  | logger | com.groupdocs.foundation.logging.ILogger | Le journaliseur. |
|

### ViewerSettings(ILogger logger) {#ViewerSettings-com.groupdocs.foundation.logging.ILogger-}
```
public ViewerSettings(ILogger logger)
```


Initialise une nouvelle instance de
ViewerSettings
classe.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | logger | com.groupdocs.foundation.logging.ILogger | Le journaliseur. |
|

### ViewerSettings(Cache cache) {#ViewerSettings-com.groupdocs.viewer.caching.Cache-}
```
public ViewerSettings(Cache cache)
```


Initialise une nouvelle instance de
ViewerSettings
classe.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | cache | [Cache](../../com.groupdocs.viewer.caching/cache) | Le cache. |
|

### ViewerSettings() {#ViewerSettings--}
```
public ViewerSettings()
```


Initialise une nouvelle instance de
ViewerSettings
classe.


### getLogger() {#getLogger--}
```
public ILogger getLogger()
```


Obtient l'implémentation du journaliseur utilisée pour la journalisation (Erreurs, Avertissements, Traces).


**Returns:**
com.groupdocs.foundation.logging.ILogger - l'implémentation du journaliseur.

### setLogger(ILogger logger) {#setLogger-com.groupdocs.foundation.logging.ILogger-}
```
public void setLogger(ILogger logger)
```


Définit l'implémentation du journaliseur utilisée pour la journalisation (Erreurs, Avertissements, Traces).


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | logger | com.groupdocs.foundation.logging.ILogger | L'implémentation du journaliseur à définir. |
|

### getCache() {#getCache--}
```
public final Cache getCache()
```


Obtient l'implémentation du cache utilisée pour stocker les résultats du rendu.


**Returns:**
[Cache](../../com.groupdocs.viewer.caching/cache) - the cache implementation.

### setCache(Cache cache) {#setCache-com.groupdocs.viewer.caching.Cache-}
```
public void setCache(Cache cache)
```


Définit l'implémentation du cache utilisée pour stocker les résultats du rendu.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | cache | [Cache](../../com.groupdocs.viewer.caching/cache) | L'implémentation du cache. |
|

