---
title: "テキスト透かしを追加"
linkTitle: "Add text watermarks"
second_title: "GroupDocs.Viewer for Python via .NET API リファレンス"
description: "Python アプリケーションで GroupDocs.Viewer を使用して、レンダリングされたドキュメントにテキスト透かしを追加します。"
type: docs
url: /ja/python-net/guides/add-text-watermark/
is_root: false
weight: 80
---


HTML/JPG/PNG/PDF 出力に透かしを追加するには、以下の手順に従ってください:

1. [HtmlViewOptions](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer.options/htmlviewoptions/) クラスのインスタンスを作成します（または [PngViewOptions](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer.options/pngviewoptions/)、[JpgViewOptions](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer.options/jpgviewoptions/)、[PdfViewOptions](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer.options/pdfviewoptions/) のいずれか）。
2. [Watermark](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer.options/watermark/) オブジェクトを作成し、そのプロパティを設定します;
3. [HtmlViewOptions](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer.options/htmlviewoptions/) クラスの [watermark](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer.options/viewoptions/#properties) メソッドを呼び出し（または [PngViewOptions](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer.options/pngviewoptions/)、[JpgViewOptions](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer.options/jpgviewoptions/)、[PdfViewOptions](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer.options/pdfviewoptions/) のいずれか）し、ステップ 2 で作成したオブジェクトを指定します;
4. [Viewer.view()](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer/viewer/#methods) メソッドを呼び出します。

以下のコードスニペットは、出力ページに透かしを適用する方法を示しています。

{{< tabs "example1">}}
{{< tab "Python" >}}
```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions, Watermark

def add_text_watermark():
    # ドキュメントを読み込む
    with Viewer("sample.docx") as viewer:
        # HTML ファイルを作成します。
        viewOptions = HtmlViewOptions.for_embedded_resources("add_text_watermark/output-watermark.html")
        # 透かしを追加します。
        viewOptions.watermark = Watermark("This is a watermark")
        viewer.view(viewOptions)

if __name__ == "__main__":
    add_text_watermark()
```
{{< /tab >}}
{{< tab "sample.docx" >}}

`sample.docx` はこの例で使用されるサンプルファイルです。[here](https://docs.groupdocs.com/viewer/python-net/_sample_files/developer-guide/rendering-documents/add-text-watermark/sample.docx) をクリックしてダウンロードしてください。

{{< /tab >}}
{{< tab \"output-watermark.html\" >}}
```text
<!DOCTYPE html><html><head><meta http-equiv="Content-Type" content="text/html; charset=utf-8" /><meta name="generator" content="Aspose.Words for .NET 26.4.0" /><title>Sample Document ver.1</title><style type="text/css">@font-face { font-family:'Calibri'; font-style:normal; font-weight:normal; src:local('☺'), url('data:application/x-font-woff;base64,d09GRgABAAAAAGlIAA0AAAAA09gAAQAAAAAAAAAAAAAAAAAAAAAAAAAAAABPUy8yAAABMAAAAGAAAABgncM96GNtYXAAAAGQAAACswAABrCp8yKHY3Z0IAAABEQAAAKEAAAFvLlw2DVmcGdtAAAGy
[TRUNCATED]
```
[Download full output](https://docs.groupdocs.com/viewer/python-net/_output_files/developer-guide/rendering-documents/add-text-watermark/add_text_watermark/output-watermark.html)
{{< /tab >}}
{{< /tabs >}}
