---
title: "ViewerLogger"
second_title: "GroupDocs.Viewer für Java API-Referenz"
description: "Globaler Viewer‑Logger."
type: docs
weight: 11
url: /de/java/com.groupdocs.viewer.logging/viewerlogger/
---
**Inheritance:**
java.lang.Object
```
public class ViewerLogger
```

Globaler Viewer‑Logger.


Die
ViewerLogger
Die Klasse bietet Funktionalität zum Protokollieren von Nachrichten an einen integrierten oder benutzerdefinierten Logger.
Sie dient als globaler Logger für das Viewer‑Modul und kann verwendet werden, um verschiedene Ereignisse und Nachrichten zu protokollieren.


Beispielverwendung:

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
Die Klasse kann konfiguriert werden, eine benutzerdefinierte Logger‑Implementierung zu verwenden, indem die Methode [setLogger(ILogger)](../../com.groupdocs.viewer.logging/viewerlogger#setLogger-ILogger-) aufgerufen wird.
Standardmäßig verwendet sie den integrierten Logger, der vom Viewer‑Modul bereitgestellt wird.*

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [ViewerLogger()](#ViewerLogger--) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [trace(String message, Object[] arguments)](#trace-java.lang.String-java.lang.Object...-) | Schreibt eine Trace‑Nachricht in die Konsole. |
|
|  | [trace(Throwable throwable, String message, Object[] arguments)](#trace-java.lang.Throwable-java.lang.String-java.lang.Object...-) | Schreibt eine Trace‑Protokollnachricht in die Konsole. |
|
|  | [isTraceEnabled()](#isTraceEnabled--) | Prüft, ob die Trace‑Ebene für das Protokollieren aktiviert ist. |
|
|  | [debug(String message, Object[] arguments)](#debug-java.lang.String-java.lang.Object...-) | Schreibt eine Debug‑Protokollnachricht in die Konsole. |
|
|  | [debug(Throwable throwable, String message, Object[] arguments)](#debug-java.lang.Throwable-java.lang.String-java.lang.Object...-) | Schreibt eine Debug‑Protokollnachricht in die Konsole. |
|
|  | [isDebugEnabled()](#isDebugEnabled--) | Prüft, ob die Debug‑Ebene für das Protokollieren aktiviert ist. |
|
|  | [warning(String message, Object[] arguments)](#warning-java.lang.String-java.lang.Object...-) | Schreibt eine Warnungs‑Protokollnachricht in die Konsole. |
|
|  | [warning(Throwable throwable, String message, Object[] arguments)](#warning-java.lang.Throwable-java.lang.String-java.lang.Object...-) | Schreibt eine Warnungs‑Protokollnachricht in die Konsole. |
|
|  | [isWarningEnabled()](#isWarningEnabled--) | Prüft, ob die Warnungs‑Ebene für das Protokollieren aktiviert ist. |
|
|  | [error(String message, Object[] arguments)](#error-java.lang.String-java.lang.Object...-) | Schreibt eine Fehler‑Protokollnachricht in die Konsole. |
|
|  | [error(Throwable throwable, String message, Object[] arguments)](#error-java.lang.Throwable-java.lang.String-java.lang.Object...-) | Schreibt eine Fehler‑Protokollnachricht in die Konsole. |
|
|  | [isErrorEnabled()](#isErrorEnabled--) | Prüft, ob das Protokollieren auf Fehler‑Ebene aktiviert ist. |
|
|  | [getLogger()](#getLogger--) | Gibt die Logger‑Instanz zurück, die zum Protokollieren von Nachrichten verwendet wird. |
|
|  | [setLogger(ILogger logger)](#setLogger-com.groupdocs.foundation.logging.ILogger-) | Setzt die Logger‑Instanz, die zum Protokollieren von Nachrichten verwendet wird. |
|
### ViewerLogger() {#ViewerLogger--}
```
public ViewerLogger()
```


### trace(String message, Object[] arguments) {#trace-java.lang.String-java.lang.Object...-}
```
public static void trace(String message, Object[] arguments)
```


Schreibt eine Trace‑Nachricht in die Konsole.
Trace‑Protokollnachrichten liefern allgemein nützliche Informationen über den Anwendungsablauf.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Nachricht | java.lang.String | Die Trace‑Nachricht. |
|
|  | Argumente | java.lang.Object[] | Die Argumente, die in der Nachricht ersetzt werden sollen. Sie ersetzen die {}‑Platzhalter in der Reihenfolge ihrer Übergabe. |
|

### trace(Throwable throwable, String message, Object[] arguments) {#trace-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public static void trace(Throwable throwable, String message, Object[] arguments)
```


Schreibt eine Trace‑Protokollnachricht in die Konsole.
Trace‑Protokollnachrichten liefern allgemein nützliche Informationen über den Anwendungsablauf.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | throwable | java.lang.Throwable | Die Ausnahme, die mit der Trace‑Protokollnachricht verbunden ist. |
|
|  | Nachricht | java.lang.String | Die Trace‑Protokollnachricht. |
|
|  | Argumente | java.lang.Object[] | Die Argumente, die in der Nachricht ersetzt werden sollen. Sie ersetzen die {}‑Platzhalter in der Reihenfolge, in der sie übergeben werden. |
|

### isTraceEnabled() {#isTraceEnabled--}
```
public static boolean isTraceEnabled()
```


Prüft, ob die Trace‑Ebene für das Protokollieren aktiviert ist.


**Returns:**
boolescher Wert -  true  wenn die Trace‑Ebene aktiviert ist,  false  andernfalls.

### debug(String message, Object[] arguments) {#debug-java.lang.String-java.lang.Object...-}
```
public static void debug(String message, Object[] arguments)
```


Schreibt eine Debug‑Protokollnachricht in die Konsole.
Debug-Protokollnachrichten liefern Informationen über verschiedene Prozesse im Anwendungsablauf.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Nachricht | java.lang.String | Die Debug-Protokollnachricht. |
|
|  | Argumente | java.lang.Object[] | Die Argumente, die in der Nachricht ersetzt werden sollen. Sie ersetzen die {}‑Platzhalter in der Reihenfolge, in der sie übergeben werden. |
|

### debug(Throwable throwable, String message, Object[] arguments) {#debug-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public static void debug(Throwable throwable, String message, Object[] arguments)
```


Schreibt eine Debug‑Protokollnachricht in die Konsole.
Debug-Protokollnachrichten liefern Informationen über verschiedene Prozesse im Anwendungsablauf.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | throwable | java.lang.Throwable | Die mit der Debug-Protokollnachricht verbundene Ausnahme. |
|
|  | Nachricht | java.lang.String | Die Debug-Protokollnachricht. |
|
|  | Argumente | java.lang.Object[] | Die Argumente, die in der Nachricht ersetzt werden sollen. Sie ersetzen die {}‑Platzhalter in der Reihenfolge, in der sie übergeben werden. |
|

### isDebugEnabled() {#isDebugEnabled--}
```
public static boolean isDebugEnabled()
```


Prüft, ob die Debug‑Ebene für das Protokollieren aktiviert ist.


**Returns:**
boolean -  true  wenn das Debug-Level aktiviert ist,  false  andernfalls.

### warning(String message, Object[] arguments) {#warning-java.lang.String-java.lang.Object...-}
```
public static void warning(String message, Object[] arguments)
```


Schreibt eine Warnungs‑Protokollnachricht in die Konsole.
Warnungsprotokollnachrichten liefern Informationen über unerwartete und wiederherstellbare Ereignisse im Anwendungsablauf.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Nachricht | java.lang.String | Die Warnungsprotokollnachricht. |
|
|  | Argumente | java.lang.Object[] | Die Argumente, die in der Nachricht ersetzt werden sollen. Sie ersetzen die {}‑Platzhalter in der Reihenfolge, in der sie übergeben werden. |
|

### warning(Throwable throwable, String message, Object[] arguments) {#warning-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public static void warning(Throwable throwable, String message, Object[] arguments)
```


Schreibt eine Warnungs‑Protokollnachricht in die Konsole.
Warnungsprotokollnachrichten liefern Informationen über unerwartete und wiederherstellbare Ereignisse im Anwendungsablauf.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | throwable | java.lang.Throwable | Die mit der Warnungsprotokollnachricht verbundene Ausnahme. |
|
|  | Nachricht | java.lang.String | Die Warnungsprotokollnachricht. |
|
|  | Argumente | java.lang.Object[] | Die Argumente, die in der Nachricht ersetzt werden sollen. Sie ersetzen die {}‑Platzhalter in der Reihenfolge, in der sie übergeben werden. |
|

### isWarningEnabled() {#isWarningEnabled--}
```
public static boolean isWarningEnabled()
```


Prüft, ob die Warnungs‑Ebene für das Protokollieren aktiviert ist.


**Returns:**
boolean -  true  wenn das Warnungs-Level aktiviert ist,  false  andernfalls.

### error(String message, Object[] arguments) {#error-java.lang.String-java.lang.Object...-}
```
public static void error(String message, Object[] arguments)
```


Schreibt eine Fehler‑Protokollnachricht in die Konsole.
Fehlerprotokollnachrichten liefern Informationen über nicht wiederherstellbare Ereignisse im Anwendungsablauf.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Nachricht | java.lang.String | Die Fehlerprotokollnachricht. |
|
|  | Argumente | java.lang.Object[] | Die Argumente, die in der Nachricht ersetzt werden sollen. Sie ersetzen die {}‑Platzhalter in der Reihenfolge, in der sie übergeben werden. |
|

### error(Throwable throwable, String message, Object[] arguments) {#error-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public static void error(Throwable throwable, String message, Object[] arguments)
```


Schreibt eine Fehler‑Protokollnachricht in die Konsole.
Fehlerprotokollnachrichten liefern Informationen über nicht wiederherstellbare Ereignisse im Anwendungsablauf.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | throwable | java.lang.Throwable | Die mit der Fehlerprotokollnachricht verbundene Ausnahme. |
|
|  | Nachricht | java.lang.String | Die Fehlerprotokollnachricht. |
|
|  | Argumente | java.lang.Object[] | Die Argumente, die in der Nachricht ersetzt werden sollen. Sie ersetzen die {}‑Platzhalter in der Reihenfolge, in der sie übergeben werden. |
|

### isErrorEnabled() {#isErrorEnabled--}
```
public static boolean isErrorEnabled()
```


Prüft, ob das Protokollieren auf Fehler‑Ebene aktiviert ist.


**Returns:**
boolean -  true  wenn das Fehler-Level-Logging aktiviert ist,  false  andernfalls.

### getLogger() {#getLogger--}
```
public static synchronized ILogger getLogger()
```


Gibt die Logger‑Instanz zurück, die zum Protokollieren von Nachrichten verwendet wird.
Die Logger-Instanz kann verwendet werden, um Nachrichten verschiedener Ebenen wie trace, debug, warning und error zu protokollieren.


**Returns:**
com.groupdocs.foundation.logging.ILogger - die Logger-Instanz.

### setLogger(ILogger logger) {#setLogger-com.groupdocs.foundation.logging.ILogger-}
```
public static synchronized void setLogger(ILogger logger)
```


Setzt die Logger‑Instanz, die zum Protokollieren von Nachrichten verwendet wird.
Die Logger-Instanz kann verwendet werden, um Nachrichten verschiedener Ebenen wie trace, debug, warning und error zu protokollieren.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Logger | com.groupdocs.foundation.logging.ILogger | Die zu setzende Logger-Instanz. |
|

