---
title: "__init__ 构造函数"
second_title: "GroupDocs.Viewer 用于 Python，通过 .NET API 参考"
description: "初始化 FolderFontSource 的新实例。"
type: docs
url: /zh/python-net/groupdocs.viewer.fonts/folderfontsource/__init__/
is_root: false
weight: 10
---


## __init__ {#folder_path-search_option}

初始化一个新的实例 [`FolderFontSource`](/viewer/python-net/groupdocs.viewer.fonts/folderfontsource/)。

```python
def __init__(self, folder_path, search_option):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| folder_path | `str` | 包含 TrueType 字体的文件夹路径。 |
| search_option | `SearchOption` | 指定是仅搜索当前文件夹，还是搜索当前文件夹及所有子文件夹。 |

| 引发 | 描述 |
| :- | :- |
| `ValueError` | 如果 `folder_path` 为 None。 |
| `FileNotFoundError` | 如果在 `folder_path` 中指定的路径无法定位。 |

### 示例

```python
from groupdocs.viewer.fonts import FolderFontSource, SearchOption, FontSettings

src1 = FolderFontSource("C:/fonts/primary", SearchOption.ALL_FOLDERS)
src2 = FolderFontSource("C:/fonts/backup", SearchOption.TOP_FOLDER_ONLY)

# 注册用于渲染的字体来源
FontSettings.set_font_sources(src1, src2)

# 完成后，重置以避免泄漏来源
FontSettings.reset_font_sources()
```

### 另见
* class [`FolderFontSource`](/viewer/python-net/groupdocs.viewer.fonts/folderfontsource/)
