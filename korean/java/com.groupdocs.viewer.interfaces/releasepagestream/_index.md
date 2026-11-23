---
title: "ReleasePageStream"
second_title: "GroupDocs.Viewer for Java API Reference"
description: "CreatePageStream 인터페이스와 연결된 메서드에 의해 인스턴스화된 스트림을 해제합니다."
type: docs
weight: 18
url: /ko/java/com.groupdocs.viewer.interfaces/releasepagestream/
---```
public interface ReleasePageStream
```

Releases a stream that was instantiated by the method associated with the CreatePageStream interface.


The 
ReleasePageStream
 interface represents a functional interface that declares a method to release a stream
that was previously instantiated by the corresponding method in the [CreatePageStream](../../com.groupdocs.viewer.interfaces/createpagestream) interface. Implementations
of this interface should provide the necessary functionality to release any resources associated with the stream.


Example usage:

````

 ReleasePageStream releasePageStream = ((pageNumber, pageStream) -> {
     // Custom implementation to release any resources associated with the file stream
 };

 PngViewOptions pngViewOptions = new PngViewOptions(createPageStream, releasePageStream);
 // Use pngViewOptions in Viewer
 
````


## Methods

| Method | Description |
| --- | --- |
| [invoke(int pageNumber, Closeable pageStream)](#invoke-int-java.io.Closeable-) | Releases the stream created by the method associated with the [CreatePageStream](../../com.groupdocs.viewer.interfaces/createpagestream) interface.
 |
### invoke(int pageNumber, Closeable pageStream) {#invoke-int-java.io.Closeable-}
```
public abstract void invoke(int pageNumber, Closeable pageStream)
```


Releases the stream created by the method associated with the [CreatePageStream](../../com.groupdocs.viewer.interfaces/createpagestream) interface.


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pageNumber | int | The number of the page.
 |
| pageStream | java.io.Closeable | The stream to be released.
 |

