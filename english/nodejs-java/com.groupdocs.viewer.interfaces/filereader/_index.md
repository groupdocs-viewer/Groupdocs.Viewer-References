---
title: FileReader
second_title: GroupDocs.Viewer for Node.js via Java API Reference
description: Declares an interface for reading a file stream.
type: docs
weight: 14
url: /nodejs-java/com.groupdocs.viewer.interfaces/filereader/
---
**All Implemented Interfaces:**
java.io.Closeable
```
public interface FileReader extends Closeable
```

Declares an interface for reading a file stream.

The FileReader interface provides a method for reading a file stream. It is used for accessing and reading the contents of a file in a sequential manner. Implementations of this interface should handle the necessary operations to read data from a file.

Example usage:

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
## Methods

| Method | Description |
| --- | --- |
| [read()](#read--) | Returns an InputStream that represents a readable stream for the file. |
| [close()](#close--) | Disposes the object and releases any system resources associated with it. |
### read() {#read--}
```
public abstract InputStream read()
```


Returns an InputStream that represents a readable stream for the file.

**Returns:**
java.io.InputStream - the InputStream readable stream.
### close() {#close--}
```
public abstract void close()
```


Disposes the object and releases any system resources associated with it.

