---
title: "त्वरित प्रारम्भ गाइड"
linkTitle: "Quick Start Guide"
second_title: "GroupDocs.Viewer Python के लिए .NET के माध्यम से API संदर्भ"
description: "एक वर्चुअल एनवायरनमेंट सेट करें, groupdocs-viewer-net इंस्टॉल करें, और पाँच मिनट से कम समय में तीन न्यूनतम उदाहरण चलाएँ — DOCX → HTML, DOCX → PDF, और DOCX → प्रति‑पृष्ठ PNG —।"
type: docs
url: /hi/python-net/guides/quick-start-guide/
is_root: false
weight: 20
---


यह गाइड GroupDocs.Viewer को Python के लिए .NET के माध्यम से सेटअप और उपयोग शुरू करने का त्वरित अवलोकन प्रदान करता है। यह लाइब्रेरी डेवलपर्स को न्यूनतम कॉन्फ़िगरेशन के साथ दस्तावेज़ों को HTML, PDF, PNG, और JPG फ़ॉर्मेट में रेंडर करने में सक्षम बनाती है।

## Prerequisites

आगे बढ़ने के लिए, सुनिश्चित करें कि आपके पास है:

1. **Configured** पर्यावरण जैसा कि [System Requirements]() विषय में वर्णित है।
2. **Optionally** आप सभी उत्पाद सुविधाओं का परीक्षण करने के लिए [अस्थायी लाइसेंस प्राप्त करें](https://purchase.groupdocs.com/temporary-license/)।

## Set Up Your Development Environment

सर्वोत्तम प्रथाओं के लिए, Python एप्लिकेशन में निर्भरताओं को प्रबंधित करने हेतु वर्चुअल एनवायरनमेंट का उपयोग करें। वर्चुअल एनवायरनमेंट के बारे में अधिक जानने के लिए [Create and Use Virtual Environments](https://packaging.python.org/en/latest/guides/installing-using-pip-and-virtual-environments/#create-and-use-virtual-environments) दस्तावेज़ विषय देखें।

### Create and Activate a Virtual Environment

एक वर्चुअल एनवायरनमेंट बनाएं:

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

वर्चुअल एनवायरनमेंट सक्रिय करें:

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

वर्चुअल एनवायरनमेंट सक्रिय करने के बाद, पैकेज का नवीनतम संस्करण स्थापित करने के लिए अपने टर्मिनल में निम्न कमांड चलाएँ:

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

सुनिश्चित करें कि पैकेज सफलतापूर्वक स्थापित हो गया है। आपको यह संदेश दिखना चाहिए

```bash
Successfully installed groupdocs-viewer-net-*
```

## Example 1: Render document to HTML

लाइब्रेरी का त्वरित परीक्षण करने के लिए, चलिए एक DOCX फ़ाइल को HTML में रेंडर करते हैं। आप वह ऐप भी डाउनलोड कर सकते हैं जिसे हम बनाने जा रहे हैं [यहाँ](https://docs.groupdocs.com/viewer/python-net/_sample_files/getting-started/quick-start-guide/render_docx_to_html.zip)।

{{< tabs "demo_app_render_docx_to_html">}}
{{< tab "render_docx_to_html.py" >}}
```python
import os
from groupdocs.viewer import License, Viewer
from groupdocs.viewer.options import HtmlViewOptions

def render_docx_to_html():
    # लाइसेंस फ़ाइल का पूर्ण पथ प्राप्त करें
    license_path = os.path.abspath("./GroupDocs.Viewer.lic")

    if os.path.exists(license_path):
        # लाइसेंस बनाएं और पथ सेट करें
        license = License()
        license.set_license(license_path)

    # DOCX फ़ाइल लोड करें
    with Viewer("./sample.docx") as viewer:
        # व्यू विकल्प बनाएं
        html_options = HtmlViewOptions.for_embedded_resources("render_docx_to_html/page_{0}.html")

        # DOCX को HTML में रेंडर करें
        viewer.view(html_options)

if __name__ == "__main__":
    render_docx_to_html()
```
{{< /tab >}}
{{< tab "sample.docx" >}}

`sample.docx` इस उदाहरण में उपयोग की गई नमूना फ़ाइल है। इसे डाउनलोड करने के लिए [यहाँ](https://docs.groupdocs.com/viewer/python-net/_sample_files/getting-started/quick-start-guide/sample.docx) क्लिक करें।

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

आपकी फ़ोल्डर ट्री निम्नलिखित डायरेक्टरी संरचना जैसी दिखनी चाहिए:

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

ऐप चलाने के बाद आप `deactivate` कमांड चलाकर या अपना शेल बंद करके वर्चुअल एनवायरनमेंट को निष्क्रिय कर सकते हैं।

### Explanation
- `Viewer("./sample.docx")`: Initializes the viewer with the DOCX file.
- `HtmlViewOptions.for_embedded_resources("render_docx_to_html/page_{0}.html")`: Specifies the output format as HTML with embedded resources.
- `viewer.view(html_options)`: Renders the DOCX file to HTML and saves it as `page_1.html`, `page_2.html`, etc.

## Example 2: Render document to PDF

इस उदाहरण में हम एक DOCX फ़ाइल को PDF में रेंडर करेंगे। आप वह ऐप जिसे हम बनाने वाले हैं, [यहाँ](https://docs.groupdocs.com/viewer/python-net/_sample_files/getting-started/quick-start-guide/render_docx_to_pdf.zip) डाउनलोड कर सकते हैं।

{{< tabs "demo_app_render_docx_to_pdf">}}
{{< tab "render_docx_to_pdf.py" >}}
```python
import os
from groupdocs.viewer import License, Viewer
from groupdocs.viewer.options import PdfViewOptions

def render_docx_to_pdf():
    # लाइसेंस फ़ाइल का पूर्ण पथ प्राप्त करें
    license_path = os.path.abspath("./GroupDocs.Viewer.lic")

    if os.path.exists(license_path):
        # लाइसेंस बनाएं और पथ सेट करें
        license = License()
        license.set_license(license_path)

    # DOCX फ़ाइल लोड करें
    with Viewer("./sample.docx") as viewer:
        # व्यू विकल्प बनाएं
        pdf_options = PdfViewOptions("render_docx_to_pdf/output.pdf")

        # DOCX को PDF में रेंडर करें
        viewer.view(pdf_options)

if __name__ == "__main__":
    render_docx_to_pdf()
```
{{< /tab >}}
{{< tab "sample.docx" >}}

`sample.docx` इस उदाहरण में उपयोग की गई नमूना फ़ाइल है। इसे डाउनलोड करने के लिए [यहाँ](https://docs.groupdocs.com/viewer/python-net/_sample_files/getting-started/quick-start-guide/sample.docx) क्लिक करें।

{{< /tab >}}
{{< tab "output.pdf" >}}
```text
Binary file (PDF, 234 KB)
```
[Download full output](https://docs.groupdocs.com/viewer/python-net/_output_files/getting-started/quick-start-guide/render_docx_to_pdf/output.pdf)
{{< /tab >}}
{{< /tabs >}}

आपकी फ़ोल्डर ट्री निम्नलिखित डायरेक्टरी संरचना जैसी दिखनी चाहिए:

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

ऐप चलाने के बाद आप `deactivate` कमांड चलाकर या अपना शेल बंद करके वर्चुअल एनवायरनमेंट को निष्क्रिय कर सकते हैं।

### Explanation
- `Viewer("./sample.docx")`: Initializes the viewer with the DOCX file.
- `PdfViewOptions("output.pdf")`: Specifies the output format as PDF.
- `viewer.view(pdf_options)`: Renders the DOCX file to PDF and saves it as `output.pdf`.

## Example 3: Render document to PNG images

इस उदाहरण में हम एक DOCX फ़ाइल को PNG इमेजेज़ में रेंडर करेंगे। आप वह ऐप जिसे हम बनाने वाले हैं, [यहाँ](https://docs.groupdocs.com/viewer/python-net/_sample_files/getting-started/quick-start-guide/render_docx_to_png.zip) डाउनलोड कर सकते हैं।

{{< tabs "demo_app_render_docx_to_png">}}
{{< tab "render_docx_to_png.py" >}}
```python
import os
from groupdocs.viewer import License, Viewer
from groupdocs.viewer.options import PngViewOptions

def render_docx_to_png():
    # लाइसेंस फ़ाइल का पूर्ण पथ प्राप्त करें
    license_path = os.path.abspath("./GroupDocs.Viewer.lic")

    if os.path.exists(license_path):
        # लाइसेंस बनाएं और पथ सेट करें
        license = License()
        license.set_license(license_path)

    # DOCX फ़ाइल लोड करें
    with Viewer("./sample.docx") as viewer:
        # व्यू विकल्प बनाएं
        png_options = PngViewOptions("render_docx_to_png/output_{0}.png")

        # DOCX को PNG इमेजेज़ में रेंडर करें
        viewer.view(png_options)

if __name__ == "__main__":
    render_docx_to_png()
```
{{< /tab >}}
{{< tab "sample.docx" >}}

`sample.docx` इस उदाहरण में उपयोग की गई नमूना फ़ाइल है। इसे डाउनलोड करने के लिए [यहाँ](https://docs.groupdocs.com/viewer/python-net/_sample_files/getting-started/quick-start-guide/sample.docx) क्लिक करें।

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

आपकी फ़ोल्डर ट्री निम्नलिखित डायरेक्टरी संरचना जैसी दिखनी चाहिए:

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

ऐप चलाने के बाद आप `deactivate` कमांड चलाकर या अपना शेल बंद करके वर्चुअल एनवायरनमेंट को निष्क्रिय कर सकते हैं।

### Explanation
- `Viewer("./sample.docx")`: Initializes the viewer with the DOCX file.
- `PngViewOptions("render_docx_to_png/output_{0}.png")`: Specifies the output format as PNG images.
- `viewer.view(png_options)`: Renders each page of the DOCX file to PNG and saves them as `output_1.png`, `output_2.png`, etc.

## Next Steps

बुनियादी बातें पूरी करने के बाद, अपने उपयोग को बेहतर बनाने के लिए अतिरिक्त संसाधनों का अन्वेषण करें:
- [Supported File Formats](): Review the full list of supported file types.
- [Licensing](): Check details on licensing and evaluation.
- [Technical Support](): Contact support for assistance if you encounter issues.
