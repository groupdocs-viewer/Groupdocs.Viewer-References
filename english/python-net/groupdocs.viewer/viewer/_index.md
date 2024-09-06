---
title: Viewer
second_title: GroupDocs.Viewer for Python via .NET API Reference
description: 
type: docs
weight: 40
url: /python-net/groupdocs.viewer/viewer/
---

## Viewer class

Represents main class that controls document rendering process.

The Viewer type exposes the following members:
## Constructors
| Name | Description |
| :- | :- |
|Viewer(stream)|Initializes a new instance of the Viewer class|
|Viewer(stream, leave_open)|Initializes a new instance of the Viewer class|
|Viewer(stream, load_options)|Initializes a new instance of the Viewer class|
|Viewer(stream, load_options, leave_open)|Initializes a new instance of the Viewer class|
|Viewer(stream, settings)|Initializes a new instance of the Viewer class|
|Viewer(stream, settings, leave_open)|Initializes a new instance of the Viewer class|
|Viewer(stream, load_options, settings)|Initializes a new instance of the Viewer class|
|Viewer(stream, load_options, settings, leave_open)|Initializes a new instance of the Viewer class|
|Viewer(file_path)|Initializes a new instance of the Viewer class|
|Viewer(file_path, settings)|Initializes a new instance of the Viewer class|
|Viewer(file_path, load_options)|Initializes a new instance of the Viewer class|
|Viewer(file_path, load_options, settings)|Initializes a new instance of the Viewer class|
## Methods
| Name | Description |
| :- | :- |
|view(options)|Creates view of all document pages.|
|view(options, page_numbers)|Creates view of specific document pages.|
|get_view_info(options)|Returns information about view and document specific information.|
|get_attachments()|Returns attachments contained by the document.|
|save_attachment(attachment, destination)|Saves attachment file to|
|get_file_info()|Returns information about file such as file-type and flag that indicates if file is encrypted.|

### See Also

* namespace [groupdocs.viewer](/viewer/python-net/groupdocs.viewer/)
* assembly [GroupDocs.Viewer](/viewer/python-net/)

