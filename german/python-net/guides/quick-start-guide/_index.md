---
title: "Schnellstartanleitung"
linkTitle: "Quick Start Guide"
second_title: "GroupDocs.Viewer für Python über .NET API-Referenzen"
description: "Richten Sie eine virtuelle Umgebung ein, installieren Sie groupdocs-viewer-net und führen Sie drei minimale Beispiele aus — DOCX → HTML, DOCX → PDF und DOCX → PNG pro Seite — in weniger als fünf Minuten."
type: docs
url: /de/python-net/guides/quick-start-guide/
is_root: false
weight: 20
---


Dieses Handbuch bietet einen kurzen Überblick darüber, wie Sie GroupDocs.Viewer für Python über .NET einrichten und nutzen können. Diese Bibliothek ermöglicht Entwicklern, Dokumente mit minimaler Konfiguration in HTML-, PDF-, PNG- und JPG-Formate zu rendern.

## Prerequisites

Um fortzufahren, stellen Sie sicher, dass Sie Folgendes haben:

1. **Configured** Umgebung wie im Thema [System Requirements]() beschrieben.
2. **Optionally** können Sie [Get a Temporary License](https://purchase.groupdocs.com/temporary-license/) erhalten, um alle Produktfunktionen zu testen.

## Set Up Your Development Environment

Für bewährte Verfahren verwenden Sie eine virtuelle Umgebung, um Abhängigkeiten in Python-Anwendungen zu verwalten. Erfahren Sie mehr über virtuelle Umgebungen im Thema [Create and Use Virtual Environments](https://packaging.python.org/en/latest/guides/installing-using-pip-and-virtual-environments/#create-and-use-virtual-environments) Dokumentation.

### Create and Activate a Virtual Environment

Erstellen Sie eine virtuelle Umgebung:

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

Aktiviere eine virtuelle Umgebung:

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

Nachdem die virtuelle Umgebung aktiviert wurde, führen Sie den folgenden Befehl in Ihrem Terminal aus, um die neueste Version des Pakets zu installieren:

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

Stellen Sie sicher, dass das Paket erfolgreich installiert wurde. Sie sollten die Meldung sehen

```bash
Successfully installed groupdocs-viewer-net-*
```

## Example 1: Render document to HTML

Um die Bibliothek schnell zu testen, rendern wir eine DOCX-Datei zu HTML. Sie können die Anwendung, die wir bauen werden, auch [hier](https://docs.groupdocs.com/viewer/python-net/_sample_files/getting-started/quick-start-guide/render_docx_to_html.zip) herunterladen.

{{< tabs "demo_app_render_docx_to_html">}}
{{< tab "render_docx_to_html.py" >}}
```python
import os
from groupdocs.viewer import License, Viewer
from groupdocs.viewer.options import HtmlViewOptions

def render_docx_to_html():
    # Abrufen des absoluten Pfads der Lizenzdatei
    license_path = os.path.abspath("./GroupDocs.Viewer.lic")

    if os.path.exists(license_path):
        # Lizenz erstellen und den Pfad festlegen
        license = License()
        license.set_license(license_path)

    # DOCX-Datei laden
    with Viewer("./sample.docx") as viewer:
        # Ansichtsoptionen erstellen
        html_options = HtmlViewOptions.for_embedded_resources("render_docx_to_html/page_{0}.html")

        # DOCX nach HTML rendern
        viewer.view(html_options)

if __name__ == "__main__":
    render_docx_to_html()
```
{{< /tab >}}
{{< tab \"sample.docx\" >}}

`sample.docx` ist die in diesem Beispiel verwendete Beispieldatei. Klicken Sie [hier](https://docs.groupdocs.com/viewer/python-net/_sample_files/getting-started/quick-start-guide/sample.docx) zum Herunterladen.

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

Ihr Ordnerbaum sollte einer ähnlichen Verzeichnisstruktur wie folgt aussehen:

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

Nach dem Ausführen der Anwendung können Sie die virtuelle Umgebung deaktivieren, indem Sie `deactivate` ausführen oder Ihre Shell schließen.

### Explanation
- `Viewer("./sample.docx")`: Initializes the viewer with the DOCX file.
- `HtmlViewOptions.for_embedded_resources("render_docx_to_html/page_{0}.html")`: Specifies the output format as HTML with embedded resources.
- `viewer.view(html_options)`: Renders the DOCX file to HTML and saves it as `page_1.html`, `page_2.html`, etc.

## Example 2: Render document to PDF

In diesem Beispiel rendern wir eine DOCX-Datei zu PDF. Sie können die Anwendung, die wir bauen werden, auch [hier](https://docs.groupdocs.com/viewer/python-net/_sample_files/getting-started/quick-start-guide/render_docx_to_pdf.zip) herunterladen.

{{< tabs "demo_app_render_docx_to_pdf">}}
{{< tab "render_docx_to_pdf.py" >}}
```python
import os
from groupdocs.viewer import License, Viewer
from groupdocs.viewer.options import PdfViewOptions

def render_docx_to_pdf():
    # Abrufen des absoluten Pfads der Lizenzdatei
    license_path = os.path.abspath("./GroupDocs.Viewer.lic")

    if os.path.exists(license_path):
        # Lizenz erstellen und den Pfad festlegen
        license = License()
        license.set_license(license_path)

    # DOCX-Datei laden
    with Viewer("./sample.docx") as viewer:
        # Ansichtsoptionen erstellen
        pdf_options = PdfViewOptions("render_docx_to_pdf/output.pdf")

        # DOCX zu PDF rendern
        viewer.view(pdf_options)

if __name__ == "__main__":
    render_docx_to_pdf()
```
{{< /tab >}}
{{< tab \"sample.docx\" >}}

`sample.docx` ist die in diesem Beispiel verwendete Beispieldatei. Klicken Sie [hier](https://docs.groupdocs.com/viewer/python-net/_sample_files/getting-started/quick-start-guide/sample.docx) zum Herunterladen.

{{< /tab >}}
{{< tab "output.pdf" >}}
```text
Binary file (PDF, 234 KB)
```
[Download full output](https://docs.groupdocs.com/viewer/python-net/_output_files/getting-started/quick-start-guide/render_docx_to_pdf/output.pdf)
{{< /tab >}}
{{< /tabs >}}

Ihr Ordnerbaum sollte einer ähnlichen Verzeichnisstruktur wie folgt aussehen:

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

Nach dem Ausführen der Anwendung können Sie die virtuelle Umgebung deaktivieren, indem Sie `deactivate` ausführen oder Ihre Shell schließen.

### Explanation
- `Viewer("./sample.docx")`: Initializes the viewer with the DOCX file.
- `PdfViewOptions("output.pdf")`: Specifies the output format as PDF.
- `viewer.view(pdf_options)`: Renders the DOCX file to PDF and saves it as `output.pdf`.

## Example 3: Render document to PNG images

In diesem Beispiel rendern wir eine DOCX-Datei zu PNG-Bildern. Sie können die Anwendung, die wir bauen werden, auch [hier](https://docs.groupdocs.com/viewer/python-net/_sample_files/getting-started/quick-start-guide/render_docx_to_png.zip) herunterladen.

{{< tabs "demo_app_render_docx_to_png">}}
{{< tab "render_docx_to_png.py" >}}
```python
import os
from groupdocs.viewer import License, Viewer
from groupdocs.viewer.options import PngViewOptions

def render_docx_to_png():
    # Abrufen des absoluten Pfads der Lizenzdatei
    license_path = os.path.abspath("./GroupDocs.Viewer.lic")

    if os.path.exists(license_path):
        # Lizenz erstellen und den Pfad festlegen
        license = License()
        license.set_license(license_path)

    # DOCX-Datei laden
    with Viewer("./sample.docx") as viewer:
        # Ansichtsoptionen erstellen
        png_options = PngViewOptions("render_docx_to_png/output_{0}.png")

        # DOCX in PNG-Bilder rendern
        viewer.view(png_options)

if __name__ == "__main__":
    render_docx_to_png()
```
{{< /tab >}}
{{< tab \"sample.docx\" >}}

`sample.docx` ist die in diesem Beispiel verwendete Beispieldatei. Klicken Sie [hier](https://docs.groupdocs.com/viewer/python-net/_sample_files/getting-started/quick-start-guide/sample.docx) zum Herunterladen.

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

Ihr Ordnerbaum sollte einer ähnlichen Verzeichnisstruktur wie folgt aussehen:

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

Nach dem Ausführen der Anwendung können Sie die virtuelle Umgebung deaktivieren, indem Sie `deactivate` ausführen oder Ihre Shell schließen.

### Explanation
- `Viewer("./sample.docx")`: Initializes the viewer with the DOCX file.
- `PngViewOptions("render_docx_to_png/output_{0}.png")`: Specifies the output format as PNG images.
- `viewer.view(png_options)`: Renders each page of the DOCX file to PNG and saves them as `output_1.png`, `output_2.png`, etc.

## Next Steps

Nachdem Sie die Grundlagen abgeschlossen haben, erkunden Sie zusätzliche Ressourcen, um Ihre Nutzung zu verbessern:
- [Supported File Formats](): Review the full list of supported file types.
- [Licensing](): Check details on licensing and evaluation.
- [Technical Support](): Contact support for assistance if you encounter issues.
