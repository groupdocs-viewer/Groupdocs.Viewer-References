---
title: "PdfOptimizationOptions クラス"
second_title: "GroupDocs.Viewer for Python via .NET API リファレンス"
description: "出力 PDF ファイルに適用する PDF 最適化オプションを表します。"
type: docs
url: /ja/python-net/groupdocs.viewer.options/pdfoptimizationoptions/
is_root: false
weight: 150
---


## PdfOptimizationOptions class

出力 PDF ファイルに適用する PDF 最適化オプションを表します。

詳細およびコードサンプルについては、ドキュメントページをご覧ください。

PdfOptimizationOptions 型は次のメンバーを公開します：

### コンストラクタ
| コンストラクタ | 説明 |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/__init__/) | MaxResolution オプションのデフォルト値を 300、ImageQuality オプションのデフォルト値を 100 に初期化します。 |

### プロパティ
| プロパティ | 説明 |
| :- | :- |
| [compress_images](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/compress_images/) | このプロパティは、出力 PDF ファイルの画像圧縮を有効にします。 |
| [convert_to_gray_scale](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/convert_to_gray_scale/) | このプロパティは、出力 PDF ファイルをグレースケールに変換することを有効にします。 |
| [image_quality](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/image_quality/) | 出力 PDF ファイルの画像品質（パーセンテージで表記）。 |
| [lineriaze](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/lineriaze/) | このプロパティは、ウェブブラウザーでのオンライン閲覧用に出力 PDF ファイルの最適化を有効にします。 |
| [max_resolution](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/max_resolution/) | 出力 PDF ファイルの最大解像度。 |
| [optimize_spreadsheets](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/optimize_spreadsheets/) | このプロパティは、PDF ファイル内のスプレッドシートの最適化を有効にします。 |
| [remove_annotations](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/remove_annotations/) | このプロパティは、出力 PDF ファイルから注釈を削除することを有効にします。 |
| [remove_form_fields](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/remove_form_fields/) | このプロパティは、PDF ファイルからフォームフィールドを削除することを有効にします。 |
| [remove_unused_objects](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/remove_unused_objects/) | このプロパティは、PDF ファイルから未使用（孤立）オブジェクトを削除します。 |
| [remove_unused_streams](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/remove_unused_streams/) | このプロパティは、ページリソース辞書で参照されているもののページコンテンツで使用されていない未使用（孤立）ストリームを PDF ファイルから削除します。デフォルトでは無効 (`False`) です；`True` に設定すると出力 PDF のサイズが縮小します。 |
| [resize_images](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/resize_images/) | このプロパティは、出力 PDF ファイルの最大解像度の設定を可能にします。 |
| [subset_fonts](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/subset_fonts/) | このプロパティは、出力 PDF ファイルのフォントをサブセット化します。 |

### 例

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions, PdfOptimizationOptions

def optimize_pdf():
    with Viewer("sample.docx") as viewer:
        view_options = PdfViewOptions("output/optimized.pdf")
        view_options.pdf_optimization_options = PdfOptimizationOptions()
        # ウェブプレビューを高速化するためにリニアライズを有効にします
        view_options.pdf_optimization_options.lineriaze = True
        # サイズ削減のために注釈とフォームフィールドを削除します
        view_options.pdf_optimization_options.remove_annotations = True
        view_options.pdf_optimization_options.remove_form_fields = True

        viewer.view(view_options)
```

### 参照
* module [`groupdocs.viewer.options`](/viewer/python-net/groupdocs.viewer.options/)
