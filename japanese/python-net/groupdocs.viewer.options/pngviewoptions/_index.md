---
title: "PngViewOptions クラス"
second_title: "GroupDocs.Viewer for Python via .NET API リファレンス"
description: "ドキュメントを PNG 形式にレンダリングするオプションを表します。"
type: docs
url: /ja/python-net/groupdocs.viewer.options/pngviewoptions/
is_root: false
weight: 190
---


## PngViewOptions class

ドキュメントを PNG 形式にレンダリングするオプションを表します。

詳細については、オンラインドキュメントをご覧ください。

PngViewOptions 型は次のメンバーを公開します：

### コンストラクタ
| コンストラクタ | 説明 |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.options/pngviewoptions/__init__/#create_page_stream) | 新しい [`PngViewOptions`](/viewer/python-net/groupdocs.viewer.options/pngviewoptions/) インスタンスを初期化します。 |
| [__init__](/viewer/python-net/groupdocs.viewer.options/pngviewoptions/__init__/#create_page_stream-release_page_stream) | [`PngViewOptions`](/viewer/python-net/groupdocs.viewer.options/pngviewoptions/) クラスのインスタンスを初期化します。 |
| [__init__](/viewer/python-net/groupdocs.viewer.options/pngviewoptions/__init__/#page_stream_factory) | 新しい [`PngViewOptions`](/viewer/python-net/groupdocs.viewer.options/pngviewoptions/) インスタンスを初期化します。 |
| [__init__](/viewer/python-net/groupdocs.viewer.options/pngviewoptions/__init__/) | PngViewOptions インスタンスを初期化します。 |
| [__init__](/viewer/python-net/groupdocs.viewer.options/pngviewoptions/__init__/#file_path_format) | 新しい [`PngViewOptions`](/viewer/python-net/groupdocs.viewer.options/pngviewoptions/) インスタンスを初期化します。 |

### メソッド
| メソッド | 説明 |
| :- | :- |
| [rotate_page](/viewer/python-net/groupdocs.viewer.options/viewoptions/rotate_page/) | ページに時計回りの回転を適用します。(継承元 [`ViewOptions`](/viewer/python-net/groupdocs.viewer.options/viewoptions/)) |
| [rotate_page_int32](/viewer/python-net/groupdocs.viewer.options/viewoptions/rotate_page_int32/) | (継承元 [`ViewOptions`](/viewer/python-net/groupdocs.viewer.options/viewoptions/)) |

### プロパティ
| プロパティ | 説明 |
| :- | :- |
| [extract_text](/viewer/python-net/groupdocs.viewer.options/pngviewoptions/extract_text/) | このプロパティはテキスト抽出を有効にします。 |
| [height](/viewer/python-net/groupdocs.viewer.options/pngviewoptions/height/) | 出力画像の高さ（ピクセル単位）。 |
| [max_height](/viewer/python-net/groupdocs.viewer.options/pngviewoptions/max_height/) | 出力画像の最大高さ（ピクセル単位）。 |
| [max_width](/viewer/python-net/groupdocs.viewer.options/pngviewoptions/max_width/) | 出力画像の最大幅（ピクセル単位）。 |
| [width](/viewer/python-net/groupdocs.viewer.options/pngviewoptions/width/) | 出力画像の幅（ピクセル単位）。 |
| [archive_options](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/archive_options/) | アーカイブ ファイルの表示オプション。 (inherited from [`BaseViewOptions`](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/)) |
| [cad_options](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/cad_options/) | CAD 図面の表示オプション。 (inherited from [`BaseViewOptions`](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/)) |
| [default_font_name](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/default_font_name/) | 必要なフォントが見つからない場合に、レンダリング中に使用されるドキュメントのデフォルトフォント。 (inherited from [`BaseViewOptions`](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/)) |
| [email_options](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/email_options/) | メール メッセージの表示オプション。 (inherited from [`BaseViewOptions`](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/)) |
| [mail_storage_options](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/mail_storage_options/) | メール ストレージ データ ファイルの表示オプション。 (inherited from [`BaseViewOptions`](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/)) |
| [outlook_options](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/outlook_options/) | Microsoft Outlook データ ファイルの表示オプション。 (inherited from [`BaseViewOptions`](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/)) |
| [page_rotations](/viewer/python-net/groupdocs.viewer.options/viewoptions/page_rotations/) | ページの回転。(継承元 [`ViewOptions`](/viewer/python-net/groupdocs.viewer.options/viewoptions/)) |
| [pdf_options](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/pdf_options/) | PDF ドキュメントの表示オプション。 (inherited from [`BaseViewOptions`](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/)) |
| [presentation_options](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/presentation_options/) | プレゼンテーション ファイルの表示オプション。 (inherited from [`BaseViewOptions`](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/)) |
| [project_management_options](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/project_management_options/) | プロジェクト管理ファイルの表示オプション。 (inherited from [`BaseViewOptions`](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/)) |
| [remove_comments](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/remove_comments/) | このプロパティは True に設定された場合、コメントのレンダリングを無効にします。デフォルトは False で、すべてのコメントが表示されます。 (inherited from [`BaseViewOptions`](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/)) |
| [render_comments](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/render_comments/) | このプロパティはコメントのレンダリングを有効または無効にします。 (inherited from [`BaseViewOptions`](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/)) |
| [render_hidden_pages](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/render_hidden_pages/) | このプロパティは非表示ページのレンダリングを有効にします。 (inherited from [`BaseViewOptions`](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/)) |
| [render_notes](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/render_notes/) | このプロパティは一部の形式でノートと注釈のレンダリングを有効にします。 (inherited from [`BaseViewOptions`](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/)) |
| [spreadsheet_options](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/spreadsheet_options/) | スプレッドシート ファイルの表示オプション。 (inherited from [`BaseViewOptions`](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/)) |
| [text_options](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/text_options/) | テキスト ファイルのレンダリングオプション。 (inherited from [`BaseViewOptions`](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/)) |
| [visio_rendering_options](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/visio_rendering_options/) | Visio ファイルの表示オプション。 (inherited from [`BaseViewOptions`](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/)) |
| [watermark](/viewer/python-net/groupdocs.viewer.options/viewoptions/watermark/) | 各ページに適用されるテキスト透かし。(継承元 [`ViewOptions`](/viewer/python-net/groupdocs.viewer.options/viewoptions/)) |
| [web_document_options](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/web_document_options/) | Web ファイルの表示オプション。 (inherited from [`BaseViewOptions`](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/)) |
| [word_processing_options](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/word_processing_options/) | ワードプロセッシング ファイルの表示オプション。 (inherited from [`BaseViewOptions`](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/)) |

### 例

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PngViewOptions

with Viewer("document.pdf") as viewer:
    viewer.view(PngViewOptions("page_{0}.png"))
```

### Guides
`PngViewOptions` を使用するタスク ガイド：

* [Quick Start Guide](/viewer/python-net/guides/quick-start-guide/)

### 参照
* module [`groupdocs.viewer.options`](/viewer/python-net/groupdocs.viewer.options/)
