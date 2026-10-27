---
title: "WordProcessingFontInfo クラス"
second_title: "GroupDocs.Viewer for Python via .NET API リファレンス"
description: "Viewer インスタンスにロードされた WordProcessing ドキュメントから取得したフォントのメタ情報とバイナリ データをカプセル化します。"
type: docs
url: /ja/python-net/groupdocs.viewer.fonts/wordprocessingfontinfo/
is_root: false
weight: 110
---


## WordProcessingFontInfo class

`[`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/)` インスタンスにロードされた WordProcessing ドキュメントからのフォントのメタ情報とバイナリデータをカプセル化します。

不変構造体です。

そのインスタンスは [`GroupDocs.Viewer`](/viewer/python-net/groupdocs.viewer/viewer/) のパブリック API によって生成および返却され、通常ユーザーが作成すべきではありません。

詳細については、ドキュメントをご覧ください: https://docs.groupdocs.com/viewer/net/getting-used-fonts/

WordProcessingFontInfo 型は次のメンバーを公開します:

### コンストラクタ
| コンストラクタ | 説明 |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingfontinfo/__init__/) |  |

### メソッド
| メソッド | 説明 |
| :- | :- |
| [serialize_to_css](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingfontinfo/serialize_to_css/#output) | フォント情報を @font-face の at-rule としてシリアライズし、指定されたテキストライターに書き込みます。 |
| [serialize_to_css_text_writer](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingfontinfo/serialize_to_css_text_writer/) |  |
| [to_string](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingfontinfo/to_string/) | 次のテンプレートでこのフォント データのデバッグ情報を返します: "name style, embedded/system, format"。 |

### プロパティ
| プロパティ | 説明 |
| :- | :- |
| [alt_family_name](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingfontinfo/alt_family_name/) | フォントの代替ファミリ名です。存在しない場合は空文字列になります。 |
| [charset](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingfontinfo/charset/) | このフォントの文字セットです。 |
| [content](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingfontinfo/content/) | このフォントの内容をバイト配列として取得します。フォントのメタ情報のみが利用可能でバイナリ内容が利用できない場合、プロパティは None を返します。 |
| [family_name](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingfontinfo/family_name/) | スタイルなしのフォントのファミリ名を取得します。None や空文字列になることはありません。 |
| [format](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingfontinfo/format/) | このフォントの形式を取得します。 |
| [is_embedded](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingfontinfo/is_embedded/) | このプロパティは、フォントがドキュメント内に埋め込まれていて [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/) インスタンスにロードされているか (`True`)、あるいはシステムフォントであるか (`False`) を示します。 |
| [style](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingfontinfo/style/) | フォントのスタイルです — Regular、Bold、Italic、または Bold Italic のいずれかです。 |

### 参照
* module [`groupdocs.viewer.fonts`](/viewer/python-net/groupdocs.viewer.fonts/)
