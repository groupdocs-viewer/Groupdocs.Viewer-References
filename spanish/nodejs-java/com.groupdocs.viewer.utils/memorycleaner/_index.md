---
title: "MemoryCleaner"
second_title: "Referencia de API de GroupDocs.Viewer para Node.js vía Java"
description: "Limpia diferentes recursos para liberar memoria."
type: docs
weight: 10
url: /es/nodejs-java/com.groupdocs.viewer.utils/memorycleaner/
---
**Inheritance:**
java.lang.Object
```
public final class MemoryCleaner
```

Limpia diferentes recursos para liberar memoria.

Esta clase proporciona métodos para liberar memoria del heap, eliminar archivos temporales y borrar la información del registro de fuentes. También incluye un método para limpiar de forma segura las instancias locales del hilo para el hilo actual.

Ejemplo de uso:

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
## Constructores

| Constructor | Descripción |
| --- | --- |
| [MemoryCleaner()](#MemoryCleaner--) |  |
## Métodos

| Método | Descripción |
| --- | --- |
| [clearKeepingFontSettings()](#clearKeepingFontSettings--) | Libera la memoria del heap de instancias PDF estáticas (static y threadLocal) y elimina todos los archivos temporales. |
| [clear()](#clear--) | Libera la memoria del heap de instancias PDF estáticas (static y threadLocal) y elimina todos los archivos temporales. |
| [clearStaticInstances()](#clearStaticInstances--) | Libera la memoria del heap de instancias PDF estáticas. |
| [clearAllTempFiles()](#clearAllTempFiles--) | Elimina los archivos temporales creados por GroupDocs.Viewer en el directorio temporal del sistema. |
| [clearFontRegistry()](#clearFontRegistry--) | Borra la información del registro de fuentes de la memoria del heap. |
| [clearCurrentThreadLocals()](#clearCurrentThreadLocals--) | Limpia de forma segura la memoria del heap de instancias locales del hilo para el hilo actual. |
### MemoryCleaner() {#MemoryCleaner--}
```
public MemoryCleaner()
```


### clearKeepingFontSettings() {#clearKeepingFontSettings--}
```
public static void clearKeepingFontSettings()
```


Libera la memoria del heap de instancias PDF estáticas (static y threadLocal) y elimina todos los archivos temporales. Este método no afecta la configuración de fuentes.

### clear() {#clear--}
```
public static void clear()
```


Libera la memoria del heap de instancias PDF estáticas (static y threadLocal) y elimina todos los archivos temporales.

### clearStaticInstances() {#clearStaticInstances--}
```
public static void clearStaticInstances()
```


Libera la memoria del heap de instancias PDF estáticas.

### clearAllTempFiles() {#clearAllTempFiles--}
```
public static void clearAllTempFiles()
```


Elimina los archivos temporales creados por GroupDocs.Viewer en el directorio temporal del sistema.

### clearFontRegistry() {#clearFontRegistry--}
```
public static void clearFontRegistry()
```


Borra la información del registro de fuentes de la memoria del heap.

### clearCurrentThreadLocals() {#clearCurrentThreadLocals--}
```
public static void clearCurrentThreadLocals()
```


Limpia de forma segura la memoria del heap de instancias locales del hilo para el hilo actual.

