---
title: "ViewerLogger"
second_title: "GroupDocs.Viewer için Node.js üzerinden Java API Referansı"
description: "Genel görüntüleyici günlüğü."
type: docs
weight: 11
url: /tr/nodejs-java/com.groupdocs.viewer.logging/viewerlogger/
---
**Inheritance:**
java.lang.Object
```
public class ViewerLogger
```

Genel görüntüleyici günlüğü.

ViewerLogger sınıfı, mesajları entegre bir ya da kullanıcı tanımlı bir kaydediciye kaydetme işlevi sağlar. Görüntüleyici modülü için küresel kaydedici olarak hizmet verir ve çeşitli olayları ve mesajları kaydetmek için kullanılabilir.

Örnek kullanım:

```

 // Configure the viewer logger to use the default integrated logger
 ViewerLogger.setLogger(new FileLogger("/path/to/file.log"));

 // Log an debug message
 ViewerLogger.debug("Debug message");

 // Log an error message
 ViewerLogger.error("Error message");
 
```

***Note:** The  ViewerLogger  class can be configured to use a custom logger implementation by calling the [setLogger(ILogger)](../../com.groupdocs.viewer.logging/viewerlogger\#setLogger-ILogger-) method. By default, it uses the integrated logger provided by the viewer module.*
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [ViewerLogger()](#ViewerLogger--) |  |
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
| [getLogger()](#getLogger--) | Mesajları günlüğe kaydetmek için kullanılacak kaydedici örneğini alır. |
| [setLogger(ILogger logger)](#setLogger-com.groupdocs.foundation.logging.ILogger-) | Mesajları günlüğe kaydetmek için kullanılacak kaydedici örneğini ayarlar. |
### ViewerLogger() {#ViewerLogger--}
```
public ViewerLogger()
```


### trace(String message, Object[] arguments) {#trace-java.lang.String-java.lang.Object...-}
```
public static void trace(String message, Object[] arguments)
```


Konsola bir izleme mesajı yazar. İzleme günlük mesajları, uygulama akışı hakkında genellikle faydalı bilgiler sağlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| mesaj | java.lang.String | İzleme mesajı. |
| argümanlar | java.lang.Object[] | Mesajda değiştirilecek argümanlar. Geçiş sırasına göre \{\} yer tutucularını değiştireceklerdir. |

### trace(Throwable throwable, String message, Object[] arguments) {#trace-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public static void trace(Throwable throwable, String message, Object[] arguments)
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
public static boolean isTraceEnabled()
```


İzleme seviyesinin günlükleme için etkin olup olmadığını kontrol eder.

**Returns:**
boolean -  true  izleme seviyesi etkinse,  false  aksi takdirde.
### debug(String message, Object[] arguments) {#debug-java.lang.String-java.lang.Object...-}
```
public static void debug(String message, Object[] arguments)
```


Konsola bir hata ayıklama günlük mesajı yazar. Hata ayıklama günlük mesajları, uygulama akışındaki farklı süreçler hakkında bilgi sağlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| mesaj | java.lang.String | Hata ayıklama günlük mesajı. |
| argümanlar | java.lang.Object[] | Mesajda değiştirilecek argümanlar. Argümanlar, gönderildikleri sırada \{\} yer tutucularını değiştirecektir. |

### debug(Throwable throwable, String message, Object[] arguments) {#debug-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public static void debug(Throwable throwable, String message, Object[] arguments)
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
public static boolean isDebugEnabled()
```


Hata ayıklama seviyesinin günlükleme için etkin olup olmadığını kontrol eder.

**Returns:**
boolean -  true  hata ayıklama seviyesi etkinse,  false  aksi takdirde.
### warning(String message, Object[] arguments) {#warning-java.lang.String-java.lang.Object...-}
```
public static void warning(String message, Object[] arguments)
```


Konsola bir uyarı günlük mesajı yazar. Uyarı günlük mesajları, uygulama akışındaki beklenmeyen ve kurtarılabilir olaylar hakkında bilgi sağlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| mesaj | java.lang.String | Uyarı günlük mesajı. |
| argümanlar | java.lang.Object[] | Mesajda değiştirilecek argümanlar. Argümanlar, gönderildikleri sırada \{\} yer tutucularını değiştirecektir. |

### warning(Throwable throwable, String message, Object[] arguments) {#warning-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public static void warning(Throwable throwable, String message, Object[] arguments)
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
public static boolean isWarningEnabled()
```


Uyarı seviyesinin günlükleme için etkin olup olmadığını kontrol eder.

**Returns:**
boolean -  true  uyarı seviyesi etkinse,  false  aksi takdirde.
### error(String message, Object[] arguments) {#error-java.lang.String-java.lang.Object...-}
```
public static void error(String message, Object[] arguments)
```


Konsola bir hata günlük mesajı yazar. Hata günlük mesajları, uygulama akışındaki kurtarılamaz olaylar hakkında bilgi sağlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| mesaj | java.lang.String | Hata günlük mesajı. |
| argümanlar | java.lang.Object[] | Mesajda değiştirilecek argümanlar. Argümanlar, gönderildikleri sırada \{\} yer tutucularını değiştirecektir. |

### error(Throwable throwable, String message, Object[] arguments) {#error-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public static void error(Throwable throwable, String message, Object[] arguments)
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
public static boolean isErrorEnabled()
```


Hata seviyesindeki günlüklemenin etkin olup olmadığını kontrol eder.

**Returns:**
boolean -  true  hata seviyesi günlük kaydı etkinse,  false  aksi takdirde.
### getLogger() {#getLogger--}
```
public static synchronized ILogger getLogger()
```


Mesajları günlüğe kaydetmek için kullanılacak logger örneğini alır. Logger örneği, izleme, hata ayıklama, uyarı ve hata gibi farklı seviyelerdeki mesajları kaydetmek için kullanılabilir.

**Returns:**
com.groupdocs.foundation.logging.ILogger - logger örneği.
### setLogger(ILogger logger) {#setLogger-com.groupdocs.foundation.logging.ILogger-}
```
public static synchronized void setLogger(ILogger logger)
```


Mesajları günlüğe kaydetmek için kullanılacak logger örneğini ayarlar. Logger örneği, izleme, hata ayıklama, uyarı ve hata gibi farklı seviyelerdeki mesajları kaydetmek için kullanılabilir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| logger | com.groupdocs.foundation.logging.ILogger | Ayarlanacak logger örneği. |

