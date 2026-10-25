---
title: "FileReader"
second_title: "Справочник API GroupDocs.Viewer для Java"
description: "Объявляет интерфейс для чтения файлового потока."
type: docs
weight: 14
url: /ru/java/com.groupdocs.viewer.interfaces/filereader/
---
**All Implemented Interfaces:**
java.io.Closeable
```
public interface FileReader extends Closeable
```

Объявляет интерфейс для чтения файлового потока.


Интерфейс FileReader предоставляет метод для чтения файлового потока. Он используется для доступа и чтения содержимого
файла последовательным способом. Реализации этого интерфейса должны выполнять необходимые операции для чтения данных из файла.


Пример использования:

````

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
 
````


## Методы

| Метод | Описание |
| --- | --- |
|  | [read()](#read--) | Возвращает InputStream, представляющий читаемый поток для файла. |
|
|  | [close()](#close--) | Освобождает объект и высвобождает любые системные ресурсы, связанные с ним. |
|
### read() {#read--}
```
public abstract InputStream read()
```


Возвращает InputStream, представляющий читаемый поток для файла.


**Returns:**
java.io.InputStream — читаемый поток InputStream.

### close() {#close--}
```
public abstract void close()
```


Освобождает объект и высвобождает любые системные ресурсы, связанные с ним.


