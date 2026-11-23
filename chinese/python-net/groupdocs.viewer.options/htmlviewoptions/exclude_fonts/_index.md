---
title: "exclude_fonts 属性"
second_title: "GroupDocs.Viewer 用于 Python，通过 .NET API 参考"
description: "此属性禁用向 HTML 文档中添加任何字体。"
type: docs
url: /zh/python-net/groupdocs.viewer.options/htmlviewoptions/exclude_fonts/
is_root: false
weight: 2010
---


## exclude_fonts property

此属性禁用向 HTML 文档中添加任何字体。

默认情况下，GroupDocs.Viewer 会将文档中使用的字体嵌入到 HTML 标记中，而此属性的值为 `False`。要阻止嵌入字体，请将此属性设置为 `True`。

有关详细信息和代码示例，请参阅文档。

### Definition:
```python
@property
def exclude_fonts(self):
    ...
@exclude_fonts.setter
def exclude_fonts(self, value):
    ...
```

### 另见
* class [`HtmlViewOptions`](/viewer/python-net/groupdocs.viewer.options/htmlviewoptions/)
