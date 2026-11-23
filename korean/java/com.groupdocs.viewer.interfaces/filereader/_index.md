---
title: "FileReader"
second_title: "GroupDocs.Viewer for Java API Reference"
description: "파일 스트림을 읽기 위한 인터페이스를 선언합니다."
type: docs
weight: 14
url: /ko/java/com.groupdocs.viewer.interfaces/filereader/
---
**All Implemented Interfaces:**
java.io.Closeable
```
public interface FileReader extends Closeable
```

파일 스트림을 읽기 위한 인터페이스를 선언합니다.


FileReader 인터페이스는 파일 스트림을 읽기 위한 메서드를 제공합니다. 이는 파일에 접근하고 내용을 읽는 데 사용됩니다.
파일을 순차적으로 읽습니다. 이 인터페이스의 구현은 파일에서 데이터를 읽기 위한 필요한 작업을 처리해야 합니다.


사용 예시:

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


## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [read()](#read--) | 파일에 대한 읽기 가능한 스트림을 나타내는 InputStream을 반환합니다. |
|
|  | [close()](#close--) | 객체를 폐기하고 해당 객체와 연결된 모든 시스템 리소스를 해제합니다. |
|
### read() {#read--}
```
public abstract InputStream read()
```


파일에 대한 읽기 가능한 스트림을 나타내는 InputStream을 반환합니다.


**Returns:**
java.io.InputStream - 읽기 가능한 스트림.

### close() {#close--}
```
public abstract void close()
```


객체를 폐기하고 해당 객체와 연결된 모든 시스템 리소스를 해제합니다.


