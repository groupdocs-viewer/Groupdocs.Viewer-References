---
title: "Attachment 类"
second_title: "GroupDocs.Viewer 用于 Python，通过 .NET API 参考"
description: "表示电子邮件、归档、PDF 文档或 Outlook 数据文件中包含的附件文件。"
type: docs
url: /zh/python-net/groupdocs.viewer.results/attachment/
is_root: false
weight: 20
---


## Attachment class

表示电子邮件、归档、PDF 文档或 Outlook 数据文件中包含的附件文件。

Attachment 类型公开以下成员：

### 构造函数
| 构造函数 | 描述 |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.results/attachment/__init__/) | 初始化一个新的 [`Attachment`](/viewer/python-net/groupdocs.viewer.results/attachment/) 实例。 |
| [__init__](/viewer/python-net/groupdocs.viewer.results/attachment/__init__/#file_name-file_path) | 初始化一个新的 Attachment 实例。 |
| [__init__](/viewer/python-net/groupdocs.viewer.results/attachment/__init__/#id-file_name-file_path-size) | 初始化 Attachment 类的一个新实例。 |
| [__init__](/viewer/python-net/groupdocs.viewer.results/attachment/__init__/#id-file_name-file_path-file_type-size) | 初始化 Attachment 类的一个新实例。 |

### 方法
| 方法 | 描述 |
| :- | :- |
| [to_string](/viewer/python-net/groupdocs.viewer.results/attachment/to_string/) | 返回表示当前对象的字符串。 |

### 属性
| 属性 | 描述 |
| :- | :- |
| [file_name](/viewer/python-net/groupdocs.viewer.results/attachment/file_name/) | 附件文件名。 |
| [file_path](/viewer/python-net/groupdocs.viewer.results/attachment/file_path/) | 附件的相对路径，例如 `folder/file.docx`，或者当文件位于归档根目录、电子邮件消息或数据文件中时的文件名。 |
| [file_type](/viewer/python-net/groupdocs.viewer.results/attachment/file_type/) | 附件文件类型。 |
| [id](/viewer/python-net/groupdocs.viewer.results/attachment/id/) | 在包含此附件的单个文件上下文中，附件的唯一标识符。 |
| [size](/viewer/python-net/groupdocs.viewer.results/attachment/size/) | 附件文件大小（字节）。 |

### 示例

```python
from groupdocs.viewer import Viewer

with Viewer("with_attachments.msg") as viewer:
    for attachment in viewer.get_attachments():
        # 访问附件属性，例如，文件名
        print(attachment.file_name)
        # 将附件保存到文件路径
        viewer.save_attachment(attachment, f"./out/{attachment.file_name}")
```

### 另见
* module [`groupdocs.viewer.results`](/viewer/python-net/groupdocs.viewer.results/)
