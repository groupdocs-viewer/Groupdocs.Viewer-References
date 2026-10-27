---
title: "Guide de démarrage rapide"
linkTitle: "Quick Start Guide"
second_title: "Références API de GroupDocs.Viewer pour Python via .NET"
description: "Configurez un environnement virtuel, installez groupdocs-viewer-net et exécutez trois exemples minimalistes — DOCX → HTML, DOCX → PDF et DOCX → PNG par page — en moins de cinq minutes."
type: docs
url: /fr/python-net/guides/quick-start-guide/
is_root: false
weight: 20
---


Ce guide fournit un aperçu rapide de la façon de configurer et de commencer à utiliser GroupDocs.Viewer pour Python via .NET. Cette bibliothèque permet aux développeurs de rendre les documents aux formats HTML, PDF, PNG et JPG avec une configuration minimale.

## Prerequisites

Pour continuer, assurez‑vous que vous avez :

1. **configuré** environnement comme décrit dans le sujet [System Requirements]() .
2. **Optionnellement** vous pouvez [Obtenir une licence temporaire](https://purchase.groupdocs.com/temporary-license/) pour tester toutes les fonctionnalités du produit.

## Set Up Your Development Environment

Pour les meilleures pratiques, utilisez un environnement virtuel pour gérer les dépendances dans les applications Python. En savoir plus sur les environnements virtuels dans le sujet de documentation [Créer et utiliser des environnements virtuels](https://packaging.python.org/en/latest/guides/installing-using-pip-and-virtual-environments/#create-and-use-virtual-environments).

### Create and Activate a Virtual Environment

Créez un environnement virtuel :

{{< tabs \"example1\">}}
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

Activez un environnement virtuel :

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

Après avoir activé l'environnement virtuel, exécutez la commande suivante dans votre terminal pour installer la dernière version du paquet :

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

Assurez‑vous que le paquet est installé avec succès. Vous devriez voir le message

```bash
Successfully installed groupdocs-viewer-net-*
```

## Example 1: Render document to HTML

Pour tester rapidement la bibliothèque, rendons un fichier DOCX en HTML. Vous pouvez également télécharger l'application que nous allons créer [ici](https://docs.groupdocs.com/viewer/python-net/_sample_files/getting-started/quick-start-guide/render_docx_to_html.zip).

{{< tabs "demo_app_render_docx_to_html">}}
{{< tab "render_docx_to_html.py" >}}
```python
import os
from groupdocs.viewer import License, Viewer
from groupdocs.viewer.options import HtmlViewOptions

def render_docx_to_html():
    # Obtenez le chemin absolu du fichier de licence
    license_path = os.path.abspath("./GroupDocs.Viewer.lic")

    if os.path.exists(license_path):
        # Créez la licence et définissez le chemin
        license = License()
        license.set_license(license_path)

    # Chargez le fichier DOCX
    with Viewer("./sample.docx") as viewer:
        # Créez les options d'affichage
        html_options = HtmlViewOptions.for_embedded_resources("render_docx_to_html/page_{0}.html")

        # Rendu du DOCX en HTML
        viewer.view(html_options)

if __name__ == "__main__":
    render_docx_to_html()
```
{{< /tab >}}
{{< tab \"sample.docx\" >}}

`sample.docx` est le fichier d'exemple utilisé dans cet exemple. Cliquez [ici](https://docs.groupdocs.com/viewer/python-net/_sample_files/getting-started/quick-start-guide/sample.docx) pour le télécharger.

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

Votre arborescence de dossiers devrait ressembler à la structure de répertoires suivante :

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

Après avoir exécuté l'application, vous pouvez désactiver l'environnement virtuel en exécutant `deactivate` ou en fermant votre terminal.

### Explanation
- `Viewer("./sample.docx")`: Initializes the viewer with the DOCX file.
- `HtmlViewOptions.for_embedded_resources("render_docx_to_html/page_{0}.html")`: Specifies the output format as HTML with embedded resources.
- `viewer.view(html_options)`: Renders the DOCX file to HTML and saves it as `page_1.html`, `page_2.html`, etc.

## Example 2: Render document to PDF

Dans cet exemple, nous allons rendre un fichier DOCX en PDF. Vous pouvez télécharger l'application que nous allons créer [ici](https://docs.groupdocs.com/viewer/python-net/_sample_files/getting-started/quick-start-guide/render_docx_to_pdf.zip).

{{< tabs "demo_app_render_docx_to_pdf">}}
{{< tab "render_docx_to_pdf.py" >}}
```python
import os
from groupdocs.viewer import License, Viewer
from groupdocs.viewer.options import PdfViewOptions

def render_docx_to_pdf():
    # Obtenez le chemin absolu du fichier de licence
    license_path = os.path.abspath("./GroupDocs.Viewer.lic")

    if os.path.exists(license_path):
        # Créez la licence et définissez le chemin
        license = License()
        license.set_license(license_path)

    # Chargez le fichier DOCX
    with Viewer("./sample.docx") as viewer:
        # Créez les options d'affichage
        pdf_options = PdfViewOptions("render_docx_to_pdf/output.pdf")

        # Rendre le DOCX en PDF
        viewer.view(pdf_options)

if __name__ == "__main__":
    render_docx_to_pdf()
```
{{< /tab >}}
{{< tab \"sample.docx\" >}}

`sample.docx` est le fichier d'exemple utilisé dans cet exemple. Cliquez [ici](https://docs.groupdocs.com/viewer/python-net/_sample_files/getting-started/quick-start-guide/sample.docx) pour le télécharger.

{{< /tab >}}
{{< tab "output.pdf" >}}
```text
Binary file (PDF, 234 KB)
```
[Download full output](https://docs.groupdocs.com/viewer/python-net/_output_files/getting-started/quick-start-guide/render_docx_to_pdf/output.pdf)
{{< /tab >}}
{{< /tabs >}}

Votre arborescence de dossiers devrait ressembler à la structure de répertoires suivante :

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

Après avoir exécuté l'application, vous pouvez désactiver l'environnement virtuel en exécutant `deactivate` ou en fermant votre terminal.

### Explanation
- `Viewer("./sample.docx")`: Initializes the viewer with the DOCX file.
- `PdfViewOptions("output.pdf")`: Specifies the output format as PDF.
- `viewer.view(pdf_options)`: Renders the DOCX file to PDF and saves it as `output.pdf`.

## Example 3: Render document to PNG images

Dans cet exemple, nous allons rendre un fichier DOCX en images PNG. Vous pouvez télécharger l'application que nous allons créer [ici](https://docs.groupdocs.com/viewer/python-net/_sample_files/getting-started/quick-start-guide/render_docx_to_png.zip).

{{< tabs "demo_app_render_docx_to_png">}}
{{< tab "render_docx_to_png.py" >}}
```python
import os
from groupdocs.viewer import License, Viewer
from groupdocs.viewer.options import PngViewOptions

def render_docx_to_png():
    # Obtenez le chemin absolu du fichier de licence
    license_path = os.path.abspath("./GroupDocs.Viewer.lic")

    if os.path.exists(license_path):
        # Créez la licence et définissez le chemin
        license = License()
        license.set_license(license_path)

    # Chargez le fichier DOCX
    with Viewer("./sample.docx") as viewer:
        # Créez les options d'affichage
        png_options = PngViewOptions("render_docx_to_png/output_{0}.png")

        # Rendre le DOCX en images PNG
        viewer.view(png_options)

if __name__ == "__main__":
    render_docx_to_png()
```
{{< /tab >}}
{{< tab \"sample.docx\" >}}

`sample.docx` est le fichier d'exemple utilisé dans cet exemple. Cliquez [ici](https://docs.groupdocs.com/viewer/python-net/_sample_files/getting-started/quick-start-guide/sample.docx) pour le télécharger.

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

Votre arborescence de dossiers devrait ressembler à la structure de répertoires suivante :

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

Après avoir exécuté l'application, vous pouvez désactiver l'environnement virtuel en exécutant `deactivate` ou en fermant votre terminal.

### Explanation
- `Viewer("./sample.docx")`: Initializes the viewer with the DOCX file.
- `PngViewOptions("render_docx_to_png/output_{0}.png")`: Specifies the output format as PNG images.
- `viewer.view(png_options)`: Renders each page of the DOCX file to PNG and saves them as `output_1.png`, `output_2.png`, etc.

## Next Steps

Après avoir terminé les bases, explorez des ressources supplémentaires pour améliorer votre utilisation :
- [Supported File Formats](): Review the full list of supported file types.
- [Licensing](): Check details on licensing and evaluation.
- [Technical Support](): Contact support for assistance if you encounter issues.
