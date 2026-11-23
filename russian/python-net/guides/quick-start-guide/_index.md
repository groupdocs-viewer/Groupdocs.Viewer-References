---
title: "Руководство быстрого старта"
linkTitle: "Quick Start Guide"
second_title: "Справочник API GroupDocs.Viewer для Python через .NET"
description: "Создайте виртуальное окружение, установите groupdocs-viewer-net и запустите три минимальных примера — DOCX → HTML, DOCX → PDF и DOCX → PNG по страницам — менее чем за пять минут."
type: docs
url: /ru/python-net/guides/quick-start-guide/
is_root: false
weight: 20
---


Это руководство дает краткий обзор того, как настроить и начать использовать GroupDocs.Viewer для Python через .NET. Эта библиотека позволяет разработчикам преобразовывать документы в форматы HTML, PDF, PNG и JPG с минимальной конфигурацией.

## Prerequisites

Чтобы продолжить, убедитесь, что у вас есть:

1. **Configured** среда, как описано в теме [System Requirements]().
2. **Optionally** вы можете [Получить временную лицензию](https://purchase.groupdocs.com/temporary-license/), чтобы протестировать все функции продукта.

## Set Up Your Development Environment

Для лучших практик используйте виртуальное окружение для управления зависимостями в приложениях Python. Узнайте больше о виртуальном окружении в теме документации [Создание и использование виртуальных окружений](https://packaging.python.org/en/latest/guides/installing-using-pip-and-virtual-environments/#create-and-use-virtual-environments).

### Create and Activate a Virtual Environment

Создайте виртуальное окружение:

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

Активируйте виртуальное окружение:

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

После активации виртуального окружения выполните следующую команду в терминале, чтобы установить последнюю версию пакета:

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

Убедитесь, что пакет установлен успешно. Вы должны увидеть сообщение

```bash
Successfully installed groupdocs-viewer-net-*
```

## Example 1: Render document to HTML

Чтобы быстро протестировать библиотеку, давайте преобразуем файл DOCX в HTML. Вы также можете скачать приложение, которое мы собираемся собрать, [здесь](https://docs.groupdocs.com/viewer/python-net/_sample_files/getting-started/quick-start-guide/render_docx_to_html.zip).

{{< tabs "demo_app_render_docx_to_html">}}
{{< tab "render_docx_to_html.py" >}}
```python
import os
from groupdocs.viewer import License, Viewer
from groupdocs.viewer.options import HtmlViewOptions

def render_docx_to_html():
    # Получить абсолютный путь к файлу лицензии
    license_path = os.path.abspath("./GroupDocs.Viewer.lic")

    if os.path.exists(license_path):
        # Создать лицензию и установить путь
        license = License()
        license.set_license(license_path)

    # Загрузить файл DOCX
    with Viewer("./sample.docx") as viewer:
        # Создать параметры просмотра
        html_options = HtmlViewOptions.for_embedded_resources("render_docx_to_html/page_{0}.html")

        # Преобразовать DOCX в HTML
        viewer.view(html_options)

if __name__ == "__main__":
    render_docx_to_html()
```
{{< /tab >}}
{{< tab \"sample.docx\" >}}

`sample.docx` является примером файла, используемого в этом примере. Нажмите [здесь](https://docs.groupdocs.com/viewer/python-net/_sample_files/getting-started/quick-start-guide/sample.docx), чтобы скачать его.

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

Ваша структура папок должна выглядеть примерно так, как показано ниже:

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

После запуска приложения вы можете деактивировать виртуальное окружение, выполнив `deactivate`, или закрыв оболочку.

### Explanation
- `Viewer("./sample.docx")`: Initializes the viewer with the DOCX file.
- `HtmlViewOptions.for_embedded_resources("render_docx_to_html/page_{0}.html")`: Specifies the output format as HTML with embedded resources.
- `viewer.view(html_options)`: Renders the DOCX file to HTML and saves it as `page_1.html`, `page_2.html`, etc.

## Example 2: Render document to PDF

В этом примере мы преобразуем файл DOCX в PDF. Вы можете скачать приложение, которое мы собираемся собрать, [здесь](https://docs.groupdocs.com/viewer/python-net/_sample_files/getting-started/quick-start-guide/render_docx_to_pdf.zip).

{{< tabs "demo_app_render_docx_to_pdf">}}
{{< tab "render_docx_to_pdf.py" >}}
```python
import os
from groupdocs.viewer import License, Viewer
from groupdocs.viewer.options import PdfViewOptions

def render_docx_to_pdf():
    # Получить абсолютный путь к файлу лицензии
    license_path = os.path.abspath("./GroupDocs.Viewer.lic")

    if os.path.exists(license_path):
        # Создать лицензию и установить путь
        license = License()
        license.set_license(license_path)

    # Загрузить файл DOCX
    with Viewer("./sample.docx") as viewer:
        # Создать параметры просмотра
        pdf_options = PdfViewOptions("render_docx_to_pdf/output.pdf")

        # Преобразовать DOCX в PDF
        viewer.view(pdf_options)

if __name__ == "__main__":
    render_docx_to_pdf()
```
{{< /tab >}}
{{< tab \"sample.docx\" >}}

`sample.docx` является примером файла, используемого в этом примере. Нажмите [здесь](https://docs.groupdocs.com/viewer/python-net/_sample_files/getting-started/quick-start-guide/sample.docx), чтобы скачать его.

{{< /tab >}}
{{< tab "output.pdf" >}}
```text
Binary file (PDF, 234 KB)
```
[Download full output](https://docs.groupdocs.com/viewer/python-net/_output_files/getting-started/quick-start-guide/render_docx_to_pdf/output.pdf)
{{< /tab >}}
{{< /tabs >}}

Ваша структура папок должна выглядеть примерно так, как показано ниже:

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

После запуска приложения вы можете деактивировать виртуальное окружение, выполнив `deactivate`, или закрыв оболочку.

### Explanation
- `Viewer("./sample.docx")`: Initializes the viewer with the DOCX file.
- `PdfViewOptions("output.pdf")`: Specifies the output format as PDF.
- `viewer.view(pdf_options)`: Renders the DOCX file to PDF and saves it as `output.pdf`.

## Example 3: Render document to PNG images

В этом примере мы преобразуем файл DOCX в изображения PNG. Вы можете скачать приложение, которое мы собираемся собрать, [здесь](https://docs.groupdocs.com/viewer/python-net/_sample_files/getting-started/quick-start-guide/render_docx_to_png.zip).

{{< tabs "demo_app_render_docx_to_png">}}
{{< tab "render_docx_to_png.py" >}}
```python
import os
from groupdocs.viewer import License, Viewer
from groupdocs.viewer.options import PngViewOptions

def render_docx_to_png():
    # Получить абсолютный путь к файлу лицензии
    license_path = os.path.abspath("./GroupDocs.Viewer.lic")

    if os.path.exists(license_path):
        # Создать лицензию и установить путь
        license = License()
        license.set_license(license_path)

    # Загрузить файл DOCX
    with Viewer("./sample.docx") as viewer:
        # Создать параметры просмотра
        png_options = PngViewOptions("render_docx_to_png/output_{0}.png")

        # Преобразовать DOCX в изображения PNG
        viewer.view(png_options)

if __name__ == "__main__":
    render_docx_to_png()
```
{{< /tab >}}
{{< tab \"sample.docx\" >}}

`sample.docx` является примером файла, используемого в этом примере. Нажмите [здесь](https://docs.groupdocs.com/viewer/python-net/_sample_files/getting-started/quick-start-guide/sample.docx), чтобы скачать его.

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

Ваша структура папок должна выглядеть примерно так, как показано ниже:

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

После запуска приложения вы можете деактивировать виртуальное окружение, выполнив `deactivate`, или закрыв оболочку.

### Explanation
- `Viewer("./sample.docx")`: Initializes the viewer with the DOCX file.
- `PngViewOptions("render_docx_to_png/output_{0}.png")`: Specifies the output format as PNG images.
- `viewer.view(png_options)`: Renders each page of the DOCX file to PNG and saves them as `output_1.png`, `output_2.png`, etc.

## Next Steps

После освоения базовых навыков изучите дополнительные ресурсы, чтобы расширить возможности использования:
- [Supported File Formats](): Review the full list of supported file types.
- [Licensing](): Check details on licensing and evaluation.
- [Technical Support](): Contact support for assistance if you encounter issues.
