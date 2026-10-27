---
title: "SpreadsheetFontInfo クラス"
second_title: "GroupDocs.Viewer for Python via .NET API リファレンス"
description: "Viewer インスタンスにロードされたスプレッドシート ドキュメントからのフォントのメタ情報とバイナリ データをカプセル化します。"
type: docs
url: /ja/python-net/groupdocs.viewer.fonts/spreadsheetfontinfo/
is_root: false
weight: 100
---


## SpreadsheetFontInfo class

スプレッドシートドキュメントからロードされたフォントのメタ情報とバイナリデータを、[`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/) インスタンスでカプセル化します。スプレッドシートドキュメントは埋め込みフォントを持つことができないため、[`Viewer.get_all_fonts`](/viewer/python-net/groupdocs.viewer/viewer/get_all_fonts/) が返すフォントはビューアが実行されるオペレーティングシステムにインストールされます。

SpreadsheetFontInfo 型は次のメンバーを公開します：

### コンストラクタ
| コンストラクタ | 説明 |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.fonts/spreadsheetfontinfo/__init__/) |  |

### メソッド
| メソッド | 説明 |
| :- | :- |
| [serialize_to_css](/viewer/python-net/groupdocs.viewer.fonts/spreadsheetfontinfo/serialize_to_css/#output) | フォント情報を @font-face の at-rule としてシリアライズし、指定されたテキストライターに書き込みます。 |
| [serialize_to_css_text_writer](/viewer/python-net/groupdocs.viewer.fonts/spreadsheetfontinfo/serialize_to_css_text_writer/) |  |

### プロパティ
| プロパティ | 説明 |
| :- | :- |
| [charset](/viewer/python-net/groupdocs.viewer.fonts/spreadsheetfontinfo/charset/) | このフォントの文字セットです。 |
| [color](/viewer/python-net/groupdocs.viewer.fonts/spreadsheetfontinfo/color/) | このフォントの色です。 |
| [content](/viewer/python-net/groupdocs.viewer.fonts/spreadsheetfontinfo/content/) | このフォントの内容はバイト配列です。このフォントに関するメタ情報のみが利用可能でバイナリ コンテンツが利用できない場合、プロパティは None を返します。 |
| [family_name](/viewer/python-net/groupdocs.viewer.fonts/spreadsheetfontinfo/family_name/) | スタイルなしのフォントのファミリ名で、null または空文字列になることはありません。 |
| [format](/viewer/python-net/groupdocs.viewer.fonts/spreadsheetfontinfo/format/) | このフォントの形式を取得します。 |
| [is_strikeout](/viewer/python-net/groupdocs.viewer.fonts/spreadsheetfontinfo/is_strikeout/) | フォントは単一の取り消し線が付いています。 |
| [is_underline](/viewer/python-net/groupdocs.viewer.fonts/spreadsheetfontinfo/is_underline/) | フォントは下線が付いています。 |
| [style](/viewer/python-net/groupdocs.viewer.fonts/spreadsheetfontinfo/style/) | このフォントのスタイル — Regular、Bold、Italic、または Bold Italic のいずれかです。 |

### 参照
* module [`groupdocs.viewer.fonts`](/viewer/python-net/groupdocs.viewer.fonts/)
