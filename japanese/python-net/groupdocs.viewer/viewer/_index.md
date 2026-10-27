---
title: "Viewer クラス"
second_title: "GroupDocs.Viewer for Python via .NET API リファレンス"
description: "ドキュメントのレンダリングプロセスを制御するメインクラスを表します。"
type: docs
url: /ja/python-net/groupdocs.viewer/viewer/
is_root: false
weight: 100
---


## Viewer class

ドキュメントのレンダリングプロセスを制御するメインクラスを表します。

Viewer タイプは以下のメンバーを公開します:

### コンストラクタ
| コンストラクタ | 説明 |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer/viewer/__init__/#get_file_stream) | `[`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/)` クラスの新しいインスタンスを初期化します。 |
| [__init__](/viewer/python-net/groupdocs.viewer/viewer/__init__/#get_file_stream-get_load_options) | `[`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/)` の新しいインスタンスを初期化します。 |
| [__init__](/viewer/python-net/groupdocs.viewer/viewer/__init__/#get_file_stream-settings) | 新しい [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/) インスタンスを初期化します。 |
| [__init__](/viewer/python-net/groupdocs.viewer/viewer/__init__/#get_file_stream-get_load_options-settings) | 新しい Viewer インスタンスを初期化します。 |
| [__init__](/viewer/python-net/groupdocs.viewer/viewer/__init__/#stream) | `[`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/)` クラスの新しいインスタンスを初期化します。 |
| [__init__](/viewer/python-net/groupdocs.viewer/viewer/__init__/#stream-leave_open) | 新しい Viewer インスタンスを初期化します。 |
| [__init__](/viewer/python-net/groupdocs.viewer/viewer/__init__/#stream-load_options) | `[`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/)` の新しいインスタンスを初期化します。 |
| [__init__](/viewer/python-net/groupdocs.viewer/viewer/__init__/#stream-load_options-leave_open) | 新しい Viewer インスタンスを初期化します。 |
| [__init__](/viewer/python-net/groupdocs.viewer/viewer/__init__/#stream-settings) | 新しい Viewer インスタンスを初期化します。 |
| [__init__](/viewer/python-net/groupdocs.viewer/viewer/__init__/#stream-settings-leave_open) | 新しい Viewer インスタンスを初期化します。 |
| [__init__](/viewer/python-net/groupdocs.viewer/viewer/__init__/#stream-load_options-settings) | 新しい Viewer インスタンスを初期化します。 |
| [__init__](/viewer/python-net/groupdocs.viewer/viewer/__init__/#stream-load_options-settings-leave_open) | `[`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/)` の新しいインスタンスを初期化します。 |
| [__init__](/viewer/python-net/groupdocs.viewer/viewer/__init__/#file_path) | `[`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/)` クラスの新しいインスタンスを初期化します。 |
| [__init__](/viewer/python-net/groupdocs.viewer/viewer/__init__/#file_path-settings) | `[`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/)` クラスの新しいインスタンスを初期化します。 |
| [__init__](/viewer/python-net/groupdocs.viewer/viewer/__init__/#file_path-load_options) | `[`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/)` の新しいインスタンスを初期化します。 |
| [__init__](/viewer/python-net/groupdocs.viewer/viewer/__init__/#file_path-load_options-settings) | 新しい Viewer インスタンスを初期化します。 |

### メソッド
| メソッド | 説明 |
| :- | :- |
| [dispose](/viewer/python-net/groupdocs.viewer/viewer/dispose/) | ファイルストリームと管理された内部リソースを解放します。 |
| [get_all_fonts](/viewer/python-net/groupdocs.viewer/viewer/get_all_fonts/) | ロードされたドキュメントで使用されているすべてのフォントを返します。埋め込みフォントと OS にインストールされているシステムフォントを含みます。 |
| [get_attachments](/viewer/python-net/groupdocs.viewer/viewer/get_attachments/) | ドキュメントに含まれる添付ファイルを返します。 |
| [get_file_info](/viewer/python-net/groupdocs.viewer/viewer/get_file_info/) | ファイルタイプやファイルが暗号化されているかどうかを示すフラグなど、ファイルに関する情報を返します。 |
| [get_view_info](/viewer/python-net/groupdocs.viewer/viewer/get_view_info/#options) | ビューおよびドキュメント固有の情報を返します。 |
| [get_view_info_view_info_options](/viewer/python-net/groupdocs.viewer/viewer/get_view_info_view_info_options/) |  |
| [save_attachment](/viewer/python-net/groupdocs.viewer/viewer/save_attachment/#attachment-destination) | `destination` ストリームに添付ファイルを保存します。 |
| [save_attachment_attachment](/viewer/python-net/groupdocs.viewer/viewer/save_attachment_attachment/) |  |
| [save_attachment_stream](/viewer/python-net/groupdocs.viewer/viewer/save_attachment_stream/) |  |
| [save_attachment_streams](/viewer/python-net/groupdocs.viewer/viewer/save_attachment_streams/) |  |
| [search](/viewer/python-net/groupdocs.viewer/viewer/search/#options) | テキスト検索を実行し、提供されたオプションに従ってロードされたドキュメント内で見つかったテキストをハイライトします。 |
| [search_search_highlight_options](/viewer/python-net/groupdocs.viewer/viewer/search_search_highlight_options/) |  |
| [view](/viewer/python-net/groupdocs.viewer/viewer/view/#options) | すべてのドキュメントページのビューを作成します。 |
| [view](/viewer/python-net/groupdocs.viewer/viewer/view/#options-page_numbers) | 特定のドキュメントページのビューを作成します。 |
| [view](/viewer/python-net/groupdocs.viewer/viewer/view/#options-cancellation_token-page_numbers) | 特定のドキュメントページのビューを作成します。 |
| [view_view_options](/viewer/python-net/groupdocs.viewer/viewer/view_view_options/) |  |

### 例

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions, PngViewOptions

# DOCX を HTML にレンダリングします
with Viewer("./sample.docx") as viewer:
    html_opts = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(html_opts)

# PDF を PNG にレンダリングします
with Viewer("document.pdf") as viewer:
    png_opts = PngViewOptions("page_{0}.png")
    viewer.view(png_opts)
```

### Guides
`Viewer` を使用するタスク ガイド：

* [Quick Start Guide](/viewer/python-net/guides/quick-start-guide/)
* [Get Document Information](/viewer/python-net/guides/get-document-info/)
* [Load document from local disk](/viewer/python-net/guides/load-document-from-local-disk/)
* [Load document from stream](/viewer/python-net/guides/load-document-from-stream/)
* [Load document from URL](/viewer/python-net/guides/load-document-from-url/)
* [Add text watermarks](/viewer/python-net/guides/add-text-watermark/)
* [Protect PDF document](/viewer/python-net/guides/protect-pdf-document/)
* [Reorder pages](/viewer/python-net/guides/reorder-pages/)
* [Save attachments](/viewer/python-net/guides/how-to-extract-and-save-attachments/)

### 参照
* module [`groupdocs.viewer`](/viewer/python-net/groupdocs.viewer/)
