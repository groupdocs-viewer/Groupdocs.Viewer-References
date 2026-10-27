---
title: "FolderFontSource クラス"
second_title: "GroupDocs.Viewer for Python via .NET API リファレンス"
description: "TrueType フォントを含むフォルダーを表します。"
type: docs
url: /ja/python-net/groupdocs.viewer.fonts/folderfontsource/
is_root: false
weight: 10
---


## FolderFontSource class

TrueType フォントを含むフォルダーを表します。

FolderFontSource 型は次のメンバーを公開します:

### コンストラクタ
| コンストラクタ | 説明 |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.fonts/folderfontsource/__init__/#folder_path-search_option) | 新しいインスタンスを初期化します [`FolderFontSource`](/viewer/python-net/groupdocs.viewer.fonts/folderfontsource/)。 |

### メソッド
| メソッド | 説明 |
| :- | :- |
| [equals](/viewer/python-net/groupdocs.viewer.fonts/folderfontsource/equals/#other) | 現在の FolderFontSource が指定された FolderFontSource オブジェクトと同じかどうかを判断します。 |
| [equals](/viewer/python-net/groupdocs.viewer.fonts/folderfontsource/equals/#obj) | 現在の FolderFontSource が指定されたオブジェクトと同じかどうかを判断します。 |
| [equals_folder_font_source](/viewer/python-net/groupdocs.viewer.fonts/folderfontsource/equals_folder_font_source/) |  |
| [equals_object](/viewer/python-net/groupdocs.viewer.fonts/folderfontsource/equals_object/) |  |
| [get_hash_code](/viewer/python-net/groupdocs.viewer.fonts/folderfontsource/get_hash_code/) | 現在の [`FolderFontSource`](/viewer/python-net/groupdocs.viewer.fonts/folderfontsource/) オブジェクトのハッシュコードを返します。 |
| [to_string](/viewer/python-net/groupdocs.viewer.fonts/folderfontsource/to_string/) | 現在のオブジェクトを表す文字列を返します。 |

### プロパティ
| プロパティ | 説明 |
| :- | :- |
| [folder_path](/viewer/python-net/groupdocs.viewer.fonts/folderfontsource/folder_path/) | TrueType フォントを含むフォルダーへのパスです。 |
| [search_option](/viewer/python-net/groupdocs.viewer.fonts/folderfontsource/search_option/) | 現在のフォルダーのみ検索するか、現在のフォルダーとすべてのサブフォルダーを検索するかを指定する検索オプションです。 |

### 例

```python
from groupdocs.viewer.fonts import FolderFontSource, SearchOption

# すべてのサブフォルダーを検索するフォント ソースを作成します。
src = FolderFontSource("C:/fonts/primary", SearchOption.ALL_FOLDERS)
```

### 参照
* module [`groupdocs.viewer.fonts`](/viewer/python-net/groupdocs.viewer.fonts/)
