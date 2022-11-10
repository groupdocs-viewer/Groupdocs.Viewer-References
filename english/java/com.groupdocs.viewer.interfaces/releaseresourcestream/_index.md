---
title: ReleaseResourceStream
second_title: GroupDocs.Viewer for Java API Reference
description: Releases stream which was instantiated by the method associated with  interface.
type: docs
weight: 19
url: /java/com.groupdocs.viewer.interfaces/releaseresourcestream/
---```
public interface ReleaseResourceStream
```

Releases stream which was instantiated by the method associated with [CreateResourceStream](../../com.groupdocs.viewer.interfaces/createresourcestream) interface.
## Methods

| Method | Description |
| --- | --- |
| [invoke(int pageNumber, Resource resource, OutputStream resourceStream)](#invoke-int-com.groupdocs.viewer.results.Resource-java.io.OutputStream-) | Releases stream which was instantiated by the method associated with [CreateResourceStream](../../com.groupdocs.viewer.interfaces/createresourcestream) interface. |
### invoke(int pageNumber, Resource resource, OutputStream resourceStream) {#invoke-int-com.groupdocs.viewer.results.Resource-java.io.OutputStream-}
```
public abstract void invoke(int pageNumber, Resource resource, OutputStream resourceStream)
```


Releases stream which was instantiated by the method associated with [CreateResourceStream](../../com.groupdocs.viewer.interfaces/createresourcestream) interface.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pageNumber | int |  |
| resource | [Resource](../../com.groupdocs.viewer.results/resource) |  |
| resourceStream | java.io.OutputStream |  |

