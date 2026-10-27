---
title: "FileReader"
second_title: "GroupDocs.Viewer для Node.js через Java API Reference"
description: "Объявляет интерфейс для чтения файлового потока."
type: docs
weight: 14
url: /ru/nodejs-java/com.groupdocs.viewer.interfaces/filereader/
---
**All Implemented Interfaces:**
java.io.Closeable
```
public interface FileReader extends Closeable
```

Объявляет интерфейс для чтения файлового потока.

Интерфейс FileReader предоставляет метод для чтения файлового потока. Он используется для доступа к содержимому файла и чтения его последовательно. Реализации этого интерфейса должны выполнять необходимые операции по чтению данных из файла.

Пример использования:

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
## Методы

| Метод | Описание |
| --- | --- |
| [read()](#read--) | Возвращает InputStream, представляющий читаемый поток файла. |
| [close()](#close--) | Освобождает объект и высвобождает любые системные ресурсы, связанные с ним. |
### read() {#read--}
```
public abstract InputStream read()
```


Возвращает InputStream, представляющий читаемый поток файла.

**Returns:**
java.io.InputStream - читаемый поток InputStream.
### close() {#close--}
```
public abstract void close()
```


Освобождает объект и высвобождает любые системные ресурсы, связанные с ним.

