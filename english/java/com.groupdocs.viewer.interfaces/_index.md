---
title: com.groupdocs.viewer.interfaces
second_title: GroupDocs.Viewer for Java API Reference
description: The package provides interfaces for instantiating and releasing the output document and its resources.
type: docs
weight: 15
url: /java/com.groupdocs.viewer.interfaces/
---

The package provides interfaces for instantiating and releasing the output document and its resources.

These interfaces are used to manage the creation and release of streams and URLs associated with the output file, pages, and HTML resources.

The main interfaces in this package are:

 *  [CreateFileStream](../../com.groupdocs.viewer.interfaces/createfilestream) - Represents an interface for instantiating a stream used to write output file data.
 *  [FileStreamFactory](../../com.groupdocs.viewer.interfaces/filestreamfactory) - Defines methods for instantiating and releasing the output file stream.
 *  [ReleasePageStream](../../com.groupdocs.viewer.interfaces/releasepagestream) - Releases a stream that was instantiated by a method associated with the CreatePageStream interface.

For more details on working with these interfaces and customizing the output document and resource handling in GroupDocs.Viewer, lease refer to the [GroupDocs.Viewer Documentation][].


[GroupDocs.Viewer Documentation]: https://docs.groupdocs.com/viewer/java/


## Interfaces

| Interface | Description |
| --- | --- |
| [CreateFileStream](../com.groupdocs.viewer.interfaces/createfilestream) | Represents an interface that instantiates a stream used to write output file data. |
| [CreatePageStream](../com.groupdocs.viewer.interfaces/createpagestream) | Represents an interface that instantiates a stream used to write output page data. |
| [CreateResourceStream](../com.groupdocs.viewer.interfaces/createresourcestream) | Represents an interface that instantiates a stream used to write output HTML resource data. |
| [CreateResourceUrl](../com.groupdocs.viewer.interfaces/createresourceurl) | Represents an interface that creates a URL for an HTML resource. |
| [FileReader](../com.groupdocs.viewer.interfaces/filereader) | Declares an interface for reading a file stream. |
| [FileStreamFactory](../com.groupdocs.viewer.interfaces/filestreamfactory) | Defines methods that are required for instantiating and releasing an output file stream. |
| [PageStreamFactory](../com.groupdocs.viewer.interfaces/pagestreamfactory) | Defines the methods that are required for instantiating and releasing an output page stream. |
| [ReleaseFileStream](../com.groupdocs.viewer.interfaces/releasefilestream) | Releases an interface that was instantiated by the method associated with the CreateFileStream interface. |
| [ReleasePageStream](../com.groupdocs.viewer.interfaces/releasepagestream) | Releases a stream that was instantiated by the method associated with the CreatePageStream interface. |
| [ReleaseResourceStream](../com.groupdocs.viewer.interfaces/releaseresourcestream) | Releases a stream that was instantiated by the method associated with the CreateResourceStream interface. |
| [ResourceStreamFactory](../com.groupdocs.viewer.interfaces/resourcestreamfactory) | Defines the methods that are required for creating a resource URL, instantiating, and releasing an output HTML resource stream. |
