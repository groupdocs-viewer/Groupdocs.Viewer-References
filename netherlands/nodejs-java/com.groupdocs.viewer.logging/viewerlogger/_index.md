---
title: "ViewerLogger"
second_title: "GroupDocs.Viewer voor Node.js via Java API-referentie"
description: "Globale viewerlogger."
type: docs
weight: 11
url: /nl/nodejs-java/com.groupdocs.viewer.logging/viewerlogger/
---
**Inheritance:**
java.lang.Object
```
public class ViewerLogger
```

Globale viewerlogger.

De  ViewerLogger  klasse biedt functionaliteit om berichten te loggen naar een geïntegreerde of door de gebruiker gedefinieerde logger. Het dient als de globale logger voor de viewer-module en kan worden gebruikt om verschillende gebeurtenissen en berichten te loggen.

Voorbeeldgebruik:

```

 // Configure the viewer logger to use the default integrated logger
 ViewerLogger.setLogger(new FileLogger("/path/to/file.log"));

 // Log an debug message
 ViewerLogger.debug("Debug message");

 // Log an error message
 ViewerLogger.error("Error message");
 
```

***Note:** The  ViewerLogger  class can be configured to use a custom logger implementation by calling the [setLogger(ILogger)](../../com.groupdocs.viewer.logging/viewerlogger\#setLogger-ILogger-) method. By default, it uses the integrated logger provided by the viewer module.*
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [ViewerLogger()](#ViewerLogger--) |  |
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
| [getLogger()](#getLogger--) | Haalt de loggerinstantie op die zal worden gebruikt voor het loggen van berichten. |
| [setLogger(ILogger logger)](#setLogger-com.groupdocs.foundation.logging.ILogger-) | Stelt de loggerinstantie in die zal worden gebruikt voor het loggen van berichten. |
### ViewerLogger() {#ViewerLogger--}
```
public ViewerLogger()
```


### trace(String message, Object[] arguments) {#trace-java.lang.String-java.lang.Object...-}
```
public static void trace(String message, Object[] arguments)
```


Schrijft een tracebericht naar de console. Trace-logberichten bieden over het algemeen nuttige informatie over de applicatiestroom.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| bericht | java.lang.String | Het tracebericht. |
| argumenten | java.lang.Object[] | De argumenten die in het bericht moeten worden vervangen. Ze zullen de \{\} plaatshouders vervangen in de volgorde van doorgeven. |

### trace(Throwable throwable, String message, Object[] arguments) {#trace-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public static void trace(Throwable throwable, String message, Object[] arguments)
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
public static boolean isTraceEnabled()
```


Controleert of het trace-niveau is ingeschakeld voor logging.

**Returns:**
boolean -  true  als het trace‑niveau is ingeschakeld,  false  anders.
### debug(String message, Object[] arguments) {#debug-java.lang.String-java.lang.Object...-}
```
public static void debug(String message, Object[] arguments)
```


Schrijft een debug‑logbericht naar de console. Debug‑logberichten geven informatie over verschillende processen in de applicatiestroom.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| bericht | java.lang.String | Het debug‑logbericht. |
| argumenten | java.lang.Object[] | De argumenten die in het bericht moeten worden vervangen. Ze zullen de \{\} placeholders in de volgorde waarin ze worden doorgegeven vervangen. |

### debug(Throwable throwable, String message, Object[] arguments) {#debug-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public static void debug(Throwable throwable, String message, Object[] arguments)
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
public static boolean isDebugEnabled()
```


Controleert of het debug-niveau is ingeschakeld voor logging.

**Returns:**
boolean -  true  als het debug‑niveau is ingeschakeld,  false  anders.
### warning(String message, Object[] arguments) {#warning-java.lang.String-java.lang.Object...-}
```
public static void warning(String message, Object[] arguments)
```


Schrijft een waarschuwing‑logbericht naar de console. Waarschuwing‑logberichten geven informatie over onverwachte en herstelbare gebeurtenissen in de applicatiestroom.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| bericht | java.lang.String | Het waarschuwing‑logbericht. |
| argumenten | java.lang.Object[] | De argumenten die in het bericht moeten worden vervangen. Ze zullen de \{\} placeholders in de volgorde waarin ze worden doorgegeven vervangen. |

### warning(Throwable throwable, String message, Object[] arguments) {#warning-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public static void warning(Throwable throwable, String message, Object[] arguments)
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
public static boolean isWarningEnabled()
```


Controleert of het waarschuwingsniveau is ingeschakeld voor logging.

**Returns:**
boolean -  true  als het waarschuwing‑niveau is ingeschakeld,  false  anders.
### error(String message, Object[] arguments) {#error-java.lang.String-java.lang.Object...-}
```
public static void error(String message, Object[] arguments)
```


Schrijft een fout‑logbericht naar de console. Fout‑logberichten geven informatie over niet‑herstelbare gebeurtenissen in de applicatiestroom.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| bericht | java.lang.String | Het fout‑logbericht. |
| argumenten | java.lang.Object[] | De argumenten die in het bericht moeten worden vervangen. Ze zullen de \{\} placeholders in de volgorde waarin ze worden doorgegeven vervangen. |

### error(Throwable throwable, String message, Object[] arguments) {#error-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public static void error(Throwable throwable, String message, Object[] arguments)
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
public static boolean isErrorEnabled()
```


Controleert of foutniveau-logging is ingeschakeld.

**Returns:**
boolean -  true  als fout‑niveau logging is ingeschakeld,  false  anders.
### getLogger() {#getLogger--}
```
public static synchronized ILogger getLogger()
```


Haalt de logger‑instantie op die zal worden gebruikt voor het loggen van berichten. De logger‑instantie kan worden gebruikt om berichten van verschillende niveaus te loggen, zoals trace, debug, waarschuwing en fout.

**Returns:**
com.groupdocs.foundation.logging.ILogger - de logger‑instantie.
### setLogger(ILogger logger) {#setLogger-com.groupdocs.foundation.logging.ILogger-}
```
public static synchronized void setLogger(ILogger logger)
```


Stelt de logger‑instantie in die zal worden gebruikt voor het loggen van berichten. De logger‑instantie kan worden gebruikt om berichten van verschillende niveaus te loggen, zoals trace, debug, waarschuwing en fout.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| logger | com.groupdocs.foundation.logging.ILogger | De logger‑instantie om in te stellen. |

