---
title: "FolderFontSource 类"
second_title: "GroupDocs.Viewer 用于 Python，通过 .NET API 参考"
description: "表示包含 TrueType 字体的文件夹。"
type: docs
url: /zh/python-net/groupdocs.viewer.fonts/folderfontsource/
is_root: false
weight: 10
---


## FolderFontSource class

表示包含 TrueType 字体的文件夹。

FolderFontSource 类型公开以下成员：

### 构造函数
| 构造函数 | 描述 |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.fonts/folderfontsource/__init__/#folder_path-search_option) | 初始化一个新的实例 [`FolderFontSource`](/viewer/python-net/groupdocs.viewer.fonts/folderfontsource/)。 |

### 方法
| 方法 | 描述 |
| :- | :- |
| [equals](/viewer/python-net/groupdocs.viewer.fonts/folderfontsource/equals/#other) | 确定当前 FolderFontSource 是否与指定的 FolderFontSource 对象相同。 |
| [equals](/viewer/python-net/groupdocs.viewer.fonts/folderfontsource/equals/#obj) | 确定当前 FolderFontSource 是否与指定的对象相同。 |
| [equals_folder_font_source](/viewer/python-net/groupdocs.viewer.fonts/folderfontsource/equals_folder_font_source/) |  |
| [equals_object](/viewer/python-net/groupdocs.viewer.fonts/folderfontsource/equals_object/) |  |
| [get_hash_code](/viewer/python-net/groupdocs.viewer.fonts/folderfontsource/get_hash_code/) | 返回当前 [`FolderFontSource`](/viewer/python-net/groupdocs.viewer.fonts/folderfontsource/) 对象的哈希码。 |
| [to_string](/viewer/python-net/groupdocs.viewer.fonts/folderfontsource/to_string/) | 返回表示当前对象的字符串。 |

### 属性
| 属性 | 描述 |
| :- | :- |
| [folder_path](/viewer/python-net/groupdocs.viewer.fonts/folderfontsource/folder_path/) | 包含 TrueType 字体的文件夹路径。 |
| [search_option](/viewer/python-net/groupdocs.viewer.fonts/folderfontsource/search_option/) | 搜索选项，指定是仅搜索当前文件夹，还是搜索当前文件夹及所有子文件夹。 |

### 示例

```python
from groupdocs.viewer.fonts import FolderFontSource, SearchOption

# 创建一个搜索所有子文件夹的字体源。
src = FolderFontSource("C:/fonts/primary", SearchOption.ALL_FOLDERS)
```

### 另见
* module [`groupdocs.viewer.fonts`](/viewer/python-net/groupdocs.viewer.fonts/)
