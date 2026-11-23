---
title: "from_jpg_view_options 方法"
second_title: "GroupDocs.Viewer 用于 Python，通过 .NET API 参考"
description: "根据提供的 JpgViewOptions 初始化一个 ViewInfoOptions 实例。"
type: docs
url: /zh/python-net/groupdocs.viewer.options/viewinfooptions/from_jpg_view_options/
is_root: false
weight: 1090
---


## from_jpg_view_options {#options}

基于提供的 [`JpgViewOptions`](/viewer/python-net/groupdocs.viewer.options/jpgviewoptions/) 初始化一个 [`ViewInfoOptions`](/viewer/python-net/groupdocs.viewer.options/viewinfooptions/) 实例。

```python
def from_jpg_view_options(cls, options):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| options | `JpgViewOptions` | JPG 视图选项。 |

**Returns:** ViewInfoOptions: New instance of the `ViewInfoOptions` class.

| 引发 | 描述 |
| :- | :- |
| `ValueError` | 当 `options` 为 None 时。 |

### 另见
* class [`ViewInfoOptions`](/viewer/python-net/groupdocs.viewer.options/viewinfooptions/)
