---
title: "FileLogger"
second_title: "GroupDocs.Viewer için Node.js üzerinden Java API Referansı"
description: "Günlük mesajlarını bir dosyaya yazar."
type: docs
weight: 10
url: /tr/nodejs-java/com.groupdocs.viewer.logging/filelogger/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.groupdocs.foundation.logging.ILogger
```
public class FileLogger implements ILogger
```

Günlük mesajlarını bir dosyaya yazar.

FileLogger sınıfı, günlük mesajlarını bir dosyaya yazma işlevselliği sağlar. ILogger arayüzünü uygular ve bir uygulamada çeşitli olayları ve mesajları günlüğe kaydetmek için kullanılabilir. Günlük mesajları belirtilen dosyaya yazılır.

Örnek kullanım:

```

 // Create a new instance of FileLogger with the specified log file path
 FileLogger fileLogger = new FileLogger("/path/to/logfile.txt");

 // Log an informational message
 fileLogger.debug("Debug message");

 // Log an error message
 fileLogger.error("Error message");

 // Check is logging warning messages enabled
 boolean warningEnabled = fileLogger.isWarningEnabled();
 
```

***Note:** The  FileLogger  class provides basic logging functionality. You can extend this class to add custom log levels or additional logging features as per your requirements.*
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [FileLogger(String fileName)](#FileLogger-java.lang.String-) | Sağlanan dosya adıyla belirtilen bir dosyaya mesajları kaydeden bir logger oluşturur. |
| [FileLogger(String fileName, boolean isTraceEnabled, boolean isDebugEnabled, boolean isWarningEnabled, boolean isErrorEnabled)](#FileLogger-java.lang.String-boolean-boolean-boolean-boolean-) | Belirtilen günlük seviyeleriyle bir dosyaya mesajları kaydeden bir logger oluşturur. |
## Fields

| Field | Açıklama |
| --- | --- |
| [MESSAGE](#MESSAGE) |  |
| [EXCEPTION](#EXCEPTION) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [trace(String message, Object[] arguments)](#trace-java.lang.String-java.lang.Object...-) | Konsola bir izleme mesajı yazar. |
| [trace(Throwable throwable, String message, Object[] arguments)](#trace-java.lang.Throwable-java.lang.String-java.lang.Object...-) | Konsola bir izleme günlük mesajı yazar. |
| [isTraceEnabled()](#isTraceEnabled--) | İzleme seviyesinin günlükleme için etkin olup olmadığını kontrol eder. |
| [debug(String message, Object[] arguments)](#debug-java.lang.String-java.lang.Object...-) | Konsola bir hata ayıklama günlük mesajı yazar. |
| [debug(Throwable throwable, String message, Object[] arguments)](#debug-java.lang.Throwable-java.lang.String-java.lang.Object...-) | Konsola bir hata ayıklama günlük mesajı yazar. |
| [isDebugEnabled()](#isDebugEnabled--) | Hata ayıklama seviyesinin günlükleme için etkin olup olmadığını kontrol eder. |
| [warning(String message, Object[] arguments)](#warning-java.lang.String-java.lang.Object...-) | Konsola bir uyarı günlük mesajı yazar. |
| [warning(Throwable throwable, String message, Object[] arguments)](#warning-java.lang.Throwable-java.lang.String-java.lang.Object...-) | Konsola bir uyarı günlük mesajı yazar. |
| [isWarningEnabled()](#isWarningEnabled--) | Uyarı seviyesinin günlükleme için etkin olup olmadığını kontrol eder. |
| [error(String message, Object[] arguments)](#error-java.lang.String-java.lang.Object...-) | Konsola bir hata günlük mesajı yazar. |
| [error(Throwable throwable, String message, Object[] arguments)](#error-java.lang.Throwable-java.lang.String-java.lang.Object...-) | Konsola bir hata günlük mesajı yazar. |
| [isErrorEnabled()](#isErrorEnabled--) | Hata seviyesindeki günlüklemenin etkin olup olmadığını kontrol eder. |
### FileLogger(String fileName) {#FileLogger-java.lang.String-}
```
public FileLogger(String fileName)
```


Sağlanan dosya adıyla belirtilen bir dosyaya mesajları kaydeden bir logger oluşturur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fileName | java.lang.String | Tam dosya adı ve yolu. |

### FileLogger(String fileName, boolean isTraceEnabled, boolean isDebugEnabled, boolean isWarningEnabled, boolean isErrorEnabled) {#FileLogger-java.lang.String-boolean-boolean-boolean-boolean-}
```
public FileLogger(String fileName, boolean isTraceEnabled, boolean isDebugEnabled, boolean isWarningEnabled, boolean isErrorEnabled)
```


Belirtilen günlük seviyeleriyle bir dosyaya mesajları kaydeden bir logger oluşturur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fileName | java.lang.String | Tam dosya adı ve yolu. |
| isTraceEnabled | boolean | İzleme seviyesi günlük kaydının etkin olup olmadığını belirtir. |
| isDebugEnabled | boolean | Hata ayıklama seviyesi günlük kaydının etkin olup olmadığını belirtir. |
| isWarningEnabled | boolean | Uyarı seviyesi günlük kaydının etkin olup olmadığını belirtir. |
| isErrorEnabled | boolean | Hata seviyesi günlük kaydının etkin olup olmadığını belirtir. |

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


Konsola bir izleme mesajı yazar. İzleme günlük mesajları, uygulama akışı hakkında genellikle faydalı bilgiler sağlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| mesaj | java.lang.String | İzleme mesajı. |
| argümanlar | java.lang.Object[] | Mesajda değiştirilecek argümanlar. Geçiş sırasına göre \{\} yer tutucularını değiştireceklerdir. |

### trace(Throwable throwable, String message, Object[] arguments) {#trace-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public void trace(Throwable throwable, String message, Object[] arguments)
```


Konsola bir izleme günlük mesajı yazar. İzleme günlük mesajları, uygulama akışı hakkında genellikle faydalı bilgiler sağlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fırlatılabilir | java.lang.Throwable | İzleme günlük mesajıyla ilişkili istisna. |
| mesaj | java.lang.String | İzleme günlük mesajı. |
| argümanlar | java.lang.Object[] | Mesajda değiştirilecek argümanlar. Argümanlar, gönderildikleri sırada \{\} yer tutucularını değiştirecektir. |

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


Konsola bir hata ayıklama günlük mesajı yazar. Hata ayıklama günlük mesajları, uygulama akışındaki farklı süreçler hakkında bilgi sağlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| mesaj | java.lang.String | Hata ayıklama günlük mesajı. |
| argümanlar | java.lang.Object[] | Mesajda değiştirilecek argümanlar. Argümanlar, gönderildikleri sırada \{\} yer tutucularını değiştirecektir. |

### debug(Throwable throwable, String message, Object[] arguments) {#debug-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public void debug(Throwable throwable, String message, Object[] arguments)
```


Konsola bir hata ayıklama günlük mesajı yazar. Hata ayıklama günlük mesajları, uygulama akışındaki farklı süreçler hakkında bilgi sağlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fırlatılabilir | java.lang.Throwable | Hata ayıklama günlük mesajıyla ilişkili istisna. |
| mesaj | java.lang.String | Hata ayıklama günlük mesajı. |
| argümanlar | java.lang.Object[] | Mesajda değiştirilecek argümanlar. Argümanlar, gönderildikleri sırada \{\} yer tutucularını değiştirecektir. |

### isDebugEnabled() {#isDebugEnabled--}
```
public boolean isDebugEnabled()
```


Hata ayıklama seviyesinin günlükleme için etkin olup olmadığını kontrol eder.

**Returns:**
boolean -  true  hata ayıklama seviyesi etkinse,  false  aksi takdirde.
### warning(String message, Object[] arguments) {#warning-java.lang.String-java.lang.Object...-}
```
public void warning(String message, Object[] arguments)
```


Konsola bir uyarı günlük mesajı yazar. Uyarı günlük mesajları, uygulama akışındaki beklenmeyen ve kurtarılabilir olaylar hakkında bilgi sağlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| mesaj | java.lang.String | Uyarı günlük mesajı. |
| argümanlar | java.lang.Object[] | Mesajda değiştirilecek argümanlar. Argümanlar, gönderildikleri sırada \{\} yer tutucularını değiştirecektir. |

### warning(Throwable throwable, String message, Object[] arguments) {#warning-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public void warning(Throwable throwable, String message, Object[] arguments)
```


Konsola bir uyarı günlük mesajı yazar. Uyarı günlük mesajları, uygulama akışındaki beklenmeyen ve kurtarılabilir olaylar hakkında bilgi sağlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fırlatılabilir | java.lang.Throwable | Uyarı günlük mesajıyla ilişkili istisna. |
| mesaj | java.lang.String | Uyarı günlük mesajı. |
| argümanlar | java.lang.Object[] | Mesajda değiştirilecek argümanlar. Argümanlar, gönderildikleri sırada \{\} yer tutucularını değiştirecektir. |

### isWarningEnabled() {#isWarningEnabled--}
```
public boolean isWarningEnabled()
```


Uyarı seviyesinin günlükleme için etkin olup olmadığını kontrol eder.

**Returns:**
boolean -  true  uyarı seviyesi etkinse,  false  aksi takdirde.
### error(String message, Object[] arguments) {#error-java.lang.String-java.lang.Object...-}
```
public void error(String message, Object[] arguments)
```


Konsola bir hata günlük mesajı yazar. Hata günlük mesajları, uygulama akışındaki kurtarılamaz olaylar hakkında bilgi sağlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| mesaj | java.lang.String | Hata günlük mesajı. |
| argümanlar | java.lang.Object[] | Mesajda değiştirilecek argümanlar. Argümanlar, gönderildikleri sırada \{\} yer tutucularını değiştirecektir. |

### error(Throwable throwable, String message, Object[] arguments) {#error-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public void error(Throwable throwable, String message, Object[] arguments)
```


Konsola bir hata günlük mesajı yazar. Hata günlük mesajları, uygulama akışındaki kurtarılamaz olaylar hakkında bilgi sağlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fırlatılabilir | java.lang.Throwable | Hata günlük mesajıyla ilişkili istisna. |
| mesaj | java.lang.String | Hata günlük mesajı. |
| argümanlar | java.lang.Object[] | Mesajda değiştirilecek argümanlar. Argümanlar, gönderildikleri sırada \{\} yer tutucularını değiştirecektir. |

### isErrorEnabled() {#isErrorEnabled--}
```
public boolean isErrorEnabled()
```


Hata seviyesindeki günlüklemenin etkin olup olmadığını kontrol eder.

**Returns:**
boolean -  true  hata seviyesi günlük kaydı etkinse,  false  aksi takdirde.
