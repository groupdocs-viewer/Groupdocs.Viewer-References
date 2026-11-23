---
title: "groupdocs.viewer.fonts"
second_title: "GroupDocs.Viewer for Python via .NET API リファレンス"
description: "フォントの読み込みと置換設定。"
type: docs
url: /ja/python-net/groupdocs.viewer.fonts/
is_root: false
weight: 40
---


フォントの読み込みと置換設定。

### クラス
| クラス | 説明 |
| :- | :- |
| [`FolderFontSource`](/viewer/python-net/groupdocs.viewer.fonts/folderfontsource/) | TrueType フォントを含むフォルダーを表します。 |
| [`FontSettings`](/viewer/python-net/groupdocs.viewer.fonts/fontsettings/) | TrueType フォントを検索するためのソースを操作するメソッドを提供します。 |
| [`FontStyles`](/viewer/python-net/groupdocs.viewer.fonts/fontstyles/) | 文書で使用されるフォントの4つの可能なスタイルを表します: Regular、Bold、Italic、または Bold Italic。 |
| [`IFontInfo`](/viewer/python-net/groupdocs.viewer.fonts/ifontinfo/) | PDF、WordProcessing、Spreadsheet、Presentation のすべてのサポートされているドキュメント形式ファミリーから抽出できるすべてのフォントに対する共通インターフェイスを表します。 |
| [`PdfFontInfo`](/viewer/python-net/groupdocs.viewer.fonts/pdffontinfo/) | `[`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/)` インスタンスにロードされた PDF フォントのメタデータとバイナリデータをカプセル化します。このフォントは文書に埋め込まれるか、GroupDocs.Viewer が実行されるオペレーティングシステムにインストールされる可能性があります。 |
| [`PresentationFontInfo`](/viewer/python-net/groupdocs.viewer.fonts/presentationfontinfo/) | Presentation ドキュメントからロードされたフォントのメタ情報とバイナリデータを、[`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/) インスタンスで表します。このフォントは文書内容で使用され、文書に埋め込まれるか、ビューアが実行されるオペレーティングシステムにインストールされる可能性があります。 |
| [`SpreadsheetFontInfo`](/viewer/python-net/groupdocs.viewer.fonts/spreadsheetfontinfo/) | スプレッドシートドキュメントからロードされたフォントのメタ情報とバイナリデータを、[`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/) インスタンスでカプセル化します。スプレッドシートドキュメントは埋め込みフォントを持つことができないため、[`Viewer.get_all_fonts`](/viewer/python-net/groupdocs.viewer/viewer/get_all_fonts/) が返すフォントはビューアが実行されるオペレーティングシステムにインストールされます。 |
| [`WordProcessingFontInfo`](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingfontinfo/) | `[`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/)` インスタンスにロードされた WordProcessing ドキュメントからのフォントのメタ情報とバイナリデータをカプセル化します。 |
| [`WordProcessingSubstitutedFontInfo`](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/) | ロードされた [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/) インスタンスのドキュメントで元々使用されていない WordProcessing ドキュメントからのフォント1つのメタ情報とバイナリデータをカプセル化しますが、対象マシンで見つからないフォントの代替フォントとして機能します。代替フォントは WordProcessing フォーマットファミリーにのみ存在します。 |

### 列挙型
| 列挙型 | 説明 |
| :- | :- |
| [`FontFormat`](/viewer/python-net/groupdocs.viewer.fonts/fontformat/) |  |
| [`IFontSource`](/viewer/python-net/groupdocs.viewer.fonts/ifontsource/) | フォントソースのマーカーインターフェイスを表します。 |
| [`SearchOption`](/viewer/python-net/groupdocs.viewer.fonts/searchoption/) |  |
