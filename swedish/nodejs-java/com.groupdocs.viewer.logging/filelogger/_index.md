---
title: "FileLogger"
second_title: "GroupDocs.Viewer för Node.js via Java API-referens"
description: "Skriver loggmeddelanden till en fil."
type: docs
weight: 10
url: /sv/nodejs-java/com.groupdocs.viewer.logging/filelogger/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.groupdocs.foundation.logging.ILogger
```
public class FileLogger implements ILogger
```

Skriver loggmeddelanden till en fil.

Klassen  FileLogger  tillhandahåller funktionalitet för att skriva loggmeddelanden till en fil. Den implementerar ILogger‑gränssnittet och kan användas för att logga olika händelser och meddelanden i en applikation. Loggmeddelanden skrivs till den angivna filen.

Exempel på användning:

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
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [FileLogger(String fileName)](#FileLogger-java.lang.String-) | Skapar en logger som loggar meddelanden till en fil som anges av det angivna filnamnet. |
| [FileLogger(String fileName, boolean isTraceEnabled, boolean isDebugEnabled, boolean isWarningEnabled, boolean isErrorEnabled)](#FileLogger-java.lang.String-boolean-boolean-boolean-boolean-) | Skapar en logger som loggar meddelanden till en fil med angivna loggningsnivåer. |
## Fält

| Fält | Beskrivning |
| --- | --- |
| [MESSAGE](#MESSAGE) |  |
| [EXCEPTION](#EXCEPTION) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [trace(String message, Object[] arguments)](#trace-java.lang.String-java.lang.Object...-) | Skriver ett spårningsmeddelande till konsolen. |
| [trace(Throwable throwable, String message, Object[] arguments)](#trace-java.lang.Throwable-java.lang.String-java.lang.Object...-) | Skriver ett spårningsloggmeddelande till konsolen. |
| [isTraceEnabled()](#isTraceEnabled--) | Kontrollerar om spårningsnivån är aktiverad för loggning. |
| [debug(String message, Object[] arguments)](#debug-java.lang.String-java.lang.Object...-) | Skriver ett felsökningsloggmeddelande till konsolen. |
| [debug(Throwable throwable, String message, Object[] arguments)](#debug-java.lang.Throwable-java.lang.String-java.lang.Object...-) | Skriver ett felsökningsloggmeddelande till konsolen. |
| [isDebugEnabled()](#isDebugEnabled--) | Kontrollerar om felsökningsnivån är aktiverad för loggning. |
| [warning(String message, Object[] arguments)](#warning-java.lang.String-java.lang.Object...-) | Skriver ett varningsloggmeddelande till konsolen. |
| [warning(Throwable throwable, String message, Object[] arguments)](#warning-java.lang.Throwable-java.lang.String-java.lang.Object...-) | Skriver ett varningsloggmeddelande till konsolen. |
| [isWarningEnabled()](#isWarningEnabled--) | Kontrollerar om varningsnivån är aktiverad för loggning. |
| [error(String message, Object[] arguments)](#error-java.lang.String-java.lang.Object...-) | Skriver ett felmeddelande till konsolen. |
| [error(Throwable throwable, String message, Object[] arguments)](#error-java.lang.Throwable-java.lang.String-java.lang.Object...-) | Skriver ett felmeddelande till konsolen. |
| [isErrorEnabled()](#isErrorEnabled--) | Kontrollerar om felnivåloggning är aktiverad. |
### FileLogger(String fileName) {#FileLogger-java.lang.String-}
```
public FileLogger(String fileName)
```


Skapar en logger som loggar meddelanden till en fil som anges av det angivna filnamnet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fileName | java.lang.String | Det fullständiga filnamnet med sökväg. |

### FileLogger(String fileName, boolean isTraceEnabled, boolean isDebugEnabled, boolean isWarningEnabled, boolean isErrorEnabled) {#FileLogger-java.lang.String-boolean-boolean-boolean-boolean-}
```
public FileLogger(String fileName, boolean isTraceEnabled, boolean isDebugEnabled, boolean isWarningEnabled, boolean isErrorEnabled)
```


Skapar en logger som loggar meddelanden till en fil med angivna loggningsnivåer.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fileName | java.lang.String | Det fullständiga filnamnet med sökväg. |
| isTraceEnabled | boolean | Anger om loggning på spårningsnivå är aktiverad. |
| isDebugEnabled | boolean | Anger om loggning på felsökningsnivå är aktiverad. |
| isWarningEnabled | boolean | Anger om loggning på varningsnivå är aktiverad. |
| isErrorEnabled | boolean | Anger om loggning på felnivå är aktiverad. |

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


Skriver ett spårningsmeddelande till konsolen. Spårningsloggmeddelanden ger allmänt användbar information om applikationsflödet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| meddelande | java.lang.String | Spårningsmeddelandet. |
| argument | java.lang.Object[] | Argumenten som ska ersättas i meddelandet. De kommer att ersätta \{\} platshållare i den ordning de skickas. |

### trace(Throwable throwable, String message, Object[] arguments) {#trace-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public void trace(Throwable throwable, String message, Object[] arguments)
```


Skriver ett spårningsloggmeddelande till konsolen. Spårningsloggmeddelanden ger generellt användbar information om applikationsflödet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| kastbar | java.lang.Throwable | Undantaget som är associerat med spårningsloggmeddelandet. |
| meddelande | java.lang.String | Spårningsloggmeddelandet. |
| argument | java.lang.Object[] | Argumenten som ska ersättas i meddelandet. De kommer att ersätta \{\}-platshållare i den ordning de skickas. |

### isTraceEnabled() {#isTraceEnabled--}
```
public boolean isTraceEnabled()
```


Kontrollerar om spårningsnivån är aktiverad för loggning.

**Returns:**
boolean -  true  om spårningsnivån är aktiverad,  false  annars.
### debug(String message, Object[] arguments) {#debug-java.lang.String-java.lang.Object...-}
```
public void debug(String message, Object[] arguments)
```


Skriver ett debug-loggmeddelande till konsolen. Debug-loggmeddelanden ger information om olika processer i applikationsflödet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| meddelande | java.lang.String | Debug-loggmeddelandet. |
| argument | java.lang.Object[] | Argumenten som ska ersättas i meddelandet. De kommer att ersätta \{\}-platshållare i den ordning de skickas. |

### debug(Throwable throwable, String message, Object[] arguments) {#debug-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public void debug(Throwable throwable, String message, Object[] arguments)
```


Skriver ett debug-loggmeddelande till konsolen. Debug-loggmeddelanden ger information om olika processer i applikationsflödet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| kastbar | java.lang.Throwable | Undantaget som är associerat med debug-loggmeddelandet. |
| meddelande | java.lang.String | Debug-loggmeddelandet. |
| argument | java.lang.Object[] | Argumenten som ska ersättas i meddelandet. De kommer att ersätta \{\}-platshållare i den ordning de skickas. |

### isDebugEnabled() {#isDebugEnabled--}
```
public boolean isDebugEnabled()
```


Kontrollerar om felsökningsnivån är aktiverad för loggning.

**Returns:**
boolean -  true  om debug-nivån är aktiverad,  false  annars.
### warning(String message, Object[] arguments) {#warning-java.lang.String-java.lang.Object...-}
```
public void warning(String message, Object[] arguments)
```


Skriver ett varningsloggmeddelande till konsolen. Varningsloggmeddelanden ger information om oväntade och återhämtningsbara händelser i applikationsflödet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| meddelande | java.lang.String | Varningsloggmeddelandet. |
| argument | java.lang.Object[] | Argumenten som ska ersättas i meddelandet. De kommer att ersätta \{\}-platshållare i den ordning de skickas. |

### warning(Throwable throwable, String message, Object[] arguments) {#warning-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public void warning(Throwable throwable, String message, Object[] arguments)
```


Skriver ett varningsloggmeddelande till konsolen. Varningsloggmeddelanden ger information om oväntade och återhämtningsbara händelser i applikationsflödet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| kastbar | java.lang.Throwable | Undantaget som är associerat med varningsloggmeddelandet. |
| meddelande | java.lang.String | Varningsloggmeddelandet. |
| argument | java.lang.Object[] | Argumenten som ska ersättas i meddelandet. De kommer att ersätta \{\}-platshållare i den ordning de skickas. |

### isWarningEnabled() {#isWarningEnabled--}
```
public boolean isWarningEnabled()
```


Kontrollerar om varningsnivån är aktiverad för loggning.

**Returns:**
boolean -  true  om varningsnivån är aktiverad,  false  annars.
### error(String message, Object[] arguments) {#error-java.lang.String-java.lang.Object...-}
```
public void error(String message, Object[] arguments)
```


Skriver ett fel-loggmeddelande till konsolen. Fel-loggmeddelanden ger information om oåterhämtningsbara händelser i applikationsflödet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| meddelande | java.lang.String | Fel-loggmeddelandet. |
| argument | java.lang.Object[] | Argumenten som ska ersättas i meddelandet. De kommer att ersätta \{\}-platshållare i den ordning de skickas. |

### error(Throwable throwable, String message, Object[] arguments) {#error-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public void error(Throwable throwable, String message, Object[] arguments)
```


Skriver ett fel-loggmeddelande till konsolen. Fel-loggmeddelanden ger information om oåterhämtningsbara händelser i applikationsflödet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| kastbar | java.lang.Throwable | Undantaget som är associerat med fel-loggmeddelandet. |
| meddelande | java.lang.String | Fel-loggmeddelandet. |
| argument | java.lang.Object[] | Argumenten som ska ersättas i meddelandet. De kommer att ersätta \{\}-platshållare i den ordning de skickas. |

### isErrorEnabled() {#isErrorEnabled--}
```
public boolean isErrorEnabled()
```


Kontrollerar om felnivåloggning är aktiverad.

**Returns:**
boolean -  true  om felnivåloggning är aktiverad,  false  annars.
