---
title: "MemoryCleaner"
second_title: "GroupDocs.Viewer Java için API Referansı"
description: "Belleği serbest bırakmak için farklı kaynakları temizler."
type: docs
weight: 12
url: /tr/java/com.groupdocs.viewer.utils/memorycleaner/
---
**Inheritance:**
java.lang.Object
```
public final class MemoryCleaner
```

Belleği serbest bırakmak için farklı kaynakları temizler.


Bu sınıf, yığın belleğini temizlemek, geçici dosyaları silmek ve yazı tipi kayıt bilgilerini temizlemek için yöntemler sağlar.
Ayrıca, geçerli iş parçacığı için iş parçacığı yerel örnekleri güvenli bir şekilde temizlemek için bir yöntem içerir.


Örnek kullanım:

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


## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [MemoryCleaner()](#MemoryCleaner--) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [clearKeepingFontSettings()](#clearKeepingFontSettings--) | Statik PDF örneklerinden (static ve threadLocal) yığın belleğini temizler ve tüm geçici dosyaları siler. |
|
|  | [clear()](#clear--) | Statik PDF örneklerinden (static ve threadLocal) yığın belleğini temizler ve tüm geçici dosyaları siler. |
|
|  | [clearStaticInstances()](#clearStaticInstances--) | Statik PDF örneklerinden yığın belleğini temizler. |
|
|  | [clearAllTempFiles()](#clearAllTempFiles--) | GroupDocs.Viewer tarafından sistem geçici dizininde oluşturulan geçici dosyaları temizler. |
|
|  | [clearFontRegistry()](#clearFontRegistry--) | Yazı tipi kayıt bilgilerini yığın belleğinden temizler. |
|
|  | [clearCurrentThreadLocals()](#clearCurrentThreadLocals--) | Geçerli iş parçacığı için iş parçacığı yerel örneklerden yığın belleğini güvenli bir şekilde temizler. |
|
### MemoryCleaner() {#MemoryCleaner--}
```
public MemoryCleaner()
```


### clearKeepingFontSettings() {#clearKeepingFontSettings--}
```
public static void clearKeepingFontSettings()
```


Statik PDF örneklerinden (static ve threadLocal) yığın belleğini temizler ve tüm geçici dosyaları siler.
Bu yöntem, yazı tipi ayarlarını etkilemez.


### clear() {#clear--}
```
public static void clear()
```


Statik PDF örneklerinden (static ve threadLocal) yığın belleğini temizler ve tüm geçici dosyaları siler.


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


Yazı tipi kayıt bilgilerini yığın belleğinden temizler.


### clearCurrentThreadLocals() {#clearCurrentThreadLocals--}
```
public static void clearCurrentThreadLocals()
```


Geçerli iş parçacığı için iş parçacığı yerel örneklerden yığın belleğini güvenli bir şekilde temizler.


