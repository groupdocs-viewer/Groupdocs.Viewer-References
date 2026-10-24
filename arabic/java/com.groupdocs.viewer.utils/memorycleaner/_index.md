---
title: "MemoryCleaner"
second_title: "GroupDocs.Viewer لـ Java مرجع API"
description: "ينظف موارد مختلفة لتحرير الذاكرة."
type: docs
weight: 12
url: /ar/java/com.groupdocs.viewer.utils/memorycleaner/
---
**Inheritance:**
java.lang.Object
```
public final class MemoryCleaner
```

ينظف موارد مختلفة لتحرير الذاكرة.


توفر هذه الفئة طرقًا لمسح ذاكرة الكومة، حذف الملفات المؤقتة، ومسح معلومات سجل الخطوط.
كما تتضمن طريقة لمسح مثيلات الخيط المحلي بأمان للخيط الحالي.


مثال على الاستخدام:

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


## المنشئات

| منشئ | الوصف |
| --- | --- |
| [MemoryCleaner()](#MemoryCleaner--) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [clearKeepingFontSettings()](#clearKeepingFontSettings--) | يمسح ذاكرة الكومة من مثيلات PDF الثابتة (ثابتة ومحلية الخيط) ويحذف جميع الملفات المؤقتة. |
|
|  | [clear()](#clear--) | يمسح ذاكرة الكومة من مثيلات PDF الثابتة (ثابتة ومحلية الخيط) ويحذف جميع الملفات المؤقتة. |
|
|  | [clearStaticInstances()](#clearStaticInstances--) | يمسح ذاكرة الكومة من مثيلات PDF الثابتة. |
|
|  | [clearAllTempFiles()](#clearAllTempFiles--) | يمسح الملفات المؤقتة التي أنشأها GroupDocs.Viewer في دليل الملفات المؤقتة للنظام. |
|
|  | [clearFontRegistry()](#clearFontRegistry--) | يمسح معلومات سجل الخطوط من ذاكرة الكومة. |
|
|  | [clearCurrentThreadLocals()](#clearCurrentThreadLocals--) | يمسح ذاكرة الكومة بأمان من مثيلات الخيط المحلي للخيط الحالي. |
|
### MemoryCleaner() {#MemoryCleaner--}
```
public MemoryCleaner()
```


### clearKeepingFontSettings() {#clearKeepingFontSettings--}
```
public static void clearKeepingFontSettings()
```


يمسح ذاكرة الكومة من مثيلات PDF الثابتة (ثابتة ومحلية الخيط) ويحذف جميع الملفات المؤقتة.
هذه الطريقة لا تؤثر على إعدادات الخط.


### clear() {#clear--}
```
public static void clear()
```


يمسح ذاكرة الكومة من مثيلات PDF الثابتة (ثابتة ومحلية الخيط) ويحذف جميع الملفات المؤقتة.


### clearStaticInstances() {#clearStaticInstances--}
```
public static void clearStaticInstances()
```


يمسح ذاكرة الكومة من مثيلات PDF الثابتة.


### clearAllTempFiles() {#clearAllTempFiles--}
```
public static void clearAllTempFiles()
```


يمسح الملفات المؤقتة التي أنشأها GroupDocs.Viewer في دليل الملفات المؤقتة للنظام.


### clearFontRegistry() {#clearFontRegistry--}
```
public static void clearFontRegistry()
```


يمسح معلومات سجل الخطوط من ذاكرة الكومة.


### clearCurrentThreadLocals() {#clearCurrentThreadLocals--}
```
public static void clearCurrentThreadLocals()
```


يمسح ذاكرة الكومة بأمان من مثيلات الخيط المحلي للخيط الحالي.


