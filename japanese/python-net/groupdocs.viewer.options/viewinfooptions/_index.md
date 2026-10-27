---
title: "ViewInfoOptions クラス"
second_title: "GroupDocs.Viewer for Python via .NET API リファレンス"
description: "ビュー情報を取得するために使用されるオプション。"
type: docs
url: /ja/python-net/groupdocs.viewer.options/viewinfooptions/
is_root: false
weight: 330
---


## ViewInfoOptions class

ビュー情報を取得するために使用されるオプション。

ViewInfoOptions 型は次のメンバーを公開します：

### メソッド
| メソッド | 説明 |
| :- | :- |
| [for_html_view](/viewer/python-net/groupdocs.viewer.options/viewinfooptions/for_html_view/) | HTML にレンダリングする際にビュー情報を取得するための ViewInfoOptions インスタンスを初期化します。 |
| [for_html_view](/viewer/python-net/groupdocs.viewer.options/viewinfooptions/for_html_view/#render_single_page) | HTML にレンダリングする際にビュー情報を取得するための ViewInfoOptions インスタンスを初期化します。 |
| [for_html_view_boolean](/viewer/python-net/groupdocs.viewer.options/viewinfooptions/for_html_view_boolean/) |  |
| [for_jpg_view](/viewer/python-net/groupdocs.viewer.options/viewinfooptions/for_jpg_view/) | JPG にレンダリングする際にビュー情報を取得するための [`ViewInfoOptions`](/viewer/python-net/groupdocs.viewer.options/viewinfooptions/) インスタンスを初期化します。 |
| [for_jpg_view](/viewer/python-net/groupdocs.viewer.options/viewinfooptions/for_jpg_view/#extract_text) | JPG にレンダリングする際にビュー情報を取得するための ViewInfoOptions インスタンスを初期化します。 |
| [for_jpg_view_boolean](/viewer/python-net/groupdocs.viewer.options/viewinfooptions/for_jpg_view_boolean/) |  |
| [for_pdf_view](/viewer/python-net/groupdocs.viewer.options/viewinfooptions/for_pdf_view/) | PDF にレンダリングする際にビュー情報を取得するための ViewInfoOptions インスタンスを初期化します。 |
| [for_png_view](/viewer/python-net/groupdocs.viewer.options/viewinfooptions/for_png_view/) | PNG にレンダリングする際にビュー情報を取得するための [`ViewInfoOptions`](/viewer/python-net/groupdocs.viewer.options/viewinfooptions/) クラスのインスタンスを初期化します。 |
| [for_png_view](/viewer/python-net/groupdocs.viewer.options/viewinfooptions/for_png_view/#extract_text) | PNG にレンダリングする際にビュー情報を取得するための ViewInfoOptions クラスのインスタンスを初期化します。 |
| [for_png_view_boolean](/viewer/python-net/groupdocs.viewer.options/viewinfooptions/for_png_view_boolean/) |  |
| [from_html_view_options](/viewer/python-net/groupdocs.viewer.options/viewinfooptions/from_html_view_options/#options) | HtmlViewOptions オブジェクトに基づいて ViewInfoOptions クラスのインスタンスを初期化します。 |
| [from_jpg_view_options](/viewer/python-net/groupdocs.viewer.options/viewinfooptions/from_jpg_view_options/#options) | 提供された [`JpgViewOptions`](/viewer/python-net/groupdocs.viewer.options/jpgviewoptions/) に基づいて [`ViewInfoOptions`](/viewer/python-net/groupdocs.viewer.options/viewinfooptions/) インスタンスを初期化します。 |
| [from_pdf_view_options](/viewer/python-net/groupdocs.viewer.options/viewinfooptions/from_pdf_view_options/#options) | PdfViewOptions オブジェクトから ViewInfoOptions インスタンスを初期化します。 |
| [from_png_view_options](/viewer/python-net/groupdocs.viewer.options/viewinfooptions/from_png_view_options/#options) | PngViewOptions オブジェクトから ViewInfoOptions インスタンスを初期化します。 |

### プロパティ
| プロパティ | 説明 |
| :- | :- |
| [extract_text](/viewer/python-net/groupdocs.viewer.options/viewinfooptions/extract_text/) | このプロパティはテキスト抽出を有効にします。 |
| [height](/viewer/python-net/groupdocs.viewer.options/viewinfooptions/height/) | 出力画像の高さ（ピクセル単位、PNG/JPG のレンダリング時のみ）。 |
| [max_height](/viewer/python-net/groupdocs.viewer.options/viewinfooptions/max_height/) | 出力画像の最大高さ（ピクセル単位、PNG/JPG のレンダリング時のみ）。 |
| [max_width](/viewer/python-net/groupdocs.viewer.options/viewinfooptions/max_width/) | 出力画像の最大幅（ピクセル単位、PNG/JPG のレンダリング時のみ）。 |
| [width](/viewer/python-net/groupdocs.viewer.options/viewinfooptions/width/) | 出力画像の幅（ピクセル単位、PNG/JPG のレンダリング時のみ）。 |
| [archive_options](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/archive_options/) | アーカイブ ファイルの表示オプション。 (inherited from [`BaseViewOptions`](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/)) |
| [cad_options](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/cad_options/) | CAD 図面の表示オプション。 (inherited from [`BaseViewOptions`](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/)) |
| [default_font_name](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/default_font_name/) | 必要なフォントが見つからない場合に、レンダリング中に使用されるドキュメントのデフォルトフォント。 (inherited from [`BaseViewOptions`](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/)) |
| [email_options](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/email_options/) | メール メッセージの表示オプション。 (inherited from [`BaseViewOptions`](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/)) |
| [mail_storage_options](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/mail_storage_options/) | メール ストレージ データ ファイルの表示オプション。 (inherited from [`BaseViewOptions`](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/)) |
| [outlook_options](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/outlook_options/) | Microsoft Outlook データ ファイルの表示オプション。 (inherited from [`BaseViewOptions`](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/)) |
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
| [web_document_options](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/web_document_options/) | Web ファイルの表示オプション。 (inherited from [`BaseViewOptions`](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/)) |
| [word_processing_options](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/word_processing_options/) | ワードプロセッシング ファイルの表示オプション。 (inherited from [`BaseViewOptions`](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/)) |

### 例

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import ViewInfoOptions

with Viewer("sample.pdf") as viewer:
    info = viewer.get_view_info(ViewInfoOptions.for_html_view())
    print("Document type:", info.file_type)
    print("Pages count:", len(info.pages))
```

### Guides
`ViewInfoOptions` を使用したタスクガイド：

* [Get Document Information](/viewer/python-net/guides/get-document-info/)

### 参照
* module [`groupdocs.viewer.options`](/viewer/python-net/groupdocs.viewer.options/)
