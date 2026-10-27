---
title: "LoadOptions 类"
second_title: "GroupDocs.Viewer 用于 Python，通过 .NET API 参考"
description: "用于打开文件的选项."
type: docs
url: /zh/python-net/groupdocs.viewer.options/loadoptions/
is_root: false
weight: 110
---


## LoadOptions class

用于打开文件的选项.

LoadOptions 类型公开以下成员：

### 构造函数
| 构造函数 | 描述 |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.options/loadoptions/__init__/) | 初始化 [`LoadOptions`](/viewer/python-net/groupdocs.viewer.options/loadoptions/) 类的实例。 |
| [__init__](/viewer/python-net/groupdocs.viewer.options/loadoptions/__init__/#file_type) | 初始化一个新的 LoadOptions 实例。 |

### 属性
| 属性 | 描述 |
| :- | :- |
| [detect_encoding](/viewer/python-net/groupdocs.viewer.options/loadoptions/detect_encoding/) | 该属性启用对 [`FileType.txt`](/viewer/python-net/groupdocs.viewer/filetype/txt/)、[`FileType.csv`](/viewer/python-net/groupdocs.viewer/filetype/csv/)、以及 [`FileType.tsv`](/viewer/python-net/groupdocs.viewer/filetype/tsv/) 文件的编码检测。 |
| [encoding](/viewer/python-net/groupdocs.viewer.options/loadoptions/encoding/) | 打开基于文本的文件或电子邮件（如 [`FileType.csv`](/viewer/python-net/groupdocs.viewer/filetype/csv/)、[`FileType.txt`](/viewer/python-net/groupdocs.viewer/filetype/txt/)、和 [`FileType.msg`](/viewer/python-net/groupdocs.viewer/filetype/msg/)）时使用的编码。默认值为 `utf-8`。 |
| [file_type](/viewer/python-net/groupdocs.viewer.options/loadoptions/file_type/) | 要打开的文件类型。 |
| [password](/viewer/python-net/groupdocs.viewer.options/loadoptions/password/) | 打开加密文件的密码。 |
| [resource_loading_timeout](/viewer/python-net/groupdocs.viewer.options/loadoptions/resource_loading_timeout/) | 加载外部资源的超时时间。 |
| [skip_external_resources](/viewer/python-net/groupdocs.viewer.options/loadoptions/skip_external_resources/) | 该属性禁用加载所有外部资源（例如图像），但列在 [`LoadOptions.whitelisted_resources`](/viewer/python-net/groupdocs.viewer.options/loadoptions/whitelisted_resources/) 中的除外。 |
| [try_repair](/viewer/python-net/groupdocs.viewer.options/loadoptions/try_repair/) | 该属性使 GroupDocs.Viewer 尝试修复 PDF 文档中的结构损坏。默认值为 False。 |
| [whitelisted_resources](/viewer/python-net/groupdocs.viewer.options/loadoptions/whitelisted_resources/) | 当 [`LoadOptions.skip_external_resources`](/viewer/python-net/groupdocs.viewer.options/loadoptions/skip_external_resources/) 设置为 `True` 时，应加载的对应外部资源的 URL 片段列表。 |

### 示例

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions, LoadOptions

load_options = LoadOptions()
load_options.password = "12345"

with Viewer("protected.docx", load_options) as viewer:
    viewer.view(HtmlViewOptions.for_embedded_resources("page_{0}.html"))
```

### 另见
* module [`groupdocs.viewer.options`](/viewer/python-net/groupdocs.viewer.options/)
