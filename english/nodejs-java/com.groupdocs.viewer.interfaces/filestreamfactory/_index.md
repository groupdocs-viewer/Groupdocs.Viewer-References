---
title: FileStreamFactory
second_title: GroupDocs.Viewer for Node.js via Java API Reference
description: Defines methods that are required for instantiating and releasing an output file stream.
type: docs
weight: 15
url: /nodejs-java/com.groupdocs.viewer.interfaces/filestreamfactory/
---```
public interface FileStreamFactory
```

Defines methods that are required for instantiating and releasing an output file stream.

The FileStreamFactory interface declares methods that are used to create and release an output file stream. Implementations of this interface should provide the necessary functionality to create a file stream for writing output file data, as well as release any resources associated with the file stream.

Example usage:

```

 FileStreamFactory fileStreamFactory = new FileStreamFactory() {
   @Override
   public OutputStream createFileStream() {
       // Custom implementation to create and return an output file stream for the specified file path
   }

   @Override
   public void closeFileStream(OutputStream fileStream) {
       // Custom implementation to release any resources associated with the output file stream
   }
 };

 PdfViewOptions pdfViewOptions = new PdfViewOptions(fileStreamFactory);
 // Use pdfViewOptions in Viewer
 
```
## Methods

| Method | Description |
| --- | --- |
| [createFileStream()](#createFileStream--) | The method that returns a readable stream. |
| [closeFileStream(OutputStream fileStream)](#closeFileStream-java.io.OutputStream-) | Releases the stream created by the \#createFileStream().createFileStream() method. |
### createFileStream() {#createFileStream--}
```
public abstract OutputStream createFileStream()
```


The method that returns a readable stream.

**Returns:**
java.io.OutputStream - the OutputStream used to write output file data.
### closeFileStream(OutputStream fileStream) {#closeFileStream-java.io.OutputStream-}
```
public abstract void closeFileStream(OutputStream fileStream)
```


Releases the stream created by the \#createFileStream().createFileStream() method.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fileStream | java.io.OutputStream | The OutputStream created by the \#createFileStream().createFileStream() method. |

