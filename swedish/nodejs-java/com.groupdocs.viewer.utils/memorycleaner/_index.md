---
title: "MemoryCleaner"
second_title: "GroupDocs.Viewer för Node.js via Java API-referens"
description: "Rensar olika resurser för att frigöra minne."
type: docs
weight: 10
url: /sv/nodejs-java/com.groupdocs.viewer.utils/memorycleaner/
---
**Inheritance:**
java.lang.Object
```
public final class MemoryCleaner
```

Rensar olika resurser för att frigöra minne.

Denna klass tillhandahåller metoder för att rensa heap‑minne, ta bort temporära filer och rensa information i teckensnittsregistret. Den innehåller också en metod för att säkert rensa trådlokala instanser för den aktuella tråden.

Exempel på användning:

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
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [MemoryCleaner()](#MemoryCleaner--) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [clearKeepingFontSettings()](#clearKeepingFontSettings--) | Rensar heap‑minne från statiska PDF‑instansers (statisk och trådlokal) och tar bort alla temporära filer. |
| [clear()](#clear--) | Rensar heap‑minne från statiska PDF‑instansers (statisk och trådlokal) och tar bort alla temporära filer. |
| [clearStaticInstances()](#clearStaticInstances--) | Rensar heap‑minne från statiska PDF‑instansers. |
| [clearAllTempFiles()](#clearAllTempFiles--) | Rensar temporära filer som skapats av GroupDocs.Viewer i systemets temporära katalog. |
| [clearFontRegistry()](#clearFontRegistry--) | Rensar information i teckensnittsregistret från heap‑minnet. |
| [clearCurrentThreadLocals()](#clearCurrentThreadLocals--) | Rensar säkert heap‑minne från trådlokala instanser för den aktuella tråden. |
### MemoryCleaner() {#MemoryCleaner--}
```
public MemoryCleaner()
```


### clearKeepingFontSettings() {#clearKeepingFontSettings--}
```
public static void clearKeepingFontSettings()
```


Rensar heap‑minne från statiska PDF‑instansers (statisk och trådlokal) och tar bort alla temporära filer. Denna metod påverkar inte teckensnittsinställningarna.

### clear() {#clear--}
```
public static void clear()
```


Rensar heap‑minne från statiska PDF‑instansers (statisk och trådlokal) och tar bort alla temporära filer.

### clearStaticInstances() {#clearStaticInstances--}
```
public static void clearStaticInstances()
```


Rensar heap‑minne från statiska PDF‑instansers.

### clearAllTempFiles() {#clearAllTempFiles--}
```
public static void clearAllTempFiles()
```


Rensar temporära filer som skapats av GroupDocs.Viewer i systemets temporära katalog.

### clearFontRegistry() {#clearFontRegistry--}
```
public static void clearFontRegistry()
```


Rensar information i teckensnittsregistret från heap‑minnet.

### clearCurrentThreadLocals() {#clearCurrentThreadLocals--}
```
public static void clearCurrentThreadLocals()
```


Rensar säkert heap‑minne från trådlokala instanser för den aktuella tråden.

