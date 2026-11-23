---
title: "빠른 시작 가이드"
linkTitle: "Quick Start Guide"
second_title: "GroupDocs.Viewer 용 Python via .NET API 참조"
description: "가상 환경을 설정하고, groupdocs-viewer-net을 설치한 뒤, 세 가지 최소 예제 — DOCX → HTML, DOCX → PDF, DOCX → 페이지당 PNG — 를 5분 이내에 실행합니다."
type: docs
url: /ko/python-net/guides/quick-start-guide/
is_root: false
weight: 20
---


이 가이드는 .NET을 통해 Python용 GroupDocs.Viewer를 설정하고 사용을 시작하는 방법에 대한 간략한 개요를 제공합니다. 이 라이브러리를 사용하면 개발자가 최소한의 구성으로 문서를 HTML, PDF, PNG 및 JPG 형식으로 렌더링할 수 있습니다.

## Prerequisites

진행하려면 다음이 준비되어 있는지 확인하십시오:

1. [System Requirements]() 항목에 설명된 대로 **Configured** 환경
2. **Optionally** 모든 제품 기능을 테스트하려면 [Get a Temporary License](https://purchase.groupdocs.com/temporary-license/)를 받을 수 있습니다.

## Set Up Your Development Environment

최선의 방법을 위해 Python 애플리케이션에서 종속성을 관리하려면 가상 환경을 사용하십시오. 가상 환경에 대해 자세히 알아보려면 [Create and Use Virtual Environments](https://packaging.python.org/en/latest/guides/installing-using-pip-and-virtual-environments/#create-and-use-virtual-environments) 문서 항목을 참고하십시오.

### Create and Activate a Virtual Environment

가상 환경을 생성하십시오:

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

가상 환경을 활성화하십시오:

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

가상 환경을 활성화한 후, 터미널에서 다음 명령을 실행하여 패키지의 최신 버전을 설치하십시오:

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

패키지가 성공적으로 설치되었는지 확인하십시오. 메시지가 표시될 것입니다.

```bash
Successfully installed groupdocs-viewer-net-*
```

## Example 1: Render document to HTML

라이브러리를 빠르게 테스트하려면 DOCX 파일을 HTML로 렌더링해 보겠습니다. 또한 우리가 만들 앱을 [여기](https://docs.groupdocs.com/viewer/python-net/_sample_files/getting-started/quick-start-guide/render_docx_to_html.zip)에서 다운로드할 수 있습니다.

{{< tabs "demo_app_render_docx_to_html">}}
{{< tab "render_docx_to_html.py" >}}
```python
import os
from groupdocs.viewer import License, Viewer
from groupdocs.viewer.options import HtmlViewOptions

def render_docx_to_html():
    # 라이선스 파일 절대 경로 가져오기
    license_path = os.path.abspath("./GroupDocs.Viewer.lic")

    if os.path.exists(license_path):
        # 라이선스를 생성하고 경로를 설정하십시오
        license = License()
        license.set_license(license_path)

    # DOCX 파일 로드
    with Viewer("./sample.docx") as viewer:
        # 뷰 옵션 생성
        html_options = HtmlViewOptions.for_embedded_resources("render_docx_to_html/page_{0}.html")

        # DOCX를 HTML로 렌더링합니다.
        viewer.view(html_options)

if __name__ == "__main__":
    render_docx_to_html()
```
{{< /tab >}}
{{< tab \"sample.docx\" >}}

`sample.docx`는 이 예제에서 사용되는 샘플 파일입니다. 다운로드하려면 [여기](https://docs.groupdocs.com/viewer/python-net/_sample_files/getting-started/quick-start-guide/sample.docx)를 클릭하십시오.

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

폴더 트리는 다음 디렉터리 구조와 유사하게 표시됩니다:

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

앱을 실행한 후 `deactivate`를 실행하거나 셸을 닫아 가상 환경을 비활성화할 수 있습니다.

### Explanation
- `Viewer("./sample.docx")`: Initializes the viewer with the DOCX file.
- `HtmlViewOptions.for_embedded_resources("render_docx_to_html/page_{0}.html")`: Specifies the output format as HTML with embedded resources.
- `viewer.view(html_options)`: Renders the DOCX file to HTML and saves it as `page_1.html`, `page_2.html`, etc.

## Example 2: Render document to PDF

이 예제에서는 DOCX 파일을 PDF로 렌더링합니다. 우리가 만들 앱을 [여기](https://docs.groupdocs.com/viewer/python-net/_sample_files/getting-started/quick-start-guide/render_docx_to_pdf.zip)에서 다운로드할 수 있습니다.

{{< tabs "demo_app_render_docx_to_pdf">}}
{{< tab "render_docx_to_pdf.py" >}}
```python
import os
from groupdocs.viewer import License, Viewer
from groupdocs.viewer.options import PdfViewOptions

def render_docx_to_pdf():
    # 라이선스 파일 절대 경로 가져오기
    license_path = os.path.abspath("./GroupDocs.Viewer.lic")

    if os.path.exists(license_path):
        # 라이선스를 생성하고 경로를 설정하십시오
        license = License()
        license.set_license(license_path)

    # DOCX 파일 로드
    with Viewer("./sample.docx") as viewer:
        # 뷰 옵션 생성
        pdf_options = PdfViewOptions("render_docx_to_pdf/output.pdf")

        # DOCX를 PDF로 렌더링
        viewer.view(pdf_options)

if __name__ == "__main__":
    render_docx_to_pdf()
```
{{< /tab >}}
{{< tab \"sample.docx\" >}}

`sample.docx`는 이 예제에서 사용되는 샘플 파일입니다. 다운로드하려면 [여기](https://docs.groupdocs.com/viewer/python-net/_sample_files/getting-started/quick-start-guide/sample.docx)를 클릭하십시오.

{{< /tab >}}
{{< tab "output.pdf" >}}
```text
Binary file (PDF, 234 KB)
```
[Download full output](https://docs.groupdocs.com/viewer/python-net/_output_files/getting-started/quick-start-guide/render_docx_to_pdf/output.pdf)
{{< /tab >}}
{{< /tabs >}}

폴더 트리는 다음 디렉터리 구조와 유사하게 표시됩니다:

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

앱을 실행한 후 `deactivate`를 실행하거나 셸을 닫아 가상 환경을 비활성화할 수 있습니다.

### Explanation
- `Viewer("./sample.docx")`: Initializes the viewer with the DOCX file.
- `PdfViewOptions("output.pdf")`: Specifies the output format as PDF.
- `viewer.view(pdf_options)`: Renders the DOCX file to PDF and saves it as `output.pdf`.

## Example 3: Render document to PNG images

이 예제에서는 DOCX 파일을 PNG 이미지로 렌더링합니다. 우리가 만들 앱을 [여기](https://docs.groupdocs.com/viewer/python-net/_sample_files/getting-started/quick-start-guide/render_docx_to_png.zip)에서 다운로드할 수 있습니다.

{{< tabs "demo_app_render_docx_to_png">}}
{{< tab "render_docx_to_png.py" >}}
```python
import os
from groupdocs.viewer import License, Viewer
from groupdocs.viewer.options import PngViewOptions

def render_docx_to_png():
    # 라이선스 파일 절대 경로 가져오기
    license_path = os.path.abspath("./GroupDocs.Viewer.lic")

    if os.path.exists(license_path):
        # 라이선스를 생성하고 경로를 설정하십시오
        license = License()
        license.set_license(license_path)

    # DOCX 파일 로드
    with Viewer("./sample.docx") as viewer:
        # 뷰 옵션 생성
        png_options = PngViewOptions("render_docx_to_png/output_{0}.png")

        # DOCX를 PNG 이미지로 렌더링
        viewer.view(png_options)

if __name__ == "__main__":
    render_docx_to_png()
```
{{< /tab >}}
{{< tab \"sample.docx\" >}}

`sample.docx`는 이 예제에서 사용되는 샘플 파일입니다. 다운로드하려면 [여기](https://docs.groupdocs.com/viewer/python-net/_sample_files/getting-started/quick-start-guide/sample.docx)를 클릭하십시오.

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

폴더 트리는 다음 디렉터리 구조와 유사하게 표시됩니다:

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

앱을 실행한 후 `deactivate`를 실행하거나 셸을 닫아 가상 환경을 비활성화할 수 있습니다.

### Explanation
- `Viewer("./sample.docx")`: Initializes the viewer with the DOCX file.
- `PngViewOptions("render_docx_to_png/output_{0}.png")`: Specifies the output format as PNG images.
- `viewer.view(png_options)`: Renders each page of the DOCX file to PNG and saves them as `output_1.png`, `output_2.png`, etc.

## Next Steps

기본을 완료한 후, 사용을 향상시키기 위해 추가 리소스를 탐색하십시오:
- [Supported File Formats](): Review the full list of supported file types.
- [Licensing](): Check details on licensing and evaluation.
- [Technical Support](): Contact support for assistance if you encounter issues.
