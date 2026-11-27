---
title: __init__ constructor
second_title: GroupDocs.Viewer for Python via .NET API References
description: "Initializes an instance of the PngViewOptions class."
type: docs
url: /python-net/groupdocs.viewer.options/pngviewoptions/__init__/
is_root: false
weight: 10
---


## __init__ {#create_page_stream}

Initializes an instance of the [`PngViewOptions`](/viewer/python-net/groupdocs.viewer.options/pngviewoptions/) class.

```python
def __init__(self, create_page_stream):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| create_page_stream | `CreatePageStream` | Callable that creates an `io.RawIOBase` stream used to write output page data. |

| Raises | Description |
| :- | :- |
| `ValueError` | If `create_page_stream` is None. |

## __init__ {#create_page_stream-release_page_stream}

Initializes an instance of the PngViewOptions class.

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

Initializes an instance of the [`PngViewOptions`](/viewer/python-net/groupdocs.viewer.options/pngviewoptions/) class.

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

Initializes a [`PngViewOptions`](/viewer/python-net/groupdocs.viewer.options/pngviewoptions/) instance.

Initializes a [`PngViewOptions`](/viewer/python-net/groupdocs.viewer.options/pngviewoptions/) with `"p_{0}.png"` as the file path format for the output files. The output files are placed into the current working directory of the application.

For a code example, see the documentation.

```python
def __init__(self):
    ...
```

## __init__ {#file_path_format}

Initializes an instance of the PngViewOptions class.

For the code example, see the documentation.

```python
def __init__(self, file_path_format):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| file_path_format | `str` | The file path format e.g. 'page_{0}.png'. |

| Raises | Description |
| :- | :- |
| `ValueError` | When `file_path_format` is None or empty. |

### Example

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PngViewOptions

with Viewer("document.pdf") as viewer:
    viewer.view(PngViewOptions("page_{0}.png"))
```

### See Also
* class [`PngViewOptions`](/viewer/python-net/groupdocs.viewer.options/pngviewoptions/)
