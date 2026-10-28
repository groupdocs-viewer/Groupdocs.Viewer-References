---
title: "Hızlı Başlangıç Kılavuzu"
linkTitle: "Quick Start Guide"
second_title: "GroupDocs.Viewer Python için .NET üzerinden API Referansları"
description: "Sanal bir ortam kurun, groupdocs-viewer-net'i yükleyin ve beş dakikadan kısa sürede üç temel örneği çalıştırın — DOCX → HTML, DOCX → PDF ve DOCX → sayfa başına PNG —."
type: docs
url: /tr/python-net/guides/quick-start-guide/
is_root: false
weight: 20
---


Bu kılavuz, .NET üzerinden Python için GroupDocs.Viewer'ı nasıl kurup kullanmaya başlayacağınız hakkında hızlı bir genel bakış sunar. Bu kütüphane, geliştiricilerin belgeleri minimum yapılandırma ile HTML, PDF, PNG ve JPG formatlarında oluşturmasını sağlar.

## Prerequisites

Devam etmek için, şunların olduğundan emin olun:

1. **Configured** ortam, [System Requirements]() konusunda açıklandığı gibi.
2. **Optionally** [Get a Temporary License](https://purchase.groupdocs.com/temporary-license/) alarak tüm ürün özelliklerini test edebilirsiniz.

## Set Up Your Development Environment

En iyi uygulamalar için, Python uygulamalarında bağımlılıkları yönetmek amacıyla bir sanal ortam kullanın. Sanal ortam hakkında daha fazla bilgi edinmek için [Create and Use Virtual Environments](https://packaging.python.org/en/latest/guides/installing-using-pip-and-virtual-environments/#create-and-use-virtual-environments) dokümantasyon konusuna bakın.

### Create and Activate a Virtual Environment

Sanal bir ortam oluşturun:

{{< tabs \"example1\">}}
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

Sanal ortamı etkinleştirin:

{{< tabs "example2">}}
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

Sanal ortamı etkinleştirdikten sonra, paketinin en son sürümünü yüklemek için terminalinizde aşağıdaki komutu çalıştırın:

{{< tabs "example3">}}
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

Paketin başarılı bir şekilde yüklendiğinden emin olun. Aşağıdaki mesajı görmelisiniz

```bash
Successfully installed groupdocs-viewer-net-*
```

## Example 1: Render document to HTML

Kütüphaneyi hızlıca test etmek için bir DOCX dosyasını HTML'ye dönüştürelim. Ayrıca oluşturacağımız uygulamayı [buradan](https://docs.groupdocs.com/viewer/python-net/_sample_files/getting-started/quick-start-guide/render_docx_to_html.zip) indirebilirsiniz.

{{< tabs "demo_app_render_docx_to_html">}}
{{< tab "render_docx_to_html.py" >}}
```python
import os
from groupdocs.viewer import License, Viewer
from groupdocs.viewer.options import HtmlViewOptions

def render_docx_to_html():
    # Lisans dosyasının mutlak yolunu alın
    license_path = os.path.abspath("./GroupDocs.Viewer.lic")

    if os.path.exists(license_path):
        # Lisans oluşturun ve yolu ayarlayın
        license = License()
        license.set_license(license_path)

    # DOCX dosyasını yükleyin
    with Viewer("./sample.docx") as viewer:
        # Görünüm seçeneklerini oluşturun
        html_options = HtmlViewOptions.for_embedded_resources("render_docx_to_html/page_{0}.html")

        # DOCX'i HTML'e dönüştürür
        viewer.view(html_options)

if __name__ == "__main__":
    render_docx_to_html()
```
{{< /tab >}}
{{< tab \"sample.docx\" >}}

`sample.docx` bu örnekte kullanılan örnek dosyadır. İndirmek için [buraya](https://docs.groupdocs.com/viewer/python-net/_sample_files/getting-started/quick-start-guide/sample.docx) tıklayın.

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

Klasör ağacınız aşağıdaki dizin yapısına benzer olmalıdır:

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

Uygulamayı çalıştırdıktan sonra `deactivate` komutunu çalıştırarak veya kabuğunuzu kapatarak sanal ortamı devre dışı bırakabilirsiniz.

### Explanation
- `Viewer("./sample.docx")`: Initializes the viewer with the DOCX file.
- `HtmlViewOptions.for_embedded_resources("render_docx_to_html/page_{0}.html")`: Specifies the output format as HTML with embedded resources.
- `viewer.view(html_options)`: Renders the DOCX file to HTML and saves it as `page_1.html`, `page_2.html`, etc.

## Example 2: Render document to PDF

Bu örnekte bir DOCX dosyasını PDF olarak render edeceğiz. Oluşturacağımız uygulamayı [buradan](https://docs.groupdocs.com/viewer/python-net/_sample_files/getting-started/quick-start-guide/render_docx_to_pdf.zip) indirebilirsiniz.

{{< tabs "demo_app_render_docx_to_pdf">}}
{{< tab "render_docx_to_pdf.py" >}}
```python
import os
from groupdocs.viewer import License, Viewer
from groupdocs.viewer.options import PdfViewOptions

def render_docx_to_pdf():
    # Lisans dosyasının mutlak yolunu alın
    license_path = os.path.abspath("./GroupDocs.Viewer.lic")

    if os.path.exists(license_path):
        # Lisans oluşturun ve yolu ayarlayın
        license = License()
        license.set_license(license_path)

    # DOCX dosyasını yükleyin
    with Viewer("./sample.docx") as viewer:
        # Görünüm seçeneklerini oluşturun
        pdf_options = PdfViewOptions("render_docx_to_pdf/output.pdf")

        # DOCX'i PDF'ye dönüştürün
        viewer.view(pdf_options)

if __name__ == "__main__":
    render_docx_to_pdf()
```
{{< /tab >}}
{{< tab \"sample.docx\" >}}

`sample.docx` bu örnekte kullanılan örnek dosyadır. İndirmek için [buraya](https://docs.groupdocs.com/viewer/python-net/_sample_files/getting-started/quick-start-guide/sample.docx) tıklayın.

{{< /tab >}}
{{< tab "output.pdf" >}}
```text
Binary file (PDF, 234 KB)
```
[Download full output](https://docs.groupdocs.com/viewer/python-net/_output_files/getting-started/quick-start-guide/render_docx_to_pdf/output.pdf)
{{< /tab >}}
{{< /tabs >}}

Klasör ağacınız aşağıdaki dizin yapısına benzer olmalıdır:

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

Uygulamayı çalıştırdıktan sonra `deactivate` komutunu çalıştırarak veya kabuğunuzu kapatarak sanal ortamı devre dışı bırakabilirsiniz.

### Explanation
- `Viewer("./sample.docx")`: Initializes the viewer with the DOCX file.
- `PdfViewOptions("output.pdf")`: Specifies the output format as PDF.
- `viewer.view(pdf_options)`: Renders the DOCX file to PDF and saves it as `output.pdf`.

## Example 3: Render document to PNG images

Bu örnekte bir DOCX dosyasını PNG görüntülerine render edeceğiz. Oluşturacağımız uygulamayı [buradan](https://docs.groupdocs.com/viewer/python-net/_sample_files/getting-started/quick-start-guide/render_docx_to_png.zip) indirebilirsiniz.

{{< tabs "demo_app_render_docx_to_png">}}
{{< tab "render_docx_to_png.py" >}}
```python
import os
from groupdocs.viewer import License, Viewer
from groupdocs.viewer.options import PngViewOptions

def render_docx_to_png():
    # Lisans dosyasının mutlak yolunu alın
    license_path = os.path.abspath("./GroupDocs.Viewer.lic")

    if os.path.exists(license_path):
        # Lisans oluşturun ve yolu ayarlayın
        license = License()
        license.set_license(license_path)

    # DOCX dosyasını yükleyin
    with Viewer("./sample.docx") as viewer:
        # Görünüm seçeneklerini oluşturun
        png_options = PngViewOptions("render_docx_to_png/output_{0}.png")

        # DOCX'i PNG görüntülerine dönüştürün
        viewer.view(png_options)

if __name__ == "__main__":
    render_docx_to_png()
```
{{< /tab >}}
{{< tab \"sample.docx\" >}}

`sample.docx` bu örnekte kullanılan örnek dosyadır. İndirmek için [buraya](https://docs.groupdocs.com/viewer/python-net/_sample_files/getting-started/quick-start-guide/sample.docx) tıklayın.

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

Klasör ağacınız aşağıdaki dizin yapısına benzer olmalıdır:

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

Uygulamayı çalıştırdıktan sonra `deactivate` komutunu çalıştırarak veya kabuğunuzu kapatarak sanal ortamı devre dışı bırakabilirsiniz.

### Explanation
- `Viewer("./sample.docx")`: Initializes the viewer with the DOCX file.
- `PngViewOptions("render_docx_to_png/output_{0}.png")`: Specifies the output format as PNG images.
- `viewer.view(png_options)`: Renders each page of the DOCX file to PNG and saves them as `output_1.png`, `output_2.png`, etc.

## Next Steps

Temel konuları tamamladıktan sonra, kullanımınızı geliştirmek için ek kaynakları keşfedin:
- [Supported File Formats](): Review the full list of supported file types.
- [Licensing](): Check details on licensing and evaluation.
- [Technical Support](): Contact support for assistance if you encounter issues.
