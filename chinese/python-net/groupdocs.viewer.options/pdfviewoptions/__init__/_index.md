---
title: "__init__ 构造函数"
second_title: "GroupDocs.Viewer 用于 Python，通过 .NET API 参考"
description: "初始化 PdfViewOptions 的实例。"
type: docs
url: /zh/python-net/groupdocs.viewer.options/pdfviewoptions/__init__/
is_root: false
weight: 10
---


## __init__ {#create_file_stream}

初始化 [`PdfViewOptions`](/viewer/python-net/groupdocs.viewer.options/pdfviewoptions/) 的实例。

有关代码示例，请参阅位于 https://docs.groupdocs.com/viewer/net/rendering-to-pdf/ 的文档。

```python
def __init__(self, create_file_stream):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| create_file_stream | `CreateFileStream` | 实例化用于写入输出文件数据的流的方法。 |

| 引发 | 描述 |
| :- | :- |
| `ValueError` | 如果 `create_file_stream` 为 `None`。 |

## __init__ {#create_file_stream-release_file_stream}

初始化一个新的 PdfViewOptions 实例。

有关代码示例，请参阅文档。

```python
def __init__(self, create_file_stream, release_file_stream):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| create_file_stream | `CreateFileStream` | 返回用于写入输出文件数据的 `io.RawIOBase` 流的可调用对象。 |
| release_file_stream | `ReleaseFileStream` | 释放由分配给 `create_file_stream` 的方法创建的流的可调用对象。 |

| 引发 | 描述 |
| :- | :- |
| `ValueError` | 如果 `release_file_stream` 为 None。 |

## __init__ {#file_stream_factory}

初始化 PdfViewOptions 实例。

有关代码示例，请参阅文档：https://docs.groupdocs.com/viewer/net/rendering-to-pdf/

```python
def __init__(self, file_stream_factory):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| file_stream_factory | `IFileStreamFactory` | 实现创建和释放输出文件流方法的工厂。 |

| 引发 | 描述 |
| :- | :- |
| `ValueError` | 当 `file_stream_factory` 为 None 时抛出。 |

## __init__

初始化 PdfViewOptions 实例。

此构造函数使用 `\"output.pdf\"` 作为输出文件的文件路径格式来初始化 PdfViewOptions。输出文件将放置在应用程序的当前工作目录中。

```python
def __init__(self):
    ...
```

### 示例

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions

with Viewer("spreadsheet.xlsx") as viewer:
    viewer.view(PdfViewOptions("output.pdf"))
```

## __init__ {#output_file_path}

初始化 [`PdfViewOptions`](/viewer/python-net/groupdocs.viewer.options/pdfviewoptions/) 类的实例。

有关代码示例，请参阅文档。

```python
def __init__(self, output_file_path):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| output_file_path | `str` | 输出 PDF 文件的路径。 |

| 引发 | 描述 |
| :- | :- |
| `ValueError` | 当 `output_file_path` 为 None 或为空时。 |

### 示例

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions

with Viewer("spreadsheet.xlsx") as viewer:
    viewer.view(PdfViewOptions("output.pdf"))
```

### 另见
* class [`PdfViewOptions`](/viewer/python-net/groupdocs.viewer.options/pdfviewoptions/)
