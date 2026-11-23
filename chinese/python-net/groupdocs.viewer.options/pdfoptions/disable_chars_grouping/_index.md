---
title: "disable_chars_grouping 属性"
second_title: "GroupDocs.Viewer 用于 Python，通过 .NET API 参考"
description: "此属性在页面渲染期间禁用符号分组，以实现精确的符号定位。"
type: docs
url: /zh/python-net/groupdocs.viewer.options/pdfoptions/disable_chars_grouping/
is_root: false
weight: 2010
---


## disable_chars_grouping property

此属性在页面渲染期间禁用符号分组，以实现精确的符号定位。

在转换 PDF 文件时，GroupDocs.Viewer 会将单个字符组合成单词，以提升渲染性能。如果您的文档包含象形文字或特殊符号，您可能希望禁止字符分组，以确保布局更精确。默认值为 False。

代码示例请参见文档。

### Definition:
```python
@property
def disable_chars_grouping(self):
    ...
@disable_chars_grouping.setter
def disable_chars_grouping(self, value):
    ...
```

### 另见
* class [`PdfOptions`](/viewer/python-net/groupdocs.viewer.options/pdfoptions/)
