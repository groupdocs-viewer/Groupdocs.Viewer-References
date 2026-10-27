---
title: "ローカルディスクからドキュメントをロードする"
linkTitle: "Load from local disk"
second_title: "GroupDocs.Viewer for Python via .NET API リファレンス"
description: "GroupDocs.Viewer for Python via .NET を使用して、ファイルパスでローカルディスクからドキュメントをロードします。"
type: docs
url: /ja/python-net/guides/load-document-from-local-disk/
is_root: false
weight: 50
---


ファイルへのパスを使用してローカルディスクからドキュメントをロードできます。GroupDocs.Viewer はファイルを読み取り専用モードで開きます。

以下のコードスニペットは、ローカルパス文字列を使用してドキュメントをロードする方法を示しています。

{{< tabs "example1">}}
{{< tab "Python" >}}
```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

def load_document_from_local_disk():
    # ローカルディスクからドキュメントをロードする
    with Viewer("sample.docx") as viewer:
        html_options = HtmlViewOptions.for_embedded_resources("load_document_from_local_disk/document_from_local_disk_{0}.html")
        viewer.view(html_options)

if __name__ == "__main__":
    load_document_from_local_disk()
```
{{< /tab >}}
{{< tab "sample.docx" >}}

`sample.docx` はこの例で使用されるサンプルファイルです。ダウンロードするには [here](https://docs.groupdocs.com/viewer/python-net/_sample_files/developer-guide/loading-documents/load-document-from-local-disk/sample.docx) をクリックしてください。

{{< /tab >}}
{{< tab "load-document-from-local-disk-outputs.zip" >}}
```text
load_document_from_local_disk/document_from_local_disk_1.html (317 KB)
load_document_from_local_disk/document_from_local_disk_2.html (149 KB)
load_document_from_local_disk/document_from_local_disk_3.html (113 KB)
```
[Download full output](https://docs.groupdocs.com/viewer/python-net/_output_files/developer-guide/loading-documents/load-document-from-local-disk/load_document_from_local_disk/load-document-from-local-disk-outputs.zip)
{{< /tab >}}
{{< /tabs >}}
