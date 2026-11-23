---
title: "Προστασία εγγράφου PDF"
linkTitle: "Protect PDF document"
second_title: "GroupDocs.Viewer για Python μέσω .NET Αναφορές API"
description: "Ασφαλίστε την έξοδο PDF με κωδικούς πρόσβασης και δικαιώματα κατά την απόδοση εγγράφων χρησιμοποιώντας το GroupDocs.Viewer."
type: docs
url: /el/python-net/guides/protect-pdf-document/
is_root: false
weight: 90
---


Μπορείτε να προστατέψετε ένα έγγραφο PDF ορίζοντας τις παρακάτω παραμέτρους:

* permissions
* password to open document
* password to change permissions

Για να προστατέψετε ένα έγγραφο PDF, ακολουθήστε τα παρακάτω βήματα:

1. Δημιουργήστε μια παρουσία της κλάσης [Viewer](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer/viewer). Καθορίστε τη διαδρομή του πηγαίου εγγράφου ως παράμετρο κατασκευής.
2. Δημιουργήστε το αντικείμενο [Security](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer.options/security).
3. Για να ορίσετε έναν κωδικό πρόσβασης για το άνοιγμα του εγγράφου, ορίστε την ιδιότητα [DocumentOpenPassword](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer.options/security/#properties).
4. Για να ορίσετε έναν κωδικό πρόσβασης για την αλλαγή περιορισμών, ορίστε την ιδιότητα [PermissionsPassword](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer.options/security/#properties).
5. Για να ορίσετε τα δικαιώματα του εγγράφου, ορίστε την ιδιότητα [Permissions](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer.options/permissions).
6. Δημιουργήστε το αντικείμενο [PdfViewOptions](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer.options/pdfviewoptions). Καθορίστε τη μορφή διαδρομής αποθήκευσης για το αποδοθέν έγγραφο.
7. Αρχικοποιήστε την ιδιότητα [Security](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer.options/pdfviewoptions/#properties) του αντικειμένου [PdfViewOptions](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer.options/pdfviewoptions) με το αντικείμενο που δημιουργήθηκε στα βήματα 2‑5.
8. Καλέστε τη μέθοδο [view](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer/viewer/#methods) του αντικειμένου [Viewer](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer/viewer). Καθορίστε το αντικείμενο [PdfViewOptions](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer.options/pdfviewoptions) ως παράμετρο.

Το παρακάτω απόσπασμα κώδικα δείχνει πώς να προστατεύσετε το τελικό PDF έγγραφο:

{{< tabs "example1">}}
{{< tab "Python">}}
```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions, Security, Permissions

def protect_pdf_document():
    # Φόρτωση εγγράφου
    with Viewer("sample.docx") as viewer:
        # Καθορίστε τις ρυθμίσεις ασφαλείας.
        security = Security()
        security.document_open_password = "o123"
        security.permissions_password = "p123"
        security.permissions = Permissions.ALLOW_ALL & ~Permissions.DENY_PRINTING

        # Δημιουργήστε ένα αρχείο PDF.
        pdf_options = PdfViewOptions("protect_pdf_document/protected_document.pdf")

        # Εφαρμόστε τις ρυθμίσεις ασφαλείας
        pdf_options.security = security
        viewer.view(pdf_options)

if __name__ == "__main__":
    protect_pdf_document()
```
{{< /tab >}}
{{< tab "sample.docx" >}}

`sample.docx` είναι το δείγμα αρχείου που χρησιμοποιείται σε αυτό το παράδειγμα. Κάντε κλικ [εδώ](https://docs.groupdocs.com/viewer/python-net/_sample_files/developer-guide/rendering-documents/rendering-to-pdf/protect-pdf-document/sample.docx) για να το κατεβάσετε.

{{< /tab >}}
{{< tab \"protected_document.pdf\" >}}
```text
Binary file (PDF, 238 KB)
```
[Download full output](https://docs.groupdocs.com/viewer/python-net/_output_files/developer-guide/rendering-documents/rendering-to-pdf/protect-pdf-document/protect_pdf_document/protected_document.pdf)
{{< /tab >}}
{{< /tabs >}}
