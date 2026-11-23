---
title: "快速入门指南"
linkTitle: "Quick Start Guide"
second_title: "GroupDocs.Viewer 用于 Python，通过 .NET API 参考"
description: "设置虚拟环境，安装 groupdocs-viewer-net，并在不到五分钟内运行三个最小示例 — DOCX → HTML、DOCX → PDF 和 DOCX → 每页 PNG —。"
type: docs
url: /zh/python-net/guides/quick-start-guide/
is_root: false
weight: 20
---


本指南简要概述了如何通过 .NET 设置并开始使用 GroupDocs.Viewer for Python。该库使开发人员能够以最少的配置将文档渲染为 HTML、PDF、PNG 和 JPG 格式。

## Prerequisites

要继续，请确保您已拥有：

1. **Configured** 环境，如 [System Requirements]() 主题中所述。
2. **Optionally** 您可以 [获取临时许可证](https://purchase.groupdocs.com/temporary-license/) 来测试所有产品功能。

## Set Up Your Development Environment

为了遵循最佳实践，请使用虚拟环境来管理 Python 应用程序中的依赖项。了解更多关于虚拟环境的信息，请参阅文档主题 [创建和使用虚拟环境](https://packaging.python.org/en/latest/guides/installing-using-pip-and-virtual-environments/#create-and-use-virtual-environments)。

### Create and Activate a Virtual Environment

创建虚拟环境：

{{< tabs "example1">}}
{{< tab "Windows" >}}
```ps
py -m venv .venv
```
{{< /tab >}}
{{< tab "Linux" >}}
```bash
python3 -m venv .venv
```
{{< /tab >}}
{{< tab "macOS" >}}
```bash
python3 -m venv .venv
```
{{< /tab >}}
{{< /tabs >}}

激活虚拟环境：

{{< tabs \"example2\">}}
{{< tab "Windows" >}}
```ps
.venv\Scripts\activate
```
{{< /tab >}}
{{< tab "Linux" >}}
```bash
source .venv/bin/activate
```
{{< /tab >}}
{{< tab "macOS" >}}
```bash
source .venv/bin/activate
```
{{< /tab >}}
{{< /tabs >}}

### Install `groupdocs-viewer-net` Package

激活虚拟环境后，在终端中运行以下命令以安装最新版本的包：

{{< tabs \"example3\">}}
{{< tab "Windows" >}}
```ps
py -m pip install groupdocs-viewer-net
```
{{< /tab >}}
{{< tab "Linux" >}}
```bash
python3 -m pip install groupdocs-viewer-net
```
{{< /tab >}}
{{< tab "macOS" >}}
```bash
python3 -m pip install groupdocs-viewer-net
```
{{< /tab >}}
{{< /tabs >}}

确保包已成功安装。您应该会看到该消息

```bash
Successfully installed groupdocs-viewer-net-*
```

## Example 1: Render document to HTML

为了快速测试库，让我们将 DOCX 文件渲染为 HTML。您也可以在[这里](https://docs.groupdocs.com/viewer/python-net/_sample_files/getting-started/quick-start-guide/render_docx_to_html.zip)下载我们即将构建的应用程序。

{{< tabs "demo_app_render_docx_to_html">}}
{{< tab "render_docx_to_html.py" >}}
```python
import os
from groupdocs.viewer import License, Viewer
from groupdocs.viewer.options import HtmlViewOptions

def render_docx_to_html():
    # 获取许可证文件的绝对路径
    license_path = os.path.abspath("./GroupDocs.Viewer.lic")

    if os.path.exists(license_path):
        # 创建许可证并设置路径
        license = License()
        license.set_license(license_path)

    # 加载 DOCX 文件
    with Viewer("./sample.docx") as viewer:
        # 创建视图选项
        html_options = HtmlViewOptions.for_embedded_resources("render_docx_to_html/page_{0}.html")

        # 将 DOCX 渲染为 HTML
        viewer.view(html_options)

if __name__ == "__main__":
    render_docx_to_html()
```
{{< /tab >}}
{{< tab "sample.docx" >}}

`sample.docx` 是本示例中使用的示例文件。点击[这里](https://docs.groupdocs.com/viewer/python-net/_sample_files/getting-started/quick-start-guide/sample.docx)下载它。

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

您的文件夹结构应类似于以下目录结构：

```Directory
📂 demo-app
 ├──render_docx_to_html.py
 ├──sample.docx
 └──GroupDocs.Viewer.lic (Optionally)
```

### Run the App

{{< tabs "run-the-app">}}
{{< tab "Windows" >}}
```ps
py render_docx_to_html.py
```
{{< /tab >}}
{{< tab "Linux" >}}
```bash
python3 render_docx_to_html.py
```
{{< /tab >}}
{{< tab "macOS" >}}
```bash
python3 render_docx_to_html.py
```
{{< /tab >}}
{{< /tabs >}}

运行应用程序后，您可以通过执行 `deactivate` 或关闭终端来停用虚拟环境。

### Explanation
- `Viewer("./sample.docx")`: Initializes the viewer with the DOCX file.
- `HtmlViewOptions.for_embedded_resources("render_docx_to_html/page_{0}.html")`: Specifies the output format as HTML with embedded resources.
- `viewer.view(html_options)`: Renders the DOCX file to HTML and saves it as `page_1.html`, `page_2.html`, etc.

## Example 2: Render document to PDF

在本示例中，我们将把 DOCX 文件渲染为 PDF。您可以在[这里](https://docs.groupdocs.com/viewer/python-net/_sample_files/getting-started/quick-start-guide/render_docx_to_pdf.zip)下载我们即将构建的应用程序。

{{< tabs "demo_app_render_docx_to_pdf">}}
{{< tab "render_docx_to_pdf.py" >}}
```python
import os
from groupdocs.viewer import License, Viewer
from groupdocs.viewer.options import PdfViewOptions

def render_docx_to_pdf():
    # 获取许可证文件的绝对路径
    license_path = os.path.abspath("./GroupDocs.Viewer.lic")

    if os.path.exists(license_path):
        # 创建许可证并设置路径
        license = License()
        license.set_license(license_path)

    # 加载 DOCX 文件
    with Viewer("./sample.docx") as viewer:
        # 创建视图选项
        pdf_options = PdfViewOptions("render_docx_to_pdf/output.pdf")

        # 将 DOCX 渲染为 PDF
        viewer.view(pdf_options)

if __name__ == "__main__":
    render_docx_to_pdf()
```
{{< /tab >}}
{{< tab "sample.docx" >}}

`sample.docx` 是本示例中使用的示例文件。点击[这里](https://docs.groupdocs.com/viewer/python-net/_sample_files/getting-started/quick-start-guide/sample.docx)下载它。

{{< /tab >}}
{{< tab "output.pdf" >}}
```text
Binary file (PDF, 234 KB)
```
[Download full output](https://docs.groupdocs.com/viewer/python-net/_output_files/getting-started/quick-start-guide/render_docx_to_pdf/output.pdf)
{{< /tab >}}
{{< /tabs >}}

您的文件夹结构应类似于以下目录结构：

```Directory
📂 demo-app
 ├──sample.docx
 ├──render_docx_to_pdf.py
 └──GroupDocs.Viewer.lic (Optionally)
```

### Run the App

{{< tabs "run_the_app_render_docx_to_pdf">}}
{{< tab "Windows" >}}
```ps
py render_docx_to_pdf.py
```
{{< /tab >}}
{{< tab "Linux" >}}
```bash
python3 render_docx_to_pdf.py
```
{{< /tab >}}
{{< tab "macOS" >}}
```bash
python3 render_docx_to_pdf.py
```
{{< /tab >}}
{{< /tabs >}}

运行应用程序后，您可以通过执行 `deactivate` 或关闭终端来停用虚拟环境。

### Explanation
- `Viewer("./sample.docx")`: Initializes the viewer with the DOCX file.
- `PdfViewOptions("output.pdf")`: Specifies the output format as PDF.
- `viewer.view(pdf_options)`: Renders the DOCX file to PDF and saves it as `output.pdf`.

## Example 3: Render document to PNG images

在本示例中，我们将把 DOCX 文件渲染为 PNG 图像。您可以在[这里](https://docs.groupdocs.com/viewer/python-net/_sample_files/getting-started/quick-start-guide/render_docx_to_png.zip)下载我们即将构建的应用程序。

{{< tabs "demo_app_render_docx_to_png">}}
{{< tab "render_docx_to_png.py" >}}
```python
import os
from groupdocs.viewer import License, Viewer
from groupdocs.viewer.options import PngViewOptions

def render_docx_to_png():
    # 获取许可证文件的绝对路径
    license_path = os.path.abspath("./GroupDocs.Viewer.lic")

    if os.path.exists(license_path):
        # 创建许可证并设置路径
        license = License()
        license.set_license(license_path)

    # 加载 DOCX 文件
    with Viewer("./sample.docx") as viewer:
        # 创建视图选项
        png_options = PngViewOptions("render_docx_to_png/output_{0}.png")

        # 将 DOCX 渲染为 PNG 图像
        viewer.view(png_options)

if __name__ == "__main__":
    render_docx_to_png()
```
{{< /tab >}}
{{< tab "sample.docx" >}}

`sample.docx` 是本示例中使用的示例文件。点击[这里](https://docs.groupdocs.com/viewer/python-net/_sample_files/getting-started/quick-start-guide/sample.docx)下载它。

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

您的文件夹结构应类似于以下目录结构：

```Directory
📂 demo-app
 ├──sample.docx
 ├──render_docx_to_png.py
 └──GroupDocs.Viewer.lic (Optionally)
```

### Run the App

{{< tabs "run_the_app_render_docx_to_png">}}
{{< tab "Windows" >}}
```ps
py render_docx_to_png.py
```
{{< /tab >}}
{{< tab "Linux" >}}
```bash
python3 render_docx_to_png.py
```
{{< /tab >}}
{{< tab "macOS" >}}
```bash
python3 render_docx_to_png.py
```
{{< /tab >}}
{{< /tabs >}}

运行应用程序后，您可以通过执行 `deactivate` 或关闭终端来停用虚拟环境。

### Explanation
- `Viewer("./sample.docx")`: Initializes the viewer with the DOCX file.
- `PngViewOptions("render_docx_to_png/output_{0}.png")`: Specifies the output format as PNG images.
- `viewer.view(png_options)`: Renders each page of the DOCX file to PNG and saves them as `output_1.png`, `output_2.png`, etc.

## Next Steps

完成基础学习后，探索其他资源以提升您的使用效果：
- [Supported File Formats](): Review the full list of supported file types.
- [Licensing](): Check details on licensing and evaluation.
- [Technical Support](): Contact support for assistance if you encounter issues.
