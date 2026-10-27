---
title: "MemoryCleaner"
second_title: "GroupDocs.Viewer için Node.js üzerinden Java API Referansı"
description: "Farklı kaynakları temizleyerek belleği serbest bırakır."
type: docs
weight: 10
url: /tr/nodejs-java/com.groupdocs.viewer.utils/memorycleaner/
---
**Inheritance:**
java.lang.Object
```
public final class MemoryCleaner
```

Farklı kaynakları temizleyerek belleği serbest bırakır.

Bu sınıf, yığın belleğini temizleme, geçici dosyaları silme ve yazı tipi kayıt bilgilerini temizleme yöntemleri sağlar. Ayrıca mevcut iş parçacığı için iş parçacığı yerel örneklerini güvenli bir şekilde temizleyen bir yöntem içerir.

Örnek kullanım:

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
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [MemoryCleaner()](#MemoryCleaner--) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [clearKeepingFontSettings()](#clearKeepingFontSettings--) | Statik PDF örneklerinden (statik ve threadLocal) yığın belleğini temizler ve tüm geçici dosyaları siler. |
| [clear()](#clear--) | Statik PDF örneklerinden (statik ve threadLocal) yığın belleğini temizler ve tüm geçici dosyaları siler. |
| [clearStaticInstances()](#clearStaticInstances--) | Statik PDF örneklerinden yığın belleğini temizler. |
| [clearAllTempFiles()](#clearAllTempFiles--) | GroupDocs.Viewer tarafından sistem geçici dizininde oluşturulan geçici dosyaları temizler. |
| [clearFontRegistry()](#clearFontRegistry--) | Yığın belleğinden yazı tipi kayıt bilgilerini temizler. |
| [clearCurrentThreadLocals()](#clearCurrentThreadLocals--) | Mevcut iş parçacığı için iş parçacığı yerel örneklerinden yığın belleğini güvenli bir şekilde temizler. |
### MemoryCleaner() {#MemoryCleaner--}
```
public MemoryCleaner()
```


### clearKeepingFontSettings() {#clearKeepingFontSettings--}
```
public static void clearKeepingFontSettings()
```


Statik PDF örneklerinden (statik ve threadLocal) yığın belleğini temizler ve tüm geçici dosyaları siler. Bu yöntem yazı tipi ayarlarını etkilemez.

### clear() {#clear--}
```
public static void clear()
```


Statik PDF örneklerinden (statik ve threadLocal) yığın belleğini temizler ve tüm geçici dosyaları siler.

### clearStaticInstances() {#clearStaticInstances--}
```
public static void clearStaticInstances()
```


Statik PDF örneklerinden yığın belleğini temizler.

### clearAllTempFiles() {#clearAllTempFiles--}
```
public static void clearAllTempFiles()
```


GroupDocs.Viewer tarafından sistem geçici dizininde oluşturulan geçici dosyaları temizler.

### clearFontRegistry() {#clearFontRegistry--}
```
public static void clearFontRegistry()
```


Yığın belleğinden yazı tipi kayıt bilgilerini temizler.

### clearCurrentThreadLocals() {#clearCurrentThreadLocals--}
```
public static void clearCurrentThreadLocals()
```


Mevcut iş parçacığı için iş parçacığı yerel örneklerinden yığın belleğini güvenli bir şekilde temizler.

