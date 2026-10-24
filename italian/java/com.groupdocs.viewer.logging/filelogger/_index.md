---
title: "FileLogger"
second_title: "Riferimento API di GroupDocs.Viewer per Java"
description: "Scrive i messaggi di log su un file."
type: docs
weight: 10
url: /it/java/com.groupdocs.viewer.logging/filelogger/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.groupdocs.foundation.logging.ILogger
```
public class FileLogger implements ILogger
```

Scrive i messaggi di log su un file.


Il
FileLogger
la classe fornisce funzionalità per scrivere messaggi di log su un file. Implementa l'interfaccia ILogger
e può essere utilizzato per registrare vari eventi e messaggi in un'applicazione. I messaggi di log vengono scritti nel file specificato.


Esempio di utilizzo:

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
La classe fornisce funzionalità di logging di base.
È possibile estendere questa classe per aggiungere livelli di log personalizzati o funzionalità di logging aggiuntive secondo le proprie esigenze.*

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
|  | [FileLogger(String fileName)](#FileLogger-java.lang.String-) | Crea un logger che registra i messaggi in un file specificato dal nome file fornito. |
|
|  | [FileLogger(String fileName, boolean isTraceEnabled, boolean isDebugEnabled, boolean isWarningEnabled, boolean isErrorEnabled)](#FileLogger-java.lang.String-boolean-boolean-boolean-boolean-) | Crea un logger che registra i messaggi in un file con i livelli di logging specificati. |
|
## Campi

| Campo | Descrizione |
| --- | --- |
| [MESSAGE](#MESSAGE) |  |
| [EXCEPTION](#EXCEPTION) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [trace(String message, Object[] arguments)](#trace-java.lang.String-java.lang.Object...-) | Scrive un messaggio di traccia sulla console. |
|
|  | [trace(Throwable throwable, String message, Object[] arguments)](#trace-java.lang.Throwable-java.lang.String-java.lang.Object...-) | Scrive un messaggio di log di traccia sulla console. |
|
|  | [isTraceEnabled()](#isTraceEnabled--) | Verifica se il livello di traccia è abilitato per la registrazione. |
|
|  | [debug(String message, Object[] arguments)](#debug-java.lang.String-java.lang.Object...-) | Scrive un messaggio di log di debug sulla console. |
|
|  | [debug(Throwable throwable, String message, Object[] arguments)](#debug-java.lang.Throwable-java.lang.String-java.lang.Object...-) | Scrive un messaggio di log di debug sulla console. |
|
|  | [isDebugEnabled()](#isDebugEnabled--) | Verifica se il livello di debug è abilitato per la registrazione. |
|
|  | [warning(String message, Object[] arguments)](#warning-java.lang.String-java.lang.Object...-) | Scrive un messaggio di log di avviso sulla console. |
|
|  | [warning(Throwable throwable, String message, Object[] arguments)](#warning-java.lang.Throwable-java.lang.String-java.lang.Object...-) | Scrive un messaggio di log di avviso sulla console. |
|
|  | [isWarningEnabled()](#isWarningEnabled--) | Verifica se il livello di avviso è abilitato per la registrazione. |
|
|  | [error(String message, Object[] arguments)](#error-java.lang.String-java.lang.Object...-) | Scrive un messaggio di log di errore sulla console. |
|
|  | [error(Throwable throwable, String message, Object[] arguments)](#error-java.lang.Throwable-java.lang.String-java.lang.Object...-) | Scrive un messaggio di log di errore sulla console. |
|
|  | [isErrorEnabled()](#isErrorEnabled--) | Verifica se la registrazione a livello di errore è abilitata. |
|
### FileLogger(String fileName) {#FileLogger-java.lang.String-}
```
public FileLogger(String fileName)
```


Crea un logger che registra i messaggi in un file specificato dal nome file fornito.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | fileName | java.lang.String | Il nome completo del file con percorso. |
|

### FileLogger(String fileName, boolean isTraceEnabled, boolean isDebugEnabled, boolean isWarningEnabled, boolean isErrorEnabled) {#FileLogger-java.lang.String-boolean-boolean-boolean-boolean-}
```
public FileLogger(String fileName, boolean isTraceEnabled, boolean isDebugEnabled, boolean isWarningEnabled, boolean isErrorEnabled)
```


Crea un logger che registra i messaggi in un file con i livelli di logging specificati.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | fileName | java.lang.String | Il nome completo del file con percorso. |
|
|  | isTraceEnabled | boolean | Specifica se il logging a livello di trace è abilitato. |
|
|  | isDebugEnabled | boolean | Specifica se il logging a livello di debug è abilitato. |
|
|  | isWarningEnabled | boolean | Specifica se il logging a livello di avviso è abilitato. |
|
|  | isErrorEnabled | boolean | Specifica se il logging a livello di errore è abilitato. |
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


Scrive un messaggio di traccia sulla console.
I messaggi di log di traccia forniscono informazioni generalmente utili sul flusso dell'applicazione.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | messaggio | java.lang.String | Il messaggio di traccia. |
|
|  | argomenti | java.lang.Object[] | Gli argomenti da sostituire nel messaggio. Sostituiranno i segnaposto {} nell'ordine di passaggio. |
|

### trace(Throwable throwable, String message, Object[] arguments) {#trace-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public void trace(Throwable throwable, String message, Object[] arguments)
```


Scrive un messaggio di log di traccia sulla console.
I messaggi di log di tipo trace forniscono informazioni generalmente utili sul flusso dell'applicazione.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | throwable | java.lang.Throwable | L'eccezione associata al messaggio di log trace. |
|
|  | messaggio | java.lang.String | Il messaggio di log trace. |
|
|  | argomenti | java.lang.Object[] | Gli argomenti da sostituire nel messaggio. Sostituiranno i segnaposto {} nell'ordine in cui vengono passati. |
|

### isTraceEnabled() {#isTraceEnabled--}
```
public boolean isTraceEnabled()
```


Verifica se il livello di traccia è abilitato per la registrazione.


**Returns:**
boolean -  true  se il livello trace è abilitato,  false  altrimenti.

### debug(String message, Object[] arguments) {#debug-java.lang.String-java.lang.Object...-}
```
public void debug(String message, Object[] arguments)
```


Scrive un messaggio di log di debug sulla console.
I messaggi di log di tipo debug forniscono informazioni sui diversi processi nel flusso dell'applicazione.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | messaggio | java.lang.String | Il messaggio di log debug. |
|
|  | argomenti | java.lang.Object[] | Gli argomenti da sostituire nel messaggio. Sostituiranno i segnaposto {} nell'ordine in cui vengono passati. |
|

### debug(Throwable throwable, String message, Object[] arguments) {#debug-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public void debug(Throwable throwable, String message, Object[] arguments)
```


Scrive un messaggio di log di debug sulla console.
I messaggi di log di tipo debug forniscono informazioni sui diversi processi nel flusso dell'applicazione.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | throwable | java.lang.Throwable | L'eccezione associata al messaggio di log debug. |
|
|  | messaggio | java.lang.String | Il messaggio di log debug. |
|
|  | argomenti | java.lang.Object[] | Gli argomenti da sostituire nel messaggio. Sostituiranno i segnaposto {} nell'ordine in cui vengono passati. |
|

### isDebugEnabled() {#isDebugEnabled--}
```
public boolean isDebugEnabled()
```


Verifica se il livello di debug è abilitato per la registrazione.


**Returns:**
boolean -  true  se il livello debug è abilitato,  false  altrimenti.

### warning(String message, Object[] arguments) {#warning-java.lang.String-java.lang.Object...-}
```
public void warning(String message, Object[] arguments)
```


Scrive un messaggio di log di avviso sulla console.
I messaggi di log di tipo warning forniscono informazioni su eventi inaspettati e recuperabili nel flusso dell'applicazione.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | messaggio | java.lang.String | Il messaggio di log warning. |
|
|  | argomenti | java.lang.Object[] | Gli argomenti da sostituire nel messaggio. Sostituiranno i segnaposto {} nell'ordine in cui vengono passati. |
|

### warning(Throwable throwable, String message, Object[] arguments) {#warning-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public void warning(Throwable throwable, String message, Object[] arguments)
```


Scrive un messaggio di log di avviso sulla console.
I messaggi di log di tipo warning forniscono informazioni su eventi inaspettati e recuperabili nel flusso dell'applicazione.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | throwable | java.lang.Throwable | L'eccezione associata al messaggio di log warning. |
|
|  | messaggio | java.lang.String | Il messaggio di log warning. |
|
|  | argomenti | java.lang.Object[] | Gli argomenti da sostituire nel messaggio. Sostituiranno i segnaposto {} nell'ordine in cui vengono passati. |
|

### isWarningEnabled() {#isWarningEnabled--}
```
public boolean isWarningEnabled()
```


Verifica se il livello di avviso è abilitato per la registrazione.


**Returns:**
boolean -  true  se il livello warning è abilitato,  false  altrimenti.

### error(String message, Object[] arguments) {#error-java.lang.String-java.lang.Object...-}
```
public void error(String message, Object[] arguments)
```


Scrive un messaggio di log di errore sulla console.
I messaggi di log di tipo error forniscono informazioni su eventi non recuperabili nel flusso dell'applicazione.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | messaggio | java.lang.String | Il messaggio di log error. |
|
|  | argomenti | java.lang.Object[] | Gli argomenti da sostituire nel messaggio. Sostituiranno i segnaposto {} nell'ordine in cui vengono passati. |
|

### error(Throwable throwable, String message, Object[] arguments) {#error-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public void error(Throwable throwable, String message, Object[] arguments)
```


Scrive un messaggio di log di errore sulla console.
I messaggi di log di tipo error forniscono informazioni su eventi non recuperabili nel flusso dell'applicazione.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | throwable | java.lang.Throwable | L'eccezione associata al messaggio di log error. |
|
|  | messaggio | java.lang.String | Il messaggio di log error. |
|
|  | argomenti | java.lang.Object[] | Gli argomenti da sostituire nel messaggio. Sostituiranno i segnaposto {} nell'ordine in cui vengono passati. |
|

### isErrorEnabled() {#isErrorEnabled--}
```
public boolean isErrorEnabled()
```


Verifica se la registrazione a livello di errore è abilitata.


**Returns:**
boolean -  true  se il logging a livello error è abilitato,  false  altrimenti.

