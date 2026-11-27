---
title: Viewer class
second_title: GroupDocs.Viewer for Python via .NET API References
description: "Represents the main class that controls the document rendering process."
type: docs
url: /python-net/groupdocs.viewer/viewer/
is_root: false
weight: 60
---


## Viewer class

Represents the main class that controls the document rendering process.

The Viewer type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer/viewer/__init__/#get_file_stream) | Initializes a new instance of [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/) class. |
| [__init__](/viewer/python-net/groupdocs.viewer/viewer/__init__/#get_file_stream-get_load_options) | Initializes a new Viewer instance. |
| [__init__](/viewer/python-net/groupdocs.viewer/viewer/__init__/#get_file_stream-settings) | Initializes a new instance of [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/). |
| [__init__](/viewer/python-net/groupdocs.viewer/viewer/__init__/#get_file_stream-get_load_options-settings) | Initializes a new instance of the [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/) class. |
| [__init__](/viewer/python-net/groupdocs.viewer/viewer/__init__/#stream) | Initializes a new instance of the [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/) class. |
| [__init__](/viewer/python-net/groupdocs.viewer/viewer/__init__/#stream-leave_open) | Initializes a new Viewer instance. |
| [__init__](/viewer/python-net/groupdocs.viewer/viewer/__init__/#stream-load_options) | Initializes a new Viewer instance. |
| [__init__](/viewer/python-net/groupdocs.viewer/viewer/__init__/#stream-load_options-leave_open) | Initializes a new instance of [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/). |
| [__init__](/viewer/python-net/groupdocs.viewer/viewer/__init__/#stream-settings) | Initializes a new Viewer instance. |
| [__init__](/viewer/python-net/groupdocs.viewer/viewer/__init__/#stream-settings-leave_open) | Initializes a new instance of the [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/) class. |
| [__init__](/viewer/python-net/groupdocs.viewer/viewer/__init__/#stream-load_options-settings) | Initializes a new Viewer instance. |
| [__init__](/viewer/python-net/groupdocs.viewer/viewer/__init__/#stream-load_options-settings-leave_open) | Initializes a new [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/) instance. |
| [__init__](/viewer/python-net/groupdocs.viewer/viewer/__init__/#file_path) | Initializes a new instance of the [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/) class. |
| [__init__](/viewer/python-net/groupdocs.viewer/viewer/__init__/#file_path-settings) | Initializes a new Viewer instance. |
| [__init__](/viewer/python-net/groupdocs.viewer/viewer/__init__/#file_path-load_options) | Initializes a new instance of [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/) class. |
| [__init__](/viewer/python-net/groupdocs.viewer/viewer/__init__/#file_path-load_options-settings) | Initializes a new instance of [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/) class. |

### Methods
| Method | Description |
| :- | :- |
| [dispose](/viewer/python-net/groupdocs.viewer/viewer/dispose/) | Releases file stream and managed internal resources. |
| [get_all_fonts](/viewer/python-net/groupdocs.viewer/viewer/get_all_fonts/) | Returns all fonts used in the loaded documents, including embedded and system fonts. |
| [get_attachments](/viewer/python-net/groupdocs.viewer/viewer/get_attachments/) | Returns attachments contained by the document. |
| [get_attachments](/viewer/python-net/groupdocs.viewer/viewer/get_attachments/#cancellation_token) | Returns attachments contained by the document. |
| [get_file_info](/viewer/python-net/groupdocs.viewer/viewer/get_file_info/) | Returns information about the file such as its file type and a flag indicating whether the file is encrypted. |
| [get_view_info](/viewer/python-net/groupdocs.viewer/viewer/get_view_info/#options) | Returns information about view and document-specific details. |
| [get_view_info](/viewer/python-net/groupdocs.viewer/viewer/get_view_info/#options-cancellation_token) | Returns information about the view and document-specific details. |
| [save_attachment](/viewer/python-net/groupdocs.viewer/viewer/save_attachment/#attachment-destination-cancellation_token) | Saves attachment file to `destination` stream. |
| [save_attachment](/viewer/python-net/groupdocs.viewer/viewer/save_attachment/#attachment-destination) | Saves the attachment to the provided writable stream. |
| [search](/viewer/python-net/groupdocs.viewer/viewer/search/#options) | Performs a text search and highlights the found text in the loaded document according to the provided options. |
| [view](/viewer/python-net/groupdocs.viewer/viewer/view/#options) | Creates view of all document pages. |
| [view](/viewer/python-net/groupdocs.viewer/viewer/view/#options-cancellation_token) | Creates view of all document pages. |
| [view](/viewer/python-net/groupdocs.viewer/viewer/view/#options-page_numbers) | Creates view of specific document pages. |
| [view](/viewer/python-net/groupdocs.viewer/viewer/view/#options-cancellation_token-page_numbers) | Creates view of specific document pages. |

### Example

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("./sample.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

### Guides
Task guides that use `Viewer`:

* [Quick Start Guide](/viewer/python-net/guides/quick-start-guide/)
* [Get Document Information](/viewer/python-net/guides/get-document-info/)
* [Load document from local disk](/viewer/python-net/guides/load-document-from-local-disk/)
* [Load document from stream](/viewer/python-net/guides/load-document-from-stream/)
* [Load document from URL](/viewer/python-net/guides/load-document-from-url/)
* [Add text watermarks](/viewer/python-net/guides/add-text-watermark/)
* [Protect PDF document](/viewer/python-net/guides/protect-pdf-document/)
* [Reorder pages](/viewer/python-net/guides/reorder-pages/)
* [Save attachments](/viewer/python-net/guides/how-to-extract-and-save-attachments/)
* [Save output to a stream](/viewer/python-net/guides/save-output-to-stream/)
* [Cancel rendering](/viewer/python-net/guides/cancel-rendering/)

### See Also
* module [`groupdocs.viewer`](/viewer/python-net/groupdocs.viewer/)
