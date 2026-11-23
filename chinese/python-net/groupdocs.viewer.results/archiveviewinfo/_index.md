---
title: "ArchiveViewInfo 类"
second_title: "GroupDocs.Viewer 用于 Python，通过 .NET API 参考"
description: "表示归档文件的视图信息。"
type: docs
url: /zh/python-net/groupdocs.viewer.results/archiveviewinfo/
is_root: false
weight: 10
---


## ArchiveViewInfo class

表示归档文件的视图信息。

ArchiveViewInfo 类型公开以下成员：

### 构造函数
| 构造函数 | 描述 |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.results/archiveviewinfo/__init__/) | 初始化一个新的 [`ArchiveViewInfo`](/viewer/python-net/groupdocs.viewer.results/archiveviewinfo/) 实例。 |
| [__init__](/viewer/python-net/groupdocs.viewer.results/archiveviewinfo/__init__/#file_type-pages-folders) | 初始化一个新的 ArchiveViewInfo 实例。 |

### 方法
| 方法 | 描述 |
| :- | :- |
| [to_string](/viewer/python-net/groupdocs.viewer.results/viewinfo/to_string/) | 返回表示当前对象的字符串。（继承自 [`ViewInfo`](/viewer/python-net/groupdocs.viewer.results/viewinfo/)） |

### 属性
| 属性 | 描述 |
| :- | :- |
| [folders](/viewer/python-net/groupdocs.viewer.results/archiveviewinfo/folders/) | 归档文件中包含的文件夹。 |
| [file_type](/viewer/python-net/groupdocs.viewer.results/viewinfo/file_type/) | 文件的类型。（继承自 [`ViewInfo`](/viewer/python-net/groupdocs.viewer.results/viewinfo/)） |
| [pages](/viewer/python-net/groupdocs.viewer.results/viewinfo/pages/) | 要查看的页面列表。（继承自 [`ViewInfo`](/viewer/python-net/groupdocs.viewer.results/viewinfo/)） |

### 示例

```python
from typing import cast
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import ViewInfoOptions
from groupdocs.viewer.results import ArchiveViewInfo

def get_archive_info():
    with Viewer("documents.zip") as viewer:
        info = viewer.get_view_info(ViewInfoOptions.for_html_view())
        archive_info = cast(ArchiveViewInfo, info)

        print("File type:", archive_info.file_type)
        print("Pages count:", len(archive_info.pages))
        print("Folders:")
        for folder in archive_info.folders:
            print(f"  {folder}")

if __name__ == "__main__":
    get_archive_info()
```

### Guides
使用 `ArchiveViewInfo` 的任务指南：

* [Get Document Information](/viewer/python-net/guides/get-document-info/)

### 另见
* module [`groupdocs.viewer.results`](/viewer/python-net/groupdocs.viewer.results/)
