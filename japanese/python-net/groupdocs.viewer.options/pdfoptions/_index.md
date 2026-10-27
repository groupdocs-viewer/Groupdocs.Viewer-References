---
title: "PdfOptions クラス"
second_title: "GroupDocs.Viewer for Python via .NET API リファレンス"
description: "PDF ドキュメントへのレンダリングオプションを表します。"
type: docs
url: /ja/python-net/groupdocs.viewer.options/pdfoptions/
is_root: false
weight: 160
---


## PdfOptions class

PDF ドキュメントへのレンダリングオプションを表します。

詳細については、ドキュメントをご覧ください。

PdfOptions 型は以下のメンバーを公開します：

### コンストラクタ
| コンストラクタ | 説明 |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.options/pdfoptions/__init__/) | PdfOptions クラスの新しいインスタンスを初期化します。 |

### プロパティ
| プロパティ | 説明 |
| :- | :- |
| [disable_chars_grouping](/viewer/python-net/groupdocs.viewer.options/pdfoptions/disable_chars_grouping/) | このプロパティは、ページレンダリング中の正確なシンボル配置のためにシンボルのグルーピングを無効にします。 |
| [disable_copy_protection](/viewer/python-net/groupdocs.viewer.options/pdfoptions/disable_copy_protection/) | このプロパティは、HTML へのレンダリング時にコンテンツのコピー保護を無効にします。 |
| [disable_font_license_verifications](/viewer/python-net/groupdocs.viewer.options/pdfoptions/disable_font_license_verifications/) | このプロパティは、現在の XPS/OXPS ドキュメント内のすべてのフォントに対するライセンス制限を無効にします。 |
| [enable_font_hinting](/viewer/python-net/groupdocs.viewer.options/pdfoptions/enable_font_hinting/) | このプロパティはフォントヒンティングを有効にします。 |
| [enable_layered_rendering](/viewer/python-net/groupdocs.viewer.options/pdfoptions/enable_layered_rendering/) | このプロパティは、HTML へのレンダリング時に元の PDF ドキュメントの Z オーダーでテキストとグラフィックのレンダリングを有効にします。 |
| [fixed_layout](/viewer/python-net/groupdocs.viewer.options/pdfoptions/fixed_layout/) | 固定レイアウトオプションは、PDF および EPUB ドキュメントを固定レイアウトで HTML にレンダリングすることを可能にします。 |
| [image_quality](/viewer/python-net/groupdocs.viewer.options/pdfoptions/image_quality/) | HTML へのレンダリング時の画像リソースの出力画像品質。デフォルトの品質は `ImageQuality.LOW` です。 |
| [render_original_page_size](/viewer/python-net/groupdocs.viewer.options/pdfoptions/render_original_page_size/) | 出力ページサイズは、ソース PDF ドキュメントのページサイズに合わせて設定されます。 |
| [render_text_as_image](/viewer/python-net/groupdocs.viewer.options/pdfoptions/render_text_as_image/) | このオプションは、PDF ファイル内のテキストを HTML 出力で画像としてレンダリングできるようにします。 |
| [wrap_images_in_svg](/viewer/python-net/groupdocs.viewer.options/pdfoptions/wrap_images_in_svg/) | このプロパティは、出力 HTML ドキュメント内の各画像を SVG タグでラップし、出力品質を向上させることを可能にします。 |

### 例

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PngViewOptions

with Viewer("sample.pdf") as viewer:
    view_options = PngViewOptions("output_{0}.png")
    # PDF ページを画像にレンダリングする際にフォントヒンティングを有効にします。
    view_options.pdf_options.enable_font_hinting = True
    viewer.view(view_options)
```

### 参照
* module [`groupdocs.viewer.options`](/viewer/python-net/groupdocs.viewer.options/)
