---
title: ReleaseFileStream
second_title: GroupDocs.Viewer for Node.js via Java API Reference
description: Releases an interface that was instantiated by the method associated with the CreateFileStream interface.
type: docs
weight: 17
url: /nodejs-java/com.groupdocs.viewer.interfaces/releasefilestream/
---```
public interface ReleaseFileStream
```

Releases an interface that was instantiated by the method associated with the CreateFileStream interface.

The  ReleaseFileStream  interface represents a functional interface that declares a method to release a closeable that was previously instantiated by the corresponding method in the [CreateFileStream](../../com.groupdocs.viewer.interfaces/createfilestream) interface. Implementations of this interface should provide the necessary functionality to release any resources associated with the object.

Example usage:

```

 ReleaseFileStream releaseFileStream = (fileStream) -> {
     // Custom implementation to release any resources associated with the file stream
 };

 PdfViewOptions pdfViewOptions = new PdfViewOptions(createFileStream, releaseFileStream);
 // Use pdfViewOptions in Viewer
 
```
## Methods

| Method | Description |
| --- | --- |
| [invoke(Closeable fileStream)](#invoke-java.io.Closeable-) | Releases the stream created by the method associated with the [CreateFileStream](../../com.groupdocs.viewer.interfaces/createfilestream) interface. |
### invoke(Closeable fileStream) {#invoke-java.io.Closeable-}
```
public abstract void invoke(Closeable fileStream)
```


Releases the stream created by the method associated with the [CreateFileStream](../../com.groupdocs.viewer.interfaces/createfilestream) interface.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fileStream | java.io.Closeable | The stream to be released. |

