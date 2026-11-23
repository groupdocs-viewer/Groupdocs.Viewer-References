---
title: "FileLogger"
second_title: "GroupDocs.Viewer für Java API-Referenz"
description: "Schreibt Protokollnachrichten in eine Datei."
type: docs
weight: 10
url: /de/java/com.groupdocs.viewer.logging/filelogger/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.groupdocs.foundation.logging.ILogger
```
public class FileLogger implements ILogger
```

Schreibt Protokollnachrichten in eine Datei.


Die
FileLogger
Klasse bietet Funktionalität zum Schreiben von Protokollnachrichten in eine Datei. Sie implementiert das ILogger-Interface
und kann verwendet werden, um verschiedene Ereignisse und Nachrichten in einer Anwendung zu protokollieren. Protokollnachrichten werden in die angegebene Datei geschrieben.


Beispielverwendung:

````

 // Create a new instance of FileLogger with the specified log file path
 FileLogger fileLogger = new FileLogger("/path/to/logfile.txt");

 // Log an informational message
 fileLogger.debug("Debug message");

 // Log an error message
 fileLogger.error("Error message");

 // Check is logging warning messages enabled
 boolean warningEnabled = fileLogger.isWarningEnabled();
 
````


***Note:** The 
FileLogger
Klasse bietet grundlegende Protokollierungsfunktionalität.
Sie können diese Klasse erweitern, um benutzerdefinierte Protokollstufen oder zusätzliche Protokollierungsfunktionen nach Ihren Anforderungen hinzuzufügen.*

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
|  | [FileLogger(String fileName)](#FileLogger-java.lang.String-) | Erstellt einen Logger, der Nachrichten in eine Datei protokolliert, die durch den angegebenen Dateinamen bestimmt wird. |
|
|  | [FileLogger(String fileName, boolean isTraceEnabled, boolean isDebugEnabled, boolean isWarningEnabled, boolean isErrorEnabled)](#FileLogger-java.lang.String-boolean-boolean-boolean-boolean-) | Erstellt einen Logger, der Nachrichten in eine Datei mit angegebenen Protokollstufen protokolliert. |
|
## Felder

| Feld | Beschreibung |
| --- | --- |
| [MESSAGE](#MESSAGE) |  |
| [EXCEPTION](#EXCEPTION) |  |
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
### FileLogger(String fileName) {#FileLogger-java.lang.String-}
```
public FileLogger(String fileName)
```


Erstellt einen Logger, der Nachrichten in eine Datei protokolliert, die durch den angegebenen Dateinamen bestimmt wird.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | fileName | java.lang.String | Der vollständige Dateiname mit Pfad. |
|

### FileLogger(String fileName, boolean isTraceEnabled, boolean isDebugEnabled, boolean isWarningEnabled, boolean isErrorEnabled) {#FileLogger-java.lang.String-boolean-boolean-boolean-boolean-}
```
public FileLogger(String fileName, boolean isTraceEnabled, boolean isDebugEnabled, boolean isWarningEnabled, boolean isErrorEnabled)
```


Erstellt einen Logger, der Nachrichten in eine Datei mit angegebenen Protokollstufen protokolliert.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | fileName | java.lang.String | Der vollständige Dateiname mit Pfad. |
|
|  | isTraceEnabled | boolesch | Gibt an, ob die Protokollierung auf Trace-Ebene aktiviert ist. |
|
|  | isDebugEnabled | boolesch | Gibt an, ob die Protokollierung auf Debug-Ebene aktiviert ist. |
|
|  | isWarningEnabled | boolesch | Gibt an, ob die Protokollierung auf Warnungs-Ebene aktiviert ist. |
|
|  | isErrorEnabled | boolesch | Gibt an, ob die Protokollierung auf Fehler-Ebene aktiviert ist. |
|

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
public void trace(Throwable throwable, String message, Object[] arguments)
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
public boolean isTraceEnabled()
```


Prüft, ob die Trace‑Ebene für das Protokollieren aktiviert ist.


**Returns:**
boolescher Wert -  true  wenn die Trace‑Ebene aktiviert ist,  false  andernfalls.

### debug(String message, Object[] arguments) {#debug-java.lang.String-java.lang.Object...-}
```
public void debug(String message, Object[] arguments)
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
public void debug(Throwable throwable, String message, Object[] arguments)
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
public boolean isDebugEnabled()
```


Prüft, ob die Debug‑Ebene für das Protokollieren aktiviert ist.


**Returns:**
boolean -  true  wenn das Debug-Level aktiviert ist,  false  andernfalls.

### warning(String message, Object[] arguments) {#warning-java.lang.String-java.lang.Object...-}
```
public void warning(String message, Object[] arguments)
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
public void warning(Throwable throwable, String message, Object[] arguments)
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
public boolean isWarningEnabled()
```


Prüft, ob die Warnungs‑Ebene für das Protokollieren aktiviert ist.


**Returns:**
boolean -  true  wenn das Warnungs-Level aktiviert ist,  false  andernfalls.

### error(String message, Object[] arguments) {#error-java.lang.String-java.lang.Object...-}
```
public void error(String message, Object[] arguments)
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
public void error(Throwable throwable, String message, Object[] arguments)
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
public boolean isErrorEnabled()
```


Prüft, ob das Protokollieren auf Fehler‑Ebene aktiviert ist.


**Returns:**
boolean -  true  wenn das Fehler-Level-Logging aktiviert ist,  false  andernfalls.

