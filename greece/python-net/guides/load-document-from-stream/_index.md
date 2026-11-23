---
title: "Φόρτωση εγγράφου από ροή"
linkTitle: "Load from stream"
second_title: "GroupDocs.Viewer για Python μέσω .NET Αναφορές API"
description: "Φορτώστε έγγραφα απευθείας από αντικείμενο τύπου αρχείου — ανοιχτό χειριστή αρχείου, BytesIO ή οποιαδήποτε ροή — με το GroupDocs.Viewer για Python μέσω .NET."
type: docs
url: /el/python-net/guides/load-document-from-stream/
is_root: false
weight: 60
---


Μπορείτε να φορτώσετε ένα έγγραφο από ροή χωρίς να το αποθηκεύσετε ως αρχείο στον δίσκο. Μπορείτε να χρησιμοποιήσετε αυτή τη δυνατότητα για να φορτώσετε ένα έγγραφο από διαφορετικές πηγές όπως URL, FTP κ.λπ.

Για να φορτώσετε ένα έγγραφο από ροή, ακολουθήστε τα παρακάτω βήματα:

1. Υλοποιήστε μια μέθοδο για να λάβετε τη ροή του εγγράφου.
2. Καλέστε τον κατασκευαστή κλάσης [Viewer](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer/viewer). Καθορίστε τη μέθοδο που υλοποιήθηκε στο προηγούμενο βήμα.

Το παρακάτω απόσπασμα κώδικα δείχνει πώς να φορτώσετε ένα έγγραφο από ροή:

{{< tabs "example1">}}
{{< tab "Python" >}}
```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

def load_document_from_stream():
    # Άνοιγμα ροής εγγράφου
    stream = open("sample.docx", "rb")

    # Απόδοση εγγράφου από τη ροή.
    with Viewer(stream) as viewer:
        options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
        viewer.view(options)

if __name__ == "__main__":
    load_document_from_stream()
```
{{< /tab >}}
{{< tab "sample.docx" >}}

`sample.docx` είναι το δείγμα αρχείου που χρησιμοποιείται σε αυτό το παράδειγμα. Κάντε κλικ [εδώ](https://docs.groupdocs.com/viewer/python-net/_sample_files/developer-guide/loading-documents/load-document-from-stream/sample.docx) για να το κατεβάσετε.

{{< /tab >}}
{{< tab "load-document-from-stream-outputs.zip" >}}
```text
page_1.html (317 KB)
page_2.html (149 KB)
page_3.html (113 KB)
```
[Download full output](https://docs.groupdocs.com/viewer/python-net/_output_files/developer-guide/loading-documents/load-document-from-stream/load_document_from_stream/load-document-from-stream-outputs.zip)
{{< /tab >}}
{{< /tabs >}}

Δείτε επίσης [Load document from URL]() για ένα συγκεκριμένο παράδειγμα λήψης ενός εγγράφου σε ροή `BytesIO` και απόδοσής του χωρίς ποτέ να το γράψετε σε δίσκο.
