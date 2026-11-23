---
title: "__init__ コンストラクタ"
second_title: "GroupDocs.Viewer for Python via .NET API リファレンス"
description: "FolderFontSource の新しいインスタンスを初期化します。"
type: docs
url: /ja/python-net/groupdocs.viewer.fonts/folderfontsource/__init__/
is_root: false
weight: 10
---


## __init__ {#folder_path-search_option}

新しいインスタンスを初期化します [`FolderFontSource`](/viewer/python-net/groupdocs.viewer.fonts/folderfontsource/)。

```python
def __init__(self, folder_path, search_option):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| folder_path | `str` | TrueType フォントを含むフォルダーへのパス。 |
| search_option | `SearchOption` | 現在のフォルダーのみ検索するか、現在のフォルダーとすべてのサブフォルダーも検索するかを指定します。 |

| 例外 | 説明 |
| :- | :- |
| `ValueError` | `folder_path` が None の場合。 |
| `FileNotFoundError` | `folder_path` で指定されたパスが見つからない場合。 |

### 例

```python
from groupdocs.viewer.fonts import FolderFontSource, SearchOption, FontSettings

src1 = FolderFontSource("C:/fonts/primary", SearchOption.ALL_FOLDERS)
src2 = FolderFontSource("C:/fonts/backup", SearchOption.TOP_FOLDER_ONLY)

# レンダリング用にフォントソースを登録します
FontSettings.set_font_sources(src1, src2)

# 完了したら、ソースのリークを防ぐためにリセットします
FontSettings.reset_font_sources()
```

### 参照
* class [`FolderFontSource`](/viewer/python-net/groupdocs.viewer.fonts/folderfontsource/)
