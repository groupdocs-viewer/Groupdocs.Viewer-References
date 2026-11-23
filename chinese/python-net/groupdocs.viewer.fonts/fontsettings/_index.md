---
title: "FontSettings 类"
second_title: "GroupDocs.Viewer 用于 Python，通过 .NET API 参考"
description: "提供用于查找 TrueType 字体来源的方法。"
type: docs
url: /zh/python-net/groupdocs.viewer.fonts/fontsettings/
is_root: false
weight: 30
---


## FontSettings class

提供用于查找 TrueType 字体来源的方法。

FontSettings 类型公开以下成员：

### 方法
| 方法 | 描述 |
| :- | :- |
| [reset_font_sources](/viewer/python-net/groupdocs.viewer.fonts/fontsettings/reset_font_sources/) | 重置之前设置的字体来源。 |
| [set_font_sources](/viewer/python-net/groupdocs.viewer.fonts/fontsettings/set_font_sources/#font_sources) | 设置在渲染文档时查找 TrueType 字体的来源。 |

### 示例

```python
from groupdocs.viewer.fonts import FontSettings, FolderFontSource, SearchOption

src1 = FolderFontSource("C:/fonts/primary", SearchOption.ALL_FOLDERS)
src2 = FolderFontSource("C:/fonts/backup", SearchOption.TOP_FOLDER_ONLY)

# 使用各种参数形式设置字体来源（内部已展平）
FontSettings.set_font_sources(src1, src2)          # varargs
FontSettings.set_font_sources([src1, src2])        # single list
FontSettings.set_font_sources([src1], [src2])      # multiple lists (flattened)
FontSettings.set_font_sources([src1, src2], src2)  # mixed — also flattened

# 清除所有已注册的字体来源
FontSettings.reset_font_sources()
```

### 另见
* module [`groupdocs.viewer.fonts`](/viewer/python-net/groupdocs.viewer.fonts/)
