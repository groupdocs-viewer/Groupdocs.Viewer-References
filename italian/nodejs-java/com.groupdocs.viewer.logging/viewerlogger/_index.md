---
title: "ViewerLogger"
second_title: "GroupDocs.Viewer per Node.js via Java Riferimento API"
description: "Logger globale del visualizzatore."
type: docs
weight: 11
url: /it/nodejs-java/com.groupdocs.viewer.logging/viewerlogger/
---
**Inheritance:**
java.lang.Object
```
public class ViewerLogger
```

Logger globale del visualizzatore.

La classe ViewerLogger fornisce funzionalità per registrare messaggi su un logger integrato o definito dall'utente. Funziona come logger globale per il modulo viewer e può essere usata per registrare vari eventi e messaggi.

Esempio di utilizzo:

```

 // Configure the viewer logger to use the default integrated logger
 ViewerLogger.setLogger(new FileLogger("/path/to/file.log"));

 // Log an debug message
 ViewerLogger.debug("Debug message");

 // Log an error message
 ViewerLogger.error("Error message");
 
```

***Note:** The  ViewerLogger  class can be configured to use a custom logger implementation by calling the [setLogger(ILogger)](../../com.groupdocs.viewer.logging/viewerlogger\#setLogger-ILogger-) method. By default, it uses the integrated logger provided by the viewer module.*
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [ViewerLogger()](#ViewerLogger--) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [trace(String message, Object[] arguments)](#trace-java.lang.String-java.lang.Object...-) | Scrive un messaggio di traccia sulla console. |
| [trace(Throwable throwable, String message, Object[] arguments)](#trace-java.lang.Throwable-java.lang.String-java.lang.Object...-) | Scrive un messaggio di log di traccia sulla console. |
| [isTraceEnabled()](#isTraceEnabled--) | Verifica se il livello di traccia è abilitato per la registrazione. |
| [debug(String message, Object[] arguments)](#debug-java.lang.String-java.lang.Object...-) | Scrive un messaggio di log di debug sulla console. |
| [debug(Throwable throwable, String message, Object[] arguments)](#debug-java.lang.Throwable-java.lang.String-java.lang.Object...-) | Scrive un messaggio di log di debug sulla console. |
| [isDebugEnabled()](#isDebugEnabled--) | Verifica se il livello di debug è abilitato per la registrazione. |
| [warning(String message, Object[] arguments)](#warning-java.lang.String-java.lang.Object...-) | Scrive un messaggio di log di avviso sulla console. |
| [warning(Throwable throwable, String message, Object[] arguments)](#warning-java.lang.Throwable-java.lang.String-java.lang.Object...-) | Scrive un messaggio di log di avviso sulla console. |
| [isWarningEnabled()](#isWarningEnabled--) | Verifica se il livello di avviso è abilitato per la registrazione. |
| [error(String message, Object[] arguments)](#error-java.lang.String-java.lang.Object...-) | Scrive un messaggio di log di errore sulla console. |
| [error(Throwable throwable, String message, Object[] arguments)](#error-java.lang.Throwable-java.lang.String-java.lang.Object...-) | Scrive un messaggio di log di errore sulla console. |
| [isErrorEnabled()](#isErrorEnabled--) | Verifica se la registrazione a livello di errore è abilitata. |
| [getLogger()](#getLogger--) | Ottiene l'istanza del logger che sarà usata per registrare i messaggi. |
| [setLogger(ILogger logger)](#setLogger-com.groupdocs.foundation.logging.ILogger-) | Imposta l'istanza del logger che sarà usata per registrare i messaggi. |
### ViewerLogger() {#ViewerLogger--}
```
public ViewerLogger()
```


### trace(String message, Object[] arguments) {#trace-java.lang.String-java.lang.Object...-}
```
public static void trace(String message, Object[] arguments)
```


Scrive un messaggio di traccia sulla console. I messaggi di log di traccia forniscono informazioni generalmente utili sul flusso dell'applicazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| messaggio | java.lang.String | Il messaggio di traccia. |
| argomenti | java.lang.Object[] | Gli argomenti da sostituire nel messaggio. Sostituiranno i segnaposto \\{\\} nell'ordine di passaggio. |

### trace(Throwable throwable, String message, Object[] arguments) {#trace-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public static void trace(Throwable throwable, String message, Object[] arguments)
```


Scrive un messaggio di log trace sulla console. I messaggi di log trace forniscono informazioni generalmente utili sul flusso dell'applicazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| Throwable | java.lang.Throwable | L'eccezione associata al messaggio di log trace. |
| messaggio | java.lang.String | Il messaggio di log trace. |
| argomenti | java.lang.Object[] | Gli argomenti da sostituire nel messaggio. Sostituiranno i segnaposto \{\} nell'ordine in cui vengono passati. |

### isTraceEnabled() {#isTraceEnabled--}
```
public static boolean isTraceEnabled()
```


Verifica se il livello di traccia è abilitato per la registrazione.

**Returns:**
boolean -  true  se il livello trace è abilitato,  false  altrimenti.
### debug(String message, Object[] arguments) {#debug-java.lang.String-java.lang.Object...-}
```
public static void debug(String message, Object[] arguments)
```


Scrive un messaggio di log debug sulla console. I messaggi di log debug forniscono informazioni sui diversi processi nel flusso dell'applicazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| messaggio | java.lang.String | Il messaggio di log debug. |
| argomenti | java.lang.Object[] | Gli argomenti da sostituire nel messaggio. Sostituiranno i segnaposto \{\} nell'ordine in cui vengono passati. |

### debug(Throwable throwable, String message, Object[] arguments) {#debug-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public static void debug(Throwable throwable, String message, Object[] arguments)
```


Scrive un messaggio di log debug sulla console. I messaggi di log debug forniscono informazioni sui diversi processi nel flusso dell'applicazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| Throwable | java.lang.Throwable | L'eccezione associata al messaggio di log debug. |
| messaggio | java.lang.String | Il messaggio di log debug. |
| argomenti | java.lang.Object[] | Gli argomenti da sostituire nel messaggio. Sostituiranno i segnaposto \{\} nell'ordine in cui vengono passati. |

### isDebugEnabled() {#isDebugEnabled--}
```
public static boolean isDebugEnabled()
```


Verifica se il livello di debug è abilitato per la registrazione.

**Returns:**
boolean -  true  se il livello debug è abilitato,  false  altrimenti.
### warning(String message, Object[] arguments) {#warning-java.lang.String-java.lang.Object...-}
```
public static void warning(String message, Object[] arguments)
```


Scrive un messaggio di log warning sulla console. I messaggi di log warning forniscono informazioni su eventi inaspettati e recuperabili nel flusso dell'applicazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| messaggio | java.lang.String | Il messaggio di log warning. |
| argomenti | java.lang.Object[] | Gli argomenti da sostituire nel messaggio. Sostituiranno i segnaposto \{\} nell'ordine in cui vengono passati. |

### warning(Throwable throwable, String message, Object[] arguments) {#warning-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public static void warning(Throwable throwable, String message, Object[] arguments)
```


Scrive un messaggio di log warning sulla console. I messaggi di log warning forniscono informazioni su eventi inaspettati e recuperabili nel flusso dell'applicazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| Throwable | java.lang.Throwable | L'eccezione associata al messaggio di log warning. |
| messaggio | java.lang.String | Il messaggio di log warning. |
| argomenti | java.lang.Object[] | Gli argomenti da sostituire nel messaggio. Sostituiranno i segnaposto \{\} nell'ordine in cui vengono passati. |

### isWarningEnabled() {#isWarningEnabled--}
```
public static boolean isWarningEnabled()
```


Verifica se il livello di avviso è abilitato per la registrazione.

**Returns:**
boolean -  true  se il livello warning è abilitato,  false  altrimenti.
### error(String message, Object[] arguments) {#error-java.lang.String-java.lang.Object...-}
```
public static void error(String message, Object[] arguments)
```


Scrive un messaggio di log error sulla console. I messaggi di log error forniscono informazioni su eventi irrecuperabili nel flusso dell'applicazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| messaggio | java.lang.String | Il messaggio di log error. |
| argomenti | java.lang.Object[] | Gli argomenti da sostituire nel messaggio. Sostituiranno i segnaposto \{\} nell'ordine in cui vengono passati. |

### error(Throwable throwable, String message, Object[] arguments) {#error-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public static void error(Throwable throwable, String message, Object[] arguments)
```


Scrive un messaggio di log error sulla console. I messaggi di log error forniscono informazioni su eventi irrecuperabili nel flusso dell'applicazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| Throwable | java.lang.Throwable | L'eccezione associata al messaggio di log error. |
| messaggio | java.lang.String | Il messaggio di log error. |
| argomenti | java.lang.Object[] | Gli argomenti da sostituire nel messaggio. Sostituiranno i segnaposto \{\} nell'ordine in cui vengono passati. |

### isErrorEnabled() {#isErrorEnabled--}
```
public static boolean isErrorEnabled()
```


Verifica se la registrazione a livello di errore è abilitata.

**Returns:**
boolean -  true  se la registrazione a livello error è abilitata,  false  altrimenti.
### getLogger() {#getLogger--}
```
public static synchronized ILogger getLogger()
```


Ottiene l'istanza del logger che verrà utilizzata per registrare i messaggi. L'istanza del logger può essere usata per registrare messaggi di diversi livelli come trace, debug, warning ed error.

**Returns:**
com.groupdocs.foundation.logging.ILogger - l'istanza del logger.
### setLogger(ILogger logger) {#setLogger-com.groupdocs.foundation.logging.ILogger-}
```
public static synchronized void setLogger(ILogger logger)
```


Imposta l'istanza del logger che verrà utilizzata per registrare i messaggi. L'istanza del logger può essere usata per registrare messaggi di diversi livelli come trace, debug, warning ed error.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| logger | com.groupdocs.foundation.logging.ILogger | L'istanza del logger da impostare. |

