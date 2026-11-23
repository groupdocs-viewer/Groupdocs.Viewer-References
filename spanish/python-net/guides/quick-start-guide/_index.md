---
title: "Guía de inicio rápido"
linkTitle: "Quick Start Guide"
second_title: "Referencias de API de GroupDocs.Viewer para Python vía .NET"
description: "Configure un entorno virtual, instale groupdocs-viewer-net y ejecute tres ejemplos mínimos — DOCX → HTML, DOCX → PDF y DOCX → PNG por página — en menos de cinco minutos."
type: docs
url: /es/python-net/guides/quick-start-guide/
is_root: false
weight: 20
---


Esta guía ofrece una visión rápida de cómo configurar y comenzar a usar GroupDocs.Viewer para Python a través de .NET. Esta biblioteca permite a los desarrolladores renderizar documentos a formatos HTML, PDF, PNG y JPG con una configuración mínima.

## Prerequisites

Para continuar, asegúrese de que tiene:

1. Entorno **Configurado** según lo descrito en el tema [System Requirements]().
2. **Opcionalmente**, puede [Obtener una licencia temporal](https://purchase.groupdocs.com/temporary-license/) para probar todas las funciones del producto.

## Set Up Your Development Environment

Para seguir las mejores prácticas, use un entorno virtual para gestionar dependencias en aplicaciones Python. Obtenga más información sobre entornos virtuales en el tema de documentación [Create and Use Virtual Environments](https://packaging.python.org/en/latest/guides/installing-using-pip-and-virtual-environments/#create-and-use-virtual-environments).

### Create and Activate a Virtual Environment

Cree un entorno virtual:

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

Active un entorno virtual:

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

Después de activar el entorno virtual, ejecute el siguiente comando en su terminal para instalar la última versión del paquete:

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

Asegúrese de que el paquete se haya instalado correctamente. Debería ver el mensaje

```bash
Successfully installed groupdocs-viewer-net-*
```

## Example 1: Render document to HTML

Para probar rápidamente la biblioteca, rendericemos un archivo DOCX a HTML. También puede descargar la aplicación que vamos a crear [aquí](https://docs.groupdocs.com/viewer/python-net/_sample_files/getting-started/quick-start-guide/render_docx_to_html.zip).

{{< tabs "demo_app_render_docx_to_html">}}
{{< tab "render_docx_to_html.py" >}}
```python
import os
from groupdocs.viewer import License, Viewer
from groupdocs.viewer.options import HtmlViewOptions

def render_docx_to_html():
    # Obtener la ruta absoluta del archivo de licencia
    license_path = os.path.abspath("./GroupDocs.Viewer.lic")

    if os.path.exists(license_path):
        # Crear la licencia y establecer la ruta
        license = License()
        license.set_license(license_path)

    # Cargar el archivo DOCX
    with Viewer("./sample.docx") as viewer:
        # Crear opciones de vista
        html_options = HtmlViewOptions.for_embedded_resources("render_docx_to_html/page_{0}.html")

        # Renderiza DOCX a HTML
        viewer.view(html_options)

if __name__ == "__main__":
    render_docx_to_html()
```
{{< /tab >}}
{{< tab \"sample.docx\" >}}

`sample.docx` es el archivo de ejemplo usado en este ejemplo. Haga clic [aquí](https://docs.groupdocs.com/viewer/python-net/_sample_files/getting-started/quick-start-guide/sample.docx) para descargarlo.

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

Su árbol de carpetas debería verse similar a la siguiente estructura de directorios:

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

Después de ejecutar la aplicación, puede desactivar el entorno virtual ejecutando `deactivate` o cerrando su terminal.

### Explanation
- `Viewer("./sample.docx")`: Initializes the viewer with the DOCX file.
- `HtmlViewOptions.for_embedded_resources("render_docx_to_html/page_{0}.html")`: Specifies the output format as HTML with embedded resources.
- `viewer.view(html_options)`: Renders the DOCX file to HTML and saves it as `page_1.html`, `page_2.html`, etc.

## Example 2: Render document to PDF

En este ejemplo renderizaremos un archivo DOCX a PDF. Puede descargar la aplicación que vamos a crear [aquí](https://docs.groupdocs.com/viewer/python-net/_sample_files/getting-started/quick-start-guide/render_docx_to_pdf.zip).

{{< tabs "demo_app_render_docx_to_pdf">}}
{{< tab "render_docx_to_pdf.py" >}}
```python
import os
from groupdocs.viewer import License, Viewer
from groupdocs.viewer.options import PdfViewOptions

def render_docx_to_pdf():
    # Obtener la ruta absoluta del archivo de licencia
    license_path = os.path.abspath("./GroupDocs.Viewer.lic")

    if os.path.exists(license_path):
        # Crear la licencia y establecer la ruta
        license = License()
        license.set_license(license_path)

    # Cargar el archivo DOCX
    with Viewer("./sample.docx") as viewer:
        # Crear opciones de vista
        pdf_options = PdfViewOptions("render_docx_to_pdf/output.pdf")

        # Renderizar DOCX a PDF
        viewer.view(pdf_options)

if __name__ == "__main__":
    render_docx_to_pdf()
```
{{< /tab >}}
{{< tab \"sample.docx\" >}}

`sample.docx` es el archivo de ejemplo usado en este ejemplo. Haga clic [aquí](https://docs.groupdocs.com/viewer/python-net/_sample_files/getting-started/quick-start-guide/sample.docx) para descargarlo.

{{< /tab >}}
{{< tab "output.pdf" >}}
```text
Binary file (PDF, 234 KB)
```
[Download full output](https://docs.groupdocs.com/viewer/python-net/_output_files/getting-started/quick-start-guide/render_docx_to_pdf/output.pdf)
{{< /tab >}}
{{< /tabs >}}

Su árbol de carpetas debería verse similar a la siguiente estructura de directorios:

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

Después de ejecutar la aplicación, puede desactivar el entorno virtual ejecutando `deactivate` o cerrando su terminal.

### Explanation
- `Viewer("./sample.docx")`: Initializes the viewer with the DOCX file.
- `PdfViewOptions("output.pdf")`: Specifies the output format as PDF.
- `viewer.view(pdf_options)`: Renders the DOCX file to PDF and saves it as `output.pdf`.

## Example 3: Render document to PNG images

En este ejemplo renderizaremos un archivo DOCX a imágenes PNG. Puede descargar la aplicación que vamos a crear [aquí](https://docs.groupdocs.com/viewer/python-net/_sample_files/getting-started/quick-start-guide/render_docx_to_png.zip).

{{< tabs "demo_app_render_docx_to_png">}}
{{< tab "render_docx_to_png.py" >}}
```python
import os
from groupdocs.viewer import License, Viewer
from groupdocs.viewer.options import PngViewOptions

def render_docx_to_png():
    # Obtener la ruta absoluta del archivo de licencia
    license_path = os.path.abspath("./GroupDocs.Viewer.lic")

    if os.path.exists(license_path):
        # Crear la licencia y establecer la ruta
        license = License()
        license.set_license(license_path)

    # Cargar el archivo DOCX
    with Viewer("./sample.docx") as viewer:
        # Crear opciones de vista
        png_options = PngViewOptions("render_docx_to_png/output_{0}.png")

        # Renderizar DOCX a imágenes PNG
        viewer.view(png_options)

if __name__ == "__main__":
    render_docx_to_png()
```
{{< /tab >}}
{{< tab \"sample.docx\" >}}

`sample.docx` es el archivo de ejemplo usado en este ejemplo. Haga clic [aquí](https://docs.groupdocs.com/viewer/python-net/_sample_files/getting-started/quick-start-guide/sample.docx) para descargarlo.

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

Su árbol de carpetas debería verse similar a la siguiente estructura de directorios:

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

Después de ejecutar la aplicación, puede desactivar el entorno virtual ejecutando `deactivate` o cerrando su terminal.

### Explanation
- `Viewer("./sample.docx")`: Initializes the viewer with the DOCX file.
- `PngViewOptions("render_docx_to_png/output_{0}.png")`: Specifies the output format as PNG images.
- `viewer.view(png_options)`: Renders each page of the DOCX file to PNG and saves them as `output_1.png`, `output_2.png`, etc.

## Next Steps

Después de completar lo básico, explore recursos adicionales para mejorar su uso:
- [Supported File Formats](): Review the full list of supported file types.
- [Licensing](): Check details on licensing and evaluation.
- [Technical Support](): Contact support for assistance if you encounter issues.
