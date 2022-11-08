---
title: CreateResourceStream
second_title: GroupDocs.Viewer for Java API Reference
description: Represents interface that instantiates stream used to write output HTML resource data.
type: docs
weight: 12
url: /java/com.groupdocs.viewer.interfaces/createresourcestream/
---```
public interface CreateResourceStream
```

Represents interface that instantiates stream used to write output HTML resource data.
## Methods

| Method | Description |
| --- | --- |
| [invoke(int pageNumber, Resource resource)](#invoke-int-com.groupdocs.viewer.results.Resource-) | The method must return OutputStream that will be used to write output HTML resource data. |
### invoke(int pageNumber, Resource resource) {#invoke-int-com.groupdocs.viewer.results.Resource-}
```
public abstract OutputStream invoke(int pageNumber, Resource resource)
```


The method must return OutputStream that will be used to write output HTML resource data.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pageNumber | int | Number of the page. |
| resource | [Resource](../../com.groupdocs.viewer.results/resource) | HTML resource such as font, style, image or graphics. |

**Returns:**
java.io.OutputStream - The stream used to write output HTML resource data.
