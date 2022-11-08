---
title: CreateResourceUrl
second_title: GroupDocs.Viewer for Java API Reference
description: Represents interface that creates URL for HTML resource.
type: docs
weight: 13
url: /java/com.groupdocs.viewer.interfaces/createresourceurl/
---```
public interface CreateResourceUrl
```

Represents interface that creates URL for HTML resource.
## Methods

| Method | Description |
| --- | --- |
| [invoke(int pageNumber, Resource resource)](#invoke-int-com.groupdocs.viewer.results.Resource-) | Represents the method that creates URL for HTML resource. |
### invoke(int pageNumber, Resource resource) {#invoke-int-com.groupdocs.viewer.results.Resource-}
```
public abstract String invoke(int pageNumber, Resource resource)
```


Represents the method that creates URL for HTML resource.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pageNumber | int | Number of the page. |
| resource | [Resource](../../com.groupdocs.viewer.results/resource) | HTML resource such as font, style, image or graphics. |

**Returns:**
java.lang.String
