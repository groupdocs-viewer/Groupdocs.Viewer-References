---
title: Security class
second_title: GroupDocs.Viewer for Python via .NET API References
description: "The PDF document security options."
type: docs
url: /python-net/groupdocs.viewer.options/security/
is_root: false
weight: 260
---


## Security class

The PDF document security options.

For details, see the documentation.

The Security type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.options/security/__init__/) | Initializes an instance of the [`Security`](/viewer/python-net/groupdocs.viewer.options/security/) class. |

### Properties
| Property | Description |
| :- | :- |
| [document_open_password](/viewer/python-net/groupdocs.viewer.options/security/document_open_password/) | The password required to open the PDF document. |
| [permissions](/viewer/python-net/groupdocs.viewer.options/security/permissions/) | The PDF document permissions such as printing, modification and data extraction. |
| [permissions_password](/viewer/python-net/groupdocs.viewer.options/security/permissions_password/) | The password required to change permission settings. |

### Example

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions, Security, Permissions

with Viewer("sample.docx") as viewer:
    security = Security()
    security.document_open_password = "o123"
    security.permissions_password = "p123"
    security.permissions = Permissions.ALLOW_ALL & ~Permissions.DENY_PRINTING

    pdf_options = PdfViewOptions("protected_document.pdf")
    pdf_options.security = security
    viewer.view(pdf_options)
```

### Guides
Task guides that use `Security`:

* [Protect PDF document](/viewer/python-net/guides/protect-pdf-document/)

### See Also
* module [`groupdocs.viewer.options`](/viewer/python-net/groupdocs.viewer.options/)
