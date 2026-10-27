---
title: "get_attachments 方法"
second_title: "GroupDocs.Viewer 用于 Python，通过 .NET API 参考"
description: "返回文档中包含的附件。"
type: docs
url: /zh/python-net/groupdocs.viewer/viewer/get_attachments/
is_root: false
weight: 1030
---


## get_attachments

返回文档中包含的附件。

了解更多：
- Learn more about getting document attachments in C#: https://docs.groupdocs.com/display/viewernet/Get+attachments
- Learn more about saving document attachments in C#: https://docs.groupdocs.com/display/viewernet/Save+attachments

```python
def get_attachments(self):
    ...
```

**Returns:** Attachments contained by the document.

| 引发 | 描述 |
| :- | :- |
| `PasswordRequiredException` | 当打开文档需要密码时抛出。 |
| `IncorrectPasswordException` | 当指定的密码不正确时抛出。 |

### 示例

```python
from groupdocs.viewer import Viewer

with Viewer("with_attachments.msg") as viewer:
    for attachment in viewer.get_attachments():
        # 将每个附件保存到文件
        viewer.save_attachment(attachment, f"./out/{attachment.file_name}")
```

### 另见
* class [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/)
