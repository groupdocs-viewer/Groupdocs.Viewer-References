---
title: ReleaseResourceStream
second_title: GroupDocs.Viewer for Python via .NET API Reference
description: Releases stream which was instantiated by the method associated with CreateResourceStream./createresourcestream delegate.
type: docs
weight: 690
url: /python-net/groupdocs.viewer.interfaces/releaseresourcestream/
---
## ReleaseResourceStream delegate

Releases stream which was instantiated by the method associated with [`CreateResourceStream`](../createresourcestream) delegate.

```csharp
public delegate void ReleaseResourceStream(int pageNumber, Resource resource, 
    Stream resourceStream);
```

| Parameter | Type | Description |
| --- | --- | --- |
| pageNumber | Int32 | Number of the page. |
| resource | Resource | HTML resource such as font, style, image or graphics. |
| resourceStream | Stream | The stream created by the method associated with [`CreateResourceStream`](../createresourcestream) delegate. |

### See Also

* class [Resource](../../groupdocs.viewer.results/resource)
* namespace [GroupDocs.Viewer.Interfaces](../../groupdocs.viewer.interfaces)
* assembly [GroupDocs.Viewer](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.viewer.dll -->