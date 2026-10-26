---
title: "ViewerLogger"
second_title: "GroupDocs.Viewer untuk Node.js melalui Java Referensi API"
description: "Logger penampil global."
type: docs
weight: 11
url: /id/nodejs-java/com.groupdocs.viewer.logging/viewerlogger/
---
**Inheritance:**
java.lang.Object
```
public class ViewerLogger
```

Logger penampil global.

Kelas  ViewerLogger  menyediakan fungsionalitas untuk mencatat pesan ke logger terintegrasi atau yang didefinisikan pengguna. Kelas ini berfungsi sebagai logger global untuk modul viewer dan dapat digunakan untuk mencatat berbagai peristiwa dan pesan.

Contoh penggunaan:

```

 // Configure the viewer logger to use the default integrated logger
 ViewerLogger.setLogger(new FileLogger("/path/to/file.log"));

 // Log an debug message
 ViewerLogger.debug("Debug message");

 // Log an error message
 ViewerLogger.error("Error message");
 
```

***Note:** The  ViewerLogger  class can be configured to use a custom logger implementation by calling the [setLogger(ILogger)](../../com.groupdocs.viewer.logging/viewerlogger\#setLogger-ILogger-) method. By default, it uses the integrated logger provided by the viewer module.*
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [ViewerLogger()](#ViewerLogger--) |  |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [trace(String message, Object[] arguments)](#trace-java.lang.String-java.lang.Object...-) | Menulis pesan jejak ke konsol. |
| [trace(Throwable throwable, String message, Object[] arguments)](#trace-java.lang.Throwable-java.lang.String-java.lang.Object...-) | Menulis pesan log jejak ke konsol. |
| [isTraceEnabled()](#isTraceEnabled--) | Memeriksa apakah level jejak diaktifkan untuk pencatatan. |
| [debug(String message, Object[] arguments)](#debug-java.lang.String-java.lang.Object...-) | Menulis pesan log debug ke konsol. |
| [debug(Throwable throwable, String message, Object[] arguments)](#debug-java.lang.Throwable-java.lang.String-java.lang.Object...-) | Menulis pesan log debug ke konsol. |
| [isDebugEnabled()](#isDebugEnabled--) | Memeriksa apakah level debug diaktifkan untuk pencatatan. |
| [warning(String message, Object[] arguments)](#warning-java.lang.String-java.lang.Object...-) | Menulis pesan log peringatan ke konsol. |
| [warning(Throwable throwable, String message, Object[] arguments)](#warning-java.lang.Throwable-java.lang.String-java.lang.Object...-) | Menulis pesan log peringatan ke konsol. |
| [isWarningEnabled()](#isWarningEnabled--) | Memeriksa apakah level peringatan diaktifkan untuk pencatatan. |
| [error(String message, Object[] arguments)](#error-java.lang.String-java.lang.Object...-) | Menulis pesan log error ke konsol. |
| [error(Throwable throwable, String message, Object[] arguments)](#error-java.lang.Throwable-java.lang.String-java.lang.Object...-) | Menulis pesan log error ke konsol. |
| [isErrorEnabled()](#isErrorEnabled--) | Memeriksa apakah pencatatan tingkat error diaktifkan. |
| [getLogger()](#getLogger--) | Mendapatkan instance logger yang akan digunakan untuk mencatat pesan. |
| [setLogger(ILogger logger)](#setLogger-com.groupdocs.foundation.logging.ILogger-) | Menetapkan instance logger yang akan digunakan untuk mencatat pesan. |
### ViewerLogger() {#ViewerLogger--}
```
public ViewerLogger()
```


### trace(String message, Object[] arguments) {#trace-java.lang.String-java.lang.Object...-}
```
public static void trace(String message, Object[] arguments)
```


Menulis pesan jejak ke konsol. Pesan log jejak menyediakan informasi yang umumnya berguna tentang alur aplikasi.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pesan | java.lang.String | Pesan jejak. |
| argumen | java.lang.Object[] | Argumen yang akan digantikan dalam pesan. Mereka akan menggantikan placeholder \{\} secara berurutan sesuai dengan pemanggilan. |

### trace(Throwable throwable, String message, Object[] arguments) {#trace-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public static void trace(Throwable throwable, String message, Object[] arguments)
```


Menulis pesan log jejak ke konsol. Pesan log jejak menyediakan informasi yang umumnya berguna tentang alur aplikasi.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| throwable | java.lang.Throwable | Pengecualian yang terkait dengan pesan log jejak. |
| pesan | java.lang.String | Pesan log jejak. |
| argumen | java.lang.Object[] | Argumen yang akan diganti dalam pesan. Mereka akan menggantikan placeholder \{\} secara berurutan sesuai dengan urutan yang diberikan. |

### isTraceEnabled() {#isTraceEnabled--}
```
public static boolean isTraceEnabled()
```


Memeriksa apakah level jejak diaktifkan untuk pencatatan.

**Returns:**
boolean -  true  jika level jejak diaktifkan,  false  jika tidak.
### debug(String message, Object[] arguments) {#debug-java.lang.String-java.lang.Object...-}
```
public static void debug(String message, Object[] arguments)
```


Menulis pesan log debug ke konsol. Pesan log debug menyediakan informasi tentang proses yang berbeda dalam alur aplikasi.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pesan | java.lang.String | Pesan log debug. |
| argumen | java.lang.Object[] | Argumen yang akan diganti dalam pesan. Mereka akan menggantikan placeholder \{\} secara berurutan sesuai dengan urutan yang diberikan. |

### debug(Throwable throwable, String message, Object[] arguments) {#debug-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public static void debug(Throwable throwable, String message, Object[] arguments)
```


Menulis pesan log debug ke konsol. Pesan log debug menyediakan informasi tentang proses yang berbeda dalam alur aplikasi.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| throwable | java.lang.Throwable | Pengecualian yang terkait dengan pesan log debug. |
| pesan | java.lang.String | Pesan log debug. |
| argumen | java.lang.Object[] | Argumen yang akan diganti dalam pesan. Mereka akan menggantikan placeholder \{\} secara berurutan sesuai dengan urutan yang diberikan. |

### isDebugEnabled() {#isDebugEnabled--}
```
public static boolean isDebugEnabled()
```


Memeriksa apakah level debug diaktifkan untuk pencatatan.

**Returns:**
boolean -  true  jika level debug diaktifkan,  false  jika tidak.
### warning(String message, Object[] arguments) {#warning-java.lang.String-java.lang.Object...-}
```
public static void warning(String message, Object[] arguments)
```


Menulis pesan log peringatan ke konsol. Pesan log peringatan menyediakan informasi tentang kejadian tak terduga dan dapat dipulihkan dalam alur aplikasi.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pesan | java.lang.String | Pesan log peringatan. |
| argumen | java.lang.Object[] | Argumen yang akan diganti dalam pesan. Mereka akan menggantikan placeholder \{\} secara berurutan sesuai dengan urutan yang diberikan. |

### warning(Throwable throwable, String message, Object[] arguments) {#warning-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public static void warning(Throwable throwable, String message, Object[] arguments)
```


Menulis pesan log peringatan ke konsol. Pesan log peringatan menyediakan informasi tentang kejadian tak terduga dan dapat dipulihkan dalam alur aplikasi.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| throwable | java.lang.Throwable | Pengecualian yang terkait dengan pesan log peringatan. |
| pesan | java.lang.String | Pesan log peringatan. |
| argumen | java.lang.Object[] | Argumen yang akan diganti dalam pesan. Mereka akan menggantikan placeholder \{\} secara berurutan sesuai dengan urutan yang diberikan. |

### isWarningEnabled() {#isWarningEnabled--}
```
public static boolean isWarningEnabled()
```


Memeriksa apakah level peringatan diaktifkan untuk pencatatan.

**Returns:**
boolean -  true  jika level peringatan diaktifkan,  false  jika tidak.
### error(String message, Object[] arguments) {#error-java.lang.String-java.lang.Object...-}
```
public static void error(String message, Object[] arguments)
```


Menulis pesan log error ke konsol. Pesan log error menyediakan informasi tentang kejadian yang tidak dapat dipulihkan dalam alur aplikasi.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pesan | java.lang.String | Pesan log error. |
| argumen | java.lang.Object[] | Argumen yang akan diganti dalam pesan. Mereka akan menggantikan placeholder \{\} secara berurutan sesuai dengan urutan yang diberikan. |

### error(Throwable throwable, String message, Object[] arguments) {#error-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public static void error(Throwable throwable, String message, Object[] arguments)
```


Menulis pesan log error ke konsol. Pesan log error menyediakan informasi tentang kejadian yang tidak dapat dipulihkan dalam alur aplikasi.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| throwable | java.lang.Throwable | Pengecualian yang terkait dengan pesan log error. |
| pesan | java.lang.String | Pesan log error. |
| argumen | java.lang.Object[] | Argumen yang akan diganti dalam pesan. Mereka akan menggantikan placeholder \{\} secara berurutan sesuai dengan urutan yang diberikan. |

### isErrorEnabled() {#isErrorEnabled--}
```
public static boolean isErrorEnabled()
```


Memeriksa apakah pencatatan tingkat error diaktifkan.

**Returns:**
boolean -  true  jika logging tingkat error diaktifkan,  false  jika tidak.
### getLogger() {#getLogger--}
```
public static synchronized ILogger getLogger()
```


Mendapatkan instance logger yang akan digunakan untuk mencatat pesan. Instance logger dapat digunakan untuk mencatat pesan pada berbagai tingkat seperti jejak, debug, peringatan, dan error.

**Returns:**
com.groupdocs.foundation.logging.ILogger - instance logger.
### setLogger(ILogger logger) {#setLogger-com.groupdocs.foundation.logging.ILogger-}
```
public static synchronized void setLogger(ILogger logger)
```


Mengatur instance logger yang akan digunakan untuk mencatat pesan. Instance logger dapat digunakan untuk mencatat pesan pada berbagai tingkat seperti jejak, debug, peringatan, dan error.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| logger | com.groupdocs.foundation.logging.ILogger | Instance logger yang akan diatur. |

