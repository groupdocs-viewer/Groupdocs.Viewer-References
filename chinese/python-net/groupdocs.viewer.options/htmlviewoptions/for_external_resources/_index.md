---
title: "for_external_resources 方法"
second_title: "GroupDocs.Viewer 用于 Python，通过 .NET API 参考"
description: "初始化 HtmlViewOptions 类的实例，用于渲染为带有外部资源的 HTML。"
type: docs
url: /zh/python-net/groupdocs.viewer.options/htmlviewoptions/for_external_resources/
is_root: false
weight: 1060
---


## for_external_resources {#create_page_stream-create_resource_stream-create_resource_url}

初始化 [`HtmlViewOptions`](/viewer/python-net/groupdocs.viewer.options/htmlviewoptions/) 类的实例，用于渲染为带有外部资源的 HTML。

有关代码示例，请参阅文档。

```python
def for_external_resources(cls, create_page_stream, create_resource_stream, create_resource_url):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| create_page_stream | `CreatePageStream` | 实例化用于写入输出页面数据的流的方法。 |
| create_resource_stream | `CreateResourceStream` | 释放由 `create_page_stream` 方法创建的流的方法。 |
| create_resource_url | `CreateResourceUrl` | 创建 HTML 资源 URL 的方法。 |

**Returns:** New instance of the `HtmlViewOptions` class for rendering into HTML with external resources.

| 引发 | 描述 |
| :- | :- |
| `ValueError` | 当 `create_resource_url` 为 None 时。 |

### 示例

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("sample.docx") as viewer:
    options = HtmlViewOptions.for_external_resources(
        "page_{0}.html",
        "page_{0}/resource_{0}_{1}",
        "page_{0}/resource_{0}_{1}"
    )
    viewer.view(options)
```

## for_external_resources {#create_page_stream-create_resource_stream-create_resource_url-release_page_stream-release_resource_stream}

初始化 HtmlViewOptions 类的实例，用于渲染为带有外部资源的 HTML。

有关其他使用示例，请参阅 GroupDocs Viewer 文档。

```python
def for_external_resources(cls, create_page_stream, create_resource_stream, create_resource_url, release_page_stream, release_resource_stream):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| create_page_stream | `CreatePageStream` | 实例化用于写入输出页面数据的流的方法。 |
| create_resource_stream | `CreateResourceStream` | 实例化用于写入输出 HTML 资源数据的流的方法。 |
| create_resource_url | `CreateResourceUrl` | 创建 HTML 资源 URL 的方法。 |
| release_page_stream | `ReleasePageStream` | 释放由传递给 `create_page_stream` 的委托创建的流的方法。 |
| release_resource_stream | `ReleaseResourceStream` | 释放由传递给 `create_resource_stream` 的委托创建的流的方法。 |

**Returns:** HtmlViewOptions: New instance of the HtmlViewOptions class for rendering into HTML with external resources.

| 引发 | 描述 |
| :- | :- |
| `ValueError` | 当 `release_resource_stream` 为 None 时。 |

### 示例

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

def render_excel_to_html_external():
    # 加载 Excel 电子表格
    with Viewer("invoice.xlsx") as viewer:
        # 将电子表格转换为带有外部资源的 HTML。
        # {0} 和 {1} 分别被替换为当前页码和资源名称。
        view_options = HtmlViewOptions.for_external_resources(
            "render_excel_to_html_external/pdf_page_{0}.html",
            "render_excel_to_html_external/pdf_page_{0}/resource_{0}_{1}",
            "render_excel_to_html_external/pdf_page_{0}/resource_{0}_{1}"
        )
        viewer.view(view_options)

if __name__ == "__main__":
    render_excel_to_html_external()
```

## for_external_resources {#page_stream_factory-resource_stream_factory}

初始化一个 HtmlViewOptions 实例，用于渲染为带有外部资源的 HTML。

欲了解更多详情，请参阅在线文档。

```python
def for_external_resources(cls, page_stream_factory, resource_stream_factory):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| page_stream_factory | `IPageStreamFactory` | 实现创建和释放输出页面流方法的工厂。 |
| resource_stream_factory | `IResourceStreamFactory` | 实现创建资源 URL、实例化以及释放输出 HTML 资源流所需方法的工厂。 |

**Returns:** HtmlViewOptions: A new HtmlViewOptions instance configured for external resources.

| 引发 | 描述 |
| :- | :- |
| `ValueError` | 如果 `resource_stream_factory` 为 None。 |

### 示例

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

def render_to_html_external():
    # 为每个页面创建一个 HTML 文件，并单独存储外部资源。
    # {0} 和 {1} 分别被替换为当前页码和资源名称。
    with Viewer("sample.docx") as viewer:
        html_options = HtmlViewOptions.for_external_resources(
            "page_{0}.html",
            "page_{0}/resource_{0}_{1}",
            "page_{0}/resource_{0}_{1}"
        )
        viewer.view(html_options)

if __name__ == "__main__":
    render_to_html_external()
```

## for_external_resources

初始化一个配置为生成带有外部资源的 HTML 文件的 HtmlViewOptions 实例。

实例使用提供的格式字符串：
- `html_file_path_format` – file path format for the output HTML files (e.g., `"page_{0}.html"`).
- `resources_path_format` – folder path format for external resource files (e.g., `"page_{0}/resource_{0}_{1}"`).
- `resources_url_format` – URL format for HTML resources (e.g., `"page_{0}/resource_{0}_{1}"`).

输出文件放置在应用程序的当前工作目录中。

```python
def for_external_resources(cls):
    ...
```

**Returns:** HtmlViewOptions: Configured options for rendering HTML with external resources.

### 示例

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

def render_docx_to_html_external():
    with Viewer("sample.docx") as viewer:
        html_options = HtmlViewOptions.for_external_resources(
            "page_{0}.html",
            "page_{0}/resource_{0}_{1}",
            "page_{0}/resource_{0}_{1}"
        )
        viewer.view(html_options)

if __name__ == "__main__":
    render_docx_to_html_external()
```

## for_external_resources {#file_path_format-resource_file_path_format-resource_url_format}

初始化 [`HtmlViewOptions`](/viewer/python-net/groupdocs.viewer.options/htmlviewoptions/) 类的实例。

有关代码示例，请参阅文档。

```python
def for_external_resources(cls, file_path_format, resource_file_path_format, resource_url_format):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| file_path_format | `str` | 文件路径格式，例如 `'page_{0}.html'`。 |
| resource_file_path_format | `str` | 资源文件路径格式，例如 `'page_{0}/resource_{1}'`。 |
| resource_url_format | `str` | 资源 URL 格式，例如 `'page_{0}/resource_{1}'`。 |

| 引发 | 描述 |
| :- | :- |
| `ValueError` | 如果 `resource_url_format` 为 None 或为空。 |

### 示例

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

def render_to_html_external():
    # 加载文档并将每页渲染为带有外部资源的 HTML 文件。
    with Viewer("sample.docx") as viewer:
        html_options = HtmlViewOptions.for_external_resources(
            "page_{0}.html",
            "page_{0}/resource_{0}_{1}",
            "page_{0}/resource_{0}_{1}"
        )
        viewer.view(html_options)

if __name__ == "__main__":
    render_to_html_external()
```

### 另见
* class [`HtmlViewOptions`](/viewer/python-net/groupdocs.viewer.options/htmlviewoptions/)
