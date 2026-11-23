---
title: "FileReader"
second_title: "GroupDocs.Viewer for Node.js via Java API 参考"
description: "声明用于读取文件流的接口。"
type: docs
weight: 14
url: /zh/nodejs-java/com.groupdocs.viewer.interfaces/filereader/
---
**All Implemented Interfaces:**
java.io.Closeable
```
public interface FileReader extends Closeable
```

声明用于读取文件流的接口。

FileReader 接口提供用于读取文件流的方法。它用于以顺序方式访问和读取文件的内容。该接口的实现应处理读取文件数据所需的操作。

示例用法：

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
## 方法

| 方法 | 描述 |
| --- | --- |
| [read()](#read--) | 返回表示文件可读流的 InputStream。 |
| [close()](#close--) | 释放对象并释放与之关联的任何系统资源。 |
### read() {#read--}
```
public abstract InputStream read()
```


返回表示文件可读流的 InputStream。

**Returns:**
java.io.InputStream - 可读的 InputStream 流。
### close() {#close--}
```
public abstract void close()
```


释放对象并释放与之关联的任何系统资源。

