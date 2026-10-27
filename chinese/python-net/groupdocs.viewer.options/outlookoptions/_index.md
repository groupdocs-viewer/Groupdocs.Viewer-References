---
title: "OutlookOptions 类"
second_title: "GroupDocs.Viewer 用于 Python，通过 .NET API 参考"
description: "包含渲染 Outlook 数据文件的选项."
type: docs
url: /zh/python-net/groupdocs.viewer.options/outlookoptions/
is_root: false
weight: 130
---


## OutlookOptions class

包含渲染 Outlook 数据文件的选项.

有关详细信息，请参阅 GroupDocs 文档。

OutlookOptions 类型公开以下成员：

### 构造函数
| 构造函数 | 描述 |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.options/outlookoptions/__init__/) |  |

### 属性
| 属性 | 描述 |
| :- | :- |
| [address_filter](/viewer/python-net/groupdocs.viewer.options/outlookoptions/address_filter/) | 用于按发件人或收件人过滤邮件的电子邮件地址。 |
| [folder](/viewer/python-net/groupdocs.viewer.options/outlookoptions/folder/) | 要呈现的文件夹名称（例如 Inbox、Sent Item 或 Deleted Items）。 |
| [max_items_in_folder](/viewer/python-net/groupdocs.viewer.options/outlookoptions/max_items_in_folder/) | 可以从单个文件夹呈现的最大消息或项目数量。 |
| [text_filter](/viewer/python-net/groupdocs.viewer.options/outlookoptions/text_filter/) | 用于过滤消息的关键字。 |

### 示例

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

def render_outlook():
    with Viewer("sample.pst") as viewer:
        view_options = HtmlViewOptions.for_embedded_resources(
            "outlook.html"
        )
        # 限制每个文件夹呈现的项目数量。
        view_options.outlook_options.max_items_in_folder = 30
        viewer.view(view_options)
```

### 另见
* module [`groupdocs.viewer.options`](/viewer/python-net/groupdocs.viewer.options/)
