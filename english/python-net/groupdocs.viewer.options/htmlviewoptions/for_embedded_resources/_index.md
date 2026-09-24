---
title: for_embedded_resources method
second_title: GroupDocs.Viewer for Python via .NET API References
description: "Initializes an HtmlViewOptions instance for rendering HTML with embedded resources."
type: docs
url: /python-net/groupdocs.viewer.options/htmlviewoptions/for_embedded_resources/
is_root: false
weight: 1010
---


## for_embedded_resources {#create_page_stream}

Initializes an HtmlViewOptions instance for rendering HTML with embedded resources.

For more details, see the documentation.

```python
def for_embedded_resources(cls, create_page_stream):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| create_page_stream | `CreatePageStream` | The method that instantiates a stream used to write output page data. |

**Returns:** HtmlViewOptions: New instance configured for rendering HTML with embedded resources.

| Raises | Description |
| :- | :- |
| `ValueError` | If `create_page_stream` is None. |

### Example

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("document.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

## for_embedded_resources {#create_page_stream-release_page_stream}

Initializes an instance of the [`HtmlViewOptions`](/viewer/python-net/groupdocs.viewer.options/htmlviewoptions/) class for rendering into HTML with embedded resources.

```python
def for_embedded_resources(cls, create_page_stream, release_page_stream):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| create_page_stream | `CreatePageStream` | The method that instantiates the stream used to write output page data. |
| release_page_stream | `ReleasePageStream` | The method that releases the stream created by the method assigned to the `create_page_stream` parameter. |

**Returns:** HtmlViewOptions: New instance of the `HtmlViewOptions` class for rendering into HTML with embedded resources.

| Raises | Description |
| :- | :- |
| `ValueError` | If `release_page_stream` is `None`. For the code example, see the documentation. |

## for_embedded_resources {#page_stream_factory}

Initializes an HtmlViewOptions instance for rendering into HTML with embedded resources.

For the code example, see the documentation at https://docs.groupdocs.com/viewer/net/rendering-to-html/#rendering-to-html-with-embedded-resources.

```python
def for_embedded_resources(cls, page_stream_factory):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| page_stream_factory | `IPageStreamFactory` | The factory which implements methods for creating and releasing output page stream. |

**Returns:** HtmlViewOptions: New instance of HtmlViewOptions for rendering into HTML with embedded resources.

| Raises | Description |
| :- | :- |
| `ValueError` | When page_stream_factory is None. |

### Example

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("document.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

## for_embedded_resources

Initializes an instance of the [`HtmlViewOptions`](/viewer/python-net/groupdocs.viewer.options/htmlviewoptions/) class with embedded resources.

For the code example, see the documentation.

```python
def for_embedded_resources(cls):
    ...
```

### Example

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("document.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

## for_embedded_resources {#file_path_format}

Initializes an HtmlViewOptions instance for embedded resources.

For the code example, see the documentation.

```python
def for_embedded_resources(cls, file_path_format):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| file_path_format | `str` | The file path format e.g. 'page_{0}.html'. |

| Raises | Description |
| :- | :- |
| `ValueError` | When `file_path_format` is None or empty. |

### Example

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("document.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

### See Also
* class [`HtmlViewOptions`](/viewer/python-net/groupdocs.viewer.options/htmlviewoptions/)
