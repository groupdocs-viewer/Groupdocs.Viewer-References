---
title: "Οδηγός Γρήγορης Εκκίνησης"
linkTitle: "Quick Start Guide"
second_title: "GroupDocs.Viewer για Python μέσω .NET Αναφορές API"
description: "Ρυθμίστε ένα εικονικό περιβάλλον, εγκαταστήστε το groupdocs-viewer-net και εκτελέστε τρία ελάχιστα παραδείγματα — DOCX → HTML, DOCX → PDF και DOCX → PNG ανά σελίδα — σε λιγότερο από πέντε λεπτά."
type: docs
url: /el/python-net/guides/quick-start-guide/
is_root: false
weight: 20
---


Αυτός ο οδηγός παρέχει μια γρήγορη επισκόπηση του πώς να ρυθμίσετε και να αρχίσετε να χρησιμοποιείτε το GroupDocs.Viewer για Python μέσω .NET. Αυτή η βιβλιοθήκη επιτρέπει στους προγραμματιστές να αποδίδουν έγγραφα σε μορφές HTML, PDF, PNG και JPG με ελάχιστη διαμόρφωση.

## Prerequisites

Για να προχωρήσετε, βεβαιωθείτε ότι έχετε:

1. **Configured** περιβάλλον όπως περιγράφεται στο θέμα [System Requirements]().
2. **Optionally** μπορείτε να [Αποκτήστε μια προσωρινή άδεια](https://purchase.groupdocs.com/temporary-license/) για να δοκιμάσετε όλες τις δυνατότητες του προϊόντος.

## Set Up Your Development Environment

Για βέλτιστες πρακτικές, χρησιμοποιήστε ένα εικονικό περιβάλλον για τη διαχείριση των εξαρτήσεων σε εφαρμογές Python. Μάθετε περισσότερα για το εικονικό περιβάλλον στο θέμα τεκμηρίωσης [Δημιουργία και Χρήση Εικονικών Περιβαλλόντων](https://packaging.python.org/en/latest/guides/installing-using-pip-and-virtual-environments/#create-and-use-virtual-environments).

### Create and Activate a Virtual Environment

Δημιουργήστε ένα εικονικό περιβάλλον:

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

Ενεργοποιήστε ένα εικονικό περιβάλλον:

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

Αφού ενεργοποιήσετε το εικονικό περιβάλλον, εκτελέστε την παρακάτω εντολή στο τερματικό σας για να εγκαταστήσετε την πιο πρόσφατη έκδοση του πακέτου:

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

Βεβαιωθείτε ότι το πακέτο εγκαταστάθηκε επιτυχώς. Θα πρέπει να δείτε το μήνυμα

```bash
Successfully installed groupdocs-viewer-net-*
```

## Example 1: Render document to HTML

Για γρήγορη δοκιμή της βιβλιοθήκης, ας αποδώσουμε ένα αρχείο DOCX σε HTML. Μπορείτε επίσης να κατεβάσετε την εφαρμογή που θα δημιουργήσουμε [εδώ](https://docs.groupdocs.com/viewer/python-net/_sample_files/getting-started/quick-start-guide/render_docx_to_html.zip).

{{< tabs "demo_app_render_docx_to_html">}}
{{< tab "render_docx_to_html.py" >}}
```python
import os
from groupdocs.viewer import License, Viewer
from groupdocs.viewer.options import HtmlViewOptions

def render_docx_to_html():
    # Αποκτήστε την απόλυτη διαδρομή του αρχείου άδειας
    license_path = os.path.abspath("./GroupDocs.Viewer.lic")

    if os.path.exists(license_path):
        # Δημιουργήστε την άδεια και ορίστε τη διαδρομή
        license = License()
        license.set_license(license_path)

    # Φορτώστε το αρχείο DOCX
    with Viewer("./sample.docx") as viewer:
        # Δημιουργήστε επιλογές προβολής
        html_options = HtmlViewOptions.for_embedded_resources("render_docx_to_html/page_{0}.html")

        # Μετατροπή DOCX σε HTML
        viewer.view(html_options)

if __name__ == "__main__":
    render_docx_to_html()
```
{{< /tab >}}
{{< tab "sample.docx" >}}

`sample.docx` είναι το δείγμα αρχείου που χρησιμοποιείται σε αυτό το παράδειγμα. Κάντε κλικ [εδώ](https://docs.groupdocs.com/viewer/python-net/_sample_files/getting-started/quick-start-guide/sample.docx) για να το κατεβάσετε.

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

Η δομή φακέλων σας θα πρέπει να μοιάζει με την παρακάτω δομή καταλόγου:

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

Μετά την εκτέλεση της εφαρμογής μπορείτε να απενεργοποιήσετε το εικονικό περιβάλλον εκτελώντας `deactivate` ή κλείνοντας το τερματικό σας.

### Explanation
- `Viewer("./sample.docx")`: Initializes the viewer with the DOCX file.
- `HtmlViewOptions.for_embedded_resources("render_docx_to_html/page_{0}.html")`: Specifies the output format as HTML with embedded resources.
- `viewer.view(html_options)`: Renders the DOCX file to HTML and saves it as `page_1.html`, `page_2.html`, etc.

## Example 2: Render document to PDF

Σε αυτό το παράδειγμα θα μετατρέψουμε ένα αρχείο DOCX σε PDF. Μπορείτε να κατεβάσετε την εφαρμογή που θα δημιουργήσουμε [εδώ](https://docs.groupdocs.com/viewer/python-net/_sample_files/getting-started/quick-start-guide/render_docx_to_pdf.zip).

{{< tabs "demo_app_render_docx_to_pdf">}}
{{< tab "render_docx_to_pdf.py" >}}
```python
import os
from groupdocs.viewer import License, Viewer
from groupdocs.viewer.options import PdfViewOptions

def render_docx_to_pdf():
    # Αποκτήστε την απόλυτη διαδρομή του αρχείου άδειας
    license_path = os.path.abspath("./GroupDocs.Viewer.lic")

    if os.path.exists(license_path):
        # Δημιουργήστε την άδεια και ορίστε τη διαδρομή
        license = License()
        license.set_license(license_path)

    # Φορτώστε το αρχείο DOCX
    with Viewer("./sample.docx") as viewer:
        # Δημιουργήστε επιλογές προβολής
        pdf_options = PdfViewOptions("render_docx_to_pdf/output.pdf")

        # Μετατροπή DOCX σε PDF
        viewer.view(pdf_options)

if __name__ == "__main__":
    render_docx_to_pdf()
```
{{< /tab >}}
{{< tab "sample.docx" >}}

`sample.docx` είναι το δείγμα αρχείου που χρησιμοποιείται σε αυτό το παράδειγμα. Κάντε κλικ [εδώ](https://docs.groupdocs.com/viewer/python-net/_sample_files/getting-started/quick-start-guide/sample.docx) για να το κατεβάσετε.

{{< /tab >}}
{{< tab "output.pdf" >}}
```text
Binary file (PDF, 234 KB)
```
[Download full output](https://docs.groupdocs.com/viewer/python-net/_output_files/getting-started/quick-start-guide/render_docx_to_pdf/output.pdf)
{{< /tab >}}
{{< /tabs >}}

Η δομή φακέλων σας θα πρέπει να μοιάζει με την παρακάτω δομή καταλόγου:

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

Μετά την εκτέλεση της εφαρμογής μπορείτε να απενεργοποιήσετε το εικονικό περιβάλλον εκτελώντας `deactivate` ή κλείνοντας το τερματικό σας.

### Explanation
- `Viewer("./sample.docx")`: Initializes the viewer with the DOCX file.
- `PdfViewOptions("output.pdf")`: Specifies the output format as PDF.
- `viewer.view(pdf_options)`: Renders the DOCX file to PDF and saves it as `output.pdf`.

## Example 3: Render document to PNG images

Σε αυτό το παράδειγμα θα μετατρέψουμε ένα αρχείο DOCX σε εικόνες PNG. Μπορείτε να κατεβάσετε την εφαρμογή που θα δημιουργήσουμε [εδώ](https://docs.groupdocs.com/viewer/python-net/_sample_files/getting-started/quick-start-guide/render_docx_to_png.zip).

{{< tabs "demo_app_render_docx_to_png">}}
{{< tab "render_docx_to_png.py" >}}
```python
import os
from groupdocs.viewer import License, Viewer
from groupdocs.viewer.options import PngViewOptions

def render_docx_to_png():
    # Αποκτήστε την απόλυτη διαδρομή του αρχείου άδειας
    license_path = os.path.abspath("./GroupDocs.Viewer.lic")

    if os.path.exists(license_path):
        # Δημιουργήστε την άδεια και ορίστε τη διαδρομή
        license = License()
        license.set_license(license_path)

    # Φορτώστε το αρχείο DOCX
    with Viewer("./sample.docx") as viewer:
        # Δημιουργήστε επιλογές προβολής
        png_options = PngViewOptions("render_docx_to_png/output_{0}.png")

        # Μετατροπή DOCX σε εικόνες PNG
        viewer.view(png_options)

if __name__ == "__main__":
    render_docx_to_png()
```
{{< /tab >}}
{{< tab "sample.docx" >}}

`sample.docx` είναι το δείγμα αρχείου που χρησιμοποιείται σε αυτό το παράδειγμα. Κάντε κλικ [εδώ](https://docs.groupdocs.com/viewer/python-net/_sample_files/getting-started/quick-start-guide/sample.docx) για να το κατεβάσετε.

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

Η δομή φακέλων σας θα πρέπει να μοιάζει με την παρακάτω δομή καταλόγου:

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

Μετά την εκτέλεση της εφαρμογής μπορείτε να απενεργοποιήσετε το εικονικό περιβάλλον εκτελώντας `deactivate` ή κλείνοντας το τερματικό σας.

### Explanation
- `Viewer("./sample.docx")`: Initializes the viewer with the DOCX file.
- `PngViewOptions("render_docx_to_png/output_{0}.png")`: Specifies the output format as PNG images.
- `viewer.view(png_options)`: Renders each page of the DOCX file to PNG and saves them as `output_1.png`, `output_2.png`, etc.

## Next Steps

Αφού ολοκληρώσετε τα βασικά, εξερευνήστε πρόσθετους πόρους για να βελτιώσετε τη χρήση σας:
- [Supported File Formats](): Review the full list of supported file types.
- [Licensing](): Check details on licensing and evaluation.
- [Technical Support](): Contact support for assistance if you encounter issues.
