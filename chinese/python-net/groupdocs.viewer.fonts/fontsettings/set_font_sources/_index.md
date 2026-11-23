---
title: "set_font_sources 方法"
second_title: "GroupDocs.Viewer 用于 Python，通过 .NET API 参考"
description: "设置在渲染文档时查找 TrueType 字体的来源。"
type: docs
url: /zh/python-net/groupdocs.viewer.fonts/fontsettings/set_font_sources/
is_root: false
weight: 1020
---


## set_font_sources {#font_sources}

设置在渲染文档时查找 TrueType 字体的来源。

该方法接受任意组合的单个 [`IFontSource`](/viewer/python-net/groupdocs.viewer.fonts/ifontsource/) 对象、它们的列表，或两者的混合；所有输入在应用之前都会被展平为单个列表。字符串路径会原样传递，不会被拆分为字符。

```python
def set_font_sources(cls, font_sources):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| font_sources | `list[IFontSource]` | 字体来源。 |

| 引发 | 描述 |
| :- | :- |
| `ValueError` | 当 `font_sources` 为 None 时。 |

### 示例

```python
from groupdocs.viewer.fonts import FontSettings, FolderFontSource, SearchOption

src1 = FolderFontSource("C:/fonts/primary", SearchOption.ALL_FOLDERS)
src2 = FolderFontSource("C:/fonts/backup", SearchOption.TOP_FOLDER_ONLY)

# 可变参数
FontSettings.set_font_sources(src1, src2)
# 单个列表
FontSettings.set_font_sources([src1, src2])
# 多个列表（已展平）
FontSettings.set_font_sources([src1], [src2])
# 混合 — 也已展平
FontSettings.set_font_sources([src1, src2], src2)
```

### 另见
* class [`FontSettings`](/viewer/python-net/groupdocs.viewer.fonts/fontsettings/)
