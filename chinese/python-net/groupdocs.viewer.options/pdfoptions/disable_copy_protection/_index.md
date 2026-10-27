---
title: "disable_copy_protection 属性"
second_title: "GroupDocs.Viewer 用于 Python，通过 .NET API 参考"
description: "此属性在渲染为 HTML 时禁用内容复制保护。"
type: docs
url: /zh/python-net/groupdocs.viewer.options/pdfoptions/disable_copy_protection/
is_root: false
weight: 2020
---


## disable_copy_protection property

此属性在渲染为 HTML 时禁用内容复制保护。

在将 PDF 文件渲染为 HTML 并对文本和图像的复制进行保护时，GroupDocs.Viewer 会向 HTML BODY 标签添加 `inert` HTML 属性。默认值为 `False`，表示仅在 PDF 文档受保护时才添加 `inert` 属性。

有关代码示例，请参阅文档。

### Definition:
```python
@property
def disable_copy_protection(self):
    ...
@disable_copy_protection.setter
def disable_copy_protection(self, value):
    ...
```

### 另见
* class [`PdfOptions`](/viewer/python-net/groupdocs.viewer.options/pdfoptions/)
