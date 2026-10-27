---
title: "PresentationFontInfo クラス"
second_title: "GroupDocs.Viewer for Python via .NET API リファレンス"
description: "Viewer インスタンスにロードされたプレゼンテーション ドキュメントからのフォントのメタ情報とバイナリ データを表します。"
type: docs
url: /ja/python-net/groupdocs.viewer.fonts/presentationfontinfo/
is_root: false
weight: 80
---


## PresentationFontInfo class

Presentation ドキュメントからロードされたフォントのメタ情報とバイナリデータを、[`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/) インスタンスで表します。このフォントは文書内容で使用され、文書に埋め込まれるか、ビューアが実行されるオペレーティングシステムにインストールされる可能性があります。

PresentationFontInfo 型は次のメンバーを公開します：

### コンストラクタ
| コンストラクタ | 説明 |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.fonts/presentationfontinfo/__init__/) |  |

### メソッド
| メソッド | 説明 |
| :- | :- |
| [serialize_to_css](/viewer/python-net/groupdocs.viewer.fonts/presentationfontinfo/serialize_to_css/#output) | このフォント情報を @font-face の at-rule としてシリアライズし、指定されたテキストライターに書き込みます。 |
| [serialize_to_css_text_writer](/viewer/python-net/groupdocs.viewer.fonts/presentationfontinfo/serialize_to_css_text_writer/) |  |

### プロパティ
| プロパティ | 説明 |
| :- | :- |
| [content](/viewer/python-net/groupdocs.viewer.fonts/presentationfontinfo/content/) | このフォントの内容はバイト配列です。 |
| [family_name](/viewer/python-net/groupdocs.viewer.fonts/presentationfontinfo/family_name/) | スタイルなしのフォントのファミリ名を取得します。None や空文字列になることはありません。 |
| [format](/viewer/python-net/groupdocs.viewer.fonts/presentationfontinfo/format/) | このフォントの形式を取得します。 |
| [is_embedded](/viewer/python-net/groupdocs.viewer.fonts/presentationfontinfo/is_embedded/) | このプロパティは、フォントがドキュメントに埋め込まれ、[`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/) インスタンスにロードされているか (`True`)、あるいはシステムフォントであるか (`False`) を示します。 |
| [style](/viewer/python-net/groupdocs.viewer.fonts/presentationfontinfo/style/) | フォントのスタイルです — Regular、Bold、Italic、または Bold Italic のいずれかです。 |

### 参照
* module [`groupdocs.viewer.fonts`](/viewer/python-net/groupdocs.viewer.fonts/)
