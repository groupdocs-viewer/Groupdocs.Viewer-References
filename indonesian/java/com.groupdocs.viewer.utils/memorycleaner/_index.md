---
title: "MemoryCleaner"
second_title: "Referensi API GroupDocs.Viewer for Java"
description: "Membersihkan berbagai sumber daya untuk membebaskan memori."
type: docs
weight: 12
url: /id/java/com.groupdocs.viewer.utils/memorycleaner/
---
**Inheritance:**
java.lang.Object
```
public final class MemoryCleaner
```

Membersihkan berbagai sumber daya untuk membebaskan memori.


Kelas ini menyediakan metode untuk membersihkan memori heap, menghapus file sementara, dan membersihkan informasi registri font.
Ini juga menyertakan metode untuk membersihkan instance thread-local secara aman untuk thread saat ini.


Contoh penggunaan:

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


## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [MemoryCleaner()](#MemoryCleaner--) |  |
## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [clearKeepingFontSettings()](#clearKeepingFontSettings--) | Membersihkan memori heap dari instance PDF statis (statis dan threadLocal) dan menghapus semua file sementara. |
|
|  | [clear()](#clear--) | Membersihkan memori heap dari instance PDF statis (statis dan threadLocal) dan menghapus semua file sementara. |
|
|  | [clearStaticInstances()](#clearStaticInstances--) | Membersihkan memori heap dari instance PDF statis. |
|
|  | [clearAllTempFiles()](#clearAllTempFiles--) | Menghapus file sementara yang dibuat oleh GroupDocs.Viewer di direktori sementara sistem. |
|
|  | [clearFontRegistry()](#clearFontRegistry--) | Membersihkan informasi registri font dari memori heap. |
|
|  | [clearCurrentThreadLocals()](#clearCurrentThreadLocals--) | Membersihkan memori heap secara aman dari instance thread-local untuk thread saat ini. |
|
### MemoryCleaner() {#MemoryCleaner--}
```
public MemoryCleaner()
```


### clearKeepingFontSettings() {#clearKeepingFontSettings--}
```
public static void clearKeepingFontSettings()
```


Membersihkan memori heap dari instance PDF statis (statis dan threadLocal) dan menghapus semua file sementara.
Metode ini tidak memengaruhi pengaturan font.


### clear() {#clear--}
```
public static void clear()
```


Membersihkan memori heap dari instance PDF statis (statis dan threadLocal) dan menghapus semua file sementara.


### clearStaticInstances() {#clearStaticInstances--}
```
public static void clearStaticInstances()
```


Membersihkan memori heap dari instance PDF statis.


### clearAllTempFiles() {#clearAllTempFiles--}
```
public static void clearAllTempFiles()
```


Menghapus file sementara yang dibuat oleh GroupDocs.Viewer di direktori sementara sistem.


### clearFontRegistry() {#clearFontRegistry--}
```
public static void clearFontRegistry()
```


Membersihkan informasi registri font dari memori heap.


### clearCurrentThreadLocals() {#clearCurrentThreadLocals--}
```
public static void clearCurrentThreadLocals()
```


Membersihkan memori heap secara aman dari instance thread-local untuk thread saat ini.


