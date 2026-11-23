---
title: "クイックスタート ガイド"
linkTitle: "Quick Start Guide"
second_title: "GroupDocs.Viewer for Python via .NET API リファレンス"
description: "仮想環境を設定し、groupdocs-viewer-net をインストールして、3 つの最小限のサンプル — DOCX → HTML、DOCX → PDF、DOCX → ページ単位 PNG — を 5 分未満で実行します。"
type: docs
url: /ja/python-net/guides/quick-start-guide/
is_root: false
weight: 20
---


このガイドは、.NET 経由で Python 用 GroupDocs.Viewer を設定し使用開始する方法の概要を簡潔に示します。このライブラリにより、開発者は最小限の構成でドキュメントを HTML、PDF、PNG、JPG 形式にレンダリングできます。

## Prerequisites

続行するには、以下が揃っていることを確認してください:

1. **Configured** 環境は [System Requirements]() トピックで説明されている通りです。
2. **Optionally** [一時ライセンスを取得](https://purchase.groupdocs.com/temporary-license/) して、すべての製品機能をテストできます。

## Set Up Your Development Environment

ベストプラクティスとして、Python アプリケーションの依存関係管理に仮想環境を使用してください。仮想環境の詳細は [Create and Use Virtual Environments](https://packaging.python.org/en/latest/guides/installing-using-pip-and-virtual-environments/#create-and-use-virtual-environments) のドキュメント トピックをご覧ください。

### Create and Activate a Virtual Environment

仮想環境を作成します:

{{< tabs "example1">}}
{{< tab \"Windows\" >}}
```ps
py -m venv .venv
```
{{< /tab >}}
{{< tab \"Linux\" >}}
```bash
python3 -m venv .venv
```
{{< /tab >}}
{{< tab \"macOS\" >}}
```bash
python3 -m venv .venv
```
{{< /tab >}}
{{< /tabs >}}

仮想環境を有効化します:

{{< tabs \"example2\">}}
{{< tab \"Windows\" >}}
```ps
.venv\Scripts\activate
```
{{< /tab >}}
{{< tab \"Linux\" >}}
```bash
source .venv/bin/activate
```
{{< /tab >}}
{{< tab \"macOS\" >}}
```bash
source .venv/bin/activate
```
{{< /tab >}}
{{< /tabs >}}

### Install `groupdocs-viewer-net` Package

仮想環境を有効化した後、ターミナルで次のコマンドを実行してパッケージの最新バージョンをインストールしてください：

{{< tabs \"example3\">}}
{{< tab \"Windows\" >}}
```ps
py -m pip install groupdocs-viewer-net
```
{{< /tab >}}
{{< tab \"Linux\" >}}
```bash
python3 -m pip install groupdocs-viewer-net
```
{{< /tab >}}
{{< tab \"macOS\" >}}
```bash
python3 -m pip install groupdocs-viewer-net
```
{{< /tab >}}
{{< /tabs >}}

パッケージが正常にインストールされたことを確認してください。メッセージが表示されるはずです。

```bash
Successfully installed groupdocs-viewer-net-*
```

## Example 1: Render document to HTML

ライブラリを手早くテストするために、DOCX ファイルを HTML に変換しましょう。作成するアプリは[ここ](https://docs.groupdocs.com/viewer/python-net/_sample_files/getting-started/quick-start-guide/render_docx_to_html.zip)からダウンロードできます。

{{< tabs "demo_app_render_docx_to_html">}}
{{< tab "render_docx_to_html.py" >}}
```python
import os
from groupdocs.viewer import License, Viewer
from groupdocs.viewer.options import HtmlViewOptions

def render_docx_to_html():
    # ライセンスファイルの絶対パスを取得する
    license_path = os.path.abspath("./GroupDocs.Viewer.lic")

    if os.path.exists(license_path):
        # ライセンスを作成し、パスを設定する
        license = License()
        license.set_license(license_path)

    # DOCX ファイルを読み込む
    with Viewer("./sample.docx") as viewer:
        # ビューオプションを作成する
        html_options = HtmlViewOptions.for_embedded_resources("render_docx_to_html/page_{0}.html")

        # DOCX を HTML にレンダリングします
        viewer.view(html_options)

if __name__ == "__main__":
    render_docx_to_html()
```
{{< /tab >}}
{{< tab "sample.docx" >}}

`sample.docx` はこの例で使用されるサンプルファイルです。[ここ](https://docs.groupdocs.com/viewer/python-net/_sample_files/getting-started/quick-start-guide/sample.docx)をクリックしてダウンロードしてください。

{{< /tab >}}
{{< tab "render-docx-to-html-outputs.zip" >}}
```text
render_docx_to_html/page_1.html (317 KB)
render_docx_to_html/page_2.html (149 KB)
render_docx_to_html/page_3.html (113 KB)
```
[Download full output](https://docs.groupdocs.com/viewer/python-net/_output_files/getting-started/quick-start-guide/render_docx_to_html/render-docx-to-html-outputs.zip)
{{< /tab >}}
{{< /tabs >}}

フォルダー構成は以下のディレクトリ構造と同様になるはずです：

```Directory
📂 demo-app
 ├──render_docx_to_html.py
 ├──sample.docx
 └──GroupDocs.Viewer.lic (Optionally)
```

### Run the App

{{< tabs "run-the-app">}}
{{< tab \"Windows\" >}}
```ps
py render_docx_to_html.py
```
{{< /tab >}}
{{< tab \"Linux\" >}}
```bash
python3 render_docx_to_html.py
```
{{< /tab >}}
{{< tab \"macOS\" >}}
```bash
python3 render_docx_to_html.py
```
{{< /tab >}}
{{< /tabs >}}

アプリを実行した後、`deactivate` を実行するかシェルを閉じて仮想環境を無効化できます。

### Explanation
- `Viewer("./sample.docx")`: Initializes the viewer with the DOCX file.
- `HtmlViewOptions.for_embedded_resources("render_docx_to_html/page_{0}.html")`: Specifies the output format as HTML with embedded resources.
- `viewer.view(html_options)`: Renders the DOCX file to HTML and saves it as `page_1.html`, `page_2.html`, etc.

## Example 2: Render document to PDF

この例では DOCX ファイルを PDF に変換します。作成するアプリは[ここ](https://docs.groupdocs.com/viewer/python-net/_sample_files/getting-started/quick-start-guide/render_docx_to_pdf.zip)からダウンロードできます。

{{< tabs "demo_app_render_docx_to_pdf">}}
{{< tab "render_docx_to_pdf.py" >}}
```python
import os
from groupdocs.viewer import License, Viewer
from groupdocs.viewer.options import PdfViewOptions

def render_docx_to_pdf():
    # ライセンスファイルの絶対パスを取得する
    license_path = os.path.abspath("./GroupDocs.Viewer.lic")

    if os.path.exists(license_path):
        # ライセンスを作成し、パスを設定する
        license = License()
        license.set_license(license_path)

    # DOCX ファイルを読み込む
    with Viewer("./sample.docx") as viewer:
        # ビューオプションを作成する
        pdf_options = PdfViewOptions("render_docx_to_pdf/output.pdf")

        # DOCX を PDF に変換する
        viewer.view(pdf_options)

if __name__ == "__main__":
    render_docx_to_pdf()
```
{{< /tab >}}
{{< tab "sample.docx" >}}

`sample.docx` はこの例で使用されるサンプルファイルです。[ここ](https://docs.groupdocs.com/viewer/python-net/_sample_files/getting-started/quick-start-guide/sample.docx)をクリックしてダウンロードしてください。

{{< /tab >}}
{{< tab "output.pdf" >}}
```text
Binary file (PDF, 234 KB)
```
[Download full output](https://docs.groupdocs.com/viewer/python-net/_output_files/getting-started/quick-start-guide/render_docx_to_pdf/output.pdf)
{{< /tab >}}
{{< /tabs >}}

フォルダー構成は以下のディレクトリ構造と同様になるはずです：

```Directory
📂 demo-app
 ├──sample.docx
 ├──render_docx_to_pdf.py
 └──GroupDocs.Viewer.lic (Optionally)
```

### Run the App

{{< tabs "run_the_app_render_docx_to_pdf">}}
{{< tab \"Windows\" >}}
```ps
py render_docx_to_pdf.py
```
{{< /tab >}}
{{< tab \"Linux\" >}}
```bash
python3 render_docx_to_pdf.py
```
{{< /tab >}}
{{< tab \"macOS\" >}}
```bash
python3 render_docx_to_pdf.py
```
{{< /tab >}}
{{< /tabs >}}

アプリを実行した後、`deactivate` を実行するかシェルを閉じて仮想環境を無効化できます。

### Explanation
- `Viewer("./sample.docx")`: Initializes the viewer with the DOCX file.
- `PdfViewOptions("output.pdf")`: Specifies the output format as PDF.
- `viewer.view(pdf_options)`: Renders the DOCX file to PDF and saves it as `output.pdf`.

## Example 3: Render document to PNG images

この例では DOCX ファイルを PNG 画像に変換します。作成するアプリは[ここ](https://docs.groupdocs.com/viewer/python-net/_sample_files/getting-started/quick-start-guide/render_docx_to_png.zip)からダウンロードできます。

{{< tabs "demo_app_render_docx_to_png">}}
{{< tab "render_docx_to_png.py" >}}
```python
import os
from groupdocs.viewer import License, Viewer
from groupdocs.viewer.options import PngViewOptions

def render_docx_to_png():
    # ライセンスファイルの絶対パスを取得する
    license_path = os.path.abspath("./GroupDocs.Viewer.lic")

    if os.path.exists(license_path):
        # ライセンスを作成し、パスを設定する
        license = License()
        license.set_license(license_path)

    # DOCX ファイルを読み込む
    with Viewer("./sample.docx") as viewer:
        # ビューオプションを作成する
        png_options = PngViewOptions("render_docx_to_png/output_{0}.png")

        # DOCX を PNG 画像に変換する
        viewer.view(png_options)

if __name__ == "__main__":
    render_docx_to_png()
```
{{< /tab >}}
{{< tab "sample.docx" >}}

`sample.docx` はこの例で使用されるサンプルファイルです。[ここ](https://docs.groupdocs.com/viewer/python-net/_sample_files/getting-started/quick-start-guide/sample.docx)をクリックしてダウンロードしてください。

{{< /tab >}}
{{< tab "render-docx-to-png-outputs.zip" >}}
```text
render_docx_to_png/output_1.png (89 KB)
render_docx_to_png/output_2.png (77 KB)
render_docx_to_png/output_3.png (50 KB)
```
[Download full output](https://docs.groupdocs.com/viewer/python-net/_output_files/getting-started/quick-start-guide/render_docx_to_png/render-docx-to-png-outputs.zip)
{{< /tab >}}
{{< /tabs >}}

フォルダー構成は以下のディレクトリ構造と同様になるはずです：

```Directory
📂 demo-app
 ├──sample.docx
 ├──render_docx_to_png.py
 └──GroupDocs.Viewer.lic (Optionally)
```

### Run the App

{{< tabs "run_the_app_render_docx_to_png">}}
{{< tab \"Windows\" >}}
```ps
py render_docx_to_png.py
```
{{< /tab >}}
{{< tab \"Linux\" >}}
```bash
python3 render_docx_to_png.py
```
{{< /tab >}}
{{< tab \"macOS\" >}}
```bash
python3 render_docx_to_png.py
```
{{< /tab >}}
{{< /tabs >}}

アプリを実行した後、`deactivate` を実行するかシェルを閉じて仮想環境を無効化できます。

### Explanation
- `Viewer("./sample.docx")`: Initializes the viewer with the DOCX file.
- `PngViewOptions("render_docx_to_png/output_{0}.png")`: Specifies the output format as PNG images.
- `viewer.view(png_options)`: Renders each page of the DOCX file to PNG and saves them as `output_1.png`, `output_2.png`, etc.

## Next Steps

基本を終えたら、使用方法を向上させるための追加リソースを探しましょう：
- [Supported File Formats](): Review the full list of supported file types.
- [Licensing](): Check details on licensing and evaluation.
- [Technical Support](): Contact support for assistance if you encounter issues.
