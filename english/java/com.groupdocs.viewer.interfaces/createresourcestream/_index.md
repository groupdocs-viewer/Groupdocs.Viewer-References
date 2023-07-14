---
title: CreateResourceStream
second_title: GroupDocs.Viewer for Java API Reference
description: Represents an interface that instantiates a stream used to write output HTML resource data.
type: docs
weight: 12
url: /java/com.groupdocs.viewer.interfaces/createresourcestream/
---```
public interface CreateResourceStream
```

Represents an interface that instantiates a stream used to write output HTML resource data.

The CreateResourceStream interface is a functional interface that provides a method for creating a stream to write the output HTML resource data. It can be implemented by custom classes to define the behavior of generating and writing HTML resource data to a stream.

Example usage:

```

 CreateResourceStream createResourceStream = (pageNumber, resource)
      -> new FileOutputStream("file-" + pageNumber + "-" + resource.getFileName());
 HtmlViewOptions.forExternalResources(pageStreamFactory, createResourceStream);
 
```
## Methods

| Method | Description |
| --- | --- |
| [invoke(int pageNumber, Resource resource)](#invoke-int-com.groupdocs.viewer.results.Resource-) | Returns an OutputStream that will be used to write output HTML resource data. |
### invoke(int pageNumber, Resource resource) {#invoke-int-com.groupdocs.viewer.results.Resource-}
```
public abstract OutputStream invoke(int pageNumber, Resource resource)
```


Returns an OutputStream that will be used to write output HTML resource data.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pageNumber | int | Number of the page. |
| resource | [Resource](../../com.groupdocs.viewer.results/resource) | HTML resource such as font, style, image, or graphics. |

**Returns:**
java.io.OutputStream - the stream used to write output HTML resource data.
