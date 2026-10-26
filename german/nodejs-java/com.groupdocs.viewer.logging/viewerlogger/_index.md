---
title: "ViewerLogger"
second_title: "GroupDocs.Viewer für Node.js über Java API-Referenz"
description: "Globaler Viewer-Logger."
type: docs
weight: 11
url: /de/nodejs-java/com.groupdocs.viewer.logging/viewerlogger/
---
**Inheritance:**
java.lang.Object
```
public class ViewerLogger
```

Globaler Viewer-Logger.

Die ViewerLogger‑Klasse bietet Funktionalität zum Protokollieren von Nachrichten an einen integrierten oder benutzerdefinierten Logger. Sie dient als globaler Logger für das Viewer‑Modul und kann verwendet werden, um verschiedene Ereignisse und Nachrichten zu protokollieren.

Beispielhafte Verwendung:

```

 // Configure the viewer logger to use the default integrated logger
 ViewerLogger.setLogger(new FileLogger("/path/to/file.log"));

 // Log an debug message
 ViewerLogger.debug("Debug message");

 // Log an error message
 ViewerLogger.error("Error message");
 
```

***Note:** The  ViewerLogger  class can be configured to use a custom logger implementation by calling the [setLogger(ILogger)](../../com.groupdocs.viewer.logging/viewerlogger\#setLogger-ILogger-) method. By default, it uses the integrated logger provided by the viewer module.*
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [ViewerLogger()](#ViewerLogger--) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [trace(String message, Object[] arguments)](#trace-java.lang.String-java.lang.Object...-) | Schreibt eine Trace‑Nachricht in die Konsole. |
| [trace(Throwable throwable, String message, Object[] arguments)](#trace-java.lang.Throwable-java.lang.String-java.lang.Object...-) | Schreibt eine Trace‑Log‑Nachricht in die Konsole. |
| [isTraceEnabled()](#isTraceEnabled--) | Prüft, ob die Trace‑Stufe für das Protokollieren aktiviert ist. |
| [debug(String message, Object[] arguments)](#debug-java.lang.String-java.lang.Object...-) | Schreibt eine Debug‑Log‑Nachricht in die Konsole. |
| [debug(Throwable throwable, String message, Object[] arguments)](#debug-java.lang.Throwable-java.lang.String-java.lang.Object...-) | Schreibt eine Debug‑Log‑Nachricht in die Konsole. |
| [isDebugEnabled()](#isDebugEnabled--) | Prüft, ob die Debug‑Stufe für das Protokollieren aktiviert ist. |
| [warning(String message, Object[] arguments)](#warning-java.lang.String-java.lang.Object...-) | Schreibt eine Warn‑Log‑Nachricht in die Konsole. |
| [warning(Throwable throwable, String message, Object[] arguments)](#warning-java.lang.Throwable-java.lang.String-java.lang.Object...-) | Schreibt eine Warn‑Log‑Nachricht in die Konsole. |
| [isWarningEnabled()](#isWarningEnabled--) | Prüft, ob die Warn‑Stufe für das Protokollieren aktiviert ist. |
| [error(String message, Object[] arguments)](#error-java.lang.String-java.lang.Object...-) | Schreibt eine Fehler‑Log‑Nachricht in die Konsole. |
| [error(Throwable throwable, String message, Object[] arguments)](#error-java.lang.Throwable-java.lang.String-java.lang.Object...-) | Schreibt eine Fehler‑Log‑Nachricht in die Konsole. |
| [isErrorEnabled()](#isErrorEnabled--) | Prüft, ob das Protokollieren auf Fehler‑Ebene aktiviert ist. |
| [getLogger()](#getLogger--) | Gibt die Logger‑Instanz zurück, die zum Protokollieren von Nachrichten verwendet wird. |
| [setLogger(ILogger logger)](#setLogger-com.groupdocs.foundation.logging.ILogger-) | Setzt die Logger‑Instanz, die zum Protokollieren von Nachrichten verwendet wird. |
### ViewerLogger() {#ViewerLogger--}
```
public ViewerLogger()
```


### trace(String message, Object[] arguments) {#trace-java.lang.String-java.lang.Object...-}
```
public static void trace(String message, Object[] arguments)
```


Schreibt eine Trace‑Nachricht in die Konsole. Trace‑Log‑Nachrichten liefern allgemein nützliche Informationen über den Anwendungsablauf.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Nachricht | java.lang.String | Die Trace‑Nachricht. |
| Argumente | java.lang.Object[] | Die Argumente, die in der Nachricht ersetzt werden sollen. Sie ersetzen die \{\}-Platzhalter in der Reihenfolge des Übergebens. |

### trace(Throwable throwable, String message, Object[] arguments) {#trace-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public static void trace(Throwable throwable, String message, Object[] arguments)
```


Schreibt eine Trace-Protokollnachricht in die Konsole. Trace-Protokollnachrichten liefern allgemein nützliche Informationen über den Anwendungsablauf.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| throwable | java.lang.Throwable | Die mit der Trace-Protokollnachricht verbundene Ausnahme. |
| Nachricht | java.lang.String | Die Trace-Protokollnachricht. |
| Argumente | java.lang.Object[] | Die Argumente, die in der Nachricht ersetzt werden sollen. Sie ersetzen die \{\}-Platzhalter in der Reihenfolge, in der sie übergeben werden. |

### isTraceEnabled() {#isTraceEnabled--}
```
public static boolean isTraceEnabled()
```


Prüft, ob die Trace‑Stufe für das Protokollieren aktiviert ist.

**Returns:**
boolean -  true  wenn die Trace-Stufe aktiviert ist,  false  sonst.
### debug(String message, Object[] arguments) {#debug-java.lang.String-java.lang.Object...-}
```
public static void debug(String message, Object[] arguments)
```


Schreibt eine Debug-Protokollnachricht in die Konsole. Debug-Protokollnachrichten liefern Informationen über verschiedene Prozesse im Anwendungsablauf.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Nachricht | java.lang.String | Die Debug-Protokollnachricht. |
| Argumente | java.lang.Object[] | Die Argumente, die in der Nachricht ersetzt werden sollen. Sie ersetzen die \{\}-Platzhalter in der Reihenfolge, in der sie übergeben werden. |

### debug(Throwable throwable, String message, Object[] arguments) {#debug-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public static void debug(Throwable throwable, String message, Object[] arguments)
```


Schreibt eine Debug-Protokollnachricht in die Konsole. Debug-Protokollnachrichten liefern Informationen über verschiedene Prozesse im Anwendungsablauf.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| throwable | java.lang.Throwable | Die mit der Debug-Protokollnachricht verbundene Ausnahme. |
| Nachricht | java.lang.String | Die Debug-Protokollnachricht. |
| Argumente | java.lang.Object[] | Die Argumente, die in der Nachricht ersetzt werden sollen. Sie ersetzen die \{\}-Platzhalter in der Reihenfolge, in der sie übergeben werden. |

### isDebugEnabled() {#isDebugEnabled--}
```
public static boolean isDebugEnabled()
```


Prüft, ob die Debug‑Stufe für das Protokollieren aktiviert ist.

**Returns:**
boolean -  true  wenn die Debug-Stufe aktiviert ist,  false  sonst.
### warning(String message, Object[] arguments) {#warning-java.lang.String-java.lang.Object...-}
```
public static void warning(String message, Object[] arguments)
```


Schreibt eine Warnungs-Protokollnachricht in die Konsole. Warnungs-Protokollnachrichten liefern Informationen über unerwartete und wiederherstellbare Ereignisse im Anwendungsablauf.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Nachricht | java.lang.String | Die Warnungs-Protokollnachricht. |
| Argumente | java.lang.Object[] | Die Argumente, die in der Nachricht ersetzt werden sollen. Sie ersetzen die \{\}-Platzhalter in der Reihenfolge, in der sie übergeben werden. |

### warning(Throwable throwable, String message, Object[] arguments) {#warning-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public static void warning(Throwable throwable, String message, Object[] arguments)
```


Schreibt eine Warnungs-Protokollnachricht in die Konsole. Warnungs-Protokollnachrichten liefern Informationen über unerwartete und wiederherstellbare Ereignisse im Anwendungsablauf.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| throwable | java.lang.Throwable | Die mit der Warnungs-Protokollnachricht verbundene Ausnahme. |
| Nachricht | java.lang.String | Die Warnungs-Protokollnachricht. |
| Argumente | java.lang.Object[] | Die Argumente, die in der Nachricht ersetzt werden sollen. Sie ersetzen die \{\}-Platzhalter in der Reihenfolge, in der sie übergeben werden. |

### isWarningEnabled() {#isWarningEnabled--}
```
public static boolean isWarningEnabled()
```


Prüft, ob die Warn‑Stufe für das Protokollieren aktiviert ist.

**Returns:**
boolean -  true  wenn die Warnungs-Stufe aktiviert ist,  false  sonst.
### error(String message, Object[] arguments) {#error-java.lang.String-java.lang.Object...-}
```
public static void error(String message, Object[] arguments)
```


Schreibt eine Fehler-Protokollnachricht in die Konsole. Fehler-Protokollnachrichten liefern Informationen über nicht wiederherstellbare Ereignisse im Anwendungsablauf.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Nachricht | java.lang.String | Die Fehler-Protokollnachricht. |
| Argumente | java.lang.Object[] | Die Argumente, die in der Nachricht ersetzt werden sollen. Sie ersetzen die \{\}-Platzhalter in der Reihenfolge, in der sie übergeben werden. |

### error(Throwable throwable, String message, Object[] arguments) {#error-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public static void error(Throwable throwable, String message, Object[] arguments)
```


Schreibt eine Fehler-Protokollnachricht in die Konsole. Fehler-Protokollnachrichten liefern Informationen über nicht wiederherstellbare Ereignisse im Anwendungsablauf.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| throwable | java.lang.Throwable | Die mit der Fehler-Protokollnachricht verbundene Ausnahme. |
| Nachricht | java.lang.String | Die Fehler-Protokollnachricht. |
| Argumente | java.lang.Object[] | Die Argumente, die in der Nachricht ersetzt werden sollen. Sie ersetzen die \{\}-Platzhalter in der Reihenfolge, in der sie übergeben werden. |

### isErrorEnabled() {#isErrorEnabled--}
```
public static boolean isErrorEnabled()
```


Prüft, ob das Protokollieren auf Fehler‑Ebene aktiviert ist.

**Returns:**
boolean -  true  wenn das Logging auf Fehler-Ebene aktiviert ist,  false  sonst.
### getLogger() {#getLogger--}
```
public static synchronized ILogger getLogger()
```


Ruft die Logger-Instanz ab, die zum Protokollieren von Nachrichten verwendet wird. Die Logger-Instanz kann verwendet werden, um Nachrichten verschiedener Stufen wie Trace, Debug, Warnung und Fehler zu protokollieren.

**Returns:**
com.groupdocs.foundation.logging.ILogger - die Logger-Instanz.
### setLogger(ILogger logger) {#setLogger-com.groupdocs.foundation.logging.ILogger-}
```
public static synchronized void setLogger(ILogger logger)
```


Setzt die Logger-Instanz, die zum Protokollieren von Nachrichten verwendet wird. Die Logger-Instanz kann verwendet werden, um Nachrichten verschiedener Stufen wie Trace, Debug, Warnung und Fehler zu protokollieren.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Logger | com.groupdocs.foundation.logging.ILogger | Die zu setzende Logger-Instanz. |

