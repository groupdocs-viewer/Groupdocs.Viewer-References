---
title: "page_size 属性"
second_title: "GroupDocs.Viewer 用于 Python，通过 .NET API 参考"
description: "输出页面的尺寸。"
type: docs
url: /zh/python-net/groupdocs.viewer.options/wordprocessingoptions/page_size/
is_root: false
weight: 2060
---


## page_size property

输出页面的尺寸。

默认值为 `PageSize.Unspecified`，这意味着使用页面设置（页面设置）中设定的页面大小。

在渲染 HTM 和 HTML 文件时，默认页面大小设置为 Letter 792 x 612 点。

因此，部分内容可能无法适应页面框架。

设置更大的页面尺寸，例如 `PageSize.A3`，以适应内容。

### Definition:
```python
@property
def page_size(self):
    ...
@page_size.setter
def page_size(self, value):
    ...
```

### 另见
* class [`WordProcessingOptions`](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/)
