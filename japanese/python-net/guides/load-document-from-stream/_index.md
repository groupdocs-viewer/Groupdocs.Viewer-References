---
title: "ストリームからドキュメントを読み込む"
linkTitle: "Load from stream"
second_title: "GroupDocs.Viewer for Python via .NET API リファレンス"
description: "GroupDocs.Viewer for Python via .NET を使用して、ファイルハンドル、BytesIO、または任意のストリームなどのファイルライクオブジェクトから直接ドキュメントを読み込みます。"
type: docs
url: /ja/python-net/guides/load-document-from-stream/
is_root: false
weight: 60
---


ストリームからドキュメントをディスク上のファイルとして保存せずに読み込むことができます。この機能を使用して、URL、FTP などのさまざまなソースからドキュメントを読み込むことが可能です。

ストリームからドキュメントを読み込むには、次の手順に従ってください：

1. ドキュメントストリームを取得するメソッドを実装します。
2. [Viewer](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer/viewer) クラスのコンストラクタを呼び出します。前のステップで実装したメソッドを指定します。

以下のコードスニペットは、ストリームからドキュメントを読み込む方法を示しています：

{{< tabs "example1">}}
{{< tab "Python" >}}
```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

def load_document_from_stream():
    # ドキュメントストリームを開く
    stream = open("sample.docx", "rb")

    # ストリームからドキュメントをレンダリングします。
    with Viewer(stream) as viewer:
        options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
        viewer.view(options)

if __name__ == "__main__":
    load_document_from_stream()
```
{{< /tab >}}
{{< tab "sample.docx" >}}

`sample.docx` はこの例で使用されるサンプルファイルです。ダウンロードするには [here](https://docs.groupdocs.com/viewer/python-net/_sample_files/developer-guide/loading-documents/load-document-from-stream/sample.docx) をクリックしてください。

{{< /tab >}}
{{< tab "load-document-from-stream-outputs.zip" >}}
```text
page_1.html (317 KB)
page_2.html (149 KB)
page_3.html (113 KB)
```
[Download full output](https://docs.groupdocs.com/viewer/python-net/_output_files/developer-guide/loading-documents/load-document-from-stream/load_document_from_stream/load-document-from-stream-outputs.zip)
{{< /tab >}}
{{< /tabs >}}

また、[Load document from URL]() を参照してください。`BytesIO` ストリームにドキュメントをダウンロードし、ディスクに書き込むことなくレンダリングする具体的な例です。
