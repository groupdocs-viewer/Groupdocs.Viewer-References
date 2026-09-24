---
title: LoadOptions class
second_title: GroupDocs.Viewer for Python via .NET API References
description: "The options used to open a file."
type: docs
url: /python-net/groupdocs.viewer.options/loadoptions/
is_root: false
weight: 110
---


## LoadOptions class

The options used to open a file.

The LoadOptions type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.options/loadoptions/__init__/) | Initializes an instance of the [`LoadOptions`](/viewer/python-net/groupdocs.viewer.options/loadoptions/) class. |
| [__init__](/viewer/python-net/groupdocs.viewer.options/loadoptions/__init__/#file_type) | Initializes a new LoadOptions instance. |

### Properties
| Property | Description |
| :- | :- |
| [detect_encoding](/viewer/python-net/groupdocs.viewer.options/loadoptions/detect_encoding/) | The property enables encoding detection for [`FileType.txt`](/viewer/python-net/groupdocs.viewer/filetype/txt/), [`FileType.csv`](/viewer/python-net/groupdocs.viewer/filetype/csv/), and [`FileType.tsv`](/viewer/python-net/groupdocs.viewer/filetype/tsv/) files. |
| [encoding](/viewer/python-net/groupdocs.viewer.options/loadoptions/encoding/) | The encoding used when opening text-based files or email messages such as [`FileType.csv`](/viewer/python-net/groupdocs.viewer/filetype/csv/), [`FileType.txt`](/viewer/python-net/groupdocs.viewer/filetype/txt/), and [`FileType.msg`](/viewer/python-net/groupdocs.viewer/filetype/msg/). Default value is `utf-8`. |
| [file_type](/viewer/python-net/groupdocs.viewer.options/loadoptions/file_type/) | The type of the file to open. |
| [password](/viewer/python-net/groupdocs.viewer.options/loadoptions/password/) | The password to open an encrypted file. |
| [resource_loading_timeout](/viewer/python-net/groupdocs.viewer.options/loadoptions/resource_loading_timeout/) | The timeout to load external resources. |
| [skip_external_resources](/viewer/python-net/groupdocs.viewer.options/loadoptions/skip_external_resources/) | The property disables loading of all external resources such as images, except those listed in [`LoadOptions.whitelisted_resources`](/viewer/python-net/groupdocs.viewer.options/loadoptions/whitelisted_resources/). |
| [try_repair](/viewer/python-net/groupdocs.viewer.options/loadoptions/try_repair/) | The property enables GroupDocs.Viewer to attempt repairing structural corruption in PDF documents. Default is False. |
| [whitelisted_resources](/viewer/python-net/groupdocs.viewer.options/loadoptions/whitelisted_resources/) | The list of URL fragments corresponding to external resources that should be loaded when [`LoadOptions.skip_external_resources`](/viewer/python-net/groupdocs.viewer.options/loadoptions/skip_external_resources/) is set to `True`. |

### Example

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions, LoadOptions

load_options = LoadOptions()
load_options.password = "12345"

with Viewer("protected.docx", load_options) as viewer:
    viewer.view(HtmlViewOptions.for_embedded_resources("page_{0}.html"))
```

### See Also
* module [`groupdocs.viewer.options`](/viewer/python-net/groupdocs.viewer.options/)
