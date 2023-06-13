---
title: MemoryCleaner
second_title: GroupDocs.Viewer for Java API Reference
description: Cleans different resources to free memory.
type: docs
weight: 10
url: /java/com.groupdocs.viewer.utils/memorycleaner/
---
**Inheritance:**
java.lang.Object
```
public final class MemoryCleaner
```

Cleans different resources to free memory.

This class provides methods to clear heap memory, delete temp files, and clear font registry information. It also includes a method to safely clear thread-local instances for the current thread.

Example usage:

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
## Constructors

| Constructor | Description |
| --- | --- |
| [MemoryCleaner()](#MemoryCleaner--) |  |
## Methods

| Method | Description |
| --- | --- |
| [clearKeepingFontSettings()](#clearKeepingFontSettings--) | Clears heap memory from static PDF instances (static and threadLocal) and deletes all temp files. |
| [clear()](#clear--) | Clears heap memory from static PDF instances (static and threadLocal) and deletes all temp files. |
| [clearStaticInstances()](#clearStaticInstances--) | Clears heap memory from static PDF instances. |
| [clearAllTempFiles()](#clearAllTempFiles--) | Clears temp files created by GroupDocs.Viewer in the system temp directory. |
| [clearFontRegistry()](#clearFontRegistry--) | Clears font registry information from heap memory. |
| [clearCurrentThreadLocals()](#clearCurrentThreadLocals--) | Safely clears heap memory from thread-local instances for the current thread. |
### MemoryCleaner() {#MemoryCleaner--}
```
public MemoryCleaner()
```


### clearKeepingFontSettings() {#clearKeepingFontSettings--}
```
public static void clearKeepingFontSettings()
```


Clears heap memory from static PDF instances (static and threadLocal) and deletes all temp files. This method does not affect font settings.

### clear() {#clear--}
```
public static void clear()
```


Clears heap memory from static PDF instances (static and threadLocal) and deletes all temp files.

### clearStaticInstances() {#clearStaticInstances--}
```
public static void clearStaticInstances()
```


Clears heap memory from static PDF instances.

### clearAllTempFiles() {#clearAllTempFiles--}
```
public static void clearAllTempFiles()
```


Clears temp files created by GroupDocs.Viewer in the system temp directory.

### clearFontRegistry() {#clearFontRegistry--}
```
public static void clearFontRegistry()
```


Clears font registry information from heap memory.

### clearCurrentThreadLocals() {#clearCurrentThreadLocals--}
```
public static void clearCurrentThreadLocals()
```


Safely clears heap memory from thread-local instances for the current thread.

