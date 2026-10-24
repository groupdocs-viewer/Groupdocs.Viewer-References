---
title: "MemoryCleaner"
second_title: "Riferimento API di GroupDocs.Viewer per Java"
description: "Pulisce diverse risorse per liberare memoria."
type: docs
weight: 12
url: /it/java/com.groupdocs.viewer.utils/memorycleaner/
---
**Inheritance:**
java.lang.Object
```
public final class MemoryCleaner
```

Pulisce diverse risorse per liberare memoria.


Questa classe fornisce metodi per liberare la memoria heap, eliminare i file temporanei e cancellare le informazioni del registro dei font.
Include anche un metodo per cancellare in modo sicuro le istanze thread-local per il thread corrente.


Esempio di utilizzo:

````

 // Clean heap memory, keeping font settings
 MemoryCleaner.clearKeepingFontSettings();

 // Clean heap memory and delete temp files
 MemoryCleaner.clear();

 // Clean heap memory from static PDF instances
 MemoryCleaner.clearStaticInstances();

 // Delete all temp files created by PDF in the system temp directory
 MemoryCleaner.clearAllTempFiles();

 // Clear font registry information from heap memory
 MemoryCleaner.clearFontRegistry();

 // Safely clear thread-local instances for the current thread
 MemoryCleaner.clearCurrentThreadLocals();
 
````


## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [MemoryCleaner()](#MemoryCleaner--) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [clearKeepingFontSettings()](#clearKeepingFontSettings--) | Cancella la memoria heap dalle istanze PDF statiche (static e threadLocal) ed elimina tutti i file temporanei. |
|
|  | [clear()](#clear--) | Cancella la memoria heap dalle istanze PDF statiche (static e threadLocal) ed elimina tutti i file temporanei. |
|
|  | [clearStaticInstances()](#clearStaticInstances--) | Cancella la memoria heap dalle istanze PDF statiche. |
|
|  | [clearAllTempFiles()](#clearAllTempFiles--) | Cancella i file temporanei creati da GroupDocs.Viewer nella directory temporanea di sistema. |
|
|  | [clearFontRegistry()](#clearFontRegistry--) | Cancella le informazioni del registro dei font dalla memoria heap. |
|
|  | [clearCurrentThreadLocals()](#clearCurrentThreadLocals--) | Cancella in modo sicuro la memoria heap dalle istanze thread-local per il thread corrente. |
|
### MemoryCleaner() {#MemoryCleaner--}
```
public MemoryCleaner()
```


### clearKeepingFontSettings() {#clearKeepingFontSettings--}
```
public static void clearKeepingFontSettings()
```


Cancella la memoria heap dalle istanze PDF statiche (static e threadLocal) ed elimina tutti i file temporanei.
Questo metodo non influisce sulle impostazioni dei font.


### clear() {#clear--}
```
public static void clear()
```


Cancella la memoria heap dalle istanze PDF statiche (static e threadLocal) ed elimina tutti i file temporanei.


### clearStaticInstances() {#clearStaticInstances--}
```
public static void clearStaticInstances()
```


Cancella la memoria heap dalle istanze PDF statiche.


### clearAllTempFiles() {#clearAllTempFiles--}
```
public static void clearAllTempFiles()
```


Cancella i file temporanei creati da GroupDocs.Viewer nella directory temporanea di sistema.


### clearFontRegistry() {#clearFontRegistry--}
```
public static void clearFontRegistry()
```


Cancella le informazioni del registro dei font dalla memoria heap.


### clearCurrentThreadLocals() {#clearCurrentThreadLocals--}
```
public static void clearCurrentThreadLocals()
```


Cancella in modo sicuro la memoria heap dalle istanze thread-local per il thread corrente.


