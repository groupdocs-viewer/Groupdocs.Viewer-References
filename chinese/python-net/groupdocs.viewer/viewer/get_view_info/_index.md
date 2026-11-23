---
title: "get_view_info 方法"
second_title: "GroupDocs.Viewer 用于 Python，通过 .NET API 参考"
description: "返回视图和文档特定的信息。"
type: docs
url: /zh/python-net/groupdocs.viewer/viewer/get_view_info/
is_root: false
weight: 1050
---


## get_view_info {#options}

返回视图和文档特定的信息。

了解有关文档的更多信息——文件类型、页数以及其他特定格式属性：
- [How to get file information using GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Get+file+information)

```python
def get_view_info(self, options):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| options | `ViewInfoOptions` | 视图信息选项。 |

**Returns:** Information about view and document specific information.

| 引发 | 描述 |
| :- | :- |
| `ValueError` | 当 `options` 为 None 时。 |
| `PasswordRequiredException` | 当打开文档需要密码时。 |
| `IncorrectPasswordException` | 当指定的密码不正确时。 |

### 示例

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import ViewInfoOptions

with Viewer("document.pdf") as viewer:
    info = viewer.get_view_info(ViewInfoOptions.for_html_view())
    print(f"Pages: {len(info.pages)}")
    for page in info.pages:
        print(f"  Page {page.number}: {page.width}x{page.height}")
```

### 另见
* class [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/)
