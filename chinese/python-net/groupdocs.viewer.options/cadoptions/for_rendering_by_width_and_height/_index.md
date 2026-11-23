---
title: "for_rendering_by_width_and_height 方法"
second_title: "GroupDocs.Viewer 用于 Python，通过 .NET API 参考"
description: "初始化一个用于按宽度和高度渲染的 CadOptions 类实例。"
type: docs
url: /zh/python-net/groupdocs.viewer.options/cadoptions/for_rendering_by_width_and_height/
is_root: false
weight: 1040
---


## for_rendering_by_width_and_height {#width-height}

初始化一个用于按宽度和高度渲染的 CadOptions 类实例。

代码示例请参见文档。

```python
def for_rendering_by_width_and_height(cls, width, height):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| width | `int` | 输出结果的宽度（以像素为单位）。 |
| height | `int` | 输出结果的高度（像素）。 |

**Returns:** CadOptions: New instance of CadOptions class for rendering by width and height.

| 引发 | 描述 |
| :- | :- |
| `ValueError` | 如果 `height` 小于或等于零。 |

### 另见
* class [`CadOptions`](/viewer/python-net/groupdocs.viewer.options/cadoptions/)
