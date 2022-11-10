---
title: FileStreamFactory
second_title: GroupDocs.Viewer for Java API Reference
description: Defines methods which are required for instantiating and releasing output file stream.
type: docs
weight: 15
url: /java/com.groupdocs.viewer.interfaces/filestreamfactory/
---```
public interface FileStreamFactory
```

Defines methods which are required for instantiating and releasing output file stream.
## Methods

| Method | Description |
| --- | --- |
| [createFileStream()](#createFileStream--) | The method that returns readable stream. |
| [closeFileStream(OutputStream fileStream)](#closeFileStream-java.io.OutputStream-) | Releases the stream created by \#createFileStream().createFileStream() method. |
### createFileStream() {#createFileStream--}
```
public abstract OutputStream createFileStream()
```


The method that returns readable stream.

**Returns:**
java.io.OutputStream - OutputStream used to write output file data.
### closeFileStream(OutputStream fileStream) {#closeFileStream-java.io.OutputStream-}
```
public abstract void closeFileStream(OutputStream fileStream)
```


Releases the stream created by \#createFileStream().createFileStream() method.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fileStream | java.io.OutputStream | OutputStream created by \#createFileStream().createFileStream() method. |

