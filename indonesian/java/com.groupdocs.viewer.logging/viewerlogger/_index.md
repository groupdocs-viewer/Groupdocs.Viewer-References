---
title: "ViewerLogger"
second_title: "Referensi API GroupDocs.Viewer for Java"
description: "Logger penampil global."
type: docs
weight: 11
url: /id/java/com.groupdocs.viewer.logging/viewerlogger/
---
**Inheritance:**
java.lang.Object
```
public class ViewerLogger
```

Logger penampil global.


The
ViewerLogger
kelas menyediakan fungsionalitas untuk mencatat pesan ke logger terintegrasi atau yang didefinisikan pengguna.
Ini berfungsi sebagai logger global untuk modul viewer dan dapat digunakan untuk mencatat berbagai peristiwa dan pesan.


Contoh penggunaan:

````

 // Configure the viewer logger to use the default integrated logger
 ViewerLogger.setLogger(new FileLogger("/path/to/file.log"));

 // Log an debug message
 ViewerLogger.debug("Debug message");

 // Log an error message
 ViewerLogger.error("Error message");
 
````


***Note:** The 
ViewerLogger
kelas dapat dikonfigurasi untuk menggunakan implementasi logger khusus dengan memanggil metode [setLogger(ILogger)](../../com.groupdocs.viewer.logging/viewerlogger#setLogger-ILogger-).
Secara default, ia menggunakan logger terintegrasi yang disediakan oleh modul viewer.*

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [ViewerLogger()](#ViewerLogger--) |  |
## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [trace(String message, Object[] arguments)](#trace-java.lang.String-java.lang.Object...-) | Menulis pesan jejak ke konsol. |
|
|  | [trace(Throwable throwable, String message, Object[] arguments)](#trace-java.lang.Throwable-java.lang.String-java.lang.Object...-) | Menulis pesan log jejak ke konsol. |
|
|  | [isTraceEnabled()](#isTraceEnabled--) | Memeriksa apakah level jejak diaktifkan untuk pencatatan. |
|
|  | [debug(String message, Object[] arguments)](#debug-java.lang.String-java.lang.Object...-) | Menulis pesan log debug ke konsol. |
|
|  | [debug(Throwable throwable, String message, Object[] arguments)](#debug-java.lang.Throwable-java.lang.String-java.lang.Object...-) | Menulis pesan log debug ke konsol. |
|
|  | [isDebugEnabled()](#isDebugEnabled--) | Memeriksa apakah level debug diaktifkan untuk pencatatan. |
|
|  | [warning(String message, Object[] arguments)](#warning-java.lang.String-java.lang.Object...-) | Menulis pesan log peringatan ke konsol. |
|
|  | [warning(Throwable throwable, String message, Object[] arguments)](#warning-java.lang.Throwable-java.lang.String-java.lang.Object...-) | Menulis pesan log peringatan ke konsol. |
|
|  | [isWarningEnabled()](#isWarningEnabled--) | Memeriksa apakah level peringatan diaktifkan untuk pencatatan. |
|
|  | [error(String message, Object[] arguments)](#error-java.lang.String-java.lang.Object...-) | Menulis pesan log error ke konsol. |
|
|  | [error(Throwable throwable, String message, Object[] arguments)](#error-java.lang.Throwable-java.lang.String-java.lang.Object...-) | Menulis pesan log error ke konsol. |
|
|  | [isErrorEnabled()](#isErrorEnabled--) | Memeriksa apakah pencatatan tingkat error diaktifkan. |
|
|  | [getLogger()](#getLogger--) | Mendapatkan instance logger yang akan digunakan untuk mencatat pesan. |
|
|  | [setLogger(ILogger logger)](#setLogger-com.groupdocs.foundation.logging.ILogger-) | Menetapkan instance logger yang akan digunakan untuk mencatat pesan. |
|
### ViewerLogger() {#ViewerLogger--}
```
public ViewerLogger()
```


### trace(String message, Object[] arguments) {#trace-java.lang.String-java.lang.Object...-}
```
public static void trace(String message, Object[] arguments)
```


Menulis pesan jejak ke konsol.
Pesan log jejak menyediakan informasi yang umumnya berguna tentang alur aplikasi.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | pesan | java.lang.String | Pesan jejak. |
|
|  | argumen | java.lang.Object[] | Argumen yang akan diganti dalam pesan. Mereka akan menggantikan placeholder {} sesuai urutan pemanggilan. |
|

### trace(Throwable throwable, String message, Object[] arguments) {#trace-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public static void trace(Throwable throwable, String message, Object[] arguments)
```


Menulis pesan log jejak ke konsol.
Pesan log jejak menyediakan informasi yang umumnya berguna tentang alur aplikasi.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | throwable | java.lang.Throwable | Pengecualian yang terkait dengan pesan log jejak. |
|
|  | pesan | java.lang.String | Pesan log jejak. |
|
|  | argumen | java.lang.Object[] | Argumen yang akan diganti dalam pesan. Mereka akan menggantikan placeholder {} sesuai urutan mereka diteruskan. |
|

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


Menulis pesan log debug ke konsol.
Pesan log debug menyediakan informasi tentang proses yang berbeda dalam alur aplikasi.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | pesan | java.lang.String | Pesan log debug. |
|
|  | argumen | java.lang.Object[] | Argumen yang akan diganti dalam pesan. Mereka akan menggantikan placeholder {} sesuai urutan mereka diteruskan. |
|

### debug(Throwable throwable, String message, Object[] arguments) {#debug-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public static void debug(Throwable throwable, String message, Object[] arguments)
```


Menulis pesan log debug ke konsol.
Pesan log debug menyediakan informasi tentang proses yang berbeda dalam alur aplikasi.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | throwable | java.lang.Throwable | Pengecualian yang terkait dengan pesan log debug. |
|
|  | pesan | java.lang.String | Pesan log debug. |
|
|  | argumen | java.lang.Object[] | Argumen yang akan diganti dalam pesan. Mereka akan menggantikan placeholder {} sesuai urutan mereka diteruskan. |
|

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


Menulis pesan log peringatan ke konsol.
Pesan log peringatan menyediakan informasi tentang peristiwa tak terduga dan dapat dipulihkan dalam alur aplikasi.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | pesan | java.lang.String | Pesan log peringatan. |
|
|  | argumen | java.lang.Object[] | Argumen yang akan diganti dalam pesan. Mereka akan menggantikan placeholder {} sesuai urutan mereka diteruskan. |
|

### warning(Throwable throwable, String message, Object[] arguments) {#warning-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public static void warning(Throwable throwable, String message, Object[] arguments)
```


Menulis pesan log peringatan ke konsol.
Pesan log peringatan menyediakan informasi tentang peristiwa tak terduga dan dapat dipulihkan dalam alur aplikasi.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | throwable | java.lang.Throwable | Pengecualian yang terkait dengan pesan log peringatan. |
|
|  | pesan | java.lang.String | Pesan log peringatan. |
|
|  | argumen | java.lang.Object[] | Argumen yang akan diganti dalam pesan. Mereka akan menggantikan placeholder {} sesuai urutan mereka diteruskan. |
|

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


Menulis pesan log error ke konsol.
Pesan log error menyediakan informasi tentang peristiwa yang tidak dapat dipulihkan dalam alur aplikasi.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | pesan | java.lang.String | Pesan log error. |
|
|  | argumen | java.lang.Object[] | Argumen yang akan diganti dalam pesan. Mereka akan menggantikan placeholder {} sesuai urutan mereka diteruskan. |
|

### error(Throwable throwable, String message, Object[] arguments) {#error-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public static void error(Throwable throwable, String message, Object[] arguments)
```


Menulis pesan log error ke konsol.
Pesan log error menyediakan informasi tentang peristiwa yang tidak dapat dipulihkan dalam alur aplikasi.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | throwable | java.lang.Throwable | Pengecualian yang terkait dengan pesan log error. |
|
|  | pesan | java.lang.String | Pesan log error. |
|
|  | argumen | java.lang.Object[] | Argumen yang akan diganti dalam pesan. Mereka akan menggantikan placeholder {} sesuai urutan mereka diteruskan. |
|

### isErrorEnabled() {#isErrorEnabled--}
```
public static boolean isErrorEnabled()
```


Memeriksa apakah pencatatan tingkat error diaktifkan.


**Returns:**
boolean -  true  jika pencatatan tingkat error diaktifkan,  false  jika tidak.

### getLogger() {#getLogger--}
```
public static synchronized ILogger getLogger()
```


Mendapatkan instance logger yang akan digunakan untuk mencatat pesan.
Instansi logger dapat digunakan untuk mencatat pesan pada berbagai level seperti jejak, debug, peringatan, dan error.


**Returns:**
com.groupdocs.foundation.logging.ILogger - instansi logger.

### setLogger(ILogger logger) {#setLogger-com.groupdocs.foundation.logging.ILogger-}
```
public static synchronized void setLogger(ILogger logger)
```


Menetapkan instance logger yang akan digunakan untuk mencatat pesan.
Instansi logger dapat digunakan untuk mencatat pesan pada berbagai level seperti jejak, debug, peringatan, dan error.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | logger | com.groupdocs.foundation.logging.ILogger | Instansi logger yang akan diatur. |
|

