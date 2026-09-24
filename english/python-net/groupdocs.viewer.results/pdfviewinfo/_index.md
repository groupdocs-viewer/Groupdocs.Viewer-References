---
title: PdfViewInfo class
second_title: GroupDocs.Viewer for Python via .NET API References
description: "Represents view information for a PDF document."
type: docs
url: /python-net/groupdocs.viewer.results/pdfviewinfo/
is_root: false
weight: 140
---


## PdfViewInfo class

Represents view information for a PDF document.

The PdfViewInfo type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.results/pdfviewinfo/__init__/) | Initializes a new PdfViewInfo instance. |
| [__init__](/viewer/python-net/groupdocs.viewer.results/pdfviewinfo/__init__/#file_type-pages-printing_allowed) | Initializes a new PdfViewInfo instance. |

### Methods
| Method | Description |
| :- | :- |
| [to_string](/viewer/python-net/groupdocs.viewer.results/viewinfo/to_string/) | Returns a string that represents the current object. (inherited from [`ViewInfo`](/viewer/python-net/groupdocs.viewer.results/viewinfo/)) |

### Properties
| Property | Description |
| :- | :- |
| [printing_allowed](/viewer/python-net/groupdocs.viewer.results/pdfviewinfo/printing_allowed/) | The printing_allowed property indicates whether printing of the document is allowed. |
| [file_type](/viewer/python-net/groupdocs.viewer.results/viewinfo/file_type/) | The type of the file. (inherited from [`ViewInfo`](/viewer/python-net/groupdocs.viewer.results/viewinfo/)) |
| [pages](/viewer/python-net/groupdocs.viewer.results/viewinfo/pages/) | The list of pages to view. (inherited from [`ViewInfo`](/viewer/python-net/groupdocs.viewer.results/viewinfo/)) |

### Example

```python
from typing import cast
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import ViewInfoOptions
from groupdocs.viewer.results import PdfViewInfo

def get_pdf_info():
    with Viewer("sample.pdf") as viewer:
        info = viewer.get_view_info(ViewInfoOptions.for_html_view())
        pdf_info = cast(PdfViewInfo, info)

        print("File type:", pdf_info.file_type)
        print("Pages count:", len(pdf_info.pages))
        print("Printing allowed:", pdf_info.printing_allowed)

if __name__ == "__main__":
    get_pdf_info()
```

### Guides
Task guides that use `PdfViewInfo`:

* [Get Document Information](/viewer/python-net/guides/get-document-info/)

### See Also
* module [`groupdocs.viewer.results`](/viewer/python-net/groupdocs.viewer.results/)
