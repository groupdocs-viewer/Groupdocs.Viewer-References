---
title: "Panduan Memulai Cepat"
linkTitle: "Quick Start Guide"
second_title: "Referensi API GroupDocs.Viewer untuk Python via .NET"
description: "Siapkan lingkungan virtual, instal groupdocs-viewer-net, dan jalankan tiga contoh minimal — DOCX → HTML, DOCX → PDF, dan DOCX → PNG per halaman — dalam waktu kurang dari lima menit."
type: docs
url: /id/python-net/guides/quick-start-guide/
is_root: false
weight: 20
---


Panduan ini memberikan gambaran singkat tentang cara menyiapkan dan mulai menggunakan GroupDocs.Viewer untuk Python melalui .NET. Perpustakaan ini memungkinkan pengembang merender dokumen ke format HTML, PDF, PNG, dan JPG dengan konfigurasi minimal.

## Prerequisites

Untuk melanjutkan, pastikan Anda memiliki:

1. Lingkungan **Dikonfigurasi** seperti yang dijelaskan dalam topik [System Requirements]().
2. **Opsional**, Anda dapat [Mendapatkan Lisensi Sementara](https://purchase.groupdocs.com/temporary-license/) untuk menguji semua fitur produk.

## Set Up Your Development Environment

Untuk praktik terbaik, gunakan lingkungan virtual untuk mengelola dependensi dalam aplikasi Python. Pelajari lebih lanjut tentang lingkungan virtual di topik dokumentasi [Buat dan Gunakan Lingkungan Virtual](https://packaging.python.org/en/latest/guides/installing-using-pip-and-virtual-environments/#create-and-use-virtual-environments).

### Create and Activate a Virtual Environment

Buat lingkungan virtual:

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

Aktifkan lingkungan virtual:

{{< tabs "example2">}}
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

Setelah mengaktifkan lingkungan virtual, jalankan perintah berikut di terminal Anda untuk menginstal versi terbaru paket:

{{< tabs "example3">}}
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

Pastikan paket terinstal dengan sukses. Anda harus melihat pesan

```bash
Successfully installed groupdocs-viewer-net-*
```

## Example 1: Render document to HTML

Untuk menguji perpustakaan dengan cepat, mari render file DOCX ke HTML. Anda juga dapat mengunduh aplikasi yang akan kami bangun [di sini](https://docs.groupdocs.com/viewer/python-net/_sample_files/getting-started/quick-start-guide/render_docx_to_html.zip).

{{< tabs "demo_app_render_docx_to_html">}}
{{< tab "render_docx_to_html.py" >}}
```python
import os
from groupdocs.viewer import License, Viewer
from groupdocs.viewer.options import HtmlViewOptions

def render_docx_to_html():
    # Dapatkan jalur absolut file lisensi
    license_path = os.path.abspath("./GroupDocs.Viewer.lic")

    if os.path.exists(license_path):
        # Buat Lisensi dan atur jalurnya
        license = License()
        license.set_license(license_path)

    # Muat file DOCX
    with Viewer("./sample.docx") as viewer:
        # Buat opsi tampilan
        html_options = HtmlViewOptions.for_embedded_resources("render_docx_to_html/page_{0}.html")

        # Render DOCX ke HTML
        viewer.view(html_options)

if __name__ == "__main__":
    render_docx_to_html()
```
{{< /tab >}}
{{< tab "sample.docx" >}}

`sample.docx` adalah file contoh yang digunakan dalam contoh ini. Klik [di sini](https://docs.groupdocs.com/viewer/python-net/_sample_files/getting-started/quick-start-guide/sample.docx) untuk mengunduhnya.

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

Pohon folder Anda seharusnya terlihat mirip dengan struktur direktori berikut:

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

Setelah menjalankan aplikasi, Anda dapat menonaktifkan lingkungan virtual dengan menjalankan `deactivate` atau menutup shell Anda.

### Explanation
- `Viewer("./sample.docx")`: Initializes the viewer with the DOCX file.
- `HtmlViewOptions.for_embedded_resources("render_docx_to_html/page_{0}.html")`: Specifies the output format as HTML with embedded resources.
- `viewer.view(html_options)`: Renders the DOCX file to HTML and saves it as `page_1.html`, `page_2.html`, etc.

## Example 2: Render document to PDF

Dalam contoh ini kami akan merender file DOCX ke PDF. Anda dapat mengunduh aplikasi yang akan kami bangun [di sini](https://docs.groupdocs.com/viewer/python-net/_sample_files/getting-started/quick-start-guide/render_docx_to_pdf.zip).

{{< tabs "demo_app_render_docx_to_pdf">}}
{{< tab "render_docx_to_pdf.py" >}}
```python
import os
from groupdocs.viewer import License, Viewer
from groupdocs.viewer.options import PdfViewOptions

def render_docx_to_pdf():
    # Dapatkan jalur absolut file lisensi
    license_path = os.path.abspath("./GroupDocs.Viewer.lic")

    if os.path.exists(license_path):
        # Buat Lisensi dan atur jalurnya
        license = License()
        license.set_license(license_path)

    # Muat file DOCX
    with Viewer("./sample.docx") as viewer:
        # Buat opsi tampilan
        pdf_options = PdfViewOptions("render_docx_to_pdf/output.pdf")

        # Render DOCX ke PDF
        viewer.view(pdf_options)

if __name__ == "__main__":
    render_docx_to_pdf()
```
{{< /tab >}}
{{< tab "sample.docx" >}}

`sample.docx` adalah file contoh yang digunakan dalam contoh ini. Klik [di sini](https://docs.groupdocs.com/viewer/python-net/_sample_files/getting-started/quick-start-guide/sample.docx) untuk mengunduhnya.

{{< /tab >}}
{{< tab "output.pdf" >}}
```text
Binary file (PDF, 234 KB)
```
[Download full output](https://docs.groupdocs.com/viewer/python-net/_output_files/getting-started/quick-start-guide/render_docx_to_pdf/output.pdf)
{{< /tab >}}
{{< /tabs >}}

Pohon folder Anda seharusnya terlihat mirip dengan struktur direktori berikut:

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

Setelah menjalankan aplikasi, Anda dapat menonaktifkan lingkungan virtual dengan menjalankan `deactivate` atau menutup shell Anda.

### Explanation
- `Viewer("./sample.docx")`: Initializes the viewer with the DOCX file.
- `PdfViewOptions("output.pdf")`: Specifies the output format as PDF.
- `viewer.view(pdf_options)`: Renders the DOCX file to PDF and saves it as `output.pdf`.

## Example 3: Render document to PNG images

Dalam contoh ini kami akan merender file DOCX ke gambar PNG. Anda dapat mengunduh aplikasi yang akan kami bangun [di sini](https://docs.groupdocs.com/viewer/python-net/_sample_files/getting-started/quick-start-guide/render_docx_to_png.zip).

{{< tabs "demo_app_render_docx_to_png">}}
{{< tab "render_docx_to_png.py" >}}
```python
import os
from groupdocs.viewer import License, Viewer
from groupdocs.viewer.options import PngViewOptions

def render_docx_to_png():
    # Dapatkan jalur absolut file lisensi
    license_path = os.path.abspath("./GroupDocs.Viewer.lic")

    if os.path.exists(license_path):
        # Buat Lisensi dan atur jalurnya
        license = License()
        license.set_license(license_path)

    # Muat file DOCX
    with Viewer("./sample.docx") as viewer:
        # Buat opsi tampilan
        png_options = PngViewOptions("render_docx_to_png/output_{0}.png")

        # Render DOCX ke gambar PNG
        viewer.view(png_options)

if __name__ == "__main__":
    render_docx_to_png()
```
{{< /tab >}}
{{< tab "sample.docx" >}}

`sample.docx` adalah file contoh yang digunakan dalam contoh ini. Klik [di sini](https://docs.groupdocs.com/viewer/python-net/_sample_files/getting-started/quick-start-guide/sample.docx) untuk mengunduhnya.

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

Pohon folder Anda seharusnya terlihat mirip dengan struktur direktori berikut:

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

Setelah menjalankan aplikasi, Anda dapat menonaktifkan lingkungan virtual dengan menjalankan `deactivate` atau menutup shell Anda.

### Explanation
- `Viewer("./sample.docx")`: Initializes the viewer with the DOCX file.
- `PngViewOptions("render_docx_to_png/output_{0}.png")`: Specifies the output format as PNG images.
- `viewer.view(png_options)`: Renders each page of the DOCX file to PNG and saves them as `output_1.png`, `output_2.png`, etc.

## Next Steps

Setelah menyelesaikan dasar-dasar, jelajahi sumber daya tambahan untuk meningkatkan penggunaan Anda:
- [Supported File Formats](): Review the full list of supported file types.
- [Licensing](): Check details on licensing and evaluation.
- [Technical Support](): Contact support for assistance if you encounter issues.
