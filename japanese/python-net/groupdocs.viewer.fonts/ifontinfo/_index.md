---
title: "IFontInfo クラス"
second_title: "GroupDocs.Viewer for Python via .NET API リファレンス"
description: "PDF、WordProcessing、Spreadsheet、Presentation のすべてのサポートされているドキュメント形式ファミリーから抽出できるすべてのフォントに対する共通インターフェイスを表します。"
type: docs
url: /ja/python-net/groupdocs.viewer.fonts/ifontinfo/
is_root: false
weight: 50
---


## IFontInfo class

PDF、WordProcessing、Spreadsheet、Presentation のすべてのサポートされているドキュメント形式ファミリーから抽出できるすべてのフォントに対する共通インターフェイスを表します。

IFontInfo 型は次のメンバーを公開します:

### メソッド
| メソッド | 説明 |
| :- | :- |
| [serialize_to_css](/viewer/python-net/groupdocs.viewer.fonts/ifontinfo/serialize_to_css/#output) | このフォント情報を @font-face の at-rule としてシリアライズし、指定されたテキストライターに書き込みます。 |
| [serialize_to_css_text_writer](/viewer/python-net/groupdocs.viewer.fonts/ifontinfo/serialize_to_css_text_writer/) |  |

### プロパティ
| プロパティ | 説明 |
| :- | :- |
| [content](/viewer/python-net/groupdocs.viewer.fonts/ifontinfo/content/) | フォントのバイナリ内容をバイト配列として取得します（利用可能な場合）。利用できない場合は None です。 |
| [family_name](/viewer/python-net/groupdocs.viewer.fonts/ifontinfo/family_name/) | フォントのファミリ名を文字列として取得します。 |
| [format](/viewer/python-net/groupdocs.viewer.fonts/ifontinfo/format/) | このフォントの形式を列挙型で取得します — TrueType、TrueType Collection、OpenType、Embedded OpenType、または `FontFormat.unknown`。 |
| [style](/viewer/python-net/groupdocs.viewer.fonts/ifontinfo/style/) | フォントのスタイルを列挙型で取得します（Regular、Bold、Italic、または Bold Italic）。一部のドキュメント形式では [`FontStyles.regular`](/viewer/python-net/groupdocs.viewer.fonts/fontstyles/regular/) のみがサポートされる場合があります。 |

### 参照
* module [`groupdocs.viewer.fonts`](/viewer/python-net/groupdocs.viewer.fonts/)
