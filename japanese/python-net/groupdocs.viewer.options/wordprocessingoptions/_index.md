---
title: "WordProcessingOptions クラス"
second_title: "GroupDocs.Viewer for Python via .NET API リファレンス"
description: "Word ドキュメントのレンダリングオプションを含みます。"
type: docs
url: /ja/python-net/groupdocs.viewer.options/wordprocessingoptions/
is_root: false
weight: 380
---


## WordProcessingOptions class

Word ドキュメントのレンダリングオプションを含みます。

詳細については、https://docs.groupdocs.com/viewer/net/render-word-documents/ のドキュメントをご覧ください。

WordProcessingOptions 型は次のメンバーを公開します：

### コンストラクタ
| コンストラクタ | 説明 |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/__init__/) | ワードプロセッシング文書のレンダリング用オプションを初期化します。 |

### メソッド
| メソッド | 説明 |
| :- | :- |
| [clone](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/clone/) | これらのオプションの完全なディープコピーを作成して返します。 |
| [equals](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/equals/#options) | 指定された [`WordProcessingOptions`](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/) インスタンスがこのインスタンスと等しいかどうかを判断します。 |
| [equals_word_processing_options](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/equals_word_processing_options/) |  |

### プロパティ
| プロパティ | 説明 |
| :- | :- |
| [bottom_margin](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/bottom_margin/) | ページの下余白。 |
| [enable_open_type_features](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/enable_open_type_features/) | このオプションは、アラビア語、ヘブライ語、インド系ラテン文字ベース、またはキリル文字ベースのスクリプトをレンダリングする際に、カーニングやその他の OpenType 機能を有効にします。 |
| [horizontal_resolution](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/horizontal_resolution/) | 生成された画像の水平解像度（ドット毎インチ）。このオプションは、WordProcessing 文書を PNG または JPEG 形式にレンダリングする場合にのみ使用されます。 |
| [left_margin](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/left_margin/) | ページの左余白。 |
| [page_number_location](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/page_number_location/) | 読み込まれた WordProcessing 文書のページ番号付け位置で、強制的にページ番号を適用することができます。デフォルトでは `WordsPageNumberLocation.not_apply` で、文書は変更されません。 |
| [page_size](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/page_size/) | 出力ページのサイズ。 |
| [render_tracked_changes](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/render_tracked_changes/) | このプロパティは、トラッキングされた変更（リビジョン）のレンダリングを有効にします。 |
| [right_margin](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/right_margin/) | ページの右余白。 |
| [top_margin](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/top_margin/) | ページの上余白（ポイント単位）。 |
| [unlink_table_of_contents](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/unlink_table_of_contents/) | このオプションは、HTML または PDF のレンダリング時に True に設定すると、目次からのナビゲーションを無効にします。 |
| [update_fields](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/update_fields/) | このプロパティは、WordProcessing 文書を HTML、PDF、PNG、または JPEG 形式で保存する前に、特定のタイプのフィールドが更新されるかどうかを決定します。デフォルトは True で、フィールドが更新されることを意味します。 |
| [vertical_resolution](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/vertical_resolution/) | 生成された画像の垂直解像度（ドット毎インチ）。この解像度は、WordProcessing 文書を PNG または JPEG 形式にレンダリングする場合にのみ使用されます。 |

### 例

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions

with Viewer("with_tracked_changes.docx") as viewer:
    view_options = PdfViewOptions("output/word_with_tracked_changes.pdf")
    view_options.word_processing_options.render_tracked_changes = True
    viewer.view(view_options)
```

### 参照
* module [`groupdocs.viewer.options`](/viewer/python-net/groupdocs.viewer.options/)
