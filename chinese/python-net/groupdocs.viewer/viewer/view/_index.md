---
title: "view 方法"
second_title: "GroupDocs.Viewer 用于 Python，通过 .NET API 参考"
description: "创建所有文档页面的视图。"
type: docs
url: /zh/python-net/groupdocs.viewer/viewer/view/
is_root: false
weight: 1130
---


## view {#options}

创建所有文档页面的视图。

了解更多

- More about different viewing options following this guide: https://docs.groupdocs.com/display/viewernet/Viewing

```python
def view(self, options):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| options | `ViewOptions` | 视图选项。 |

| 引发 | 描述 |
| :- | :- |
| `ValueError` | 当 `options` 为 None 时。 |
| `PasswordRequiredException` | 当打开文档需要密码时。 |
| `IncorrectPasswordException` | 当指定的密码不正确时。 |
| `GroupDocsViewerException` | 当未找到附件时。 |

### 示例

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("./sample.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

## view {#options-page_numbers}

创建特定文档页面的视图。

了解更多

- More about different viewing options following this guide: https://docs.groupdocs.com/display/viewernet/Viewing

```python
def view(self, options, page_numbers):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| options | `ViewOptions` | 视图选项。 |
| page_numbers | `list[int]` | 要查看的页码。 |

| 引发 | 描述 |
| :- | :- |
| `ValueError` | 当 `page_numbers` 为空时。 |
| `PasswordRequiredException` | 当打开文档需要密码时。 |
| `IncorrectPasswordException` | 当指定的密码不正确时。 |
| `GroupDocsViewerException` | 当未找到附件时。 |

### 示例

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("./sample.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

## view {#options-cancellation_token-page_numbers}

创建特定文档页面的视图。

了解更多：

- More about different viewing options following this guide: https://docs.groupdocs.com/display/viewernet/Viewing

```python
def view(self, options, cancellation_token, page_numbers):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| options | `ViewOptions` | 视图选项。 |
| cancellation_token | `CancellationToken` | 用于取消处理的取消令牌。 |
| page_numbers | `list[int]` | 要查看的页码。 |

| 引发 | 描述 |
| :- | :- |
| `ValueError` | 当 `page_numbers` 为空时。 |
| `PasswordRequiredException` | 当打开文档需要密码时。 |
| `IncorrectPasswordException` | 当指定的密码不正确时。 |
| `GroupDocsViewerException` | 当未找到附件时。 |

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
