---
title: "MemoryCleaner"
second_title: "GroupDocs.Viewer for Java API Reference"
description: "메모리를 해제하기 위해 다양한 리소스를 정리합니다."
type: docs
weight: 12
url: /ko/java/com.groupdocs.viewer.utils/memorycleaner/
---
**Inheritance:**
java.lang.Object
```
public final class MemoryCleaner
```

메모리를 해제하기 위해 다양한 리소스를 정리합니다.


이 클래스는 힙 메모리를 정리하고, 임시 파일을 삭제하며, 폰트 레지스트리 정보를 정리하는 메서드를 제공합니다.
또한 현재 스레드에 대한 스레드 로컬 인스턴스를 안전하게 정리하는 메서드를 포함합니다.


사용 예시:

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


## 생성자

| 생성자 | 설명 |
| --- | --- |
| [MemoryCleaner()](#MemoryCleaner--) |  |
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [clearKeepingFontSettings()](#clearKeepingFontSettings--) | 정적 PDF 인스턴스(static 및 threadLocal)에서 힙 메모리를 정리하고 모든 임시 파일을 삭제합니다. |
|
|  | [clear()](#clear--) | 정적 PDF 인스턴스(static 및 threadLocal)에서 힙 메모리를 정리하고 모든 임시 파일을 삭제합니다. |
|
|  | [clearStaticInstances()](#clearStaticInstances--) | 정적 PDF 인스턴스에서 힙 메모리를 정리합니다. |
|
|  | [clearAllTempFiles()](#clearAllTempFiles--) | 시스템 임시 디렉터리에서 GroupDocs.Viewer가 만든 임시 파일을 정리합니다. |
|
|  | [clearFontRegistry()](#clearFontRegistry--) | 힙 메모리에서 폰트 레지스트리 정보를 정리합니다. |
|
|  | [clearCurrentThreadLocals()](#clearCurrentThreadLocals--) | 현재 스레드에 대한 스레드 로컬 인스턴스에서 힙 메모리를 안전하게 정리합니다. |
|
### MemoryCleaner() {#MemoryCleaner--}
```
public MemoryCleaner()
```


### clearKeepingFontSettings() {#clearKeepingFontSettings--}
```
public static void clearKeepingFontSettings()
```


정적 PDF 인스턴스(static 및 threadLocal)에서 힙 메모리를 정리하고 모든 임시 파일을 삭제합니다.
이 메서드는 폰트 설정에 영향을 주지 않습니다.


### clear() {#clear--}
```
public static void clear()
```


정적 PDF 인스턴스(static 및 threadLocal)에서 힙 메모리를 정리하고 모든 임시 파일을 삭제합니다.


### clearStaticInstances() {#clearStaticInstances--}
```
public static void clearStaticInstances()
```


정적 PDF 인스턴스에서 힙 메모리를 정리합니다.


### clearAllTempFiles() {#clearAllTempFiles--}
```
public static void clearAllTempFiles()
```


시스템 임시 디렉터리에서 GroupDocs.Viewer가 만든 임시 파일을 정리합니다.


### clearFontRegistry() {#clearFontRegistry--}
```
public static void clearFontRegistry()
```


힙 메모리에서 폰트 레지스트리 정보를 정리합니다.


### clearCurrentThreadLocals() {#clearCurrentThreadLocals--}
```
public static void clearCurrentThreadLocals()
```


현재 스레드에 대한 스레드 로컬 인스턴스에서 힙 메모리를 안전하게 정리합니다.


