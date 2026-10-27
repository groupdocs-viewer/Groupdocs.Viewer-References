---
title: "for_embedded_resources 方法"
second_title: "GroupDocs.Viewer 用于 Python，通过 .NET API 参考"
description: "初始化一个 HtmlViewOptions 实例，用于渲染带有嵌入资源的 HTML。"
type: docs
url: /zh/python-net/groupdocs.viewer.options/htmlviewoptions/for_embedded_resources/
is_root: false
weight: 1010
---


## for_embedded_resources {#create_page_stream}

初始化一个 HtmlViewOptions 实例，用于渲染带有嵌入资源的 HTML。

欲了解更多详情，请参阅文档。

```python
def for_embedded_resources(cls, create_page_stream):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| create_page_stream | `CreatePageStream` | 实例化用于写入输出页面数据的流的方法。 |

**Returns:** HtmlViewOptions: New instance configured for rendering HTML with embedded resources.

| 引发 | 描述 |
| :- | :- |
| `ValueError` | 如果 `create_page_stream` 为 None。 |

### 示例

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("document.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

## for_embedded_resources {#create_page_stream-release_page_stream}

初始化 [`HtmlViewOptions`](/viewer/python-net/groupdocs.viewer.options/htmlviewoptions/) 类的实例，用于渲染为带有嵌入资源的 HTML。

```python
def for_embedded_resources(cls, create_page_stream, release_page_stream):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| create_page_stream | `CreatePageStream` | 实例化用于写入输出页面数据的流的方法。 |
| release_page_stream | `ReleasePageStream` | 释放由分配给 `create_page_stream` 参数的方法创建的流的方法。 |

**Returns:** HtmlViewOptions: New instance of the `HtmlViewOptions` class for rendering into HTML with embedded resources.

| 引发 | 描述 |
| :- | :- |
| `ValueError` | 如果 `release_page_stream` 为 `None`。有关代码示例，请参阅文档。 |

## for_embedded_resources {#page_stream_factory}

初始化一个 HtmlViewOptions 实例，用于渲染为带有嵌入资源的 HTML。

有关代码示例，请参阅位于 https://docs.groupdocs.com/viewer/net/rendering-to-html/#rendering-to-html-with-embedded-resources 的文档。

```python
def for_embedded_resources(cls, page_stream_factory):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| page_stream_factory | `IPageStreamFactory` | 实现创建和释放输出页面流方法的工厂。 |

**Returns:** HtmlViewOptions: New instance of HtmlViewOptions for rendering into HTML with embedded resources.

| 引发 | 描述 |
| :- | :- |
| `ValueError` | 当 page_stream_factory 为 None 时。 |

### 示例

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("document.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

## for_embedded_resources

初始化 [`HtmlViewOptions`](/viewer/python-net/groupdocs.viewer.options/htmlviewoptions/) 类的实例，使用嵌入资源。

有关代码示例，请参阅文档。

```python
def for_embedded_resources(cls):
    ...
```

### 示例

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("document.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

## for_embedded_resources {#file_path_format}

初始化一个 HtmlViewOptions 实例，用于嵌入资源。

有关代码示例，请参阅文档。

```python
def for_embedded_resources(cls, file_path_format):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| file_path_format | `str` | 文件路径格式，例如 'page_{0}.html'。 |

| 引发 | 描述 |
| :- | :- |
| `ValueError` | 当 `file_path_format` 为 None 或为空时。 |

### 示例

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("document.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

### 另见
* class [`HtmlViewOptions`](/viewer/python-net/groupdocs.viewer.options/htmlviewoptions/)
