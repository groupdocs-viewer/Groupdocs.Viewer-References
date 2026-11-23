---
title: "Αναδιάταξη σελίδων"
linkTitle: "Reorder pages"
second_title: "GroupDocs.Viewer για Python μέσω .NET Αναφορές API"
description: "Αναδιατάξτε τις σελίδες PDF κατά την απόδοση με το GroupDocs.Viewer για Python μέσω .NET. Ελέγξτε τη σειρά των σελίδων εξόδου."
type: docs
url: /el/python-net/guides/reorder-pages/
is_root: false
weight: 100
---


Το GroupDocs.Viewer διατηρεί τη σειρά των σελίδων στο αρχικό έγγραφο. Αντ' αυτού, μπορείτε να αναδιατάξετε τις σελίδες στο έγγραφο PDF εξόδου.

To reorder pages, follow these steps:

1. Δημιουργήστε το αντικείμενο [Viewer](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer/viewer).
2. Δημιουργήστε το αντικείμενο [PdfViewOptions](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer.options/pdfviewoptions).
3. Καλέστε τη μέθοδο [view](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer/viewer/#methods) του αντικειμένου [Viewer](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer/viewer). Καθορίστε τη νέα σειρά σελίδων στις τελευταίες παραμέτρους.

Το παρακάτω απόσπασμα κώδικα δείχνει πώς να επαναδιατάξετε τις σελίδες:

{{< tabs "example1">}}
{{< tab "Python">}}
```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions

def reorder_pages():
    # Φόρτωση εγγράφου
    with Viewer("sample.docx") as viewer:
        # Δημιουργήστε επιλογές προβολής.
        viewOptions = PdfViewOptions("reorder_pages/reordered_pages.pdf")

        # Περάστε τους αριθμούς σελίδων με τη σειρά που θέλετε να τα αποδώσετε.
        viewer.view(viewOptions, [2, 1])

if __name__ == "__main__":
    reorder_pages()
```
{{< /tab >}}
{{< tab "sample.docx" >}}

`sample.docx` είναι το δείγμα αρχείου που χρησιμοποιείται σε αυτό το παράδειγμα. Κάντε κλικ [εδώ](https://docs.groupdocs.com/viewer/python-net/_sample_files/developer-guide/rendering-documents/rendering-to-pdf/reorder-pages/sample.docx) για να το κατεβάσετε.

{{< /tab >}}
{{< tab "reordered_pages.pdf" >}}
```text
Binary file (PDF, 176 KB)
```
[Download full output](https://docs.groupdocs.com/viewer/python-net/_output_files/developer-guide/rendering-documents/rendering-to-pdf/reorder-pages/reorder_pages/reordered_pages.pdf)
{{< /tab >}}
{{< /tabs >}}
