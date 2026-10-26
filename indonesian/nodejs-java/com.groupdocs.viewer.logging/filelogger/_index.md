---
title: "FileLogger"
second_title: "GroupDocs.Viewer untuk Node.js melalui Java Referensi API"
description: "Menulis pesan log ke sebuah file."
type: docs
weight: 10
url: /id/nodejs-java/com.groupdocs.viewer.logging/filelogger/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.groupdocs.foundation.logging.ILogger
```
public class FileLogger implements ILogger
```

Menulis pesan log ke sebuah file.

Kelas  FileLogger  menyediakan fungsionalitas untuk menulis pesan log ke sebuah file. Kelas ini mengimplementasikan antarmuka ILogger dan dapat digunakan untuk mencatat berbagai peristiwa dan pesan dalam sebuah aplikasi. Pesan log ditulis ke file yang ditentukan.

Contoh penggunaan:

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
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [FileLogger(String fileName)](#FileLogger-java.lang.String-) | Membuat logger yang mencatat pesan ke file yang ditentukan oleh nama file yang diberikan. |
| [FileLogger(String fileName, boolean isTraceEnabled, boolean isDebugEnabled, boolean isWarningEnabled, boolean isErrorEnabled)](#FileLogger-java.lang.String-boolean-boolean-boolean-boolean-) | Membuat logger yang mencatat pesan ke file dengan tingkat logging yang ditentukan. |
## Bidang

| Bidang | Deskripsi |
| --- | --- |
| [MESSAGE](#MESSAGE) |  |
| [EXCEPTION](#EXCEPTION) |  |
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
### FileLogger(String fileName) {#FileLogger-java.lang.String-}
```
public FileLogger(String fileName)
```


Membuat logger yang mencatat pesan ke file yang ditentukan oleh nama file yang diberikan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fileName | java.lang.String | Nama file lengkap dengan jalur. |

### FileLogger(String fileName, boolean isTraceEnabled, boolean isDebugEnabled, boolean isWarningEnabled, boolean isErrorEnabled) {#FileLogger-java.lang.String-boolean-boolean-boolean-boolean-}
```
public FileLogger(String fileName, boolean isTraceEnabled, boolean isDebugEnabled, boolean isWarningEnabled, boolean isErrorEnabled)
```


Membuat logger yang mencatat pesan ke file dengan tingkat logging yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fileName | java.lang.String | Nama file lengkap dengan jalur. |
| isTraceEnabled | boolean | Menentukan apakah logging tingkat trace diaktifkan. |
| isDebugEnabled | boolean | Menentukan apakah logging tingkat debug diaktifkan. |
| isWarningEnabled | boolean | Menentukan apakah logging tingkat peringatan diaktifkan. |
| isErrorEnabled | boolean | Menentukan apakah logging tingkat error diaktifkan. |

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


Menulis pesan jejak ke konsol. Pesan log jejak menyediakan informasi yang umumnya berguna tentang alur aplikasi.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pesan | java.lang.String | Pesan jejak. |
| argumen | java.lang.Object[] | Argumen yang akan digantikan dalam pesan. Mereka akan menggantikan placeholder \{\} secara berurutan sesuai dengan pemanggilan. |

### trace(Throwable throwable, String message, Object[] arguments) {#trace-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public void trace(Throwable throwable, String message, Object[] arguments)
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
public boolean isTraceEnabled()
```


Memeriksa apakah level jejak diaktifkan untuk pencatatan.

**Returns:**
boolean -  true  jika level jejak diaktifkan,  false  jika tidak.
### debug(String message, Object[] arguments) {#debug-java.lang.String-java.lang.Object...-}
```
public void debug(String message, Object[] arguments)
```


Menulis pesan log debug ke konsol. Pesan log debug menyediakan informasi tentang proses yang berbeda dalam alur aplikasi.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pesan | java.lang.String | Pesan log debug. |
| argumen | java.lang.Object[] | Argumen yang akan diganti dalam pesan. Mereka akan menggantikan placeholder \{\} secara berurutan sesuai dengan urutan yang diberikan. |

### debug(Throwable throwable, String message, Object[] arguments) {#debug-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public void debug(Throwable throwable, String message, Object[] arguments)
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
public boolean isDebugEnabled()
```


Memeriksa apakah level debug diaktifkan untuk pencatatan.

**Returns:**
boolean -  true  jika level debug diaktifkan,  false  jika tidak.
### warning(String message, Object[] arguments) {#warning-java.lang.String-java.lang.Object...-}
```
public void warning(String message, Object[] arguments)
```


Menulis pesan log peringatan ke konsol. Pesan log peringatan menyediakan informasi tentang kejadian tak terduga dan dapat dipulihkan dalam alur aplikasi.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pesan | java.lang.String | Pesan log peringatan. |
| argumen | java.lang.Object[] | Argumen yang akan diganti dalam pesan. Mereka akan menggantikan placeholder \{\} secara berurutan sesuai dengan urutan yang diberikan. |

### warning(Throwable throwable, String message, Object[] arguments) {#warning-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public void warning(Throwable throwable, String message, Object[] arguments)
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
public boolean isWarningEnabled()
```


Memeriksa apakah level peringatan diaktifkan untuk pencatatan.

**Returns:**
boolean -  true  jika level peringatan diaktifkan,  false  jika tidak.
### error(String message, Object[] arguments) {#error-java.lang.String-java.lang.Object...-}
```
public void error(String message, Object[] arguments)
```


Menulis pesan log error ke konsol. Pesan log error menyediakan informasi tentang kejadian yang tidak dapat dipulihkan dalam alur aplikasi.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pesan | java.lang.String | Pesan log error. |
| argumen | java.lang.Object[] | Argumen yang akan diganti dalam pesan. Mereka akan menggantikan placeholder \{\} secara berurutan sesuai dengan urutan yang diberikan. |

### error(Throwable throwable, String message, Object[] arguments) {#error-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public void error(Throwable throwable, String message, Object[] arguments)
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
public boolean isErrorEnabled()
```


Memeriksa apakah pencatatan tingkat error diaktifkan.

**Returns:**
boolean -  true  jika logging tingkat error diaktifkan,  false  jika tidak.
