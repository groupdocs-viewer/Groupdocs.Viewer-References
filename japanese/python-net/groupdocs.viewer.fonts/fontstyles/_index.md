---
title: "FontStyles クラス"
second_title: "GroupDocs.Viewer for Python via .NET API リファレンス"
description: "文書で使用されるフォントの4つの可能なスタイルを表します: Regular、Bold、Italic、または Bold Italic。"
type: docs
url: /ja/python-net/groupdocs.viewer.fonts/fontstyles/
is_root: false
weight: 40
---


## FontStyles class

文書で使用されるフォントの4つの可能なスタイルを表します: Regular、Bold、Italic、または Bold Italic。

便利な API と結合操作を備えた不変構造体です。

FontStyles 型は次のメンバーを公開します：

### コンストラクタ
| コンストラクタ | 説明 |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.fonts/fontstyles/__init__/#is_bold-is_italic) | 指定された bold と italic フラグから FontStyles インスタンスを初期化します。 |

### メソッド
| メソッド | 説明 |
| :- | :- |
| [equals](/viewer/python-net/groupdocs.viewer.fonts/fontstyles/equals/#other) | この FontStyles インスタンスが指定されたインスタンスと等しいかどうかを示します。 |
| [equals](/viewer/python-net/groupdocs.viewer.fonts/fontstyles/equals/#other) | この [`FontStyles`](/viewer/python-net/groupdocs.viewer.fonts/fontstyles/) インスタンスが指定されたキャストされていないオブジェクトと等しいかどうかを示します。 |
| [equals_font_styles](/viewer/python-net/groupdocs.viewer.fonts/fontstyles/equals_font_styles/) |  |
| [equals_object](/viewer/python-net/groupdocs.viewer.fonts/fontstyles/equals_object/) |  |
| [get_hash_code](/viewer/python-net/groupdocs.viewer.fonts/fontstyles/get_hash_code/) | このインスタンスのハッシュコードを返します。 |
| [to_string](/viewer/python-net/groupdocs.viewer.fonts/fontstyles/to_string/) | このフォントスタイルの名前を返します。[`FontStyles.name`](/viewer/python-net/groupdocs.viewer.fonts/fontstyles/name/) と同じです。 |
| [try_parse](/viewer/python-net/groupdocs.viewer.fonts/fontstyles/try_parse/#style-parsed) | 指定された生文字列をフォントスタイル名として解析しようとします。 |

### プロパティ
| プロパティ | 説明 |
| :- | :- |
| [is_bold](/viewer/python-net/groupdocs.viewer.fonts/fontstyles/is_bold/) | このプロパティは、この [`FontStyles`](/viewer/python-net/groupdocs.viewer.fonts/fontstyles/) インスタンスに太字フラグが有効 (`True`) か無効 (`False`) かを示します。 |
| [is_italic](/viewer/python-net/groupdocs.viewer.fonts/fontstyles/is_italic/) | この [`FontStyles`](/viewer/python-net/groupdocs.viewer.fonts/fontstyles/) インスタンスのイタリックフラグの状態です。有効な場合は `True`、無効な場合は `False`。 |
| [name](/viewer/python-net/groupdocs.viewer.fonts/fontstyles/name/) | このフォントスタイルの名前です。 |

### フィールド
| フィールド | 説明 |
| :- | :- |
| [REGULAR](/viewer/python-net/groupdocs.viewer.fonts/fontstyles/regular/) | 標準フォントスタイル、デフォルト値（太字とイタリックなし） |
| [BOLD](/viewer/python-net/groupdocs.viewer.fonts/fontstyles/bold/) | 太字フォントスタイル（太字のみ、イタリックなし） |
| [ITALIC](/viewer/python-net/groupdocs.viewer.fonts/fontstyles/italic/) | イタリックフォントスタイル（イタリックのみ、太字なし） |
| [BOLD_ITALIC](/viewer/python-net/groupdocs.viewer.fonts/fontstyles/bold_italic/) | BoldItalic フォントスタイル（太字とイタリックが同時に適用） |

### 参照
* module [`groupdocs.viewer.fonts`](/viewer/python-net/groupdocs.viewer.fonts/)
