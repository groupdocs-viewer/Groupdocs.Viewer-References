---
title: "دليل البدء السريع"
linkTitle: "Quick Start Guide"
second_title: "مراجع API لـ GroupDocs.Viewer لـ Python عبر .NET"
description: "قم بإعداد بيئة افتراضية، تثبيت groupdocs-viewer-net، وتشغيل ثلاثة أمثلة بسيطة — DOCX → HTML، DOCX → PDF، و DOCX → PNG لكل صفحة — في أقل من خمس دقائق."
type: docs
url: /ar/python-net/guides/quick-start-guide/
is_root: false
weight: 20
---


يوفر هذا الدليل نظرة سريعة حول كيفية إعداد والبدء في استخدام GroupDocs.Viewer للبايثون عبر .NET. تمكّن هذه المكتبة المطورين من تحويل المستندات إلى صيغ HTML، PDF، PNG، و JPG بأقل إعدادات.

## Prerequisites

للمتابعة، تأكد من أن لديك:

1. بيئة **مُكوَّنة** كما هو موضح في موضوع [System Requirements]().
2. **اختياريًا** يمكنك [احصل على ترخيص مؤقت](https://purchase.groupdocs.com/temporary-license/) لاختبار جميع ميزات المنتج.

## Set Up Your Development Environment

لأفضل الممارسات، استخدم بيئة افتراضية لإدارة الاعتماديات في تطبيقات بايثون. تعرف على المزيد حول البيئة الافتراضية في موضوع الوثائق [إنشاء واستخدام البيئات الافتراضية](https://packaging.python.org/en/latest/guides/installing-using-pip-and-virtual-environments/#create-and-use-virtual-environments).

### Create and Activate a Virtual Environment

إنشاء بيئة افتراضية:

{{< tabs "example1">}}
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

تفعيل بيئة افتراضية:

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

بعد تفعيل البيئة الافتراضية، نفّذ الأمر التالي في الطرفية لتثبيت أحدث نسخة من الحزمة:

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

تأكد من تثبيت الحزمة بنجاح. يجب أن ترى الرسالة

```bash
Successfully installed groupdocs-viewer-net-*
```

## Example 1: Render document to HTML

لاختبار المكتبة بسرعة، دعنا نحول ملف DOCX إلى HTML. يمكنك أيضًا تنزيل التطبيق الذي سنبنيه [هنا](https://docs.groupdocs.com/viewer/python-net/_sample_files/getting-started/quick-start-guide/render_docx_to_html.zip).

{{< tabs "demo_app_render_docx_to_html">}}
{{< tab "render_docx_to_html.py" >}}
```python
import os
from groupdocs.viewer import License, Viewer
from groupdocs.viewer.options import HtmlViewOptions

def render_docx_to_html():
    # احصل على المسار المطلق لملف الترخيص
    license_path = os.path.abspath("./GroupDocs.Viewer.lic")

    if os.path.exists(license_path):
        # إنشاء الترخيص وتعيين المسار
        license = License()
        license.set_license(license_path)

    # تحميل ملف DOCX
    with Viewer("./sample.docx") as viewer:
        # إنشاء خيارات العرض
        html_options = HtmlViewOptions.for_embedded_resources("render_docx_to_html/page_{0}.html")

        # تحويل DOCX إلى HTML
        viewer.view(html_options)

if __name__ == "__main__":
    render_docx_to_html()
```
{{< /tab >}}
{{< tab "sample.docx" >}}

`sample.docx` هو ملف العينة المستخدم في هذا المثال. انقر [هنا](https://docs.groupdocs.com/viewer/python-net/_sample_files/getting-started/quick-start-guide/sample.docx) لتنزيله.

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

يجب أن يبدو هيكل المجلدات الخاص بك مشابهًا للهيكل التالي:

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

بعد تشغيل التطبيق يمكنك إلغاء تنشيط البيئة الافتراضية بتنفيذ `deactivate` أو إغلاق الصدفة.

### Explanation
- `Viewer("./sample.docx")`: Initializes the viewer with the DOCX file.
- `HtmlViewOptions.for_embedded_resources("render_docx_to_html/page_{0}.html")`: Specifies the output format as HTML with embedded resources.
- `viewer.view(html_options)`: Renders the DOCX file to HTML and saves it as `page_1.html`, `page_2.html`, etc.

## Example 2: Render document to PDF

في هذا المثال سنقوم بتحويل ملف DOCX إلى PDF. يمكنك تنزيل التطبيق الذي سنبنيه [هنا](https://docs.groupdocs.com/viewer/python-net/_sample_files/getting-started/quick-start-guide/render_docx_to_pdf.zip).

{{< tabs "demo_app_render_docx_to_pdf">}}
{{< tab "render_docx_to_pdf.py" >}}
```python
import os
from groupdocs.viewer import License, Viewer
from groupdocs.viewer.options import PdfViewOptions

def render_docx_to_pdf():
    # احصل على المسار المطلق لملف الترخيص
    license_path = os.path.abspath("./GroupDocs.Viewer.lic")

    if os.path.exists(license_path):
        # إنشاء الترخيص وتعيين المسار
        license = License()
        license.set_license(license_path)

    # تحميل ملف DOCX
    with Viewer("./sample.docx") as viewer:
        # إنشاء خيارات العرض
        pdf_options = PdfViewOptions("render_docx_to_pdf/output.pdf")

        # تحويل DOCX إلى PDF
        viewer.view(pdf_options)

if __name__ == "__main__":
    render_docx_to_pdf()
```
{{< /tab >}}
{{< tab "sample.docx" >}}

`sample.docx` هو ملف العينة المستخدم في هذا المثال. انقر [هنا](https://docs.groupdocs.com/viewer/python-net/_sample_files/getting-started/quick-start-guide/sample.docx) لتنزيله.

{{< /tab >}}
{{< tab "output.pdf" >}}
```text
Binary file (PDF, 234 KB)
```
[Download full output](https://docs.groupdocs.com/viewer/python-net/_output_files/getting-started/quick-start-guide/render_docx_to_pdf/output.pdf)
{{< /tab >}}
{{< /tabs >}}

يجب أن يبدو هيكل المجلدات الخاص بك مشابهًا للهيكل التالي:

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

بعد تشغيل التطبيق يمكنك إلغاء تنشيط البيئة الافتراضية بتنفيذ `deactivate` أو إغلاق الصدفة.

### Explanation
- `Viewer("./sample.docx")`: Initializes the viewer with the DOCX file.
- `PdfViewOptions("output.pdf")`: Specifies the output format as PDF.
- `viewer.view(pdf_options)`: Renders the DOCX file to PDF and saves it as `output.pdf`.

## Example 3: Render document to PNG images

في هذا المثال سنقوم بتحويل ملف DOCX إلى صور PNG. يمكنك تنزيل التطبيق الذي سنبنيه [هنا](https://docs.groupdocs.com/viewer/python-net/_sample_files/getting-started/quick-start-guide/render_docx_to_png.zip).

{{< tabs "demo_app_render_docx_to_png">}}
{{< tab "render_docx_to_png.py" >}}
```python
import os
from groupdocs.viewer import License, Viewer
from groupdocs.viewer.options import PngViewOptions

def render_docx_to_png():
    # احصل على المسار المطلق لملف الترخيص
    license_path = os.path.abspath("./GroupDocs.Viewer.lic")

    if os.path.exists(license_path):
        # إنشاء الترخيص وتعيين المسار
        license = License()
        license.set_license(license_path)

    # تحميل ملف DOCX
    with Viewer("./sample.docx") as viewer:
        # إنشاء خيارات العرض
        png_options = PngViewOptions("render_docx_to_png/output_{0}.png")

        # تحويل DOCX إلى صور PNG
        viewer.view(png_options)

if __name__ == "__main__":
    render_docx_to_png()
```
{{< /tab >}}
{{< tab "sample.docx" >}}

`sample.docx` هو ملف العينة المستخدم في هذا المثال. انقر [هنا](https://docs.groupdocs.com/viewer/python-net/_sample_files/getting-started/quick-start-guide/sample.docx) لتنزيله.

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

يجب أن يبدو هيكل المجلدات الخاص بك مشابهًا للهيكل التالي:

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

بعد تشغيل التطبيق يمكنك إلغاء تنشيط البيئة الافتراضية بتنفيذ `deactivate` أو إغلاق الصدفة.

### Explanation
- `Viewer("./sample.docx")`: Initializes the viewer with the DOCX file.
- `PngViewOptions("render_docx_to_png/output_{0}.png")`: Specifies the output format as PNG images.
- `viewer.view(png_options)`: Renders each page of the DOCX file to PNG and saves them as `output_1.png`, `output_2.png`, etc.

## Next Steps

بعد إكمال الأساسيات، استكشف موارد إضافية لتعزيز استخدامك:
- [Supported File Formats](): Review the full list of supported file types.
- [Licensing](): Check details on licensing and evaluation.
- [Technical Support](): Contact support for assistance if you encounter issues.
