---
title: "Security 类"
second_title: "GroupDocs.Viewer 用于 Python，通过 .NET API 参考"
description: "PDF 文档安全选项."
type: docs
url: /zh/python-net/groupdocs.viewer.options/security/
is_root: false
weight: 260
---


## Security class

PDF 文档安全选项.

有关详细信息，请参阅文档。

Security 类型公开以下成员：

### 构造函数
| 构造函数 | 描述 |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.options/security/__init__/) | 初始化 [`Security`](/viewer/python-net/groupdocs.viewer.options/security/) 类的实例。 |

### 属性
| 属性 | 描述 |
| :- | :- |
| [document_open_password](/viewer/python-net/groupdocs.viewer.options/security/document_open_password/) | 打开 PDF 文档所需的密码。 |
| [permissions](/viewer/python-net/groupdocs.viewer.options/security/permissions/) | PDF 文档的权限，例如打印、修改和数据提取。 |
| [permissions_password](/viewer/python-net/groupdocs.viewer.options/security/permissions_password/) | 更改权限设置所需的密码。 |

### 示例

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions, Security, Permissions

with Viewer("sample.docx") as viewer:
    security = Security()
    security.document_open_password = "o123"
    security.permissions_password = "p123"
    security.permissions = Permissions.ALLOW_ALL & ~Permissions.DENY_PRINTING

    pdf_options = PdfViewOptions("protected_document.pdf")
    pdf_options.security = security
    viewer.view(pdf_options)
```

### Guides
使用 `Security` 的任务指南：

* [Protect PDF document](/viewer/python-net/guides/protect-pdf-document/)

### 另见
* module [`groupdocs.viewer.options`](/viewer/python-net/groupdocs.viewer.options/)
