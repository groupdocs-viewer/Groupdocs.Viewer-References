---
title: "ArchiveOptions 类"
second_title: "GroupDocs.Viewer 用于 Python，通过 .NET API 参考"
description: "包含用于渲染归档文件的选项。"
type: docs
url: /zh/python-net/groupdocs.viewer.options/archiveoptions/
is_root: false
weight: 10
---


## ArchiveOptions class

包含用于渲染归档文件的选项。

ArchiveOptions 类型公开以下成员：

### 构造函数
| 构造函数 | 描述 |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.options/archiveoptions/__init__/) | 初始化 [`ArchiveOptions`](/viewer/python-net/groupdocs.viewer.options/archiveoptions/) 类的实例。 |

### 属性
| 属性 | 描述 |
| :- | :- |
| [file_name](/viewer/python-net/groupdocs.viewer.options/archiveoptions/file_name/) | 显示的归档文件名。 |
| [folder](/viewer/python-net/groupdocs.viewer.options/archiveoptions/folder/) | 要渲染的文件夹。 |

### 示例

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("documents.zip") as viewer:
    view_options = HtmlViewOptions.for_embedded_resources(
        "render_specific_archive_folder/specific_archive_folder.html"
    )
    view_options.archive_options.folder = "first_folder"
    viewer.view(view_options)
```

### 另见
* module [`groupdocs.viewer.options`](/viewer/python-net/groupdocs.viewer.options/)
