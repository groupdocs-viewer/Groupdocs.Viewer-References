---
title: MemoryCleaner
second_title: GroupDocs.Viewer for Java API Reference
description: Cleanes different resources to free memory
type: docs
weight: 10
url: /java/com.groupdocs.viewer.utils/memorycleaner/
---
**Inheritance:**
java.lang.Object
```
public final class MemoryCleaner
```

Cleanes different resources to free memory
## Constructors

| Constructor | Description |
| --- | --- |
| [MemoryCleaner()](#MemoryCleaner--) |  |
## Methods

| Method | Description |
| --- | --- |
| [clearKeepingFontSettings()](#clearKeepingFontSettings--) | Clears Heap memory from static PDF instances (static and threadLocal) and deletes all temp files. |
| [clear()](#clear--) | Clears Heap memory from static PDF instances (static and threadLocal) and deletes all temp files. |
| [clearStaticInstances()](#clearStaticInstances--) | Clears Heap memory from static PDF instances. |
| [clearAllTempFiles()](#clearAllTempFiles--) | Clears temp files, created by PDF in system temp directory. |
| [clearFontRegistry()](#clearFontRegistry--) | Clears FontRegistry information from the Heap memory. |
| [clearCurrentThreadLocals()](#clearCurrentThreadLocals--) | Safely clears Heap memory from ThreadLocal instances for current thread |
### MemoryCleaner() {#MemoryCleaner--}
```
public MemoryCleaner()
```


### clearKeepingFontSettings() {#clearKeepingFontSettings--}
```
public static void clearKeepingFontSettings()
```


Clears Heap memory from static PDF instances (static and threadLocal) and deletes all temp files.

### clear() {#clear--}
```
public static void clear()
```


Clears Heap memory from static PDF instances (static and threadLocal) and deletes all temp files.

### clearStaticInstances() {#clearStaticInstances--}
```
public static void clearStaticInstances()
```


Clears Heap memory from static PDF instances.

### clearAllTempFiles() {#clearAllTempFiles--}
```
public static void clearAllTempFiles()
```


Clears temp files, created by PDF in system temp directory.

### clearFontRegistry() {#clearFontRegistry--}
```
public static void clearFontRegistry()
```


Clears FontRegistry information from the Heap memory.

### clearCurrentThreadLocals() {#clearCurrentThreadLocals--}
```
public static void clearCurrentThreadLocals()
```


Safely clears Heap memory from ThreadLocal instances for current thread

