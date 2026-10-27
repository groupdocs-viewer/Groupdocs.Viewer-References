---
title: "FileLogger"
second_title: "Referencia de API de GroupDocs.Viewer para Node.js vía Java"
description: "Escribe mensajes de registro en un archivo."
type: docs
weight: 10
url: /es/nodejs-java/com.groupdocs.viewer.logging/filelogger/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.groupdocs.foundation.logging.ILogger
```
public class FileLogger implements ILogger
```

Escribe mensajes de registro en un archivo.

La clase  FileLogger  proporciona funcionalidad para escribir mensajes de registro en un archivo. Implementa la interfaz ILogger y puede usarse para registrar varios eventos y mensajes en una aplicación. Los mensajes de registro se escriben en el archivo especificado.

Ejemplo de uso:

```

 // Create a new instance of FileLogger with the specified log file path
 FileLogger fileLogger = new FileLogger("/path/to/logfile.txt");

 // Log an informational message
 fileLogger.debug("Debug message");

 // Log an error message
 fileLogger.error("Error message");

 // Check is logging warning messages enabled
 boolean warningEnabled = fileLogger.isWarningEnabled();
 
```

***Note:** The  FileLogger  class provides basic logging functionality. You can extend this class to add custom log levels or additional logging features as per your requirements.*
## Constructores

| Constructor | Descripción |
| --- | --- |
| [FileLogger(String fileName)](#FileLogger-java.lang.String-) | Crea un registrador que escribe mensajes en un archivo especificado por el nombre de archivo proporcionado. |
| [FileLogger(String fileName, boolean isTraceEnabled, boolean isDebugEnabled, boolean isWarningEnabled, boolean isErrorEnabled)](#FileLogger-java.lang.String-boolean-boolean-boolean-boolean-) | Crea un registrador que escribe mensajes en un archivo con niveles de registro especificados. |
## Fields

| Field | Descripción |
| --- | --- |
| [MESSAGE](#MESSAGE) |  |
| [EXCEPTION](#EXCEPTION) |  |
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
### FileLogger(String fileName) {#FileLogger-java.lang.String-}
```
public FileLogger(String fileName)
```


Crea un registrador que escribe mensajes en un archivo especificado por el nombre de archivo proporcionado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fileName | java.lang.String | El nombre completo del archivo con ruta. |

### FileLogger(String fileName, boolean isTraceEnabled, boolean isDebugEnabled, boolean isWarningEnabled, boolean isErrorEnabled) {#FileLogger-java.lang.String-boolean-boolean-boolean-boolean-}
```
public FileLogger(String fileName, boolean isTraceEnabled, boolean isDebugEnabled, boolean isWarningEnabled, boolean isErrorEnabled)
```


Crea un registrador que escribe mensajes en un archivo con niveles de registro especificados.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fileName | java.lang.String | El nombre completo del archivo con ruta. |
| isTraceEnabled | boolean | Especifica si el registro a nivel de traza está habilitado. |
| isDebugEnabled | boolean | Especifica si el registro a nivel de depuración está habilitado. |
| isWarningEnabled | boolean | Especifica si el registro a nivel de advertencia está habilitado. |
| isErrorEnabled | boolean | Especifica si el registro a nivel de error está habilitado. |

### MESSAGE {#MESSAGE}
```
public static final String MESSAGE
```


### EXCEPTION {#EXCEPTION}
```
public static final String EXCEPTION
```


### trace(String message, Object[] arguments) {#trace-java.lang.String-java.lang.Object...-}
```
public void trace(String message, Object[] arguments)
```


Escribe un mensaje de rastreo en la consola. Los mensajes de registro de rastreo proporcionan información generalmente útil sobre el flujo de la aplicación.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| mensaje | java.lang.String | El mensaje de rastreo. |
| argumentos | java.lang.Object[] | Los argumentos que se reemplazarán en el mensaje. Reemplazarán los marcadores \{\} en el orden de paso. |

### trace(Throwable throwable, String message, Object[] arguments) {#trace-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public void trace(Throwable throwable, String message, Object[] arguments)
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
public boolean isTraceEnabled()
```


Comprueba si el nivel de rastreo está habilitado para el registro.

**Returns:**
boolean -  true  si el nivel de traza está habilitado,  false  de lo contrario.
### debug(String message, Object[] arguments) {#debug-java.lang.String-java.lang.Object...-}
```
public void debug(String message, Object[] arguments)
```


Escribe un mensaje de registro de depuración en la consola. Los mensajes de registro de depuración proporcionan información sobre diferentes procesos en el flujo de la aplicación.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| mensaje | java.lang.String | El mensaje de registro de depuración. |
| argumentos | java.lang.Object[] | Los argumentos que se reemplazarán en el mensaje. Reemplazarán los marcadores \{\} en el orden en que se pasen. |

### debug(Throwable throwable, String message, Object[] arguments) {#debug-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public void debug(Throwable throwable, String message, Object[] arguments)
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
public boolean isDebugEnabled()
```


Comprueba si el nivel de depuración está habilitado para el registro.

**Returns:**
boolean -  true  si el nivel de depuración está habilitado,  false  de lo contrario.
### warning(String message, Object[] arguments) {#warning-java.lang.String-java.lang.Object...-}
```
public void warning(String message, Object[] arguments)
```


Escribe un mensaje de registro de advertencia en la consola. Los mensajes de registro de advertencia proporcionan información sobre eventos inesperados y recuperables en el flujo de la aplicación.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| mensaje | java.lang.String | El mensaje de registro de advertencia. |
| argumentos | java.lang.Object[] | Los argumentos que se reemplazarán en el mensaje. Reemplazarán los marcadores \{\} en el orden en que se pasen. |

### warning(Throwable throwable, String message, Object[] arguments) {#warning-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public void warning(Throwable throwable, String message, Object[] arguments)
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
public boolean isWarningEnabled()
```


Comprueba si el nivel de advertencia está habilitado para el registro.

**Returns:**
boolean -  true  si el nivel de advertencia está habilitado,  false  de lo contrario.
### error(String message, Object[] arguments) {#error-java.lang.String-java.lang.Object...-}
```
public void error(String message, Object[] arguments)
```


Escribe un mensaje de registro de error en la consola. Los mensajes de registro de error proporcionan información sobre eventos irrecuperables en el flujo de la aplicación.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| mensaje | java.lang.String | El mensaje de registro de error. |
| argumentos | java.lang.Object[] | Los argumentos que se reemplazarán en el mensaje. Reemplazarán los marcadores \{\} en el orden en que se pasen. |

### error(Throwable throwable, String message, Object[] arguments) {#error-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public void error(Throwable throwable, String message, Object[] arguments)
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
public boolean isErrorEnabled()
```


Comprueba si el registro a nivel de error está habilitado.

**Returns:**
boolean -  true  si el registro a nivel de error está habilitado,  false  de lo contrario.
