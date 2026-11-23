---
title: "save_attachment 方法"
second_title: "GroupDocs.Viewer 用于 Python，通过 .NET API 参考"
description: "将附件文件保存到目标流。"
type: docs
url: /zh/python-net/groupdocs.viewer/viewer/save_attachment/
is_root: false
weight: 1070
---


## save_attachment {#attachment-destination}

将附件文件保存到 `destination` 流。

- Learn more about getting document attachments in C#: https://docs.groupdocs.com/display/viewernet/Get+attachments
- Learn more about saving document attachments in C#: https://docs.groupdocs.com/display/viewernet/Save+attachments

```python
def save_attachment(self, attachment, destination):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| attachment | `Attachment` | 附件。 |
| destination | `io.RawIOBase` | 可写流。 |

| 引发 | 描述 |
| :- | :- |
| `ValueError` | 当 `destination` 为 None 时。 |
| `PasswordRequiredException` | 当打开文档需要密码时。 |
| `IncorrectPasswordException` | 当指定的密码不正确时。 |
| `GroupDocsViewerException` | 当未找到附件时。 |

### 示例

```python
from groupdocs.viewer import Viewer

with Viewer("with_attachments.msg") as viewer:
    for attachment in viewer.get_attachments():
        viewer.save_attachment(attachment, f"./out/{attachment.file_name}")
```

### 另见
* class [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/)
