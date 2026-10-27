---
title: "FileReader"
second_title: "GroupDocs.Viewer için Node.js üzerinden Java API Referansı"
description: "Bir dosya akışını okumak için bir arabirim bildirir."
type: docs
weight: 14
url: /tr/nodejs-java/com.groupdocs.viewer.interfaces/filereader/
---
**All Implemented Interfaces:**
java.io.Closeable
```
public interface FileReader extends Closeable
```

Bir dosya akışını okumak için bir arabirim bildirir.

FileReader arayüzü, bir dosya akışını okuma yöntemi sağlar. Dosyanın içeriğine sıralı bir şekilde erişmek ve okumak için kullanılır. Bu arayüzün uygulamaları, bir dosyadan veri okumak için gerekli işlemleri yönetmelidir.

Örnek kullanım:

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
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [read()](#read--) | Dosya için okunabilir bir akışı temsil eden bir InputStream döndürür. |
| [close()](#close--) | Nesneyi imha eder ve ona bağlı tüm sistem kaynaklarını serbest bırakır. |
### read() {#read--}
```
public abstract InputStream read()
```


Dosya için okunabilir bir akışı temsil eden bir InputStream döndürür.

**Returns:**
java.io.InputStream - InputStream okunabilir akışı.
### close() {#close--}
```
public abstract void close()
```


Nesneyi imha eder ve ona bağlı tüm sistem kaynaklarını serbest bırakır.

