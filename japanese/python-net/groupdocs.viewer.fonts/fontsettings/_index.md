---
title: "FontSettings クラス"
second_title: "GroupDocs.Viewer for Python via .NET API リファレンス"
description: "TrueType フォントを検索するためのソースを操作するメソッドを提供します。"
type: docs
url: /ja/python-net/groupdocs.viewer.fonts/fontsettings/
is_root: false
weight: 30
---


## FontSettings class

TrueType フォントを検索するためのソースを操作するメソッドを提供します。

この FontSettings 型は次のメンバーを公開します：

### メソッド
| メソッド | 説明 |
| :- | :- |
| [reset_font_sources](/viewer/python-net/groupdocs.viewer.fonts/fontsettings/reset_font_sources/) | 以前に設定されたフォントソースをリセットします。 |
| [set_font_sources](/viewer/python-net/groupdocs.viewer.fonts/fontsettings/set_font_sources/#font_sources) | ドキュメントをレンダリングする際に TrueType フォントを検索するソースを設定します。 |

### 例

```python
from groupdocs.viewer.fonts import FontSettings, FolderFontSource, SearchOption

src1 = FolderFontSource("C:/fonts/primary", SearchOption.ALL_FOLDERS)
src2 = FolderFontSource("C:/fonts/backup", SearchOption.TOP_FOLDER_ONLY)

# さまざまな引数形式を使用してフォントソースを設定します（内部でフラット化されます）
FontSettings.set_font_sources(src1, src2)          # varargs
FontSettings.set_font_sources([src1, src2])        # single list
FontSettings.set_font_sources([src1], [src2])      # multiple lists (flattened)
FontSettings.set_font_sources([src1, src2], src2)  # mixed — also flattened

# 登録されているすべてのフォントソースをクリアします
FontSettings.reset_font_sources()
```

### 参照
* module [`groupdocs.viewer.fonts`](/viewer/python-net/groupdocs.viewer.fonts/)
