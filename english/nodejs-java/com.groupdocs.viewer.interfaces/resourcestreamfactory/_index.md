---
title: ResourceStreamFactory
second_title: GroupDocs.Viewer for Node.js via Java API Reference
description: Defines the methods that are required for creating a resource URL instantiating and releasing an output HTML resource stream.
type: docs
weight: 20
url: /nodejs-java/com.groupdocs.viewer.interfaces/resourcestreamfactory/
---```
public interface ResourceStreamFactory
```

Defines the methods that are required for creating a resource URL, instantiating, and releasing an output HTML resource stream.

The  ResourceStreamFactory  interface provides the necessary methods for creating a resource URL, as well as instantiating and releasing an output HTML resource stream. Implementations of this interface should provide the functionality to handle the creation, instantiation, and release of the resource stream and URL.

Example usage:

```

 ResourceStreamFactory resourceStreamFactory = new ResourceStreamFactory() {
     @Override
     public OutputStream createResourceStream(int pageNumber, Resource resource) {
         // Custom implementation to create an output HTML resource stream based on the given resource URL
     }

     @Override
     public String createResourceUrl(int pageNumber, Resource resource) {
         // Custom implementation to create a resource URL based on the given resource name
     }

     @Override
     public void closeResourceStream(int pageNumber, Resource resource, OutputStream resourceStream) {
         // Custom implementation to release any resources associated with the resource stream
     }
 };

 HtmlViewOptions htmlViewOptions = HtmlViewOptions.forExternalResources(pageStreamFactory, resourceStreamFactory);
 // Use htmlViewOptions in Viewer
 
```
## Methods

| Method | Description |
| --- | --- |
| [createResourceStream(int pageNumber, Resource resource)](#createResourceStream-int-com.groupdocs.viewer.results.Resource-) | Creates the stream used to write output HTML resource data. |
| [createResourceUrl(int pageNumber, Resource resource)](#createResourceUrl-int-com.groupdocs.viewer.results.Resource-) | Creates the URL for the specified HTML resource based on the page number and resource type. |
| [closeResourceStream(int pageNumber, Resource resource, OutputStream resourceStream)](#closeResourceStream-int-com.groupdocs.viewer.results.Resource-java.io.OutputStream-) | Releases the stream created by the [createResourceStream(int, Resource)](../../com.groupdocs.viewer.interfaces/resourcestreamfactory\#createResourceStream-int--Resource-) method for the specified page number and HTML resource. |
### createResourceStream(int pageNumber, Resource resource) {#createResourceStream-int-com.groupdocs.viewer.results.Resource-}
```
public abstract OutputStream createResourceStream(int pageNumber, Resource resource)
```


Creates the stream used to write output HTML resource data.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pageNumber | int | The number of the page. |
| resource | [Resource](../../com.groupdocs.viewer.results/resource) | The HTML resource such as font, style, image, or graphics. |

**Returns:**
java.io.OutputStream - the stream used to write output resource data.
### createResourceUrl(int pageNumber, Resource resource) {#createResourceUrl-int-com.groupdocs.viewer.results.Resource-}
```
public abstract String createResourceUrl(int pageNumber, Resource resource)
```


Creates the URL for the specified HTML resource based on the page number and resource type.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pageNumber | int | The number of the page that contains the resource. |
| resource | [Resource](../../com.groupdocs.viewer.results/resource) | The HTML resource such as font, style, image, or graphics. |

**Returns:**
java.lang.String - the URL string representing the location of the HTML resource.
### closeResourceStream(int pageNumber, Resource resource, OutputStream resourceStream) {#closeResourceStream-int-com.groupdocs.viewer.results.Resource-java.io.OutputStream-}
```
public abstract void closeResourceStream(int pageNumber, Resource resource, OutputStream resourceStream)
```


Releases the stream created by the [createResourceStream(int, Resource)](../../com.groupdocs.viewer.interfaces/resourcestreamfactory\#createResourceStream-int--Resource-) method for the specified page number and HTML resource.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pageNumber | int | The number of the page that contains the resource. |
| resource | [Resource](../../com.groupdocs.viewer.results/resource) | The HTML resource such as font, style, image, or graphics. |
| resourceStream | java.io.OutputStream | The OutputStream created by the [createResourceStream(int, Resource)](../../com.groupdocs.viewer.interfaces/resourcestreamfactory\#createResourceStream-int--Resource-) method. |

