---
title: "PdfFontInfo クラス"
second_title: "GroupDocs.Viewer for Python via .NET API リファレンス"
description: "Viewer インスタンスにロードされた PDF フォントのメタデータとバイナリデータをカプセル化します。このフォントはドキュメントに埋め込まれているか、GroupDocs.Viewer が実行されているオペレーティングシステムにインストールされている場合があります。"
type: docs
url: /ja/python-net/groupdocs.viewer.fonts/pdffontinfo/
is_root: false
weight: 70
---


## PdfFontInfo class

`[`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/)` インスタンスにロードされた PDF フォントのメタデータとバイナリデータをカプセル化します。このフォントは文書に埋め込まれるか、GroupDocs.Viewer が実行されるオペレーティングシステムにインストールされる可能性があります。

PdfFontInfo 型は以下のメンバーを公開します：

### コンストラクタ
| コンストラクタ | 説明 |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.fonts/pdffontinfo/__init__/) |  |

### メソッド
| メソッド | 説明 |
| :- | :- |
| [serialize_to_css](/viewer/python-net/groupdocs.viewer.fonts/pdffontinfo/serialize_to_css/#output) | このフォント情報を @font-face の at-rule としてシリアライズし、指定されたテキストライターに書き込みます。 |
| [serialize_to_css_text_writer](/viewer/python-net/groupdocs.viewer.fonts/pdffontinfo/serialize_to_css_text_writer/) |  |

### プロパティ
| プロパティ | 説明 |
| :- | :- |
| [content](/viewer/python-net/groupdocs.viewer.fonts/pdffontinfo/content/) | このフォントの内容をバイト配列として取得します。メタデータのみが利用可能でバイナリ内容が利用できない場合は None です。 |
| [family_name](/viewer/python-net/groupdocs.viewer.fonts/pdffontinfo/family_name/) | スタイルなしのフォントのファミリ名を取得します。None や空文字列になることはありません。 |
| [format](/viewer/python-net/groupdocs.viewer.fonts/pdffontinfo/format/) | このフォントの形式を取得します。 |
| [is_embedded](/viewer/python-net/groupdocs.viewer.fonts/pdffontinfo/is_embedded/) | このプロパティは、フォントが PDF ドキュメント内に埋め込まれ、Viewer インスタンスにロードされているか（`True`）どうかを示します。 |
| [is_installed](/viewer/python-net/groupdocs.viewer.fonts/pdffontinfo/is_installed/) | このプロパティは、GroupDocs.Viewer が実行されているオペレーティングシステムにこのフォントが存在（インストール）しているかどうかを示します。 |
| [style](/viewer/python-net/groupdocs.viewer.fonts/pdffontinfo/style/) | フォントのスタイルを取得します。Regular、Bold、Italic、または Bold Italic のいずれかです。 |

### 参照
* module [`groupdocs.viewer.fonts`](/viewer/python-net/groupdocs.viewer.fonts/)
