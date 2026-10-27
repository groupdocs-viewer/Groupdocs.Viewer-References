---
title: "PDF ドキュメントを保護"
linkTitle: "Protect PDF document"
second_title: "GroupDocs.Viewer for Python via .NET API リファレンス"
description: "GroupDocs.Viewer を使用してドキュメントをレンダリングする際に、パスワードと権限で PDF 出力を保護します。"
type: docs
url: /ja/python-net/guides/protect-pdf-document/
is_root: false
weight: 90
---


以下のパラメータを設定することで、PDF ドキュメントを保護できます：

* permissions
* password to open document
* password to change permissions

PDF ドキュメントを保護するには、次の手順に従ってください：

1. [Viewer](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer/viewer) クラスのインスタンスを作成します。コンストラクタのパラメータとしてソースドキュメントのパスを指定します。
2. [Security](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer.options/security) オブジェクトをインスタンス化します。
3. ドキュメントを開くためのパスワードを指定するには、[DocumentOpenPassword](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer.options/security/#properties) プロパティを設定します。
4. 制限を変更するためのパスワードを指定するには、[PermissionsPassword](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer.options/security/#properties) プロパティを設定します。
5. ドキュメントの権限を指定するには、[Permissions](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer.options/permissions) プロパティを設定します。
6. [PdfViewOptions](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer.options/pdfviewoptions) オブジェクトをインスタンス化します。レンダリングされたドキュメントの保存パス形式を指定します。
7. 手順 2〜5 で作成したオブジェクトを使用して、[PdfViewOptions](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer.options/pdfviewoptions) オブジェクトの [Security](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer.options/pdfviewoptions/#properties) プロパティを初期化します。
8. [Viewer](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer/viewer) オブジェクトの [view](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer/viewer/#methods) メソッドを呼び出します。パラメータとして [PdfViewOptions](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer.options/pdfviewoptions) オブジェクトを指定します。

以下のコードスニペットは、出力 PDF ドキュメントを保護する方法を示しています：

{{< tabs "example1">}}
{{< tab "Python">}}
```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions, Security, Permissions

def protect_pdf_document():
    # ドキュメントを読み込む
    with Viewer("sample.docx") as viewer:
        # セキュリティ設定を指定します。
        security = Security()
        security.document_open_password = "o123"
        security.permissions_password = "p123"
        security.permissions = Permissions.ALLOW_ALL & ~Permissions.DENY_PRINTING

        # PDF ファイルを作成します。
        pdf_options = PdfViewOptions("protect_pdf_document/protected_document.pdf")

        # セキュリティ設定を適用します
        pdf_options.security = security
        viewer.view(pdf_options)

if __name__ == "__main__":
    protect_pdf_document()
```
{{< /tab >}}
{{< tab "sample.docx" >}}

`sample.docx` はこの例で使用されるサンプルファイルです。[here](https://docs.groupdocs.com/viewer/python-net/_sample_files/developer-guide/rendering-documents/rendering-to-pdf/protect-pdf-document/sample.docx) をクリックしてダウンロードしてください。

{{< /tab >}}
{{< tab \"protected_document.pdf\" >}}
```text
Binary file (PDF, 238 KB)
```
[Download full output](https://docs.groupdocs.com/viewer/python-net/_output_files/developer-guide/rendering-documents/rendering-to-pdf/protect-pdf-document/protect_pdf_document/protected_document.pdf)
{{< /tab >}}
{{< /tabs >}}
