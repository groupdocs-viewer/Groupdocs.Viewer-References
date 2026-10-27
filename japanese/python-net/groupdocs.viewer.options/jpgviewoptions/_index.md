---
title: "JpgViewOptions クラス"
second_title: "GroupDocs.Viewer for Python via .NET API リファレンス"
description: "ドキュメントを JPG 形式にレンダリングするオプションを提供します。"
type: docs
url: /ja/python-net/groupdocs.viewer.options/jpgviewoptions/
is_root: false
weight: 100
---


## JpgViewOptions class

ドキュメントを JPG 形式にレンダリングするオプションを提供します。

JpgViewOptions 型は次のメンバーを公開します：

### コンストラクタ
| コンストラクタ | 説明 |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.options/jpgviewoptions/__init__/#create_page_stream) | JpgViewOptions クラスのインスタンスを初期化します。 |
| [__init__](/viewer/python-net/groupdocs.viewer.options/jpgviewoptions/__init__/#create_page_stream-release_page_stream) | JpgViewOptions クラスのインスタンスを初期化します。 |
| [__init__](/viewer/python-net/groupdocs.viewer.options/jpgviewoptions/__init__/#page_stream_factory) | [`JpgViewOptions`](/viewer/python-net/groupdocs.viewer.options/jpgviewoptions/) クラスのインスタンスを初期化します。 |
| [__init__](/viewer/python-net/groupdocs.viewer.options/jpgviewoptions/__init__/) | JpgViewOptions インスタンスを初期化します。 |
| [__init__](/viewer/python-net/groupdocs.viewer.options/jpgviewoptions/__init__/#file_path_format) | [`JpgViewOptions`](/viewer/python-net/groupdocs.viewer.options/jpgviewoptions/) の新しいインスタンスを初期化します。 |

### メソッド
| メソッド | 説明 |
| :- | :- |
| [rotate_page](/viewer/python-net/groupdocs.viewer.options/viewoptions/rotate_page/) | ページに時計回りの回転を適用します。(継承元 [`ViewOptions`](/viewer/python-net/groupdocs.viewer.options/viewoptions/)) |
| [rotate_page_int32](/viewer/python-net/groupdocs.viewer.options/viewoptions/rotate_page_int32/) | (継承元 [`ViewOptions`](/viewer/python-net/groupdocs.viewer.options/viewoptions/)) |

### プロパティ
| プロパティ | 説明 |
| :- | :- |
| [extract_text](/viewer/python-net/groupdocs.viewer.options/jpgviewoptions/extract_text/) | このプロパティはテキスト抽出を有効にします。 |
| [height](/viewer/python-net/groupdocs.viewer.options/jpgviewoptions/height/) | 出力画像の高さ（ピクセル単位）。 |
| [max_height](/viewer/python-net/groupdocs.viewer.options/jpgviewoptions/max_height/) | 出力画像の最大高さ（ピクセル単位）。 |
| [max_width](/viewer/python-net/groupdocs.viewer.options/jpgviewoptions/max_width/) | 出力画像の最大幅（ピクセル単位）。 |
| [quality](/viewer/python-net/groupdocs.viewer.options/jpgviewoptions/quality/) | 出力画像の品質。 |
| [width](/viewer/python-net/groupdocs.viewer.options/jpgviewoptions/width/) | 出力画像の幅（ピクセル単位）。 |
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
from groupdocs.viewer.options import JpgViewOptions

def render_to_jpg():
    # ドキュメントをロードする（例: Excel、Numbers、または画像）
    with Viewer("invoice.xlsx") as viewer:
        # 出力ファイルパターンで JPG ビューオプションを作成します。
        # {0} はページ番号に置き換えられます。
        view_options = JpgViewOptions("output_{0}.jpg")
        # 目的の出力画像サイズ（ピクセル単位）を設定します。
        view_options.width = 800
        view_options.height = 900
        # ドキュメントを JPEG ファイルにレンダリングします。
        viewer.view(view_options)

if __name__ == "__main__":
    render_to_jpg()
```

### 参照
* module [`groupdocs.viewer.options`](/viewer/python-net/groupdocs.viewer.options/)
