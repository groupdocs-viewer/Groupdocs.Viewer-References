---
title: "ViewerSettings"
second_title: "GroupDocs.Viewer for Java Referencia de API"
description: "Define configuraciones para personalizar el comportamiento del componente Viewer."
type: docs
weight: 13
url: /es/java/com.groupdocs.viewer/viewersettings/
---
**Inheritance:**
java.lang.Object
```
public class ViewerSettings
```

Define configuraciones para personalizar el comportamiento del componente Viewer.


La clase ViewerSettings proporciona opciones y propiedades para personalizar el comportamiento del componente GroupDocs.Viewer durante el proceso de renderizado del documento.
Puede usar esta clase para especificar varias configuraciones, como el registrador, una implementación de caché personalizada y más.


Ejemplo de uso:

````

 final ViewerSettings viewerSettings = new ViewerSettings();
 viewerSettings.setLogger(new ConsoleLogger(false, true));

 try (Viewer viewer = new Viewer("source.pdf", viewerSettings)) {
     // Document processing
 }
 
````


## Constructores

| Constructor | Descripción |
| --- | --- |
|  | [ViewerSettings(Cache cache, ILogger logger)](#ViewerSettings-com.groupdocs.viewer.caching.Cache-com.groupdocs.foundation.logging.ILogger-) | Inicializa una nueva instancia de la |
ViewerSettings
clase.
|
|  | [ViewerSettings(ILogger logger)](#ViewerSettings-com.groupdocs.foundation.logging.ILogger-) | Inicializa una nueva instancia de la |
ViewerSettings
clase.
|
|  | [ViewerSettings(Cache cache)](#ViewerSettings-com.groupdocs.viewer.caching.Cache-) | Inicializa una nueva instancia de la |
ViewerSettings
clase.
|
|  | [ViewerSettings()](#ViewerSettings--) | Inicializa una nueva instancia de la |
ViewerSettings
clase.
|
## Métodos

| Método | Descripción |
| --- | --- |
|  | [getLogger()](#getLogger--) | Obtiene la implementación del registrador utilizada para el registro (Errores, Advertencias, Trazas). |
|
|  | [setLogger(ILogger logger)](#setLogger-com.groupdocs.foundation.logging.ILogger-) | Establece la implementación del registrador utilizada para el registro (Errores, Advertencias, Trazas). |
|
|  | [getCache()](#getCache--) | Obtiene la implementación de caché utilizada para almacenar los resultados del renderizado. |
|
|  | [setCache(Cache cache)](#setCache-com.groupdocs.viewer.caching.Cache-) | Establece la implementación de caché utilizada para almacenar los resultados del renderizado. |
|
### ViewerSettings(Cache cache, ILogger logger) {#ViewerSettings-com.groupdocs.viewer.caching.Cache-com.groupdocs.foundation.logging.ILogger-}
```
public ViewerSettings(Cache cache, ILogger logger)
```


Inicializa una nueva instancia de la
ViewerSettings
clase.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | cache | [Cache](../../com.groupdocs.viewer.caching/cache) | La caché. |
|
|  | registrador | com.groupdocs.foundation.logging.ILogger | El registrador. |
|

### ViewerSettings(ILogger logger) {#ViewerSettings-com.groupdocs.foundation.logging.ILogger-}
```
public ViewerSettings(ILogger logger)
```


Inicializa una nueva instancia de la
ViewerSettings
clase.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | registrador | com.groupdocs.foundation.logging.ILogger | El registrador. |
|

### ViewerSettings(Cache cache) {#ViewerSettings-com.groupdocs.viewer.caching.Cache-}
```
public ViewerSettings(Cache cache)
```


Inicializa una nueva instancia de la
ViewerSettings
clase.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | cache | [Cache](../../com.groupdocs.viewer.caching/cache) | La caché. |
|

### ViewerSettings() {#ViewerSettings--}
```
public ViewerSettings()
```


Inicializa una nueva instancia de la
ViewerSettings
clase.


### getLogger() {#getLogger--}
```
public ILogger getLogger()
```


Obtiene la implementación del registrador utilizada para el registro (Errores, Advertencias, Trazas).


**Returns:**
com.groupdocs.foundation.logging.ILogger - la implementación del registrador.

### setLogger(ILogger logger) {#setLogger-com.groupdocs.foundation.logging.ILogger-}
```
public void setLogger(ILogger logger)
```


Establece la implementación del registrador utilizada para el registro (Errores, Advertencias, Trazas).


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | registrador | com.groupdocs.foundation.logging.ILogger | La implementación del registrador a establecer. |
|

### getCache() {#getCache--}
```
public final Cache getCache()
```


Obtiene la implementación de caché utilizada para almacenar los resultados del renderizado.


**Returns:**
[Cache](../../com.groupdocs.viewer.caching/cache) - the cache implementation.

### setCache(Cache cache) {#setCache-com.groupdocs.viewer.caching.Cache-}
```
public void setCache(Cache cache)
```


Establece la implementación de caché utilizada para almacenar los resultados del renderizado.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | cache | [Cache](../../com.groupdocs.viewer.caching/cache) | La implementación de caché. |
|

