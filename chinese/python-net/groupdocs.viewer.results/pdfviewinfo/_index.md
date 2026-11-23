---
title: "PdfViewInfo 类"
second_title: "GroupDocs.Viewer 用于 Python，通过 .NET API 参考"
description: "表示 PDF 文档的视图信息。"
type: docs
url: /zh/python-net/groupdocs.viewer.results/pdfviewinfo/
is_root: false
weight: 140
---


## PdfViewInfo class

表示 PDF 文档的视图信息。

该 PdfViewInfo 类型公开以下成员：

### 构造函数
| 构造函数 | 描述 |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.results/pdfviewinfo/__init__/) | 初始化一个新的 PdfViewInfo 实例。 |
| [__init__](/viewer/python-net/groupdocs.viewer.results/pdfviewinfo/__init__/#file_type-pages-printing_allowed) | 初始化一个新的 PdfViewInfo 实例。 |

### 方法
| 方法 | 描述 |
| :- | :- |
| [to_string](/viewer/python-net/groupdocs.viewer.results/viewinfo/to_string/) | 返回表示当前对象的字符串。（继承自 [`ViewInfo`](/viewer/python-net/groupdocs.viewer.results/viewinfo/)） |

### 属性
| 属性 | 描述 |
| :- | :- |
| [printing_allowed](/viewer/python-net/groupdocs.viewer.results/pdfviewinfo/printing_allowed/) | printing_allowed 属性指示是否允许对文档进行打印。 |
| [file_type](/viewer/python-net/groupdocs.viewer.results/viewinfo/file_type/) | 文件的类型。（继承自 [`ViewInfo`](/viewer/python-net/groupdocs.viewer.results/viewinfo/)） |
| [pages](/viewer/python-net/groupdocs.viewer.results/viewinfo/pages/) | 要查看的页面列表。（继承自 [`ViewInfo`](/viewer/python-net/groupdocs.viewer.results/viewinfo/)） |

### 示例

```python
from typing import cast
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import ViewInfoOptions
from groupdocs.viewer.results import PdfViewInfo

def get_pdf_info():
    with Viewer("sample.pdf") as viewer:
        info = viewer.get_view_info(ViewInfoOptions.for_html_view())
        pdf_info = cast(PdfViewInfo, info)

        print("File type:", pdf_info.file_type)
        print("Pages count:", len(pdf_info.pages))
        print("Printing allowed:", pdf_info.printing_allowed)

if __name__ == "__main__":
    get_pdf_info()
```

### Guides
使用 `PdfViewInfo` 的任务指南：

* [Get Document Information](/viewer/python-net/guides/get-document-info/)

### 另见
* module [`groupdocs.viewer.results`](/viewer/python-net/groupdocs.viewer.results/)
