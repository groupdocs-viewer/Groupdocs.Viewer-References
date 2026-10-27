---
title: "Snelstartgids"
linkTitle: "Quick Start Guide"
second_title: "GroupDocs.Viewer voor Python via .NET API-referenties"
description: "Stel een virtuele omgeving in, installeer groupdocs-viewer-net, en voer drie minimale voorbeelden uit — DOCX → HTML, DOCX → PDF en DOCX → PNG per pagina — in minder dan vijf minuten."
type: docs
url: /nl/python-net/guides/quick-start-guide/
is_root: false
weight: 20
---


Deze gids biedt een kort overzicht van hoe u GroupDocs.Viewer voor Python via .NET kunt instellen en gebruiken. Deze bibliotheek stelt ontwikkelaars in staat documenten te renderen naar HTML-, PDF-, PNG- en JPG-formaten met minimale configuratie.

## Prerequisites

Ga verder door ervoor te zorgen dat u het volgende heeft:

1. **Geconfigureerde** omgeving zoals beschreven in het onderwerp [System Requirements]().
2. **Optioneel** kunt u [Get a Temporary License](https://purchase.groupdocs.com/temporary-license/) verkrijgen om alle productfuncties te testen.

## Set Up Your Development Environment

Voor de beste praktijken gebruikt u een virtuele omgeving om afhankelijkheden in Python‑toepassingen te beheren. Meer informatie over virtuele omgevingen vindt u in de documentatie over [Create and Use Virtual Environments](https://packaging.python.org/en/latest/guides/installing-using-pip-and-virtual-environments/#create-and-use-virtual-environments).

### Create and Activate a Virtual Environment

Maak een virtuele omgeving:

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

Activeer een virtuele omgeving:

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

Na het activeren van de virtuele omgeving voert u het volgende commando uit in uw terminal om de nieuwste versie van het pakket te installeren:

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

Zorg ervoor dat het pakket succesvol is geïnstalleerd. U zou het bericht moeten zien

```bash
Successfully installed groupdocs-viewer-net-*
```

## Example 1: Render document to HTML

Om de bibliotheek snel te testen, laten we een DOCX‑bestand naar HTML renderen. U kunt de app die we gaan bouwen ook downloaden [hier](https://docs.groupdocs.com/viewer/python-net/_sample_files/getting-started/quick-start-guide/render_docx_to_html.zip).

{{< tabs "demo_app_render_docx_to_html">}}
{{< tab "render_docx_to_html.py" >}}
```python
import os
from groupdocs.viewer import License, Viewer
from groupdocs.viewer.options import HtmlViewOptions

def render_docx_to_html():
    # Haal het absolute pad van het licentiebestand op
    license_path = os.path.abspath("./GroupDocs.Viewer.lic")

    if os.path.exists(license_path):
        # Maak een licentie aan en stel het pad in
        license = License()
        license.set_license(license_path)

    # Laad DOCX-bestand
    with Viewer("./sample.docx") as viewer:
        # Maak weergaveopties aan
        html_options = HtmlViewOptions.for_embedded_resources("render_docx_to_html/page_{0}.html")

        # Render DOCX naar HTML
        viewer.view(html_options)

if __name__ == "__main__":
    render_docx_to_html()
```
{{< /tab >}}
{{< tab \"sample.docx\" >}}

`sample.docx` is het voorbeeldbestand dat in dit voorbeeld wordt gebruikt. Klik [hier](https://docs.groupdocs.com/viewer/python-net/_sample_files/getting-started/quick-start-guide/sample.docx) om het te downloaden.

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

Uw mapstructuur zou er ongeveer als volgt uit moeten zien:

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

Na het uitvoeren van de app kunt u de virtuele omgeving deactiveren door `deactivate` uit te voeren of uw shell te sluiten.

### Explanation
- `Viewer("./sample.docx")`: Initializes the viewer with the DOCX file.
- `HtmlViewOptions.for_embedded_resources("render_docx_to_html/page_{0}.html")`: Specifies the output format as HTML with embedded resources.
- `viewer.view(html_options)`: Renders the DOCX file to HTML and saves it as `page_1.html`, `page_2.html`, etc.

## Example 2: Render document to PDF

In dit voorbeeld renderen we een DOCX-bestand naar PDF. U kunt de app die we gaan bouwen downloaden [hier](https://docs.groupdocs.com/viewer/python-net/_sample_files/getting-started/quick-start-guide/render_docx_to_pdf.zip).

{{< tabs "demo_app_render_docx_to_pdf">}}
{{< tab "render_docx_to_pdf.py" >}}
```python
import os
from groupdocs.viewer import License, Viewer
from groupdocs.viewer.options import PdfViewOptions

def render_docx_to_pdf():
    # Haal het absolute pad van het licentiebestand op
    license_path = os.path.abspath("./GroupDocs.Viewer.lic")

    if os.path.exists(license_path):
        # Maak een licentie aan en stel het pad in
        license = License()
        license.set_license(license_path)

    # Laad DOCX-bestand
    with Viewer("./sample.docx") as viewer:
        # Maak weergaveopties aan
        pdf_options = PdfViewOptions("render_docx_to_pdf/output.pdf")

        # Render DOCX naar PDF
        viewer.view(pdf_options)

if __name__ == "__main__":
    render_docx_to_pdf()
```
{{< /tab >}}
{{< tab \"sample.docx\" >}}

`sample.docx` is het voorbeeldbestand dat in dit voorbeeld wordt gebruikt. Klik [hier](https://docs.groupdocs.com/viewer/python-net/_sample_files/getting-started/quick-start-guide/sample.docx) om het te downloaden.

{{< /tab >}}
{{< tab "output.pdf" >}}
```text
Binary file (PDF, 234 KB)
```
[Download full output](https://docs.groupdocs.com/viewer/python-net/_output_files/getting-started/quick-start-guide/render_docx_to_pdf/output.pdf)
{{< /tab >}}
{{< /tabs >}}

Uw mapstructuur zou er ongeveer als volgt uit moeten zien:

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

Na het uitvoeren van de app kunt u de virtuele omgeving deactiveren door `deactivate` uit te voeren of uw shell te sluiten.

### Explanation
- `Viewer("./sample.docx")`: Initializes the viewer with the DOCX file.
- `PdfViewOptions("output.pdf")`: Specifies the output format as PDF.
- `viewer.view(pdf_options)`: Renders the DOCX file to PDF and saves it as `output.pdf`.

## Example 3: Render document to PNG images

In dit voorbeeld renderen we een DOCX-bestand naar PNG-afbeeldingen. U kunt de app die we gaan bouwen downloaden [hier](https://docs.groupdocs.com/viewer/python-net/_sample_files/getting-started/quick-start-guide/render_docx_to_png.zip).

{{< tabs "demo_app_render_docx_to_png">}}
{{< tab "render_docx_to_png.py" >}}
```python
import os
from groupdocs.viewer import License, Viewer
from groupdocs.viewer.options import PngViewOptions

def render_docx_to_png():
    # Haal het absolute pad van het licentiebestand op
    license_path = os.path.abspath("./GroupDocs.Viewer.lic")

    if os.path.exists(license_path):
        # Maak een licentie aan en stel het pad in
        license = License()
        license.set_license(license_path)

    # Laad DOCX-bestand
    with Viewer("./sample.docx") as viewer:
        # Maak weergaveopties aan
        png_options = PngViewOptions("render_docx_to_png/output_{0}.png")

        # Render DOCX naar PNG-afbeeldingen
        viewer.view(png_options)

if __name__ == "__main__":
    render_docx_to_png()
```
{{< /tab >}}
{{< tab \"sample.docx\" >}}

`sample.docx` is het voorbeeldbestand dat in dit voorbeeld wordt gebruikt. Klik [hier](https://docs.groupdocs.com/viewer/python-net/_sample_files/getting-started/quick-start-guide/sample.docx) om het te downloaden.

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

Uw mapstructuur zou er ongeveer als volgt uit moeten zien:

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

Na het uitvoeren van de app kunt u de virtuele omgeving deactiveren door `deactivate` uit te voeren of uw shell te sluiten.

### Explanation
- `Viewer("./sample.docx")`: Initializes the viewer with the DOCX file.
- `PngViewOptions("render_docx_to_png/output_{0}.png")`: Specifies the output format as PNG images.
- `viewer.view(png_options)`: Renders each page of the DOCX file to PNG and saves them as `output_1.png`, `output_2.png`, etc.

## Next Steps

Na het voltooien van de basis, verken extra bronnen om uw gebruik te verbeteren:
- [Supported File Formats](): Review the full list of supported file types.
- [Licensing](): Check details on licensing and evaluation.
- [Technical Support](): Contact support for assistance if you encounter issues.
