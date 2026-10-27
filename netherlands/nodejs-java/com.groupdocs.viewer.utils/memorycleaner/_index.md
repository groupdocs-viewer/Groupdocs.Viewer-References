---
title: "MemoryCleaner"
second_title: "GroupDocs.Viewer voor Node.js via Java API-referentie"
description: "Schoont verschillende bronnen op om geheugen vrij te maken."
type: docs
weight: 10
url: /nl/nodejs-java/com.groupdocs.viewer.utils/memorycleaner/
---
**Inheritance:**
java.lang.Object
```
public final class MemoryCleaner
```

Schoont verschillende bronnen op om geheugen vrij te maken.

Deze klasse biedt methoden om heap‑geheugen te wissen, tijdelijke bestanden te verwijderen en informatie over het lettertype‑register te wissen. Het bevat ook een methode om thread‑lokale instanties voor de huidige thread veilig te wissen.

Voorbeeldgebruik:

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

| Constructor | Beschrijving |
| --- | --- |
| [MemoryCleaner()](#MemoryCleaner--) |  |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [clearKeepingFontSettings()](#clearKeepingFontSettings--) | Wist heap‑geheugen van statische PDF‑instanties (static en threadLocal) en verwijdert alle tijdelijke bestanden. |
| [clear()](#clear--) | Wist heap‑geheugen van statische PDF‑instanties (static en threadLocal) en verwijdert alle tijdelijke bestanden. |
| [clearStaticInstances()](#clearStaticInstances--) | Wist heap‑geheugen van statische PDF‑instanties. |
| [clearAllTempFiles()](#clearAllTempFiles--) | Verwijdert tijdelijke bestanden die door GroupDocs.Viewer zijn aangemaakt in de systeem‑tijdelijke map. |
| [clearFontRegistry()](#clearFontRegistry--) | Wist informatie over het lettertype‑register uit het heap‑geheugen. |
| [clearCurrentThreadLocals()](#clearCurrentThreadLocals--) | Wist heap‑geheugen veilig van thread‑lokale instanties voor de huidige thread. |
### MemoryCleaner() {#MemoryCleaner--}
```
public MemoryCleaner()
```


### clearKeepingFontSettings() {#clearKeepingFontSettings--}
```
public static void clearKeepingFontSettings()
```


Wist heap‑geheugen van statische PDF‑instanties (static en threadLocal) en verwijdert alle tijdelijke bestanden. Deze methode heeft geen invloed op de lettertype‑instellingen.

### clear() {#clear--}
```
public static void clear()
```


Wist heap‑geheugen van statische PDF‑instanties (static en threadLocal) en verwijdert alle tijdelijke bestanden.

### clearStaticInstances() {#clearStaticInstances--}
```
public static void clearStaticInstances()
```


Wist heap‑geheugen van statische PDF‑instanties.

### clearAllTempFiles() {#clearAllTempFiles--}
```
public static void clearAllTempFiles()
```


Verwijdert tijdelijke bestanden die door GroupDocs.Viewer zijn aangemaakt in de systeem‑tijdelijke map.

### clearFontRegistry() {#clearFontRegistry--}
```
public static void clearFontRegistry()
```


Wist informatie over het lettertype‑register uit het heap‑geheugen.

### clearCurrentThreadLocals() {#clearCurrentThreadLocals--}
```
public static void clearCurrentThreadLocals()
```


Wist heap‑geheugen veilig van thread‑lokale instanties voor de huidige thread.

