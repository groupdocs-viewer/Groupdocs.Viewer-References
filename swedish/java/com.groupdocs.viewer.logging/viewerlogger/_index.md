---
title: "ViewerLogger"
second_title: "GroupDocs.Viewer för Java API-referens"
description: "Global visnings‑logger."
type: docs
weight: 11
url: /sv/java/com.groupdocs.viewer.logging/viewerlogger/
---
**Inheritance:**
java.lang.Object
```
public class ViewerLogger
```

Global visnings‑logger.


Den
ViewerLogger
klassen tillhandahåller funktionalitet för att logga meddelanden till en integrerad eller användardefinierad logger.
Den fungerar som den globala loggern för viewer-modulen och kan användas för att logga olika händelser och meddelanden.


Exempel på användning:

````

 // Configure the viewer logger to use the default integrated logger
 ViewerLogger.setLogger(new FileLogger("/path/to/file.log"));

 // Log an debug message
 ViewerLogger.debug("Debug message");

 // Log an error message
 ViewerLogger.error("Error message");
 
````


***Note:** The 
ViewerLogger
klassen kan konfigureras för att använda en anpassad logger-implementation genom att anropa metoden [setLogger(ILogger)](../../com.groupdocs.viewer.logging/viewerlogger#setLogger-ILogger-).
Som standard använder den den integrerade loggern som tillhandahålls av viewer-modulen.*

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [ViewerLogger()](#ViewerLogger--) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [trace(String message, Object[] arguments)](#trace-java.lang.String-java.lang.Object...-) | Skriver ett spårningsmeddelande till konsolen. |
|
|  | [trace(Throwable throwable, String message, Object[] arguments)](#trace-java.lang.Throwable-java.lang.String-java.lang.Object...-) | Skriver ett spårningsloggmeddelande till konsolen. |
|
|  | [isTraceEnabled()](#isTraceEnabled--) | Kontrollerar om spårningsnivån är aktiverad för loggning. |
|
|  | [debug(String message, Object[] arguments)](#debug-java.lang.String-java.lang.Object...-) | Skriver ett felsökningsloggmeddelande till konsolen. |
|
|  | [debug(Throwable throwable, String message, Object[] arguments)](#debug-java.lang.Throwable-java.lang.String-java.lang.Object...-) | Skriver ett felsökningsloggmeddelande till konsolen. |
|
|  | [isDebugEnabled()](#isDebugEnabled--) | Kontrollerar om felsökningsnivån är aktiverad för loggning. |
|
|  | [warning(String message, Object[] arguments)](#warning-java.lang.String-java.lang.Object...-) | Skriver ett varningsloggmeddelande till konsolen. |
|
|  | [warning(Throwable throwable, String message, Object[] arguments)](#warning-java.lang.Throwable-java.lang.String-java.lang.Object...-) | Skriver ett varningsloggmeddelande till konsolen. |
|
|  | [isWarningEnabled()](#isWarningEnabled--) | Kontrollerar om varningsnivån är aktiverad för loggning. |
|
|  | [error(String message, Object[] arguments)](#error-java.lang.String-java.lang.Object...-) | Skriver ett felmeddelande till konsolen. |
|
|  | [error(Throwable throwable, String message, Object[] arguments)](#error-java.lang.Throwable-java.lang.String-java.lang.Object...-) | Skriver ett felmeddelande till konsolen. |
|
|  | [isErrorEnabled()](#isErrorEnabled--) | Kontrollerar om felnivåloggning är aktiverad. |
|
|  | [getLogger()](#getLogger--) | Hämtar logger-instansen som kommer att användas för att logga meddelanden. |
|
|  | [setLogger(ILogger logger)](#setLogger-com.groupdocs.foundation.logging.ILogger-) | Ställer in logger-instansen som kommer att användas för att logga meddelanden. |
|
### ViewerLogger() {#ViewerLogger--}
```
public ViewerLogger()
```


### trace(String message, Object[] arguments) {#trace-java.lang.String-java.lang.Object...-}
```
public static void trace(String message, Object[] arguments)
```


Skriver ett spårningsmeddelande till konsolen.
Spårningsloggmeddelanden ger generellt användbar information om applikationsflödet.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | meddelande | java.lang.String | Spårningsmeddelandet. |
|
|  | argument | java.lang.Object[] | Argumenten som ska ersättas i meddelandet. De kommer att ersätta {}-platshållare i den ordning de skickas. |
|

### trace(Throwable throwable, String message, Object[] arguments) {#trace-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public static void trace(Throwable throwable, String message, Object[] arguments)
```


Skriver ett spårningsloggmeddelande till konsolen.
Spårningsloggmeddelanden ger generellt användbar information om applikationsflödet.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | kastbar | java.lang.Throwable | Undantaget som är kopplat till spårningsloggmeddelandet. |
|
|  | meddelande | java.lang.String | Spårningsloggmeddelandet. |
|
|  | argument | java.lang.Object[] | Argumenten som ska ersättas i meddelandet. De kommer att ersätta {}-platshållare i den ordning de skickas. |
|

### isTraceEnabled() {#isTraceEnabled--}
```
public static boolean isTraceEnabled()
```


Kontrollerar om spårningsnivån är aktiverad för loggning.


**Returns:**
boolean -  true  om spårningsnivån är aktiverad,  false  annars.

### debug(String message, Object[] arguments) {#debug-java.lang.String-java.lang.Object...-}
```
public static void debug(String message, Object[] arguments)
```


Skriver ett felsökningsloggmeddelande till konsolen.
Felsökningsloggmeddelanden ger information om olika processer i applikationsflödet.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | meddelande | java.lang.String | Felsökningsloggmeddelandet. |
|
|  | argument | java.lang.Object[] | Argumenten som ska ersättas i meddelandet. De kommer att ersätta {}-platshållare i den ordning de skickas. |
|

### debug(Throwable throwable, String message, Object[] arguments) {#debug-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public static void debug(Throwable throwable, String message, Object[] arguments)
```


Skriver ett felsökningsloggmeddelande till konsolen.
Felsökningsloggmeddelanden ger information om olika processer i applikationsflödet.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | kastbar | java.lang.Throwable | Undantaget som är kopplat till felsökningsloggmeddelandet. |
|
|  | meddelande | java.lang.String | Felsökningsloggmeddelandet. |
|
|  | argument | java.lang.Object[] | Argumenten som ska ersättas i meddelandet. De kommer att ersätta {}-platshållare i den ordning de skickas. |
|

### isDebugEnabled() {#isDebugEnabled--}
```
public static boolean isDebugEnabled()
```


Kontrollerar om felsökningsnivån är aktiverad för loggning.


**Returns:**
boolean -  true  om felsökningsnivån är aktiverad,  false  annars.

### warning(String message, Object[] arguments) {#warning-java.lang.String-java.lang.Object...-}
```
public static void warning(String message, Object[] arguments)
```


Skriver ett varningsloggmeddelande till konsolen.
Varningsloggmeddelanden ger information om oväntade och återhämtningsbara händelser i applikationsflödet.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | meddelande | java.lang.String | Varningsloggmeddelandet. |
|
|  | argument | java.lang.Object[] | Argumenten som ska ersättas i meddelandet. De kommer att ersätta {}-platshållare i den ordning de skickas. |
|

### warning(Throwable throwable, String message, Object[] arguments) {#warning-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public static void warning(Throwable throwable, String message, Object[] arguments)
```


Skriver ett varningsloggmeddelande till konsolen.
Varningsloggmeddelanden ger information om oväntade och återhämtningsbara händelser i applikationsflödet.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | kastbar | java.lang.Throwable | Undantaget som är kopplat till varningsloggmeddelandet. |
|
|  | meddelande | java.lang.String | Varningsloggmeddelandet. |
|
|  | argument | java.lang.Object[] | Argumenten som ska ersättas i meddelandet. De kommer att ersätta {}-platshållare i den ordning de skickas. |
|

### isWarningEnabled() {#isWarningEnabled--}
```
public static boolean isWarningEnabled()
```


Kontrollerar om varningsnivån är aktiverad för loggning.


**Returns:**
boolean -  true  om varningsnivån är aktiverad,  false  annars.

### error(String message, Object[] arguments) {#error-java.lang.String-java.lang.Object...-}
```
public static void error(String message, Object[] arguments)
```


Skriver ett felmeddelande till konsolen.
Fel-loggmeddelanden ger information om oåterhämtningsbara händelser i applikationsflödet.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | meddelande | java.lang.String | Fel-loggmeddelandet. |
|
|  | argument | java.lang.Object[] | Argumenten som ska ersättas i meddelandet. De kommer att ersätta {}-platshållare i den ordning de skickas. |
|

### error(Throwable throwable, String message, Object[] arguments) {#error-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public static void error(Throwable throwable, String message, Object[] arguments)
```


Skriver ett felmeddelande till konsolen.
Fel-loggmeddelanden ger information om oåterhämtningsbara händelser i applikationsflödet.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | kastbar | java.lang.Throwable | Undantaget som är kopplat till fel-loggmeddelandet. |
|
|  | meddelande | java.lang.String | Fel-loggmeddelandet. |
|
|  | argument | java.lang.Object[] | Argumenten som ska ersättas i meddelandet. De kommer att ersätta {}-platshållare i den ordning de skickas. |
|

### isErrorEnabled() {#isErrorEnabled--}
```
public static boolean isErrorEnabled()
```


Kontrollerar om felnivåloggning är aktiverad.


**Returns:**
boolean -  true  om felnivåloggning är aktiverad,  false  annars.

### getLogger() {#getLogger--}
```
public static synchronized ILogger getLogger()
```


Hämtar logger-instansen som kommer att användas för att logga meddelanden.
Logger-instansen kan användas för att logga meddelanden på olika nivåer såsom trace, debug, warning och error.


**Returns:**
com.groupdocs.foundation.logging.ILogger - logger-instansen.

### setLogger(ILogger logger) {#setLogger-com.groupdocs.foundation.logging.ILogger-}
```
public static synchronized void setLogger(ILogger logger)
```


Ställer in logger-instansen som kommer att användas för att logga meddelanden.
Logger-instansen kan användas för att logga meddelanden på olika nivåer såsom trace, debug, warning och error.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | logger | com.groupdocs.foundation.logging.ILogger | Logger-instansen att sätta. |
|

