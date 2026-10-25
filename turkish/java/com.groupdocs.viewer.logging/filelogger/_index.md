---
title: "FileLogger"
second_title: "GroupDocs.Viewer Java için API Referansı"
description: "Günlük mesajlarını bir dosyaya yazar."
type: docs
weight: 10
url: /tr/java/com.groupdocs.viewer.logging/filelogger/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.groupdocs.foundation.logging.ILogger
```
public class FileLogger implements ILogger
```

Günlük mesajlarını bir dosyaya yazar.


Bu
FileLogger
sınıf, günlük mesajlarını bir dosyaya yazma işlevselliği sağlar. ILogger arayüzünü uygular
ve bir uygulamada çeşitli olayları ve mesajları kaydetmek için kullanılabilir. Günlük mesajları belirtilen dosyaya yazılır.


Örnek kullanım:

````

 // Create a new instance of FileLogger with the specified log file path
 FileLogger fileLogger = new FileLogger("/path/to/logfile.txt");

 // Log an informational message
 fileLogger.debug("Debug message");

 // Log an error message
 fileLogger.error("Error message");

 // Check is logging warning messages enabled
 boolean warningEnabled = fileLogger.isWarningEnabled();
 
````


***Note:** The 
FileLogger
sınıf temel günlük işlevselliği sağlar.
Bu sınıfı, gereksinimlerinize göre özel günlük seviyeleri veya ek günlük özellikleri eklemek için genişletebilirsiniz.*

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
|  | [FileLogger(String fileName)](#FileLogger-java.lang.String-) | Sağlanan dosya adıyla belirtilen bir dosyaya mesajları kaydeden bir logger oluşturur. |
|
|  | [FileLogger(String fileName, boolean isTraceEnabled, boolean isDebugEnabled, boolean isWarningEnabled, boolean isErrorEnabled)](#FileLogger-java.lang.String-boolean-boolean-boolean-boolean-) | Belirtilen günlük seviyeleriyle bir dosyaya mesajları kaydeden bir logger oluşturur. |
|
## Alanlar

| Alan | Açıklama |
| --- | --- |
| [MESSAGE](#MESSAGE) |  |
| [EXCEPTION](#EXCEPTION) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [trace(String message, Object[] arguments)](#trace-java.lang.String-java.lang.Object...-) | Konsola bir izleme mesajı yazar. |
|
|  | [trace(Throwable throwable, String message, Object[] arguments)](#trace-java.lang.Throwable-java.lang.String-java.lang.Object...-) | Konsola bir izleme günlük mesajı yazar. |
|
|  | [isTraceEnabled()](#isTraceEnabled--) | İzleme seviyesinin günlükleme için etkin olup olmadığını kontrol eder. |
|
|  | [debug(String message, Object[] arguments)](#debug-java.lang.String-java.lang.Object...-) | Konsola bir hata ayıklama günlük mesajı yazar. |
|
|  | [debug(Throwable throwable, String message, Object[] arguments)](#debug-java.lang.Throwable-java.lang.String-java.lang.Object...-) | Konsola bir hata ayıklama günlük mesajı yazar. |
|
|  | [isDebugEnabled()](#isDebugEnabled--) | Hata ayıklama seviyesinin günlükleme için etkin olup olmadığını kontrol eder. |
|
|  | [warning(String message, Object[] arguments)](#warning-java.lang.String-java.lang.Object...-) | Konsola bir uyarı günlük mesajı yazar. |
|
|  | [warning(Throwable throwable, String message, Object[] arguments)](#warning-java.lang.Throwable-java.lang.String-java.lang.Object...-) | Konsola bir uyarı günlük mesajı yazar. |
|
|  | [isWarningEnabled()](#isWarningEnabled--) | Uyarı seviyesinin günlükleme için etkin olup olmadığını kontrol eder. |
|
|  | [error(String message, Object[] arguments)](#error-java.lang.String-java.lang.Object...-) | Konsola bir hata günlük mesajı yazar. |
|
|  | [error(Throwable throwable, String message, Object[] arguments)](#error-java.lang.Throwable-java.lang.String-java.lang.Object...-) | Konsola bir hata günlük mesajı yazar. |
|
|  | [isErrorEnabled()](#isErrorEnabled--) | Hata seviyesindeki günlüklemenin etkin olup olmadığını kontrol eder. |
|
### FileLogger(String fileName) {#FileLogger-java.lang.String-}
```
public FileLogger(String fileName)
```


Sağlanan dosya adıyla belirtilen bir dosyaya mesajları kaydeden bir logger oluşturur.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | fileName | java.lang.String | Tam dosya adı ve yol. |
|

### FileLogger(String fileName, boolean isTraceEnabled, boolean isDebugEnabled, boolean isWarningEnabled, boolean isErrorEnabled) {#FileLogger-java.lang.String-boolean-boolean-boolean-boolean-}
```
public FileLogger(String fileName, boolean isTraceEnabled, boolean isDebugEnabled, boolean isWarningEnabled, boolean isErrorEnabled)
```


Belirtilen günlük seviyeleriyle bir dosyaya mesajları kaydeden bir logger oluşturur.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | fileName | java.lang.String | Tam dosya adı ve yol. |
|
|  | isTraceEnabled | boolean | İzleme seviyesi günlük kaydının etkin olup olmadığını belirtir. |
|
|  | isDebugEnabled | boolean | Hata ayıklama seviyesi günlük kaydının etkin olup olmadığını belirtir. |
|
|  | isWarningEnabled | boolean | Uyarı seviyesi günlük kaydının etkin olup olmadığını belirtir. |
|
|  | isErrorEnabled | boolean | Hata seviyesi günlük kaydının etkin olup olmadığını belirtir. |
|

### MESSAGE {#MESSAGE}
```
public static final String MESSAGE
```


### EXCEPTION {#EXCEPTION}
```
public static final String EXCEPTION
```


### trace(String message, Object[] arguments) {#trace-java.lang.String-java.lang.Object...-}
```
public void trace(String message, Object[] arguments)
```


Konsola bir izleme mesajı yazar.
İzleme günlük mesajları, uygulama akışı hakkında genel olarak faydalı bilgiler sağlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | message | java.lang.String | İzleme mesajı. |
|
|  | argümanlar | java.lang.Object[] | Mesajda değiştirilecek argümanlar. {} yer tutucularını, geçiş sırasına göre değiştireceklerdir. |
|

### trace(Throwable throwable, String message, Object[] arguments) {#trace-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public void trace(Throwable throwable, String message, Object[] arguments)
```


Konsola bir izleme günlük mesajı yazar.
İzleme günlük mesajları, uygulama akışı hakkında genel olarak faydalı bilgiler sağlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | throwable | java.lang.Throwable | İzleme günlük mesajıyla ilişkili istisna. |
|
|  | message | java.lang.String | İzleme günlük mesajı. |
|
|  | argümanlar | java.lang.Object[] | Mesajda değiştirilecek argümanlar. {} yer tutucularını, geçildiği sıraya göre değiştireceklerdir. |
|

### isTraceEnabled() {#isTraceEnabled--}
```
public boolean isTraceEnabled()
```


İzleme seviyesinin günlükleme için etkin olup olmadığını kontrol eder.


**Returns:**
boolean -  true  izleme seviyesi etkinse,  false  aksi takdirde.

### debug(String message, Object[] arguments) {#debug-java.lang.String-java.lang.Object...-}
```
public void debug(String message, Object[] arguments)
```


Konsola bir hata ayıklama günlük mesajı yazar.
Hata ayıklama günlük mesajları, uygulama akışındaki farklı süreçler hakkında bilgi sağlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | message | java.lang.String | Hata ayıklama günlük mesajı. |
|
|  | argümanlar | java.lang.Object[] | Mesajda değiştirilecek argümanlar. {} yer tutucularını, geçildiği sıraya göre değiştireceklerdir. |
|

### debug(Throwable throwable, String message, Object[] arguments) {#debug-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public void debug(Throwable throwable, String message, Object[] arguments)
```


Konsola bir hata ayıklama günlük mesajı yazar.
Hata ayıklama günlük mesajları, uygulama akışındaki farklı süreçler hakkında bilgi sağlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | throwable | java.lang.Throwable | Debug günlük mesajıyla ilişkili istisna. |
|
|  | message | java.lang.String | Hata ayıklama günlük mesajı. |
|
|  | argümanlar | java.lang.Object[] | Mesajda değiştirilecek argümanlar. {} yer tutucularını, geçildiği sıraya göre değiştireceklerdir. |
|

### isDebugEnabled() {#isDebugEnabled--}
```
public boolean isDebugEnabled()
```


Hata ayıklama seviyesinin günlükleme için etkin olup olmadığını kontrol eder.


**Returns:**
boolean -  true  eğer debug seviyesi etkinse,  false  aksi takdirde.

### warning(String message, Object[] arguments) {#warning-java.lang.String-java.lang.Object...-}
```
public void warning(String message, Object[] arguments)
```


Konsola bir uyarı günlük mesajı yazar.
Uyarı günlük mesajları, uygulama akışındaki beklenmeyen ve kurtarılabilir olaylar hakkında bilgi sağlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | message | java.lang.String | Uyarı günlük mesajı. |
|
|  | argümanlar | java.lang.Object[] | Mesajda değiştirilecek argümanlar. {} yer tutucularını, geçildiği sıraya göre değiştireceklerdir. |
|

### warning(Throwable throwable, String message, Object[] arguments) {#warning-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public void warning(Throwable throwable, String message, Object[] arguments)
```


Konsola bir uyarı günlük mesajı yazar.
Uyarı günlük mesajları, uygulama akışındaki beklenmeyen ve kurtarılabilir olaylar hakkında bilgi sağlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | throwable | java.lang.Throwable | Uyarı günlük mesajıyla ilişkili istisna. |
|
|  | message | java.lang.String | Uyarı günlük mesajı. |
|
|  | argümanlar | java.lang.Object[] | Mesajda değiştirilecek argümanlar. {} yer tutucularını, geçildiği sıraya göre değiştireceklerdir. |
|

### isWarningEnabled() {#isWarningEnabled--}
```
public boolean isWarningEnabled()
```


Uyarı seviyesinin günlükleme için etkin olup olmadığını kontrol eder.


**Returns:**
boolean -  true  eğer uyarı seviyesi etkinse,  false  aksi takdirde.

### error(String message, Object[] arguments) {#error-java.lang.String-java.lang.Object...-}
```
public void error(String message, Object[] arguments)
```


Konsola bir hata günlük mesajı yazar.
Hata günlük mesajları, uygulama akışındaki kurtarılamaz olaylar hakkında bilgi sağlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | message | java.lang.String | Hata günlük mesajı. |
|
|  | argümanlar | java.lang.Object[] | Mesajda değiştirilecek argümanlar. {} yer tutucularını, geçildiği sıraya göre değiştireceklerdir. |
|

### error(Throwable throwable, String message, Object[] arguments) {#error-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public void error(Throwable throwable, String message, Object[] arguments)
```


Konsola bir hata günlük mesajı yazar.
Hata günlük mesajları, uygulama akışındaki kurtarılamaz olaylar hakkında bilgi sağlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | throwable | java.lang.Throwable | Hata günlük mesajıyla ilişkili istisna. |
|
|  | message | java.lang.String | Hata günlük mesajı. |
|
|  | argümanlar | java.lang.Object[] | Mesajda değiştirilecek argümanlar. {} yer tutucularını, geçildiği sıraya göre değiştireceklerdir. |
|

### isErrorEnabled() {#isErrorEnabled--}
```
public boolean isErrorEnabled()
```


Hata seviyesindeki günlüklemenin etkin olup olmadığını kontrol eder.


**Returns:**
boolean -  true  eğer hata seviyesi günlük kaydı etkinse,  false  aksi takdirde.

