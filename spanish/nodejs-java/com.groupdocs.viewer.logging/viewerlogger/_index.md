---
title: "ViewerLogger"
second_title: "Referencia de API de GroupDocs.Viewer para Node.js vía Java"
description: "Registrador global del visor."
type: docs
weight: 11
url: /es/nodejs-java/com.groupdocs.viewer.logging/viewerlogger/
---
**Inheritance:**
java.lang.Object
```
public class ViewerLogger
```

Registrador global del visor.

La clase  ViewerLogger  proporciona funcionalidad para registrar mensajes en un registrador integrado o definido por el usuario. Sirve como el registrador global para el módulo viewer y puede usarse para registrar varios eventos y mensajes.

Ejemplo de uso:

```

 // Configure the viewer logger to use the default integrated logger
 ViewerLogger.setLogger(new FileLogger("/path/to/file.log"));

 // Log an debug message
 ViewerLogger.debug("Debug message");

 // Log an error message
 ViewerLogger.error("Error message");
 
```

***Note:** The  ViewerLogger  class can be configured to use a custom logger implementation by calling the [setLogger(ILogger)](../../com.groupdocs.viewer.logging/viewerlogger\#setLogger-ILogger-) method. By default, it uses the integrated logger provided by the viewer module.*
## Constructores

| Constructor | Descripción |
| --- | --- |
| [ViewerLogger()](#ViewerLogger--) |  |
## Métodos

| Método | Descripción |
| --- | --- |
| [trace(String message, Object[] arguments)](#trace-java.lang.String-java.lang.Object...-) | Escribe un mensaje de rastreo en la consola. |
| [trace(Throwable throwable, String message, Object[] arguments)](#trace-java.lang.Throwable-java.lang.String-java.lang.Object...-) | Escribe un mensaje de registro de rastreo en la consola. |
| [isTraceEnabled()](#isTraceEnabled--) | Comprueba si el nivel de rastreo está habilitado para el registro. |
| [debug(String message, Object[] arguments)](#debug-java.lang.String-java.lang.Object...-) | Escribe un mensaje de registro de depuración en la consola. |
| [debug(Throwable throwable, String message, Object[] arguments)](#debug-java.lang.Throwable-java.lang.String-java.lang.Object...-) | Escribe un mensaje de registro de depuración en la consola. |
| [isDebugEnabled()](#isDebugEnabled--) | Comprueba si el nivel de depuración está habilitado para el registro. |
| [warning(String message, Object[] arguments)](#warning-java.lang.String-java.lang.Object...-) | Escribe un mensaje de registro de advertencia en la consola. |
| [warning(Throwable throwable, String message, Object[] arguments)](#warning-java.lang.Throwable-java.lang.String-java.lang.Object...-) | Escribe un mensaje de registro de advertencia en la consola. |
| [isWarningEnabled()](#isWarningEnabled--) | Comprueba si el nivel de advertencia está habilitado para el registro. |
| [error(String message, Object[] arguments)](#error-java.lang.String-java.lang.Object...-) | Escribe un mensaje de registro de error en la consola. |
| [error(Throwable throwable, String message, Object[] arguments)](#error-java.lang.Throwable-java.lang.String-java.lang.Object...-) | Escribe un mensaje de registro de error en la consola. |
| [isErrorEnabled()](#isErrorEnabled--) | Comprueba si el registro a nivel de error está habilitado. |
| [getLogger()](#getLogger--) | Obtiene la instancia del registrador que se utilizará para registrar mensajes. |
| [setLogger(ILogger logger)](#setLogger-com.groupdocs.foundation.logging.ILogger-) | Establece la instancia del registrador que se utilizará para registrar mensajes. |
### ViewerLogger() {#ViewerLogger--}
```
public ViewerLogger()
```


### trace(String message, Object[] arguments) {#trace-java.lang.String-java.lang.Object...-}
```
public static void trace(String message, Object[] arguments)
```


Escribe un mensaje de rastreo en la consola. Los mensajes de registro de rastreo proporcionan información generalmente útil sobre el flujo de la aplicación.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| mensaje | java.lang.String | El mensaje de rastreo. |
| argumentos | java.lang.Object[] | Los argumentos que se reemplazarán en el mensaje. Reemplazarán los marcadores \{\} en el orden de paso. |

### trace(Throwable throwable, String message, Object[] arguments) {#trace-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public static void trace(Throwable throwable, String message, Object[] arguments)
```


Escribe un mensaje de registro de traza en la consola. Los mensajes de registro de traza proporcionan información generalmente útil sobre el flujo de la aplicación.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| throwable | java.lang.Throwable | La excepción asociada con el mensaje de registro de traza. |
| mensaje | java.lang.String | El mensaje de registro de traza. |
| argumentos | java.lang.Object[] | Los argumentos que se reemplazarán en el mensaje. Reemplazarán los marcadores \{\} en el orden en que se pasen. |

### isTraceEnabled() {#isTraceEnabled--}
```
public static boolean isTraceEnabled()
```


Comprueba si el nivel de rastreo está habilitado para el registro.

**Returns:**
boolean -  true  si el nivel de traza está habilitado,  false  de lo contrario.
### debug(String message, Object[] arguments) {#debug-java.lang.String-java.lang.Object...-}
```
public static void debug(String message, Object[] arguments)
```


Escribe un mensaje de registro de depuración en la consola. Los mensajes de registro de depuración proporcionan información sobre diferentes procesos en el flujo de la aplicación.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| mensaje | java.lang.String | El mensaje de registro de depuración. |
| argumentos | java.lang.Object[] | Los argumentos que se reemplazarán en el mensaje. Reemplazarán los marcadores \{\} en el orden en que se pasen. |

### debug(Throwable throwable, String message, Object[] arguments) {#debug-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public static void debug(Throwable throwable, String message, Object[] arguments)
```


Escribe un mensaje de registro de depuración en la consola. Los mensajes de registro de depuración proporcionan información sobre diferentes procesos en el flujo de la aplicación.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| throwable | java.lang.Throwable | La excepción asociada con el mensaje de registro de depuración. |
| mensaje | java.lang.String | El mensaje de registro de depuración. |
| argumentos | java.lang.Object[] | Los argumentos que se reemplazarán en el mensaje. Reemplazarán los marcadores \{\} en el orden en que se pasen. |

### isDebugEnabled() {#isDebugEnabled--}
```
public static boolean isDebugEnabled()
```


Comprueba si el nivel de depuración está habilitado para el registro.

**Returns:**
boolean -  true  si el nivel de depuración está habilitado,  false  de lo contrario.
### warning(String message, Object[] arguments) {#warning-java.lang.String-java.lang.Object...-}
```
public static void warning(String message, Object[] arguments)
```


Escribe un mensaje de registro de advertencia en la consola. Los mensajes de registro de advertencia proporcionan información sobre eventos inesperados y recuperables en el flujo de la aplicación.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| mensaje | java.lang.String | El mensaje de registro de advertencia. |
| argumentos | java.lang.Object[] | Los argumentos que se reemplazarán en el mensaje. Reemplazarán los marcadores \{\} en el orden en que se pasen. |

### warning(Throwable throwable, String message, Object[] arguments) {#warning-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public static void warning(Throwable throwable, String message, Object[] arguments)
```


Escribe un mensaje de registro de advertencia en la consola. Los mensajes de registro de advertencia proporcionan información sobre eventos inesperados y recuperables en el flujo de la aplicación.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| throwable | java.lang.Throwable | La excepción asociada con el mensaje de registro de advertencia. |
| mensaje | java.lang.String | El mensaje de registro de advertencia. |
| argumentos | java.lang.Object[] | Los argumentos que se reemplazarán en el mensaje. Reemplazarán los marcadores \{\} en el orden en que se pasen. |

### isWarningEnabled() {#isWarningEnabled--}
```
public static boolean isWarningEnabled()
```


Comprueba si el nivel de advertencia está habilitado para el registro.

**Returns:**
boolean -  true  si el nivel de advertencia está habilitado,  false  de lo contrario.
### error(String message, Object[] arguments) {#error-java.lang.String-java.lang.Object...-}
```
public static void error(String message, Object[] arguments)
```


Escribe un mensaje de registro de error en la consola. Los mensajes de registro de error proporcionan información sobre eventos irrecuperables en el flujo de la aplicación.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| mensaje | java.lang.String | El mensaje de registro de error. |
| argumentos | java.lang.Object[] | Los argumentos que se reemplazarán en el mensaje. Reemplazarán los marcadores \{\} en el orden en que se pasen. |

### error(Throwable throwable, String message, Object[] arguments) {#error-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public static void error(Throwable throwable, String message, Object[] arguments)
```


Escribe un mensaje de registro de error en la consola. Los mensajes de registro de error proporcionan información sobre eventos irrecuperables en el flujo de la aplicación.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| throwable | java.lang.Throwable | La excepción asociada con el mensaje de registro de error. |
| mensaje | java.lang.String | El mensaje de registro de error. |
| argumentos | java.lang.Object[] | Los argumentos que se reemplazarán en el mensaje. Reemplazarán los marcadores \{\} en el orden en que se pasen. |

### isErrorEnabled() {#isErrorEnabled--}
```
public static boolean isErrorEnabled()
```


Comprueba si el registro a nivel de error está habilitado.

**Returns:**
boolean -  true  si el registro a nivel de error está habilitado,  false  de lo contrario.
### getLogger() {#getLogger--}
```
public static synchronized ILogger getLogger()
```


Obtiene la instancia del registrador que se utilizará para registrar mensajes. La instancia del registrador puede usarse para registrar mensajes de diferentes niveles como traza, depuración, advertencia y error.

**Returns:**
com.groupdocs.foundation.logging.ILogger - la instancia del registrador.
### setLogger(ILogger logger) {#setLogger-com.groupdocs.foundation.logging.ILogger-}
```
public static synchronized void setLogger(ILogger logger)
```


Establece la instancia del registrador que se utilizará para registrar mensajes. La instancia del registrador puede usarse para registrar mensajes de diferentes niveles como traza, depuración, advertencia y error.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| registrador | com.groupdocs.foundation.logging.ILogger | La instancia del registrador a establecer. |

