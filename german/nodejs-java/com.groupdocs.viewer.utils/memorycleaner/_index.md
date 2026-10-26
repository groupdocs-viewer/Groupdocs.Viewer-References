---
title: "MemoryCleaner"
second_title: "GroupDocs.Viewer für Node.js über Java API-Referenz"
description: "Bereinigt verschiedene Ressourcen, um Speicher freizugeben."
type: docs
weight: 10
url: /de/nodejs-java/com.groupdocs.viewer.utils/memorycleaner/
---
**Inheritance:**
java.lang.Object
```
public final class MemoryCleaner
```

Bereinigt verschiedene Ressourcen, um Speicher freizugeben.

Diese Klasse bietet Methoden zum Löschen des Heap-Speichers, zum Entfernen temporärer Dateien und zum Bereinigen von Schriftarten-Registrierungsinformationen. Sie enthält außerdem eine Methode, um thread-lokale Instanzen für den aktuellen Thread sicher zu löschen.

Beispielhafte Verwendung:

```

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
 
```
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [MemoryCleaner()](#MemoryCleaner--) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [clearKeepingFontSettings()](#clearKeepingFontSettings--) | Löscht den Heap-Speicher von statischen PDF-Instanzen (statisch und threadLocal) und entfernt alle temporären Dateien. |
| [clear()](#clear--) | Löscht den Heap-Speicher von statischen PDF-Instanzen (statisch und threadLocal) und entfernt alle temporären Dateien. |
| [clearStaticInstances()](#clearStaticInstances--) | Löscht den Heap-Speicher von statischen PDF-Instanzen. |
| [clearAllTempFiles()](#clearAllTempFiles--) | Löscht temporäre Dateien, die von GroupDocs.Viewer im System-Temp-Verzeichnis erstellt wurden. |
| [clearFontRegistry()](#clearFontRegistry--) | Löscht Schriftarten-Registrierungsinformationen aus dem Heap-Speicher. |
| [clearCurrentThreadLocals()](#clearCurrentThreadLocals--) | Löscht den Heap-Speicher von thread-lokalen Instanzen für den aktuellen Thread sicher. |
### MemoryCleaner() {#MemoryCleaner--}
```
public MemoryCleaner()
```


### clearKeepingFontSettings() {#clearKeepingFontSettings--}
```
public static void clearKeepingFontSettings()
```


Löscht den Heap-Speicher von statischen PDF-Instanzen (statisch und threadLocal) und entfernt alle temporären Dateien. Diese Methode beeinflusst die Schriftarteinstellungen nicht.

### clear() {#clear--}
```
public static void clear()
```


Löscht den Heap-Speicher von statischen PDF-Instanzen (statisch und threadLocal) und entfernt alle temporären Dateien.

### clearStaticInstances() {#clearStaticInstances--}
```
public static void clearStaticInstances()
```


Löscht den Heap-Speicher von statischen PDF-Instanzen.

### clearAllTempFiles() {#clearAllTempFiles--}
```
public static void clearAllTempFiles()
```


Löscht temporäre Dateien, die von GroupDocs.Viewer im System-Temp-Verzeichnis erstellt wurden.

### clearFontRegistry() {#clearFontRegistry--}
```
public static void clearFontRegistry()
```


Löscht Schriftarten-Registrierungsinformationen aus dem Heap-Speicher.

### clearCurrentThreadLocals() {#clearCurrentThreadLocals--}
```
public static void clearCurrentThreadLocals()
```


Löscht den Heap-Speicher von thread-lokalen Instanzen für den aktuellen Thread sicher.

