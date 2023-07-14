---
title: ReleaseResourceStream
second_title: GroupDocs.Viewer for Java API Reference
description: Releases a stream that was instantiated by the method associated with the CreateResourceStream interface.
type: docs
weight: 19
url: /java/com.groupdocs.viewer.interfaces/releaseresourcestream/
---```
public interface ReleaseResourceStream
```

Releases a stream that was instantiated by the method associated with the CreateResourceStream interface.

The  ReleaseResourceStream  interface represents a functional interface that declares a method to release a stream that was previously instantiated by the corresponding method in the [CreateResourceStream](../../com.groupdocs.viewer.interfaces/createresourcestream) interface. Implementations of this interface should provide the necessary functionality to release any resources associated with the stream.

Example usage:

```

 ReleaseResourceStream releaseResourceStream = ((pageNumber, resource, resourceStream) -> {
     // Custom implementation to release any resources associated with the resource stream
 };

 HtmlViewOptions htmlViewOptions = HtmlViewOptions.forExternalResources(createPageStream, createResourceStream, releaseResourceStream);
 // Use htmlViewOptions in Viewer
 
```
## Methods

| Method | Description |
| --- | --- |
| [invoke(int pageNumber, Resource resource, OutputStream resourceStream)](#invoke-int-com.groupdocs.viewer.results.Resource-java.io.OutputStream-) | Releases the stream created by the method associated with the [CreateResourceStream](../../com.groupdocs.viewer.interfaces/createresourcestream) interface. |
### invoke(int pageNumber, Resource resource, OutputStream resourceStream) {#invoke-int-com.groupdocs.viewer.results.Resource-java.io.OutputStream-}
```
public abstract void invoke(int pageNumber, Resource resource, OutputStream resourceStream)
```


Releases the stream created by the method associated with the [CreateResourceStream](../../com.groupdocs.viewer.interfaces/createresourcestream) interface.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pageNumber | int | The number of the page. |
| resource | [Resource](../../com.groupdocs.viewer.results/resource) | The resource associated with the stream. |
| resourceStream | java.io.OutputStream | The stream to be released. |

