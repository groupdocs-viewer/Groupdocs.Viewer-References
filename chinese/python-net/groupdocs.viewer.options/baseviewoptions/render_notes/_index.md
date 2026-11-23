---
title: "render_notes 属性"
second_title: "GroupDocs.Viewer 用于 Python，通过 .NET API 参考"
description: "该属性启用对某些格式的注释和标注的渲染。"
type: docs
url: /zh/python-net/groupdocs.viewer.options/baseviewoptions/render_notes/
is_root: false
weight: 2130
---


## render_notes property

该属性启用对某些格式的注释和标注的渲染。

某些格式，例如演示文稿或 Microsoft Project 文件，可能包含备注。此外，PDF 文件可能具有默认隐藏的弹出注释（气泡提示），仅在 PDF 查看器中将鼠标光标指向时才可见。默认情况下，GroupDocs.Viewer 不会渲染此类备注和注释（`False`）。若要渲染，请将此属性设置为 `True`。

有关代码示例，请参阅文档。

### Definition:
```python
@property
def render_notes(self):
    ...
@render_notes.setter
def render_notes(self, value):
    ...
```

### 另见
* class [`BaseViewOptions`](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/)
