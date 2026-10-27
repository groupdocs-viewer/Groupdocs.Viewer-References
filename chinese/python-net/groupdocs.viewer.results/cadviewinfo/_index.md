---
title: "CadViewInfo 类"
second_title: "GroupDocs.Viewer 用于 Python，通过 .NET API 参考"
description: "表示 CAD 绘图的视图信息。"
type: docs
url: /zh/python-net/groupdocs.viewer.results/cadviewinfo/
is_root: false
weight: 30
---


## CadViewInfo class

表示 CAD 绘图的视图信息。

该 CadViewInfo 类型公开以下成员：

### 构造函数
| 构造函数 | 描述 |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.results/cadviewinfo/__init__/#file_type-pages-layers-layouts) | 初始化一个新的 CadViewInfo 实例。 |

### 方法
| 方法 | 描述 |
| :- | :- |
| [to_string](/viewer/python-net/groupdocs.viewer.results/viewinfo/to_string/) | 返回表示当前对象的字符串。（继承自 [`ViewInfo`](/viewer/python-net/groupdocs.viewer.results/viewinfo/)） |

### 属性
| 属性 | 描述 |
| :- | :- |
| [layers](/viewer/python-net/groupdocs.viewer.results/cadviewinfo/layers/) | 该 CAD 绘图包含的图层列表。 |
| [layouts](/viewer/python-net/groupdocs.viewer.results/cadviewinfo/layouts/) | 该 CAD 绘图包含的布局列表。 |
| [file_type](/viewer/python-net/groupdocs.viewer.results/viewinfo/file_type/) | 文件的类型。（继承自 [`ViewInfo`](/viewer/python-net/groupdocs.viewer.results/viewinfo/)） |
| [pages](/viewer/python-net/groupdocs.viewer.results/viewinfo/pages/) | 要查看的页面列表。（继承自 [`ViewInfo`](/viewer/python-net/groupdocs.viewer.results/viewinfo/)） |

### 示例

```python
from typing import cast
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import ViewInfoOptions
from groupdocs.viewer.results import CadViewInfo

def get_cad_info():
    with Viewer("sample.dwg") as viewer:
        info = viewer.get_view_info(ViewInfoOptions.for_html_view())
        cad_info = cast(CadViewInfo, info)

        print("File type:", cad_info.file_type)
        print("Pages count:", len(cad_info.pages))
        print("Layers:")
        for layer in cad_info.layers:
            print(f"  {layer.name} (visible={layer.visible})")
        print("Layouts:")
        for layout in cad_info.layouts:
            print(f"  {layout.name} ({layout.width}x{layout.height})")

if __name__ == "__main__":
    get_cad_info()
```

### Guides
使用 `CadViewInfo` 的任务指南：

* [Get Document Information](/viewer/python-net/guides/get-document-info/)

### 另见
* module [`groupdocs.viewer.results`](/viewer/python-net/groupdocs.viewer.results/)
