---
title: "MemoryCleaner"
second_title: "GroupDocs.Viewer لـ Node.js عبر مرجع API للجاڤا"
description: "ينظف موارد مختلفة لتحرير الذاكرة."
type: docs
weight: 10
url: /ar/nodejs-java/com.groupdocs.viewer.utils/memorycleaner/
---
**Inheritance:**
java.lang.Object
```
public final class MemoryCleaner
```

ينظف موارد مختلفة لتحرير الذاكرة.

هذه الفئة توفر طرقًا لمسح heap memory، حذف temp files، ومسح معلومات font registry. كما تتضمن طريقة لمسح مثيلات thread-local بأمان للخط الحالي.

مثال على الاستخدام:

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
## المُنشئات

| المُنشئ | الوصف |
| --- | --- |
| [MemoryCleaner()](#MemoryCleaner--) |  |
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [clearKeepingFontSettings()](#clearKeepingFontSettings--) | يمسح heap memory من مثيلات PDF الثابتة (static و threadLocal) ويحذف جميع temp files. |
| [clear()](#clear--) | يمسح heap memory من مثيلات PDF الثابتة (static و threadLocal) ويحذف جميع temp files. |
| [clearStaticInstances()](#clearStaticInstances--) | يمسح heap memory من مثيلات PDF الثابتة. |
| [clearAllTempFiles()](#clearAllTempFiles--) | يمسح temp files التي أنشأتها GroupDocs.Viewer في دليل temp النظام. |
| [clearFontRegistry()](#clearFontRegistry--) | يمسح معلومات font registry من heap memory. |
| [clearCurrentThreadLocals()](#clearCurrentThreadLocals--) | يمسح heap memory بأمان من مثيلات thread-local للخط الحالي. |
### MemoryCleaner() {#MemoryCleaner--}
```
public MemoryCleaner()
```


### clearKeepingFontSettings() {#clearKeepingFontSettings--}
```
public static void clearKeepingFontSettings()
```


يمسح heap memory من مثيلات PDF الثابتة (static و threadLocal) ويحذف جميع temp files. لا تؤثر هذه الطريقة على إعدادات الخط.

### clear() {#clear--}
```
public static void clear()
```


يمسح heap memory من مثيلات PDF الثابتة (static و threadLocal) ويحذف جميع temp files.

### clearStaticInstances() {#clearStaticInstances--}
```
public static void clearStaticInstances()
```


يمسح heap memory من مثيلات PDF الثابتة.

### clearAllTempFiles() {#clearAllTempFiles--}
```
public static void clearAllTempFiles()
```


يمسح temp files التي أنشأتها GroupDocs.Viewer في دليل temp النظام.

### clearFontRegistry() {#clearFontRegistry--}
```
public static void clearFontRegistry()
```


يمسح معلومات font registry من heap memory.

### clearCurrentThreadLocals() {#clearCurrentThreadLocals--}
```
public static void clearCurrentThreadLocals()
```


يمسح heap memory بأمان من مثيلات thread-local للخط الحالي.

