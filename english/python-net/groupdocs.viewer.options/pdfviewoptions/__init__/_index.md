---
title: __init__ constructor
second_title: GroupDocs.Viewer for Python via .NET API References
description: "Initializes an instance of PdfViewOptions."
type: docs
url: /python-net/groupdocs.viewer.options/pdfviewoptions/__init__/
is_root: false
weight: 10
---


## __init__ {#create_file_stream}

Initializes an instance of [`PdfViewOptions`](/viewer/python-net/groupdocs.viewer.options/pdfviewoptions/).

For the code example, see the documentation.

```python
def __init__(self, create_file_stream):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| create_file_stream | `CreateFileStream` | Callable that returns an `io.RawIOBase` stream used to write output file data. |

| Raises | Description |
| :- | :- |
| `ValueError` | If `create_file_stream` is None. |

### Example

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions

with Viewer("spreadsheet.xlsx") as viewer:
    viewer.view(PdfViewOptions("output.pdf"))
```

## __init__ {#create_file_stream-release_file_stream}

Initializes an instance of [`PdfViewOptions`](/viewer/python-net/groupdocs.viewer.options/pdfviewoptions/) class.

For the code example, see the documentation.

```python
def __init__(self, create_file_stream, release_file_stream):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| create_file_stream | `CreateFileStream` | The method that instantiates stream used to write output file data. |
| release_file_stream | `ReleaseFileStream` | The method that releases stream created by method assigned to delegate that passed to `create_file_stream` parameter. |

| Raises | Description |
| :- | :- |
| `ValueError` | When `release_file_stream` is None. |

## __init__ {#file_stream_factory}

Initializes a PdfViewOptions instance.

For additional details, see the online documentation.

```python
def __init__(self, file_stream_factory):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| file_stream_factory | `IFileStreamFactory` | The factory which implements methods for creating and releasing output file stream. |

| Raises | Description |
| :- | :- |
| `ValueError` | Raised when `file_stream_factory` is None. |

## __init__

Initializes a PdfViewOptions instance.

Initializes a PdfViewOptions instance with `"output.pdf"` as the file path format for the output file. The output file will be placed into the current working directory of the application.

```python
def __init__(self):
    ...
```

## __init__ {#output_file_path}

Initializes a new [`PdfViewOptions`](/viewer/python-net/groupdocs.viewer.options/pdfviewoptions/) instance.

For the code example, see the documentation.

```python
def __init__(self, output_file_path):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| output_file_path | `str` | The path for the output PDF file. |

| Raises | Description |
| :- | :- |
| `ValueError` | Raised when `output_file_path` is None or empty. |

### Example

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions

with Viewer("spreadsheet.xlsx") as viewer:
    viewer.view(PdfViewOptions("output.pdf"))
```

### See Also
* class [`PdfViewOptions`](/viewer/python-net/groupdocs.viewer.options/pdfviewoptions/)
