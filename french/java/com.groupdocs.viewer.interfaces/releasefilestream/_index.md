---
title: "ReleaseFileStream"
second_title: "Référence API de GroupDocs.Viewer pour Java"
description: "Libère une interface qui a été instanciée par la méthode associée à l'interface CreateFileStream."
type: docs
weight: 17
url: /fr/java/com.groupdocs.viewer.interfaces/releasefilestream/
---```
public interface ReleaseFileStream
```

Releases an interface that was instantiated by the method associated with the CreateFileStream interface.


The 
ReleaseFileStream
 interface represents a functional interface that declares a method to release a closeable
that was previously instantiated by the corresponding method in the [CreateFileStream](../../com.groupdocs.viewer.interfaces/createfilestream) interface. Implementations
of this interface should provide the necessary functionality to release any resources associated with the object.


Example usage:

````

 ReleaseFileStream releaseFileStream = (fileStream) -> {
     // Custom implementation to release any resources associated with the file stream
 };

 PdfViewOptions pdfViewOptions = new PdfViewOptions(createFileStream, releaseFileStream);
 // Use pdfViewOptions in Viewer
 
````


## Methods

| Method | Description |
| --- | --- |
| [invoke(Closeable fileStream)](#invoke-java.io.Closeable-) | Releases the stream created by the method associated with the [CreateFileStream](../../com.groupdocs.viewer.interfaces/createfilestream) interface.
 |
### invoke(Closeable fileStream) {#invoke-java.io.Closeable-}
```
public abstract void invoke(Closeable fileStream)
```


Releases the stream created by the method associated with the [CreateFileStream](../../com.groupdocs.viewer.interfaces/createfilestream) interface.


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fileStream | java.io.Closeable | The stream to be released.
 |

