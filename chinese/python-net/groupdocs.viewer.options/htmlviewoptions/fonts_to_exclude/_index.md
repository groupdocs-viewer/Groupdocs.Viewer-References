---
title: "fonts_to_exclude 属性"
second_title: "GroupDocs.Viewer 用于 Python，通过 .NET API 参考"
description: "HTML 文档中要排除的字体名称列表。"
type: docs
url: /zh/python-net/groupdocs.viewer.options/htmlviewoptions/fonts_to_exclude/
is_root: false
weight: 2020
---


## fonts_to_exclude property

HTML 文档中要排除的字体名称列表。

添加到 HTML 文档中的字体可以提升输出视图的稳定性，但同时会增加渲染结果的大小。此选项让您在稳定性和输出大小之间取得平衡。请包含在大多数系统中常见且已安装的字体名称。

请注意，只有在禁用 [`HtmlViewOptions.ExcludeFonts`](/viewer/python-net/groupdocs.viewer.options/htmlviewoptions/exclude_fonts/) 选项时，此属性才会生效。

有关详细信息和代码示例，请参阅文档。

### Definition:
```python
@property
def fonts_to_exclude(self):
    ...
@fonts_to_exclude.setter
def fonts_to_exclude(self, value):
    ...
```

### 另见
* class [`HtmlViewOptions`](/viewer/python-net/groupdocs.viewer.options/htmlviewoptions/)
