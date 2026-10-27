---
title: "MemoryCleaner"
second_title: "GroupDocs.Viewer для Node.js через Java API Reference"
description: "Очищает различные ресурсы для освобождения памяти."
type: docs
weight: 10
url: /ru/nodejs-java/com.groupdocs.viewer.utils/memorycleaner/
---
**Inheritance:**
java.lang.Object
```
public final class MemoryCleaner
```

Очищает различные ресурсы для освобождения памяти.

Этот класс предоставляет методы для очистки памяти кучи, удаления временных файлов и очистки информации реестра шрифтов. Он также включает метод для безопасной очистки потоково-локальных экземпляров текущего потока.

Пример использования:

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
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [MemoryCleaner()](#MemoryCleaner--) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [clearKeepingFontSettings()](#clearKeepingFontSettings--) | Очищает память кучи от статических PDF‑экземпляров (static и threadLocal) и удаляет все временные файлы. |
| [clear()](#clear--) | Очищает память кучи от статических PDF‑экземпляров (static и threadLocal) и удаляет все временные файлы. |
| [clearStaticInstances()](#clearStaticInstances--) | Очищает память кучи от статических PDF‑экземпляров. |
| [clearAllTempFiles()](#clearAllTempFiles--) | Очищает временные файлы, созданные GroupDocs.Viewer, в системном временном каталоге. |
| [clearFontRegistry()](#clearFontRegistry--) | Очищает информацию реестра шрифтов из памяти кучи. |
| [clearCurrentThreadLocals()](#clearCurrentThreadLocals--) | Безопасно очищает память кучи от потоково‑локальных экземпляров текущего потока. |
### MemoryCleaner() {#MemoryCleaner--}
```
public MemoryCleaner()
```


### clearKeepingFontSettings() {#clearKeepingFontSettings--}
```
public static void clearKeepingFontSettings()
```


Очищает память кучи от статических PDF‑экземпляров (static и threadLocal) и удаляет все временные файлы. Этот метод не влияет на настройки шрифтов.

### clear() {#clear--}
```
public static void clear()
```


Очищает память кучи от статических PDF‑экземпляров (static и threadLocal) и удаляет все временные файлы.

### clearStaticInstances() {#clearStaticInstances--}
```
public static void clearStaticInstances()
```


Очищает память кучи от статических PDF‑экземпляров.

### clearAllTempFiles() {#clearAllTempFiles--}
```
public static void clearAllTempFiles()
```


Очищает временные файлы, созданные GroupDocs.Viewer, в системном временном каталоге.

### clearFontRegistry() {#clearFontRegistry--}
```
public static void clearFontRegistry()
```


Очищает информацию реестра шрифтов из памяти кучи.

### clearCurrentThreadLocals() {#clearCurrentThreadLocals--}
```
public static void clearCurrentThreadLocals()
```


Безопасно очищает память кучи от потоково‑локальных экземпляров текущего потока.

