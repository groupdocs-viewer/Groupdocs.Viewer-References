---
title: "FileReader"
second_title: "GroupDocs.Viewer untuk Node.js melalui Java Referensi API"
description: "Menyatakan antarmuka untuk membaca aliran file."
type: docs
weight: 14
url: /id/nodejs-java/com.groupdocs.viewer.interfaces/filereader/
---
**All Implemented Interfaces:**
java.io.Closeable
```
public interface FileReader extends Closeable
```

Menyatakan antarmuka untuk membaca aliran file.

Antarmuka FileReader menyediakan metode untuk membaca aliran file. Antarmuka ini digunakan untuk mengakses dan membaca isi file secara berurutan. Implementasi antarmuka ini harus menangani operasi yang diperlukan untuk membaca data dari file.

Contoh penggunaan:

```

 FileReader fileReader = new FileReader() {
     @Override
     public InputStream read() {
         // Create document stream
     }

     @Override
     public void close() {
         // Close the stream
     }
 };
 try (Viewer viewer = new Viewer(fileReader, new ViewerSettings())){
     // Process document
 }
 
```
## Metode

| Metode | Deskripsi |
| --- | --- |
| [read()](#read--) | Mengembalikan InputStream yang mewakili aliran yang dapat dibaca untuk file. |
| [close()](#close--) | Membuang objek dan melepaskan semua sumber daya sistem yang terkait dengannya. |
### read() {#read--}
```
public abstract InputStream read()
```


Mengembalikan InputStream yang mewakili aliran yang dapat dibaca untuk file.

**Returns:**
java.io.InputStream - aliran InputStream yang dapat dibaca.
### close() {#close--}
```
public abstract void close()
```


Membuang objek dan melepaskan semua sumber daya sistem yang terkait dengannya.

