---
title: ResourceStreamFactory
second_title: GroupDocs.Viewer for Java API Reference
description: Defines the methods that are required for creating resource URL instantiating and releasing output HTML resource stream.
type: docs
weight: 20
url: /java/com.groupdocs.viewer.interfaces/resourcestreamfactory/
---```
public interface ResourceStreamFactory
```

Defines the methods that are required for creating resource URL, instantiating and releasing output HTML resource stream.
## Methods

| Method | Description |
| --- | --- |
| [createResourceStream(int pageNumber, Resource resource)](#createResourceStream-int-com.groupdocs.viewer.results.Resource-) | Creates the stream used to write output HTML resource data. |
| [createResourceUrl(int pageNumber, Resource resource)](#createResourceUrl-int-com.groupdocs.viewer.results.Resource-) | Creates the URL for HTML resource. |
| [closeResourceStream(int pageNumber, Resource resource, OutputStream resourceStream)](#closeResourceStream-int-com.groupdocs.viewer.results.Resource-java.io.OutputStream-) | Releases the stream created by \#createResourceStream(int, Resource).createResourceStream(int, Resource) method. |
### createResourceStream(int pageNumber, Resource resource) {#createResourceStream-int-com.groupdocs.viewer.results.Resource-}
```
public abstract OutputStream createResourceStream(int pageNumber, Resource resource)
```


Creates the stream used to write output HTML resource data.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pageNumber | int | The number of a page. |
| resource | [Resource](../../com.groupdocs.viewer.results/resource) | The HTML resource such as font, style, image or graphics. |

**Returns:**
java.io.OutputStream - OutputStream used to write output resource data.
### createResourceUrl(int pageNumber, Resource resource) {#createResourceUrl-int-com.groupdocs.viewer.results.Resource-}
```
public abstract String createResourceUrl(int pageNumber, Resource resource)
```


Creates the URL for HTML resource.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pageNumber | int | The number of a page. |
| resource | [Resource](../../com.groupdocs.viewer.results/resource) | The HTML resource such as font, style, image or graphics. |

**Returns:**
java.lang.String - URL for HTML resource.
### closeResourceStream(int pageNumber, Resource resource, OutputStream resourceStream) {#closeResourceStream-int-com.groupdocs.viewer.results.Resource-java.io.OutputStream-}
```
public abstract void closeResourceStream(int pageNumber, Resource resource, OutputStream resourceStream)
```


Releases the stream created by \#createResourceStream(int, Resource).createResourceStream(int, Resource) method.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pageNumber | int | The number of a page. |
| resource | [Resource](../../com.groupdocs.viewer.results/resource) | The HTML resource such as font, style, image or graphics. |
| resourceStream | java.io.OutputStream | OutputStream created by \#createResourceStream(int, Resource).createResourceStream(int, Resource) method. |

