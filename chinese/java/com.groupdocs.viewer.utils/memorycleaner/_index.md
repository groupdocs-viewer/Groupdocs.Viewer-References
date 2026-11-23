---
title: "MemoryCleaner"
second_title: "GroupDocs.Viewer for Java API 参考"
description: "清理各种资源以释放内存。"
type: docs
weight: 12
url: /zh/java/com.groupdocs.viewer.utils/memorycleaner/
---
**Inheritance:**
java.lang.Object
```
public final class MemoryCleaner
```

清理各种资源以释放内存。


此类提供用于清除堆内存、删除临时文件以及清除字体注册信息的方法。
它还包括一个方法，用于安全地清除当前线程的线程本地实例。


示例用法：

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


## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [MemoryCleaner()](#MemoryCleaner--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [clearKeepingFontSettings()](#clearKeepingFontSettings--) | 清除来自静态 PDF 实例（static 和 threadLocal）的堆内存并删除所有临时文件。 |
|
|  | [clear()](#clear--) | 清除来自静态 PDF 实例（static 和 threadLocal）的堆内存并删除所有临时文件。 |
|
|  | [clearStaticInstances()](#clearStaticInstances--) | 清除来自静态 PDF 实例的堆内存。 |
|
|  | [clearAllTempFiles()](#clearAllTempFiles--) | 清除 GroupDocs.Viewer 在系统临时目录中创建的临时文件。 |
|
|  | [clearFontRegistry()](#clearFontRegistry--) | 从堆内存中清除字体注册信息。 |
|
|  | [clearCurrentThreadLocals()](#clearCurrentThreadLocals--) | 安全地清除当前线程的线程本地实例中的堆内存。 |
|
### MemoryCleaner() {#MemoryCleaner--}
```
public MemoryCleaner()
```


### clearKeepingFontSettings() {#clearKeepingFontSettings--}
```
public static void clearKeepingFontSettings()
```


清除来自静态 PDF 实例（static 和 threadLocal）的堆内存并删除所有临时文件。
此方法不影响字体设置。


### clear() {#clear--}
```
public static void clear()
```


清除来自静态 PDF 实例（static 和 threadLocal）的堆内存并删除所有临时文件。


### clearStaticInstances() {#clearStaticInstances--}
```
public static void clearStaticInstances()
```


清除来自静态 PDF 实例的堆内存。


### clearAllTempFiles() {#clearAllTempFiles--}
```
public static void clearAllTempFiles()
```


清除 GroupDocs.Viewer 在系统临时目录中创建的临时文件。


### clearFontRegistry() {#clearFontRegistry--}
```
public static void clearFontRegistry()
```


从堆内存中清除字体注册信息。


### clearCurrentThreadLocals() {#clearCurrentThreadLocals--}
```
public static void clearCurrentThreadLocals()
```


安全地清除当前线程的线程本地实例中的堆内存。


