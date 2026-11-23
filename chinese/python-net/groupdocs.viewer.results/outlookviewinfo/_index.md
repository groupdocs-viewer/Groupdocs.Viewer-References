---
title: "OutlookViewInfo 类"
second_title: "GroupDocs.Viewer 用于 Python，通过 .NET API 参考"
description: "表示 Outlook 数据文件的视图信息。"
type: docs
url: /zh/python-net/groupdocs.viewer.results/outlookviewinfo/
is_root: false
weight: 120
---


## OutlookViewInfo class

表示 Outlook 数据文件的视图信息。

OutlookViewInfo 类型公开以下成员：

### 构造函数
| 构造函数 | 描述 |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.results/outlookviewinfo/__init__/) | 初始化一个新的 [`OutlookViewInfo`](/viewer/python-net/groupdocs.viewer.results/outlookviewinfo/) 实例。 |
| [__init__](/viewer/python-net/groupdocs.viewer.results/outlookviewinfo/__init__/#file_type-pages-folders) | 初始化一个新的 OutlookViewInfo 实例。 |

### 方法
| 方法 | 描述 |
| :- | :- |
| [to_string](/viewer/python-net/groupdocs.viewer.results/viewinfo/to_string/) | 返回表示当前对象的字符串。（继承自 [`ViewInfo`](/viewer/python-net/groupdocs.viewer.results/viewinfo/)） |

### 属性
| 属性 | 描述 |
| :- | :- |
| [folders](/viewer/python-net/groupdocs.viewer.results/outlookviewinfo/folders/) | Outlook 数据文件中包含的文件夹列表。 |
| [file_type](/viewer/python-net/groupdocs.viewer.results/viewinfo/file_type/) | 文件的类型。（继承自 [`ViewInfo`](/viewer/python-net/groupdocs.viewer.results/viewinfo/)） |
| [pages](/viewer/python-net/groupdocs.viewer.results/viewinfo/pages/) | 要查看的页面列表。（继承自 [`ViewInfo`](/viewer/python-net/groupdocs.viewer.results/viewinfo/)） |

### 示例

```python
from typing import cast
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import ViewInfoOptions
from groupdocs.viewer.results import OutlookViewInfo

def get_outlook_info():
    with Viewer("sample.pst") as viewer:
        info = viewer.get_view_info(ViewInfoOptions.for_html_view())
        outlook_info = cast(OutlookViewInfo, info)

        print("File type:", outlook_info.file_type)
        print("Pages count:", len(outlook_info.pages))
        print("Folders:")
        for folder in outlook_info.folders:
            print(f"  {folder}")

if __name__ == "__main__":
    get_outlook_info()
```

### Guides
使用 `OutlookViewInfo` 的任务指南：

* [Get Document Information](/viewer/python-net/guides/get-document-info/)

### 另见
* module [`groupdocs.viewer.results`](/viewer/python-net/groupdocs.viewer.results/)
