---
title: "rotate_page 方法"
second_title: "GroupDocs.Viewer 用于 Python，通过 .NET API 参考"
description: "对页面应用顺时针旋转。"
type: docs
url: /zh/python-net/groupdocs.viewer.options/viewoptions/rotate_page/
is_root: false
weight: 1010
---


## rotate_page {#page_number-rotation}

对页面应用顺时针旋转。

有关详细信息，请参阅位于 https://docs.groupdocs.com/viewer/net/flip-or-rotate-pages/ 的文档。

```python
def rotate_page(self, page_number, rotation):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| page_number | `int` | 页面编号必须严格大于 0。 |
| rotation | `Rotation` | 旋转值。 |

| 引发 | 描述 |
| :- | :- |
| `ValueError` | 如果已为编号为 `page_number` 的页面添加了旋转。 |

### 另见
* class [`ViewOptions`](/viewer/python-net/groupdocs.viewer.options/viewoptions/)
