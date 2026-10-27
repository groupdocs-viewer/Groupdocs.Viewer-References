---
title: "FileLogger"
second_title: "GroupDocs.Viewer voor Node.js via Java API-referentie"
description: "Schrijft logberichten naar een bestand."
type: docs
weight: 10
url: /nl/nodejs-java/com.groupdocs.viewer.logging/filelogger/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.groupdocs.foundation.logging.ILogger
```
public class FileLogger implements ILogger
```

Schrijft logberichten naar een bestand.

De  FileLogger  klasse biedt functionaliteit om logberichten naar een bestand te schrijven. Het implementeert de ILogger interface en kan worden gebruikt om verschillende gebeurtenissen en berichten in een applicatie te loggen. Logberichten worden naar het opgegeven bestand geschreven.

Voorbeeldgebruik:

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
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [FileLogger(String fileName)](#FileLogger-java.lang.String-) | Maakt een logger die berichten logt naar een bestand dat is opgegeven door de meegegeven bestandsnaam. |
| [FileLogger(String fileName, boolean isTraceEnabled, boolean isDebugEnabled, boolean isWarningEnabled, boolean isErrorEnabled)](#FileLogger-java.lang.String-boolean-boolean-boolean-boolean-) | Maakt een logger die berichten logt naar een bestand met opgegeven logniveaus. |
## Velden

| Veld | Beschrijving |
| --- | --- |
| [MESSAGE](#MESSAGE) |  |
| [EXCEPTION](#EXCEPTION) |  |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [trace(String message, Object[] arguments)](#trace-java.lang.String-java.lang.Object...-) | Schrijft een tracebericht naar de console. |
| [trace(Throwable throwable, String message, Object[] arguments)](#trace-java.lang.Throwable-java.lang.String-java.lang.Object...-) | Schrijft een trace-logbericht naar de console. |
| [isTraceEnabled()](#isTraceEnabled--) | Controleert of het trace-niveau is ingeschakeld voor logging. |
| [debug(String message, Object[] arguments)](#debug-java.lang.String-java.lang.Object...-) | Schrijft een debuglogbericht naar de console. |
| [debug(Throwable throwable, String message, Object[] arguments)](#debug-java.lang.Throwable-java.lang.String-java.lang.Object...-) | Schrijft een debuglogbericht naar de console. |
| [isDebugEnabled()](#isDebugEnabled--) | Controleert of het debug-niveau is ingeschakeld voor logging. |
| [warning(String message, Object[] arguments)](#warning-java.lang.String-java.lang.Object...-) | Schrijft een waarschuwingslogbericht naar de console. |
| [warning(Throwable throwable, String message, Object[] arguments)](#warning-java.lang.Throwable-java.lang.String-java.lang.Object...-) | Schrijft een waarschuwingslogbericht naar de console. |
| [isWarningEnabled()](#isWarningEnabled--) | Controleert of het waarschuwingsniveau is ingeschakeld voor logging. |
| [error(String message, Object[] arguments)](#error-java.lang.String-java.lang.Object...-) | Schrijft een foutlogbericht naar de console. |
| [error(Throwable throwable, String message, Object[] arguments)](#error-java.lang.Throwable-java.lang.String-java.lang.Object...-) | Schrijft een foutlogbericht naar de console. |
| [isErrorEnabled()](#isErrorEnabled--) | Controleert of foutniveau-logging is ingeschakeld. |
### FileLogger(String fileName) {#FileLogger-java.lang.String-}
```
public FileLogger(String fileName)
```


Maakt een logger die berichten logt naar een bestand dat is opgegeven door de meegegeven bestandsnaam.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| fileName | java.lang.String | De volledige bestandsnaam met pad. |

### FileLogger(String fileName, boolean isTraceEnabled, boolean isDebugEnabled, boolean isWarningEnabled, boolean isErrorEnabled) {#FileLogger-java.lang.String-boolean-boolean-boolean-boolean-}
```
public FileLogger(String fileName, boolean isTraceEnabled, boolean isDebugEnabled, boolean isWarningEnabled, boolean isErrorEnabled)
```


Maakt een logger die berichten logt naar een bestand met opgegeven logniveaus.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| fileName | java.lang.String | De volledige bestandsnaam met pad. |
| isTraceEnabled | boolean | Specificeert of loggen op trace-niveau is ingeschakeld. |
| isDebugEnabled | boolean | Specificeert of loggen op debug-niveau is ingeschakeld. |
| isWarningEnabled | boolean | Specificeert of loggen op waarschuwingsniveau is ingeschakeld. |
| isErrorEnabled | boolean | Specificeert of loggen op foutniveau is ingeschakeld. |

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


Schrijft een tracebericht naar de console. Trace-logberichten bieden over het algemeen nuttige informatie over de applicatiestroom.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| bericht | java.lang.String | Het tracebericht. |
| argumenten | java.lang.Object[] | De argumenten die in het bericht moeten worden vervangen. Ze zullen de \{\} plaatshouders vervangen in de volgorde van doorgeven. |

### trace(Throwable throwable, String message, Object[] arguments) {#trace-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public void trace(Throwable throwable, String message, Object[] arguments)
```


Schrijft een trace‑logbericht naar de console. Trace‑logberichten bieden over het algemeen nuttige informatie over de applicatiestroom.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| throwable | java.lang.Throwable | De uitzondering die bij het trace‑logbericht hoort. |
| bericht | java.lang.String | Het trace‑logbericht. |
| argumenten | java.lang.Object[] | De argumenten die in het bericht moeten worden vervangen. Ze zullen de \{\} placeholders in de volgorde waarin ze worden doorgegeven vervangen. |

### isTraceEnabled() {#isTraceEnabled--}
```
public boolean isTraceEnabled()
```


Controleert of het trace-niveau is ingeschakeld voor logging.

**Returns:**
boolean -  true  als het trace‑niveau is ingeschakeld,  false  anders.
### debug(String message, Object[] arguments) {#debug-java.lang.String-java.lang.Object...-}
```
public void debug(String message, Object[] arguments)
```


Schrijft een debug‑logbericht naar de console. Debug‑logberichten geven informatie over verschillende processen in de applicatiestroom.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| bericht | java.lang.String | Het debug‑logbericht. |
| argumenten | java.lang.Object[] | De argumenten die in het bericht moeten worden vervangen. Ze zullen de \{\} placeholders in de volgorde waarin ze worden doorgegeven vervangen. |

### debug(Throwable throwable, String message, Object[] arguments) {#debug-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public void debug(Throwable throwable, String message, Object[] arguments)
```


Schrijft een debug‑logbericht naar de console. Debug‑logberichten geven informatie over verschillende processen in de applicatiestroom.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| throwable | java.lang.Throwable | De uitzondering die bij het debug‑logbericht hoort. |
| bericht | java.lang.String | Het debug‑logbericht. |
| argumenten | java.lang.Object[] | De argumenten die in het bericht moeten worden vervangen. Ze zullen de \{\} placeholders in de volgorde waarin ze worden doorgegeven vervangen. |

### isDebugEnabled() {#isDebugEnabled--}
```
public boolean isDebugEnabled()
```


Controleert of het debug-niveau is ingeschakeld voor logging.

**Returns:**
boolean -  true  als het debug‑niveau is ingeschakeld,  false  anders.
### warning(String message, Object[] arguments) {#warning-java.lang.String-java.lang.Object...-}
```
public void warning(String message, Object[] arguments)
```


Schrijft een waarschuwing‑logbericht naar de console. Waarschuwing‑logberichten geven informatie over onverwachte en herstelbare gebeurtenissen in de applicatiestroom.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| bericht | java.lang.String | Het waarschuwing‑logbericht. |
| argumenten | java.lang.Object[] | De argumenten die in het bericht moeten worden vervangen. Ze zullen de \{\} placeholders in de volgorde waarin ze worden doorgegeven vervangen. |

### warning(Throwable throwable, String message, Object[] arguments) {#warning-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public void warning(Throwable throwable, String message, Object[] arguments)
```


Schrijft een waarschuwing‑logbericht naar de console. Waarschuwing‑logberichten geven informatie over onverwachte en herstelbare gebeurtenissen in de applicatiestroom.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| throwable | java.lang.Throwable | De uitzondering die bij het waarschuwing‑logbericht hoort. |
| bericht | java.lang.String | Het waarschuwing‑logbericht. |
| argumenten | java.lang.Object[] | De argumenten die in het bericht moeten worden vervangen. Ze zullen de \{\} placeholders in de volgorde waarin ze worden doorgegeven vervangen. |

### isWarningEnabled() {#isWarningEnabled--}
```
public boolean isWarningEnabled()
```


Controleert of het waarschuwingsniveau is ingeschakeld voor logging.

**Returns:**
boolean -  true  als het waarschuwing‑niveau is ingeschakeld,  false  anders.
### error(String message, Object[] arguments) {#error-java.lang.String-java.lang.Object...-}
```
public void error(String message, Object[] arguments)
```


Schrijft een fout‑logbericht naar de console. Fout‑logberichten geven informatie over niet‑herstelbare gebeurtenissen in de applicatiestroom.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| bericht | java.lang.String | Het fout‑logbericht. |
| argumenten | java.lang.Object[] | De argumenten die in het bericht moeten worden vervangen. Ze zullen de \{\} placeholders in de volgorde waarin ze worden doorgegeven vervangen. |

### error(Throwable throwable, String message, Object[] arguments) {#error-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public void error(Throwable throwable, String message, Object[] arguments)
```


Schrijft een fout‑logbericht naar de console. Fout‑logberichten geven informatie over niet‑herstelbare gebeurtenissen in de applicatiestroom.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| throwable | java.lang.Throwable | De uitzondering die bij het fout‑logbericht hoort. |
| bericht | java.lang.String | Het fout‑logbericht. |
| argumenten | java.lang.Object[] | De argumenten die in het bericht moeten worden vervangen. Ze zullen de \{\} placeholders in de volgorde waarin ze worden doorgegeven vervangen. |

### isErrorEnabled() {#isErrorEnabled--}
```
public boolean isErrorEnabled()
```


Controleert of foutniveau-logging is ingeschakeld.

**Returns:**
boolean -  true  als fout‑niveau logging is ingeschakeld,  false  anders.
