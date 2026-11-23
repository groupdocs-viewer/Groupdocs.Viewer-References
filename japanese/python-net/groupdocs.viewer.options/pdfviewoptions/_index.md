---
title: "PdfViewOptions クラス"
second_title: "GroupDocs.Viewer for Python via .NET API リファレンス"
description: "ドキュメントを PDF 形式にレンダリングするオプションを表します。"
type: docs
url: /ja/python-net/groupdocs.viewer.options/pdfviewoptions/
is_root: false
weight: 170
---


## PdfViewOptions class

ドキュメントを PDF 形式にレンダリングするオプションを表します。

詳細については、ドキュメントをご覧ください。

PdfViewOptions 型は次のメンバーを公開します：

### コンストラクタ
| コンストラクタ | 説明 |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.options/pdfviewoptions/__init__/#create_file_stream) | [`PdfViewOptions`](/viewer/python-net/groupdocs.viewer.options/pdfviewoptions/) のインスタンスを初期化します。 |
| [__init__](/viewer/python-net/groupdocs.viewer.options/pdfviewoptions/__init__/#create_file_stream-release_file_stream) | 新しい PdfViewOptions インスタンスを初期化します。 |
| [__init__](/viewer/python-net/groupdocs.viewer.options/pdfviewoptions/__init__/#file_stream_factory) | PdfViewOptions インスタンスを初期化します。 |
| [__init__](/viewer/python-net/groupdocs.viewer.options/pdfviewoptions/__init__/) | PdfViewOptions インスタンスを初期化します。 |
| [__init__](/viewer/python-net/groupdocs.viewer.options/pdfviewoptions/__init__/#output_file_path) | [`PdfViewOptions`](/viewer/python-net/groupdocs.viewer.options/pdfviewoptions/) クラスのインスタンスを初期化します。 |

### メソッド
| メソッド | 説明 |
| :- | :- |
| [rotate_page](/viewer/python-net/groupdocs.viewer.options/viewoptions/rotate_page/) | ページに時計回りの回転を適用します。(継承元 [`ViewOptions`](/viewer/python-net/groupdocs.viewer.options/viewoptions/)) |
| [rotate_page_int32](/viewer/python-net/groupdocs.viewer.options/viewoptions/rotate_page_int32/) | (継承元 [`ViewOptions`](/viewer/python-net/groupdocs.viewer.options/viewoptions/)) |

### プロパティ
| プロパティ | 説明 |
| :- | :- |
| [image_height](/viewer/python-net/groupdocs.viewer.options/pdfviewoptions/image_height/) | 出力画像の高さ（ピクセル単位）。 |
| [image_max_height](/viewer/python-net/groupdocs.viewer.options/pdfviewoptions/image_max_height/) | 出力画像の最大高さ（ピクセル単位）。 |
| [image_max_width](/viewer/python-net/groupdocs.viewer.options/pdfviewoptions/image_max_width/) | 出力画像の最大幅（ピクセル単位）。 |
| [image_width](/viewer/python-net/groupdocs.viewer.options/pdfviewoptions/image_width/) | 出力画像の幅（ピクセル単位）。 |
| [pdf_optimization_options](/viewer/python-net/groupdocs.viewer.options/pdfviewoptions/pdf_optimization_options/) | pdf_optimization_options プロパティは、最適化手法を適用して出力 PDF ファイルのサイズを削減する [`PdfOptimizationOptions`](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/) インスタンスへのアクセスを提供します。 |
| [security](/viewer/python-net/groupdocs.viewer.options/pdfviewoptions/security/) | 出力 PDF ドキュメントのセキュリティオプション。 |
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
from groupdocs.viewer.options import PdfViewOptions

with Viewer("spreadsheet.xlsx") as viewer:
    viewer.view(PdfViewOptions("output.pdf"))
```

### Guides
`PdfViewOptions` を使用するタスクガイド：

* [Quick Start Guide](/viewer/python-net/guides/quick-start-guide/)
* [Protect PDF document](/viewer/python-net/guides/protect-pdf-document/)
* [Reorder pages](/viewer/python-net/guides/reorder-pages/)

### 参照
* module [`groupdocs.viewer.options`](/viewer/python-net/groupdocs.viewer.options/)
