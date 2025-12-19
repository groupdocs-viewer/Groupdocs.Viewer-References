---
title: IResourceStreamFactory class
second_title: GroupDocs.Viewer for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.viewer.interfaces/iresourcestreamfactory/
is_root: false
weight: 30
---

## IResourceStreamFactory class

Defines the methods that are required for creating resource URL, instantiating and releasing output HTML resource stream.



The IResourceStreamFactory type exposes the following members:

### Methods
| Method | Description |
| :- | :- |
| [create_resource_stream](/viewer/python-net/groupdocs.viewer.interfaces/iresourcestreamfactory/create_resource_stream/#int-groupdocs.viewer.results.Resource) | Creates the stream used to write output HTML resource data. |
| [create_resource_url](/viewer/python-net/groupdocs.viewer.interfaces/iresourcestreamfactory/create_resource_url/#int-groupdocs.viewer.results.Resource) | Creates the URL for HTML resource. |
| [release_resource_stream](/viewer/python-net/groupdocs.viewer.interfaces/iresourcestreamfactory/release_resource_stream/#int-groupdocs.viewer.results.Resource-io.RawIOBase) | Releases the stream created by [`IResourceStreamFactory.create_resource_stream`](/viewer/python-net/groupdocs.viewer.interfaces/iresourcestreamfactory/create_resource_stream) method. |



### See Also
* module [`groupdocs.viewer.interfaces`](..)
