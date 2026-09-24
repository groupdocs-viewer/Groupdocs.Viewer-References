---
title: __init__ constructor
second_title: GroupDocs.Viewer for Python via .NET API References
description: "Initializes an instance of the JpgViewOptions class."
type: docs
url: /python-net/groupdocs.viewer.options/jpgviewoptions/__init__/
is_root: false
weight: 10
---


## __init__ {#create_page_stream}

Initializes an instance of the JpgViewOptions class.

For the code example, see the documentation.

```python
def __init__(self, create_page_stream):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| create_page_stream | `CreatePageStream` | The method that instantiates a stream used to write output page data. |

| Raises | Description |
| :- | :- |
| `ValueError` | When `create_page_stream` is None. |

## __init__ {#create_page_stream-release_page_stream}

Initializes an instance of the JpgViewOptions class.

For the code example, see the documentation.

```python
def __init__(self, create_page_stream, release_page_stream):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| create_page_stream | `CreatePageStream` | Callable that instantiates a stream used to write output page data. |
| release_page_stream | `ReleasePageStream` | Callable that releases a stream created by the method assigned to the delegate passed to `create_page_stream`. |

| Raises | Description |
| :- | :- |
| `ValueError` | If `release_page_stream` is None. |

## __init__ {#page_stream_factory}

Initializes an instance of the [`JpgViewOptions`](/viewer/python-net/groupdocs.viewer.options/jpgviewoptions/) class.

For the code example, see the documentation at https://docs.groupdocs.com/viewer/net/rendering-to-png-or-jpeg/#rendering-to-jpeg.

```python
def __init__(self, page_stream_factory):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| page_stream_factory | `IPageStreamFactory` | The factory which implements methods for creating and releasing output page stream. |

| Raises | Description |
| :- | :- |
| `ValueError` | When `page_stream_factory` is None. |

## __init__

Initializes a JpgViewOptions instance.

This constructor initializes an instance of the [`JpgViewOptions`](/viewer/python-net/groupdocs.viewer.options/jpgviewoptions/) with `"p_{0}.jpg"` as the file path format for the output files. The output files are placed into the current working directory of the application.

```python
def __init__(self):
    ...
```

### Example

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import JpgViewOptions

with Viewer("invoice.xlsx") as viewer:
    view_options = JpgViewOptions("render_excel_to_jpg/excel_to_jpg_{0}.jpg")
    view_options.width = 800
    view_options.height = 900
    viewer.view(view_options)
```

## __init__ {#file_path_format}

Initializes a new instance of [`JpgViewOptions`](/viewer/python-net/groupdocs.viewer.options/jpgviewoptions/).

For the code example, see the documentation.

```python
def __init__(self, file_path_format):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| file_path_format | `str` | The file path format, e.g. `'page_{0}.jpg'`. |

| Raises | Description |
| :- | :- |
| `ValueError` | If `file_path_format` is None or empty. |

### Example

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import JpgViewOptions

def render_to_jpg():
    # Load a document (e.g., an Excel file)
    with Viewer("invoice.xlsx") as viewer:
        # Create JPEG view options with a file name pattern.
        view_options = JpgViewOptions("output/excel_page_{0}.jpg")
        view_options.width = 800
        view_options.height = 900
        viewer.view(view_options)

if __name__ == "__main__":
    render_to_jpg()
```

### See Also
* class [`JpgViewOptions`](/viewer/python-net/groupdocs.viewer.options/jpgviewoptions/)
