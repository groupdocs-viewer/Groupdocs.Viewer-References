---
title: "FileNotFoundException"
second_title: "GroupDocs.Viewer untuk Node.js melalui Java Referensi API"
description: "Pengecualian ini dilemparkan ketika file atau direktori tidak ditemukan."
type: docs
weight: 11
url: /id/nodejs-java/com.groupdocs.viewer.exception/filenotfoundexception/
---
**Inheritance:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException, com.aspose.ms.System.Exception, com.groupdocs.foundation.exception.GroupDocsException, [com.groupdocs.viewer.exception.GroupDocsViewerException](../../com.groupdocs.viewer.exception/groupdocsviewerexception)
```
public class FileNotFoundException extends GroupDocsViewerException
```

Pengecualian ini dilemparkan ketika file atau direktori tidak ditemukan. Ini menunjukkan bahwa file atau direktori yang ditentukan tidak ada atau tidak dapat diakses.
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [FileNotFoundException(String message)](#FileNotFoundException-java.lang.String-) | Membuat sebuah instance dari kelas FileNotFoundException dengan pesan yang ditentukan. |
| [FileNotFoundException(Path path)](#FileNotFoundException-java.nio.file.Path-) | Menginisialisasi sebuah instance baru dari kelas FileNotFoundException dengan jalur file yang ditentukan. |
| [FileNotFoundException(String messageTemplate, Object[] params)](#FileNotFoundException-java.lang.String-java.lang.Object...-) | Membuat sebuah instance baru dari kelas FileNotFoundException dengan pesan error yang ditentukan. |
| [FileNotFoundException(Throwable cause)](#FileNotFoundException-java.lang.Throwable-) | Menginstansiasi sebuah instance baru dari kelas FileNotFoundException. |
| [FileNotFoundException(String message, Throwable throwable)](#FileNotFoundException-java.lang.String-java.lang.Throwable-) | Menginisialisasi sebuah instance baru dari kelas FileNotFoundException dengan pesan error yang ditentukan. |
### FileNotFoundException(String message) {#FileNotFoundException-java.lang.String-}
```
public FileNotFoundException(String message)
```


Membuat sebuah instance dari kelas FileNotFoundException dengan pesan yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pesan | java.lang.String | Pesan yang menjelaskan kesalahan. |

### FileNotFoundException(Path path) {#FileNotFoundException-java.nio.file.Path-}
```
public FileNotFoundException(Path path)
```


Menginisialisasi sebuah instance baru dari kelas FileNotFoundException dengan jalur file yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| jalur | java.nio.file.Path | Jalur file yang tidak ada. |

### FileNotFoundException(String messageTemplate, Object[] params) {#FileNotFoundException-java.lang.String-java.lang.Object...-}
```
public FileNotFoundException(String messageTemplate, Object[] params)
```


Membuat sebuah instance baru dari kelas FileNotFoundException dengan pesan error yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| messageTemplate | java.lang.String | Pesan yang menjelaskan kesalahan. |
| params | java.lang.Object[] | Parameter yang akan dimasukkan ke dalam pesan error. |

### FileNotFoundException(Throwable cause) {#FileNotFoundException-java.lang.Throwable-}
```
public FileNotFoundException(Throwable cause)
```


Menginstansiasi sebuah instance baru dari kelas FileNotFoundException.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| penyebab | java.lang.Throwable | Penyebab pengecualian. |

### FileNotFoundException(String message, Throwable throwable) {#FileNotFoundException-java.lang.String-java.lang.Throwable-}
```
public FileNotFoundException(String message, Throwable throwable)
```


Menginisialisasi sebuah instance baru dari kelas FileNotFoundException dengan pesan error yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pesan | java.lang.String | Pesan yang menjelaskan kesalahan. |
| throwable | java.lang.Throwable | Throwable yang menyebabkan pengecualian. |

