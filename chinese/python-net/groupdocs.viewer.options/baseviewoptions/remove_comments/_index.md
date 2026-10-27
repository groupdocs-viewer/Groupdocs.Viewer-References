---
title: "remove_comments 属性"
second_title: "GroupDocs.Viewer 用于 Python，通过 .NET API 参考"
description: "当设置为 True 时，此属性会禁用渲染注释。"
type: docs
url: /zh/python-net/groupdocs.viewer.options/baseviewoptions/remove_comments/
is_root: false
weight: 2100
---


## remove_comments property

当此属性设置为 True 时，禁用渲染注释。默认情况下为 False，所有注释均会显示。

某些文档格式，如 PDF 和 WordProcessing，可能包含注释。默认情况下，GroupDocs.Viewer 会渲染它们。将此选项设置为 True 时，注释可能会从生成的文档中排除。

此选项取代了已废弃的 `RenderComments` 属性。

### Definition:
```python
@property
def remove_comments(self):
    ...
@remove_comments.setter
def remove_comments(self, value):
    ...
```

### 另见
* class [`BaseViewOptions`](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/)
