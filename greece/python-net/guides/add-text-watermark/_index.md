---
title: "Προσθήκη υδατογραφιών κειμένου"
linkTitle: "Add text watermarks"
second_title: "GroupDocs.Viewer για Python μέσω .NET Αναφορές API"
description: "Προσθέστε υδατογραφήματα κειμένου σε έγγραφα που αποδίδονται χρησιμοποιώντας το GroupDocs.Viewer στις εφαρμογές Python σας."
type: docs
url: /el/python-net/guides/add-text-watermark/
is_root: false
weight: 80
---


Για να προσθέσετε υδατογράφημα στην έξοδο HTML/JPG/PNG/PDF, ακολουθήστε τα παρακάτω βήματα:

1. Δημιουργήστε μια παρουσία της κλάσης [HtmlViewOptions](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer.options/htmlviewoptions/) (ή της [PngViewOptions](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer.options/pngviewoptions/), ή της [JpgViewOptions](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer.options/jpgviewoptions/), ή της [PdfViewOptions](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer.options/pdfviewoptions/));
2. Δημιουργήστε ένα αντικείμενο [Watermark](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer.options/watermark/) και συμπληρώστε τις ιδιότητές του;
3. Καλέστε τη μέθοδο [watermark](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer.options/viewoptions/#properties) της κλάσης [HtmlViewOptions](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer.options/htmlviewoptions/) (ή της [PngViewOptions](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer.options/pngviewoptions/), ή της [JpgViewOptions](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer.options/jpgviewoptions/), ή της [PdfViewOptions](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer.options/pdfviewoptions/)) και καθορίστε το αντικείμενο που δημιουργήθηκε στο βήμα 2;
4. Καλέστε τη μέθοδο [Viewer.view()](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer/viewer/#methods).

Το παρακάτω απόσπασμα κώδικα δείχνει πώς να εφαρμόσετε το υδατογράφημα στις σελίδες εξόδου.

{{< tabs "example1">}}
{{< tab "Python" >}}
```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions, Watermark

def add_text_watermark():
    # Φόρτωση εγγράφου
    with Viewer("sample.docx") as viewer:
        # Δημιουργία αρχείου HTML.
        viewOptions = HtmlViewOptions.for_embedded_resources("add_text_watermark/output-watermark.html")
        # Προσθήκη υδατογραφήματος.
        viewOptions.watermark = Watermark("This is a watermark")
        viewer.view(viewOptions)

if __name__ == "__main__":
    add_text_watermark()
```
{{< /tab >}}
{{< tab "sample.docx" >}}

`sample.docx` είναι το δείγμα αρχείου που χρησιμοποιείται σε αυτό το παράδειγμα. Κάντε κλικ [εδώ](https://docs.groupdocs.com/viewer/python-net/_sample_files/developer-guide/rendering-documents/add-text-watermark/sample.docx) για να το κατεβάσετε.

{{< /tab >}}
{{< tab \"output-watermark.html\" >}}
```text
<!DOCTYPE html><html><head><meta http-equiv="Content-Type" content="text/html; charset=utf-8" /><meta name="generator" content="Aspose.Words for .NET 26.4.0" /><title>Sample Document ver.1</title><style type="text/css">@font-face { font-family:'Calibri'; font-style:normal; font-weight:normal; src:local('☺'), url('data:application/x-font-woff;base64,d09GRgABAAAAAGlIAA0AAAAA09gAAQAAAAAAAAAAAAAAAAAAAAAAAAAAAABPUy8yAAABMAAAAGAAAABgncM96GNtYXAAAAGQAAACswAABrCp8yKHY3Z0IAAABEQAAAKEAAAFvLlw2DVmcGdtAAAGy
[TRUNCATED]
```
[Download full output](https://docs.groupdocs.com/viewer/python-net/_output_files/developer-guide/rendering-documents/add-text-watermark/add_text_watermark/output-watermark.html)
{{< /tab >}}
{{< /tabs >}}
