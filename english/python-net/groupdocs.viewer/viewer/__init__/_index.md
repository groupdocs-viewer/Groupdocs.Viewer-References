---
title: __init__ constructor
second_title: GroupDocs.Viewer for Python via .NET API References
description: "Initializes a new instance of Viewer class."
type: docs
url: /python-net/groupdocs.viewer/viewer/__init__/
is_root: false
weight: 10
---


## __init__ {#get_file_stream}

Initializes a new instance of [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/) class.

Learn more

- More about file types supported by GroupDocs.Viewer: https://docs.groupdocs.com/viewer/python-net/getting-started/supported-document-formats/
- More about GroupDocs.Viewer for Python via .NET features: https://docs.groupdocs.com/viewer/python-net/developer-guide/

```python
def __init__(self, get_file_stream):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| get_file_stream | `Func[io.RawIOBase]` | The method that returns a readable stream. |

| Raises | Description |
| :- | :- |
| `ValueError` | If `get_file_stream` is None. |

### Example

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("./sample.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

## __init__ {#get_file_stream-get_load_options}

Initializes a new Viewer instance.

```python
def __init__(self, get_file_stream, get_load_options):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| get_file_stream | `Func[io.RawIOBase]` | Callable that returns a readable stream. |
| get_load_options | `Func[LoadOptions]` | Callable that returns document load options. |

| Raises | Description |
| :- | :- |
| `ValueError` | If `get_load_options` is None. |
| `Remarks` | - More about file types supported by GroupDocs.Viewer: https://docs.groupdocs.com/viewer/python-net/getting-started/supported-document-formats/ - More about GroupDocs.Viewer for Python via .NET features: https://docs.groupdocs.com/viewer/python-net/developer-guide/ |

## __init__ {#get_file_stream-settings}

Initializes a new instance of [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/).

Learn more

- More about file types supported by GroupDocs.Viewer: https://docs.groupdocs.com/viewer/python-net/getting-started/supported-document-formats/
- More about GroupDocs.Viewer for Python via .NET features: https://docs.groupdocs.com/viewer/python-net/developer-guide/

```python
def __init__(self, get_file_stream, settings):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| get_file_stream | `Func[io.RawIOBase]` | The method that returns a readable stream. |
| settings | `ViewerSettings` | The Viewer settings. |

| Raises | Description |
| :- | :- |
| `ValueError` | If `settings` is None. |

## __init__ {#get_file_stream-get_load_options-settings}

Initializes a new instance of the [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/) class.

```python
def __init__(self, get_file_stream, get_load_options, settings):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| get_file_stream | `Func[io.RawIOBase]` | Callable that returns a readable stream. |
| get_load_options | `Func[LoadOptions]` | Callable that returns document load options. |
| settings | `ViewerSettings` | Viewer settings. |

| Raises | Description |
| :- | :- |
| `ValueError` | Thrown when `settings` is None. |
| `Remarks` | - More about file types supported by GroupDocs.Viewer: <https://docs.groupdocs.com/viewer/python-net/getting-started/supported-document-formats/> - More about GroupDocs.Viewer for Python via .NET features: <https://docs.groupdocs.com/viewer/python-net/developer-guide/> |

## __init__ {#stream}

Initializes a new instance of the [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/) class.

- More about file types supported by GroupDocs.Viewer: https://docs.groupdocs.com/viewer/python-net/getting-started/supported-document-formats/
- More about GroupDocs.Viewer for Python via .NET features: https://docs.groupdocs.com/viewer/python-net/developer-guide/

```python
def __init__(self, stream):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| stream | `io.RawIOBase` | The file stream. |

| Raises | Description |
| :- | :- |
| `ValueError` | When `stream` is None. |

### Example

```python
from groupdocs.viewer import Viewer

with open("sample.pdf", "rb") as file_stream:
    with Viewer(file_stream) as viewer:
        # Perform viewing operations, e.g., render pages
        pass
```

## __init__ {#stream-leave_open}

Initializes a new Viewer instance.

Learn more

- More about file types supported by GroupDocs.Viewer: https://docs.groupdocs.com/viewer/python-net/getting-started/supported-document-formats/
- More about GroupDocs.Viewer for Python via .NET features: https://docs.groupdocs.com/viewer/python-net/developer-guide/

```python
def __init__(self, stream, leave_open):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| stream | `io.RawIOBase` | The file stream. |
| leave_open | `bool` | True to leave the stream open after the Viewer object is disposed; otherwise, False. |

| Raises | Description |
| :- | :- |
| `ValueError` | If `stream` is None. |

### Example

```python
import io
from groupdocs.viewer import Viewer

with open("sample.pdf", "rb") as f:
    with Viewer(f, leave_open=False) as viewer:
        # Use viewer to render or inspect the document
        pass
```

## __init__ {#stream-load_options}

Initializes a new Viewer instance.

- More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/viewer/python-net/getting-started/supported-document-formats/)
- More about GroupDocs.Viewer for Python via .NET features: [Developer Guide](https://docs.groupdocs.com/viewer/python-net/developer-guide/)

```python
def __init__(self, stream, load_options):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| stream | `io.RawIOBase` | The file stream. |
| load_options | `LoadOptions` | The document load options. |

| Raises | Description |
| :- | :- |
| `ValueError` | If `load_options` is None. |

## __init__ {#stream-load_options-leave_open}

Initializes a new instance of [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/).

The constructor accepts a file stream, document load options, and an optional flag indicating whether to leave the stream open after the viewer is disposed.

- More about file types supported by GroupDocs.Viewer: <https://docs.groupdocs.com/viewer/python-net/getting-started/supported-document-formats/>
- More about GroupDocs.Viewer for Python via .NET features: <https://docs.groupdocs.com/viewer/python-net/developer-guide/>

```python
def __init__(self, stream, load_options, leave_open):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| stream | `io.RawIOBase` | The file stream. |
| load_options | `LoadOptions` | The document load options. |
| leave_open | `bool` | True to leave the stream open after the Viewer object is disposed; otherwise, False. |

| Raises | Description |
| :- | :- |
| `ValueError` | If `load_options` is None. |

## __init__ {#stream-settings}

Initializes a new Viewer instance.

Learn more

- More about file types supported by GroupDocs.Viewer: https://docs.groupdocs.com/viewer/python-net/getting-started/supported-document-formats/
- More about GroupDocs.Viewer for Python via .NET features: https://docs.groupdocs.com/viewer/python-net/developer-guide/

```python
def __init__(self, stream, settings):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| stream | `io.RawIOBase` | The file stream. |
| settings | `ViewerSettings` | The Viewer settings. |

| Raises | Description |
| :- | :- |
| `ValueError` | When `settings` is None. |

## __init__ {#stream-settings-leave_open}

Initializes a new instance of the [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/) class.

- More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/viewer/python-net/getting-started/supported-document-formats/)
- More about GroupDocs.Viewer for Python via .NET features: [Developer Guide](https://docs.groupdocs.com/viewer/python-net/developer-guide/)

```python
def __init__(self, stream, settings, leave_open):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| stream | `io.RawIOBase` | The file stream. |
| settings | `ViewerSettings` | The Viewer settings. |
| leave_open | `bool` | True to leave the stream open after the Viewer object is disposed; otherwise, False. |

| Raises | Description |
| :- | :- |
| `ValueError` | If `settings` is None. |

## __init__ {#stream-load_options-settings}

Initializes a new Viewer instance.

The constructor accepts a file stream, document load options, and Viewer settings.

```python
def __init__(self, stream, load_options, settings):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| stream | `io.RawIOBase` | The file stream. |
| load_options | `LoadOptions` | The document load options. |
| settings | `ViewerSettings` | The Viewer settings. |

| Raises | Description |
| :- | :- |
| `ValueError` | When `settings` is None. Learn more - More about file types supported by GroupDocs.Viewer: https://docs.groupdocs.com/viewer/python-net/getting-started/supported-document-formats/ - More about GroupDocs.Viewer for Python via .NET features: https://docs.groupdocs.com/viewer/python-net/developer-guide/ |

## __init__ {#stream-load_options-settings-leave_open}

Initializes a new [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/) instance.

Learn more:
- More about file types supported by GroupDocs.Viewer: https://docs.groupdocs.com/viewer/python-net/getting-started/supported-document-formats/
- More about GroupDocs.Viewer for Python via .NET features: https://docs.groupdocs.com/viewer/python-net/developer-guide/

```python
def __init__(self, stream, load_options, settings, leave_open):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| stream | `io.RawIOBase` | The file stream. |
| load_options | `LoadOptions` | The document load options. |
| settings | `ViewerSettings` | The Viewer settings. |
| leave_open | `bool` | True to leave the stream open after the Viewer object is disposed; otherwise, False. |

| Raises | Description |
| :- | :- |
| `ValueError` | If `settings` is None. |

## __init__ {#file_path}

Initializes a new instance of the [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/) class.

Learn more:

- More about file types supported by GroupDocs.Viewer: https://docs.groupdocs.com/viewer/python-net/getting-started/supported-document-formats/
- More about GroupDocs.Viewer for Python via .NET features: https://docs.groupdocs.com/viewer/python-net/developer-guide/

```python
def __init__(self, file_path):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| file_path | `str` | The path to the file to render. |

| Raises | Description |
| :- | :- |
| `ValueError` | When `file_path` is null or empty. |

### Example

```python
from groupdocs.viewer import Viewer

with Viewer("./sample.docx") as viewer:
    # perform viewing operations here
    pass
```

## __init__ {#file_path-settings}

Initializes a new Viewer instance.

- More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/viewer/python-net/getting-started/supported-document-formats/)
- More about GroupDocs.Viewer for Python via .NET features: [Developer Guide](https://docs.groupdocs.com/viewer/python-net/developer-guide/)

```python
def __init__(self, file_path, settings):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| file_path | `str` | The path to the file to render. |
| settings | `ViewerSettings` | The Viewer settings. |

| Raises | Description |
| :- | :- |
| `ValueError` | If `settings` is null. |

## __init__ {#file_path-load_options}

Initializes a new instance of [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/) class.

- More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/viewer/python-net/getting-started/supported-document-formats/)
- More about GroupDocs.Viewer for Python via .NET features: [Developer Guide](https://docs.groupdocs.com/viewer/python-net/developer-guide/)

```python
def __init__(self, file_path, load_options):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| file_path | `str` | The path to the file to render. |
| load_options | `LoadOptions` | The options that used to open the file. |

| Raises | Description |
| :- | :- |
| `ValueError` | When `load_options` is null. |

## __init__ {#file_path-load_options-settings}

Initializes a new instance of [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/) class.

Learn more:
- More about file types supported by GroupDocs.Viewer: https://docs.groupdocs.com/viewer/python-net/getting-started/supported-document-formats/
- More about GroupDocs.Viewer for Python via .NET features: https://docs.groupdocs.com/viewer/python-net/developer-guide/

```python
def __init__(self, file_path, load_options, settings):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| file_path | `str` | The path to the file to render. |
| load_options | `LoadOptions` | The options that used to open the file. |
| settings | `ViewerSettings` | The Viewer settings. |

| Raises | Description |
| :- | :- |
| `ValueError` | When `settings` is None. |

### See Also
* class [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/)
