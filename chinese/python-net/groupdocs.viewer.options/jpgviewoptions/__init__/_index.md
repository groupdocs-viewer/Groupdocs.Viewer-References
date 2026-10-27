---
title: "__init__ 构造函数"
second_title: "GroupDocs.Viewer 用于 Python，通过 .NET API 参考"
description: "初始化 JpgViewOptions 类的实例。"
type: docs
url: /zh/python-net/groupdocs.viewer.options/jpgviewoptions/__init__/
is_root: false
weight: 10
---


## __init__ {#create_page_stream}

初始化 JpgViewOptions 类的实例。

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

初始化 JpgViewOptions 类的实例。

有关代码示例，请参阅文档。

```python
def __init__(self, create_page_stream, release_page_stream):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| create_page_stream | `CreatePageStream` | 可调用对象，用于实例化用于写入输出页面数据的流。 |
| release_page_stream | `ReleasePageStream` | 可调用对象，用于释放由传递给 `create_page_stream` 的委托分配的方法创建的流。 |

| 引发 | 描述 |
| :- | :- |
| `ValueError` | 如果 `release_page_stream` 为 None。 |

## __init__ {#page_stream_factory}

初始化 [`JpgViewOptions`](/viewer/python-net/groupdocs.viewer.options/jpgviewoptions/) 类的实例。

有关代码示例，请参阅位于 https://docs.groupdocs.com/viewer/net/rendering-to-png-or-jpeg/#rendering-to-jpeg 的文档。

```python
def __init__(self, page_stream_factory):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| page_stream_factory | `IPageStreamFactory` | 实现创建和释放输出页面流方法的工厂。 |

| 引发 | 描述 |
| :- | :- |
| `ValueError` | 当 `page_stream_factory` 为 None 时。 |

## __init__

初始化 JpgViewOptions 实例。

此构造函数使用 `"p_{0}.jpg"` 作为输出文件的文件路径格式，初始化 [`JpgViewOptions`](/viewer/python-net/groupdocs.viewer.options/jpgviewoptions/) 的实例。输出文件将放置在应用程序的当前工作目录中。

```python
def __init__(self):
    ...
```

### 示例

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

初始化 [`JpgViewOptions`](/viewer/python-net/groupdocs.viewer.options/jpgviewoptions/) 的新实例。

有关代码示例，请参阅文档。

```python
def __init__(self, file_path_format):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| file_path_format | `str` | 文件路径格式，例如 `'page_{0}.jpg'`。 |

| 引发 | 描述 |
| :- | :- |
| `ValueError` | 如果 `file_path_format` 为 None 或为空。 |

### 示例

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import JpgViewOptions

def render_to_jpg():
    # 加载文档（例如 Excel 文件）
    with Viewer("invoice.xlsx") as viewer:
        # 使用文件名模式创建 JPEG 视图选项。
        view_options = JpgViewOptions("output/excel_page_{0}.jpg")
        view_options.width = 800
        view_options.height = 900
        viewer.view(view_options)

if __name__ == "__main__":
    render_to_jpg()
```

### 另见
* class [`JpgViewOptions`](/viewer/python-net/groupdocs.viewer.options/jpgviewoptions/)
