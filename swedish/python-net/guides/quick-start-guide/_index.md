---
title: "Snabbstartsguide"
linkTitle: "Quick Start Guide"
second_title: "GroupDocs.Viewer för Python via .NET API-referenser"
description: "Skapa en virtuell miljö, installera groupdocs-viewer-net och kör tre enkla exempel — DOCX → HTML, DOCX → PDF och DOCX → per‑sida PNG — på under fem minuter."
type: docs
url: /sv/python-net/guides/quick-start-guide/
is_root: false
weight: 20
---


Denna guide ger en snabb översikt över hur du installerar och börjar använda GroupDocs.Viewer för Python via .NET. Detta bibliotek gör det möjligt för utvecklare att rendera dokument till HTML, PDF, PNG och JPG-format med minimal konfiguration.

## Prerequisites

För att fortsätta, se till att du har:

1. **Konfigurerad** miljö som beskrivs i ämnet [System Requirements]().
2. **Valfritt** kan du [Get a Temporary License](https://purchase.groupdocs.com/temporary-license/) för att testa alla produktens funktioner.

## Set Up Your Development Environment

För bästa praxis, använd en virtuell miljö för att hantera beroenden i Python‑applikationer. Läs mer om virtuell miljö i dokumentationsämnet [Create and Use Virtual Environments](https://packaging.python.org/en/latest/guides/installing-using-pip-and-virtual-environments/#create-and-use-virtual-environments).

### Create and Activate a Virtual Environment

Skapa en virtuell miljö:

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

Aktivera en virtuell miljö:

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

Efter att ha aktiverat den virtuella miljön, kör följande kommando i din terminal för att installera den senaste versionen av paketet:

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

Säkerställ att paketet har installerats framgångsrikt. Du bör se meddelandet

```bash
Successfully installed groupdocs-viewer-net-*
```

## Example 1: Render document to HTML

För att snabbt testa biblioteket, rendera en DOCX‑fil till HTML. Du kan också ladda ner appen som vi ska bygga [här](https://docs.groupdocs.com/viewer/python-net/_sample_files/getting-started/quick-start-guide/render_docx_to_html.zip).

{{< tabs "demo_app_render_docx_to_html">}}
{{< tab "render_docx_to_html.py" >}}
```python
import os
from groupdocs.viewer import License, Viewer
from groupdocs.viewer.options import HtmlViewOptions

def render_docx_to_html():
    # Hämta licensfilens absoluta sökväg
    license_path = os.path.abspath("./GroupDocs.Viewer.lic")

    if os.path.exists(license_path):
        # Skapa licens och ange sökvägen
        license = License()
        license.set_license(license_path)

    # Läs in DOCX‑fil
    with Viewer("./sample.docx") as viewer:
        # Skapa visningsalternativ
        html_options = HtmlViewOptions.for_embedded_resources("render_docx_to_html/page_{0}.html")

        # Rendera DOCX till HTML
        viewer.view(html_options)

if __name__ == "__main__":
    render_docx_to_html()
```
{{< /tab >}}
{{< tab \"sample.docx\" >}}

`sample.docx` är exempelfilen som används i detta exempel. Klicka [här](https://docs.groupdocs.com/viewer/python-net/_sample_files/getting-started/quick-start-guide/sample.docx) för att ladda ner den.

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

Din mappstruktur bör se liknande ut som följande katalogstruktur:

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

Efter att ha kört appen kan du inaktivera den virtuella miljön genom att köra `deactivate` eller stänga ditt skal.

### Explanation
- `Viewer("./sample.docx")`: Initializes the viewer with the DOCX file.
- `HtmlViewOptions.for_embedded_resources("render_docx_to_html/page_{0}.html")`: Specifies the output format as HTML with embedded resources.
- `viewer.view(html_options)`: Renders the DOCX file to HTML and saves it as `page_1.html`, `page_2.html`, etc.

## Example 2: Render document to PDF

I det här exemplet kommer vi att rendera en DOCX‑fil till PDF. Du kan ladda ner appen som vi ska bygga [här](https://docs.groupdocs.com/viewer/python-net/_sample_files/getting-started/quick-start-guide/render_docx_to_pdf.zip).

{{< tabs "demo_app_render_docx_to_pdf">}}
{{< tab "render_docx_to_pdf.py" >}}
```python
import os
from groupdocs.viewer import License, Viewer
from groupdocs.viewer.options import PdfViewOptions

def render_docx_to_pdf():
    # Hämta licensfilens absoluta sökväg
    license_path = os.path.abspath("./GroupDocs.Viewer.lic")

    if os.path.exists(license_path):
        # Skapa licens och ange sökvägen
        license = License()
        license.set_license(license_path)

    # Läs in DOCX‑fil
    with Viewer("./sample.docx") as viewer:
        # Skapa visningsalternativ
        pdf_options = PdfViewOptions("render_docx_to_pdf/output.pdf")

        # Rendera DOCX till PDF
        viewer.view(pdf_options)

if __name__ == "__main__":
    render_docx_to_pdf()
```
{{< /tab >}}
{{< tab \"sample.docx\" >}}

`sample.docx` är exempelfilen som används i detta exempel. Klicka [här](https://docs.groupdocs.com/viewer/python-net/_sample_files/getting-started/quick-start-guide/sample.docx) för att ladda ner den.

{{< /tab >}}
{{< tab "output.pdf" >}}
```text
Binary file (PDF, 234 KB)
```
[Download full output](https://docs.groupdocs.com/viewer/python-net/_output_files/getting-started/quick-start-guide/render_docx_to_pdf/output.pdf)
{{< /tab >}}
{{< /tabs >}}

Din mappstruktur bör se liknande ut som följande katalogstruktur:

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

Efter att ha kört appen kan du inaktivera den virtuella miljön genom att köra `deactivate` eller stänga ditt skal.

### Explanation
- `Viewer("./sample.docx")`: Initializes the viewer with the DOCX file.
- `PdfViewOptions("output.pdf")`: Specifies the output format as PDF.
- `viewer.view(pdf_options)`: Renders the DOCX file to PDF and saves it as `output.pdf`.

## Example 3: Render document to PNG images

I det här exemplet kommer vi att rendera en DOCX-fil till PNG-bilder. Du kan ladda ner appen som vi ska bygga [här](https://docs.groupdocs.com/viewer/python-net/_sample_files/getting-started/quick-start-guide/render_docx_to_png.zip).

{{< tabs "demo_app_render_docx_to_png">}}
{{< tab "render_docx_to_png.py" >}}
```python
import os
from groupdocs.viewer import License, Viewer
from groupdocs.viewer.options import PngViewOptions

def render_docx_to_png():
    # Hämta licensfilens absoluta sökväg
    license_path = os.path.abspath("./GroupDocs.Viewer.lic")

    if os.path.exists(license_path):
        # Skapa licens och ange sökvägen
        license = License()
        license.set_license(license_path)

    # Läs in DOCX‑fil
    with Viewer("./sample.docx") as viewer:
        # Skapa visningsalternativ
        png_options = PngViewOptions("render_docx_to_png/output_{0}.png")

        # Rendera DOCX till PNG-bilder
        viewer.view(png_options)

if __name__ == "__main__":
    render_docx_to_png()
```
{{< /tab >}}
{{< tab \"sample.docx\" >}}

`sample.docx` är exempelfilen som används i detta exempel. Klicka [här](https://docs.groupdocs.com/viewer/python-net/_sample_files/getting-started/quick-start-guide/sample.docx) för att ladda ner den.

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

Din mappstruktur bör se liknande ut som följande katalogstruktur:

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

Efter att ha kört appen kan du inaktivera den virtuella miljön genom att köra `deactivate` eller stänga ditt skal.

### Explanation
- `Viewer("./sample.docx")`: Initializes the viewer with the DOCX file.
- `PngViewOptions("render_docx_to_png/output_{0}.png")`: Specifies the output format as PNG images.
- `viewer.view(png_options)`: Renders each page of the DOCX file to PNG and saves them as `output_1.png`, `output_2.png`, etc.

## Next Steps

Efter att ha slutfört grunderna, utforska ytterligare resurser för att förbättra din användning:
- [Supported File Formats](): Review the full list of supported file types.
- [Licensing](): Check details on licensing and evaluation.
- [Technical Support](): Contact support for assistance if you encounter issues.
