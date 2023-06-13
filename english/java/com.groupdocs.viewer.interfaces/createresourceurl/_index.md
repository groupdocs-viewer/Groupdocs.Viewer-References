---
title: CreateResourceUrl
second_title: GroupDocs.Viewer for Java API Reference
description: Represents an interface that creates a URL for an HTML resource.
type: docs
weight: 13
url: /java/com.groupdocs.viewer.interfaces/createresourceurl/
---```
public interface CreateResourceUrl
```

Represents an interface that creates a URL for an HTML resource.

The  CreateResourceUrl  interface is a functional interface that provides a method for creating a URL for an HTML resource. It can be implemented by custom classes to define the behavior of generating a URL for accessing HTML resources.

Example usage:

```

 CreateResourceUrl createResourceUrl = (pageNumber, resource) -> "resource-" + pageNumber + "-" + resource.getFileName();
 HtmlViewOptions htmlViewOptions = HtmlViewOptions.forExternalResources(createPageStream, createResourceStream, createResourceUrl);
 
```
## Methods

| Method | Description |
| --- | --- |
| [invoke(int pageNumber, Resource resource)](#invoke-int-com.groupdocs.viewer.results.Resource-) | Represents the method that creates a URL for an HTML resource. |
### invoke(int pageNumber, Resource resource) {#invoke-int-com.groupdocs.viewer.results.Resource-}
```
public abstract String invoke(int pageNumber, Resource resource)
```


Represents the method that creates a URL for an HTML resource.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pageNumber | int | Number of the page. |
| resource | [Resource](../../com.groupdocs.viewer.results/resource) | HTML resource such as font, style, image, or graphics. |

**Returns:**
java.lang.String - the URL for the HTML resource.
