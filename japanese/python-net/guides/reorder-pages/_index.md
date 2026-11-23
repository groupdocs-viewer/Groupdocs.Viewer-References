---
title: "ページの並び替え"
linkTitle: "Reorder pages"
second_title: "GroupDocs.Viewer for Python via .NET API リファレンス"
description: "GroupDocs.Viewer for Python via .NET を使用してレンダリング中に PDF ページの順序を並び替えます。出力ページのシーケンスを制御します。"
type: docs
url: /ja/python-net/guides/reorder-pages/
is_root: false
weight: 100
---


GroupDocs.Viewer はソースドキュメントのページ順序を保持します。代わりに、出力 PDF ドキュメントのページを並び替えることができます。

ページを並び替えるには、以下の手順に従ってください：

1. [Viewer](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer/viewer) オブジェクトをインスタンス化します。
2. [PdfViewOptions](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer.options/pdfviewoptions) オブジェクトを作成します。
3. [Viewer](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer/viewer) オブジェクトの [view](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer/viewer/#methods) メソッドを呼び出します。最後のパラメータで新しいページ順序を指定します。

以下のコードスニペットはページの並び替え方法を示しています：

{{< tabs "example1">}}
{{< tab "Python">}}
```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions

def reorder_pages():
    # ドキュメントを読み込む
    with Viewer("sample.docx") as viewer:
        # ビューオプションを作成します。
        viewOptions = PdfViewOptions("reorder_pages/reordered_pages.pdf")

        # レンダリングしたい順序でページ番号を渡します。
        viewer.view(viewOptions, [2, 1])

if __name__ == "__main__":
    reorder_pages()
```
{{< /tab >}}
{{< tab "sample.docx" >}}

`sample.docx` はこの例で使用されるサンプルファイルです。ダウンロードするには [here](https://docs.groupdocs.com/viewer/python-net/_sample_files/developer-guide/rendering-documents/rendering-to-pdf/reorder-pages/sample.docx) をクリックしてください。

{{< /tab >}}
{{< tab "reordered_pages.pdf" >}}
```text
Binary file (PDF, 176 KB)
```
[Download full output](https://docs.groupdocs.com/viewer/python-net/_output_files/developer-guide/rendering-documents/rendering-to-pdf/reorder-pages/reorder_pages/reordered_pages.pdf)
{{< /tab >}}
{{< /tabs >}}
