---
title: "Guida rapida all'avvio"
linkTitle: "Quick Start Guide"
second_title: "Riferimenti API di GroupDocs.Viewer per Python via .NET"
description: "Configura un ambiente virtuale, installa groupdocs-viewer-net e esegui tre esempi minimi — DOCX → HTML, DOCX → PDF e DOCX → PNG per pagina — in meno di cinque minuti."
type: docs
url: /it/python-net/guides/quick-start-guide/
is_root: false
weight: 20
---


Questa guida fornisce una rapida panoramica su come configurare e iniziare a utilizzare GroupDocs.Viewer per Python tramite .NET. Questa libreria consente agli sviluppatori di renderizzare documenti in formati HTML, PDF, PNG e JPG con una configurazione minima.

## Prerequisites

Per procedere, assicurati di avere:

1. **Configured** ambiente come descritto nella sezione [System Requirements]().
2. **Optionally** puoi [Get a Temporary License](https://purchase.groupdocs.com/temporary-license/) per testare tutte le funzionalità del prodotto.

## Set Up Your Development Environment

Per le migliori pratiche, utilizza un ambiente virtuale per gestire le dipendenze nelle applicazioni Python. Scopri di più sull'ambiente virtuale nella documentazione [Create and Use Virtual Environments](https://packaging.python.org/en/latest/guides/installing-using-pip-and-virtual-environments/#create-and-use-virtual-environments).

### Create and Activate a Virtual Environment

Crea un ambiente virtuale:

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

Attiva un ambiente virtuale:

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

Dopo aver attivato l'ambiente virtuale, esegui il seguente comando nel terminale per installare l'ultima versione del pacchetto:

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

Assicurati che il pacchetto sia installato correttamente. Dovresti vedere il messaggio

```bash
Successfully installed groupdocs-viewer-net-*
```

## Example 1: Render document to HTML

Per testare rapidamente la libreria, renderizziamo un file DOCX in HTML. Puoi anche scaricare l'app che costruiremo [qui](https://docs.groupdocs.com/viewer/python-net/_sample_files/getting-started/quick-start-guide/render_docx_to_html.zip).

{{< tabs \"demo_app_render_docx_to_html\">}}
{{< tab \"render_docx_to_html.py\" >}}
```python
import os
from groupdocs.viewer import License, Viewer
from groupdocs.viewer.options import HtmlViewOptions

def render_docx_to_html():
    # Ottieni il percorso assoluto del file di licenza
    license_path = os.path.abspath("./GroupDocs.Viewer.lic")

    if os.path.exists(license_path):
        # Crea la licenza e imposta il percorso
        license = License()
        license.set_license(license_path)

    # Carica il file DOCX
    with Viewer("./sample.docx") as viewer:
        # Crea le opzioni di visualizzazione
        html_options = HtmlViewOptions.for_embedded_resources("render_docx_to_html/page_{0}.html")

        # Renderizza DOCX in HTML
        viewer.view(html_options)

if __name__ == "__main__":
    render_docx_to_html()
```
{{< /tab >}}
{{< tab \"sample.docx\" >}}

`sample.docx` è il file di esempio usato in questo esempio. Fai clic [qui](https://docs.groupdocs.com/viewer/python-net/_sample_files/getting-started/quick-start-guide/sample.docx) per scaricarlo.

{{< /tab >}}
{{< tab \"render-docx-to-html-outputs.zip\" >}}
```text
render_docx_to_html/page_1.html (317 KB)
render_docx_to_html/page_2.html (149 KB)
render_docx_to_html/page_3.html (113 KB)
```
[Download full output](https://docs.groupdocs.com/viewer/python-net/_output_files/getting-started/quick-start-guide/render_docx_to_html/render-docx-to-html-outputs.zip)
{{< /tab >}}
{{< /tabs >}}

L'albero delle cartelle dovrebbe apparire simile alla seguente struttura di directory:

```Directory
📂 demo-app
 ├──render_docx_to_html.py
 ├──sample.docx
 └──GroupDocs.Viewer.lic (Optionally)
```

### Run the App

{{< tabs \"run-the-app\">}}
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

Dopo aver eseguito l'app puoi disattivare l'ambiente virtuale eseguendo `deactivate` o chiudendo il tuo terminale.

### Explanation
- `Viewer("./sample.docx")`: Initializes the viewer with the DOCX file.
- `HtmlViewOptions.for_embedded_resources("render_docx_to_html/page_{0}.html")`: Specifies the output format as HTML with embedded resources.
- `viewer.view(html_options)`: Renders the DOCX file to HTML and saves it as `page_1.html`, `page_2.html`, etc.

## Example 2: Render document to PDF

In questo esempio renderizzeremo un file DOCX in PDF. Puoi scaricare l'app che costruiremo [qui](https://docs.groupdocs.com/viewer/python-net/_sample_files/getting-started/quick-start-guide/render_docx_to_pdf.zip).

{{< tabs \"demo_app_render_docx_to_pdf\">}}
{{< tab \"render_docx_to_pdf.py\" >}}
```python
import os
from groupdocs.viewer import License, Viewer
from groupdocs.viewer.options import PdfViewOptions

def render_docx_to_pdf():
    # Ottieni il percorso assoluto del file di licenza
    license_path = os.path.abspath("./GroupDocs.Viewer.lic")

    if os.path.exists(license_path):
        # Crea la licenza e imposta il percorso
        license = License()
        license.set_license(license_path)

    # Carica il file DOCX
    with Viewer("./sample.docx") as viewer:
        # Crea le opzioni di visualizzazione
        pdf_options = PdfViewOptions("render_docx_to_pdf/output.pdf")

        # Renderizza DOCX in PDF
        viewer.view(pdf_options)

if __name__ == "__main__":
    render_docx_to_pdf()
```
{{< /tab >}}
{{< tab \"sample.docx\" >}}

`sample.docx` è il file di esempio usato in questo esempio. Fai clic [qui](https://docs.groupdocs.com/viewer/python-net/_sample_files/getting-started/quick-start-guide/sample.docx) per scaricarlo.

{{< /tab >}}
{{< tab \"output.pdf\" >}}
```text
Binary file (PDF, 234 KB)
```
[Download full output](https://docs.groupdocs.com/viewer/python-net/_output_files/getting-started/quick-start-guide/render_docx_to_pdf/output.pdf)
{{< /tab >}}
{{< /tabs >}}

L'albero delle cartelle dovrebbe apparire simile alla seguente struttura di directory:

```Directory
📂 demo-app
 ├──sample.docx
 ├──render_docx_to_pdf.py
 └──GroupDocs.Viewer.lic (Optionally)
```

### Run the App

{{< tabs \"run_the_app_render_docx_to_pdf\">}}
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

Dopo aver eseguito l'app puoi disattivare l'ambiente virtuale eseguendo `deactivate` o chiudendo il tuo terminale.

### Explanation
- `Viewer("./sample.docx")`: Initializes the viewer with the DOCX file.
- `PdfViewOptions("output.pdf")`: Specifies the output format as PDF.
- `viewer.view(pdf_options)`: Renders the DOCX file to PDF and saves it as `output.pdf`.

## Example 3: Render document to PNG images

In questo esempio renderizzeremo un file DOCX in immagini PNG. Puoi scaricare l'app che costruiremo [qui](https://docs.groupdocs.com/viewer/python-net/_sample_files/getting-started/quick-start-guide/render_docx_to_png.zip).

{{< tabs \"demo_app_render_docx_to_png\">}}
{{< tab \"render_docx_to_png.py\" >}}
```python
import os
from groupdocs.viewer import License, Viewer
from groupdocs.viewer.options import PngViewOptions

def render_docx_to_png():
    # Ottieni il percorso assoluto del file di licenza
    license_path = os.path.abspath("./GroupDocs.Viewer.lic")

    if os.path.exists(license_path):
        # Crea la licenza e imposta il percorso
        license = License()
        license.set_license(license_path)

    # Carica il file DOCX
    with Viewer("./sample.docx") as viewer:
        # Crea le opzioni di visualizzazione
        png_options = PngViewOptions("render_docx_to_png/output_{0}.png")

        # Renderizza DOCX in immagini PNG
        viewer.view(png_options)

if __name__ == "__main__":
    render_docx_to_png()
```
{{< /tab >}}
{{< tab \"sample.docx\" >}}

`sample.docx` è il file di esempio usato in questo esempio. Fai clic [qui](https://docs.groupdocs.com/viewer/python-net/_sample_files/getting-started/quick-start-guide/sample.docx) per scaricarlo.

{{< /tab >}}
{{< tab \"render-docx-to-png-outputs.zip\" >}}
```text
render_docx_to_png/output_1.png (89 KB)
render_docx_to_png/output_2.png (77 KB)
render_docx_to_png/output_3.png (50 KB)
```
[Download full output](https://docs.groupdocs.com/viewer/python-net/_output_files/getting-started/quick-start-guide/render_docx_to_png/render-docx-to-png-outputs.zip)
{{< /tab >}}
{{< /tabs >}}

L'albero delle cartelle dovrebbe apparire simile alla seguente struttura di directory:

```Directory
📂 demo-app
 ├──sample.docx
 ├──render_docx_to_png.py
 └──GroupDocs.Viewer.lic (Optionally)
```

### Run the App

{{< tabs \"run_the_app_render_docx_to_png\">}}
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

Dopo aver eseguito l'app puoi disattivare l'ambiente virtuale eseguendo `deactivate` o chiudendo il tuo terminale.

### Explanation
- `Viewer("./sample.docx")`: Initializes the viewer with the DOCX file.
- `PngViewOptions("render_docx_to_png/output_{0}.png")`: Specifies the output format as PNG images.
- `viewer.view(png_options)`: Renders each page of the DOCX file to PNG and saves them as `output_1.png`, `output_2.png`, etc.

## Next Steps

Dopo aver completato le basi, esplora risorse aggiuntive per migliorare l'uso:
- [Supported File Formats](): Review the full list of supported file types.
- [Licensing](): Check details on licensing and evaluation.
- [Technical Support](): Contact support for assistance if you encounter issues.
