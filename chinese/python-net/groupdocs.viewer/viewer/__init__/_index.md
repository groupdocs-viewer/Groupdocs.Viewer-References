---
title: "__init__ 构造函数"
second_title: "GroupDocs.Viewer 用于 Python，通过 .NET API 参考"
description: "初始化 Viewer 类的新实例。"
type: docs
url: /zh/python-net/groupdocs.viewer/viewer/__init__/
is_root: false
weight: 10
---


## __init__ {#get_file_stream}

初始化 [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/) 类的新实例。

了解更多

- More about file types supported by GroupDocs.Viewer: https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats
- More about GroupDocs.Viewer for .NET features: https://docs.groupdocs.com/display/viewernet/Developer+Guide

```python
def __init__(self, get_file_stream):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| get_file_stream | `Func[io.RawIOBase]` | 返回可读流的方法。 |

| 引发 | 描述 |
| :- | :- |
| `ValueError` | 当 `get_file_stream` 为 None 时抛出。 |

### 示例

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("./sample.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

## __init__ {#get_file_stream-get_load_options}

初始化 [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/) 的新实例。

```python
def __init__(self, get_file_stream, get_load_options):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| get_file_stream | `Func[io.RawIOBase]` | 返回可读流的方法。 |
| get_load_options | `Func[LoadOptions]` | 返回文档加载选项的方法。 |

| 引发 | 描述 |
| :- | :- |
| `ValueError` | 当 `get_load_options` 为 None 时抛出。 |
| `Remarks` | - 更多关于 GroupDocs.Viewer 支持的文件类型: https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats - 更多关于 .NET 版 GroupDocs.Viewer 功能: https://docs.groupdocs.com/display/viewernet/Developer+Guide - 更多关于使用 .NET 版 GroupDocs.Viewer 加载加密文档和从第三方存储查看文件: https://docs.groupdocs.com/display/viewernet/Loading |

### 示例

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

def quick_example():
    """Render a DOCX document to HTML."""
    with Viewer("./sample.docx") as viewer:
        options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
        viewer.view(options)

if __name__ == "__main__":
    quick_example()
```

## __init__ {#get_file_stream-settings}

初始化一个新的 [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/) 实例。

- More about file types supported by GroupDocs.Viewer: https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats
- More about GroupDocs.Viewer for .NET features: https://docs.groupdocs.com/display/viewernet/Developer+Guide

```python
def __init__(self, get_file_stream, settings):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| get_file_stream | `Func[io.RawIOBase]` | 返回可读流的方法。 |
| settings | `ViewerSettings` | Viewer 设置。 |

| 引发 | 描述 |
| :- | :- |
| `ValueError` | 当 `settings` 为 None 时。 |

### 示例

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("./sample.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

## __init__ {#get_file_stream-get_load_options-settings}

初始化一个新的 Viewer 实例。

更多信息：

- More about file types supported by GroupDocs.Viewer: https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats
- More about GroupDocs.Viewer for .NET features: https://docs.groupdocs.com/display/viewernet/Developer+Guide
- More about loading encrypted documents and viewing files from third‑party storages with GroupDocs.Viewer for .NET: https://docs.groupdocs.com/display/viewernet/Loading

```python
def __init__(self, get_file_stream, get_load_options, settings):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| get_file_stream | `Func[io.RawIOBase]` | 返回可读流的可调用对象。 |
| get_load_options | `Func[LoadOptions]` | 返回文档加载选项的可调用对象。 |
| settings | `ViewerSettings` | Viewer 设置。 |

| 引发 | 描述 |
| :- | :- |
| `ValueError` | 如果 `settings` 为 None。 |

### 示例

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

def quick_example():
    """Render a DOCX document to HTML."""
    with Viewer("./sample.docx") as viewer:
        options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
        viewer.view(options)

if __name__ == "__main__":
    quick_example()
```

## __init__ {#stream}

初始化 [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/) 类的新实例。

- More about file types supported by GroupDocs.Viewer: https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats
- More about GroupDocs.Viewer for .NET features: https://docs.groupdocs.com/display/viewernet/Developer+Guide

```python
def __init__(self, stream):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| stream | `io.RawIOBase` | 文件流。 |

| 引发 | 描述 |
| :- | :- |
| `ValueError` | 当 `stream` 为 None 时抛出。 |

### 示例

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("./sample.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

## __init__ {#stream-leave_open}

初始化一个新的 Viewer 实例。

了解更多：

- More about file types supported by GroupDocs.Viewer: https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats
- More about GroupDocs.Viewer for .NET features: https://docs.groupdocs.com/display/viewernet/Developer+Guide

```python
def __init__(self, stream, leave_open):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| stream | `io.RawIOBase` | 文件流。 |
| leave_open | `bool` | True 表示在 Viewer 对象被释放后保持流打开；否则为 False。 |

| 引发 | 描述 |
| :- | :- |
| `ValueError` | 如果 `stream` 为 None。 |

### 示例

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

def quick_example():
    """Render a DOCX document to HTML — the hello‑world example."""
    with Viewer("./sample.docx") as viewer:
        options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
        viewer.view(options)

if __name__ == "__main__":
    quick_example()
```

## __init__ {#stream-load_options}

初始化 [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/) 的新实例。

了解更多：

- More about file types supported by GroupDocs.Viewer: <https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats>
- More about GroupDocs.Viewer for .NET features: <https://docs.groupdocs.com/display/viewernet/Developer+Guide>
- More about loading encrypted documents and viewing files from third‑party storages with GroupDocs.Viewer for .NET: <https://docs.groupdocs.com/display/viewernet/Loading>

```python
def __init__(self, stream, load_options):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| stream | `io.RawIOBase` | 文件流。 |
| load_options | `LoadOptions` | 文档加载选项。 |

| 引发 | 描述 |
| :- | :- |
| `ValueError` | 当 `load_options` 为 None。 |

### 示例

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("./sample.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

## __init__ {#stream-load_options-leave_open}

初始化一个新的 Viewer 实例。

```python
def __init__(self, stream, load_options, leave_open):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| stream | `io.RawIOBase` | 文件流。 |
| load_options | `LoadOptions` | 文档加载选项。 |
| leave_open | `bool` | True 表示在 Viewer 对象被释放后保持流打开；否则为 False。 |

| 引发 | 描述 |
| :- | :- |
| `ValueError` | 当 `load_options` 为 None。 |
| `Remarks` | - 更多关于 GroupDocs.Viewer 支持的文件类型: <https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats> - 更多关于 GroupDocs.Viewer for .NET 功能: <https://docs.groupdocs.com/display/viewernet/Developer+Guide> - 更多关于使用 GroupDocs.Viewer for .NET 加载加密文档和从第三方存储查看文件: <https://docs.groupdocs.com/display/viewernet/Loading> |

### 示例

```python
import io
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with open("sample.docx", "rb") as file_stream:
    viewer = Viewer(file_stream, loadOptions=None, leaveOpen=False)
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

## __init__ {#stream-settings}

初始化一个新的 Viewer 实例。

- More about file types supported by GroupDocs.Viewer: https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats
- More about GroupDocs.Viewer for .NET features: https://docs.groupdocs.com/display/viewernet/Developer+Guide

```python
def __init__(self, stream, settings):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| stream | `io.RawIOBase` | 文件流。 |
| settings | `ViewerSettings` | Viewer 设置。 |

| 引发 | 描述 |
| :- | :- |
| `ValueError` | 如果 `settings` 为 None。 |

### 示例

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("./sample.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

## __init__ {#stream-settings-leave_open}

初始化一个新的 Viewer 实例。

- More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
- More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)

```python
def __init__(self, stream, settings, leave_open):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| stream | `io.RawIOBase` | 文件流。 |
| settings | `ViewerSettings` | Viewer 设置。 |
| leave_open | `bool` | True 表示在 Viewer 对象被释放后保持流打开；否则为 False。 |

| 引发 | 描述 |
| :- | :- |
| `ValueError` | 当 `settings` 为 None 时。 |

### 示例

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("./sample.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

## __init__ {#stream-load_options-settings}

初始化一个新的 Viewer 实例。

构造函数需要一个文件流 (`io.RawIOBase`)，并可选接受文档加载选项和 Viewer 设置。

- More about file types supported by GroupDocs.Viewer: https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats
- More about GroupDocs.Viewer for .NET features: https://docs.groupdocs.com/display/viewernet/Developer+Guide
- More about loading encrypted documents and viewing files from third‑party storages with GroupDocs.Viewer for .NET: https://docs.groupdocs.com/display/viewernet/Loading

```python
def __init__(self, stream, load_options, settings):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| stream | `io.RawIOBase` | 文件流。 |
| load_options | `LoadOptions` | 文档加载选项。 |
| settings | `ViewerSettings` | Viewer 设置。 |

| 引发 | 描述 |
| :- | :- |
| `ValueError` | 如果 `stream`、`load_options` 或 `settings` 为 None。 |

### 示例

```python
from groupdocs.viewer import Viewer

# 以二进制流打开文件并创建 Viewer
with open("sample.docx", "rb") as file_stream:
    viewer = Viewer(file_stream)
    # 使用 viewer，例如渲染为 HTML
    # ...
```

## __init__ {#stream-load_options-settings-leave_open}

初始化 [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/) 的新实例。

了解更多：

- More about file types supported by GroupDocs.Viewer: https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats
- More about GroupDocs.Viewer for .NET features: https://docs.groupdocs.com/display/viewernet/Developer+Guide
- More about loading encrypted documents and viewing files from third‑party storages with GroupDocs.Viewer for .NET: https://docs.groupdocs.com/display/viewernet/Loading

```python
def __init__(self, stream, load_options, settings, leave_open):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| stream | `io.RawIOBase` | 文件流。 |
| load_options | `LoadOptions` | 文档加载选项。 |
| settings | `ViewerSettings` | Viewer 设置。 |
| leave_open | `bool` | True 表示在 Viewer 对象被释放后保持流打开；否则为 False。 |

| 引发 | 描述 |
| :- | :- |
| `ValueError` | 如果 `settings` 为 None。 |

### 示例

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("./sample.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

## __init__ {#file_path}

初始化 [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/) 类的新实例。

- More about file types supported by GroupDocs.Viewer: https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats
- More about GroupDocs.Viewer for .NET features: https://docs.groupdocs.com/display/viewernet/Developer+Guide

```python
def __init__(self, file_path):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| file_path | `str` | 要渲染的文件路径。 |

| 引发 | 描述 |
| :- | :- |
| `ValueError` | 如果 `file_path` 为 `None` 或为空。 |

### 示例

```python
from groupdocs.viewer import Viewer

# 使用文档路径初始化 viewer
with Viewer("./sample.docx") as viewer:
    # viewer 已准备好渲染文档
    pass
```

## __init__ {#file_path-settings}

初始化 [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/) 类的新实例。

了解更多：

- More about file types supported by GroupDocs.Viewer: https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats
- More about GroupDocs.Viewer for .NET features: https://docs.groupdocs.com/display/viewernet/Developer+Guide

```python
def __init__(self, file_path, settings):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| file_path | `str` | 要渲染的文件路径。 |
| settings | `ViewerSettings` | Viewer 设置。 |

| 引发 | 描述 |
| :- | :- |
| `ValueError` | 如果 `settings` 为 null。 |

### 示例

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("./sample.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

## __init__ {#file_path-load_options}

初始化 [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/) 的新实例。

- More about file types supported by GroupDocs.Viewer: Document formats supported by GroupDocs.Viewer (https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
- More about GroupDocs.Viewer for .NET features: Developer Guide (https://docs.groupdocs.com/display/viewernet/Developer+Guide)
- More about loading encrypted documents and viewing files from third‑party storages with GroupDocs.Viewer for .NET: How to load and view document with GroupDocs.Viewer (https://docs.groupdocs.com/display/viewernet/Loading)

```python
def __init__(self, file_path, load_options):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| file_path | `str` | 要渲染的文件路径。 |
| load_options | `LoadOptions` | 用于打开文件的选项。 |

| 引发 | 描述 |
| :- | :- |
| `ValueError` | 如果 `load_options` 为 None。 |

### 示例

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("./sample.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

## __init__ {#file_path-load_options-settings}

初始化一个新的 Viewer 实例。

- More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
- More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)
- More about loading encrypted documents and viewing files from third‑party storages with GroupDocs.Viewer for .NET: [How to load and view document with GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Loading)

```python
def __init__(self, file_path, load_options, settings):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| file_path | `str` | 要渲染的文件路径。 |
| load_options | `LoadOptions` | 用于打开文件的选项。 |
| settings | `ViewerSettings` | Viewer 设置。 |

| 引发 | 描述 |
| :- | :- |
| `ValueError` | 如果 `settings` 为 None。 |

### 示例

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("./sample.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

### 另见
* class [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/)
