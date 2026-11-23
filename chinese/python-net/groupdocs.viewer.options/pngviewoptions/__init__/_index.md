---
title: "__init__ 构造函数"
second_title: "GroupDocs.Viewer 用于 Python，通过 .NET API 参考"
description: "初始化一个新的 PngViewOptions 实例。"
type: docs
url: /zh/python-net/groupdocs.viewer.options/pngviewoptions/__init__/
is_root: false
weight: 10
---


## __init__ {#create_page_stream}

初始化一个新的 [`PngViewOptions`](/viewer/python-net/groupdocs.viewer.options/pngviewoptions/) 实例。

有关代码示例，请参阅文档。

```python
def __init__(self, create_page_stream):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| create_page_stream | `CreatePageStream` | 实例化用于写入输出页面数据的流的方法。 |

| 引发 | 描述 |
| :- | :- |
| `ValueError` | 当 `create_page_stream` 为 None 时。 |

## __init__ {#create_page_stream-release_page_stream}

初始化一个 [`PngViewOptions`](/viewer/python-net/groupdocs.viewer.options/pngviewoptions/) 类的实例。

有关代码示例，请参阅文档。

```python
def __init__(self, create_page_stream, release_page_stream):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| create_page_stream | `CreatePageStream` | 实例化用于写入输出页面数据的流的方法。 |
| release_page_stream | `ReleasePageStream` | 释放由分配给传递给 `create_page_stream` 参数的委托的方法创建的流的方法。 |

| 引发 | 描述 |
| :- | :- |
| `ValueError` | 当 `release_page_stream` 为 None 时。 |

## __init__ {#page_stream_factory}

初始化一个新的 [`PngViewOptions`](/viewer/python-net/groupdocs.viewer.options/pngviewoptions/) 实例。

欲了解更多信息，请参阅文档。

```python
def __init__(self, page_stream_factory):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| page_stream_factory | `IPageStreamFactory` | 实现创建和释放输出页面流方法的工厂。 |

| 引发 | 描述 |
| :- | :- |
| `ValueError` | 如果 `page_stream_factory` 为 `None`。 |

## __init__

初始化一个 PngViewOptions 实例。

此构造函数创建一个 [`PngViewOptions`](/viewer/python-net/groupdocs.viewer.options/pngviewoptions/)，默认文件路径格式为 ``\"p_{0}.png\"`` 用于输出文件。生成的 PNG 文件保存在应用程序的当前工作目录中。

```python
def __init__(self):
    ...
```

### 示例

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PngViewOptions

with Viewer("document.pdf") as viewer:
    viewer.view(PngViewOptions("page_{0}.png"))
```

## __init__ {#file_path_format}

初始化一个新的 [`PngViewOptions`](/viewer/python-net/groupdocs.viewer.options/pngviewoptions/) 实例。

有关代码示例，请参阅文档。

```python
def __init__(self, file_path_format):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| file_path_format | `str` | 文件路径格式，例如 `'page_{0}.png'`。 |

| 引发 | 描述 |
| :- | :- |
| `ValueError` | 当 `file_path_format` 为 None 或为空时。 |

### 示例

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PngViewOptions

with Viewer("document.pdf") as viewer:
    viewer.view(PngViewOptions("page_{0}.png"))
```

### 另见
* class [`PngViewOptions`](/viewer/python-net/groupdocs.viewer.options/pngviewoptions/)
