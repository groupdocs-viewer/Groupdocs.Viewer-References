---
title: "Φόρτωση εγγράφου από τοπικό δίσκο"
linkTitle: "Load from local disk"
second_title: "GroupDocs.Viewer για Python μέσω .NET Αναφορές API"
description: "Φορτώστε έγγραφα από τον τοπικό σας δίσκο χρησιμοποιώντας διαδρομή αρχείου με το GroupDocs.Viewer for Python μέσω .NET."
type: docs
url: /el/python-net/guides/load-document-from-local-disk/
is_root: false
weight: 50
---


Μπορείτε να φορτώσετε ένα έγγραφο από τοπικό δίσκο χρησιμοποιώντας μια διαδρομή προς ένα αρχείο. Το GroupDocs.Viewer ανοίγει το αρχείο σε λειτουργία μόνο για ανάγνωση.

Το παρακάτω απόσπασμα κώδικα δείχνει πώς να φορτώσετε ένα έγγραφο χρησιμοποιώντας τη συμβολοσειρά τοπικής διαδρομής:

{{< tabs "example1">}}
{{< tab "Python" >}}
```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

def load_document_from_local_disk():
    # Φόρτωση εγγράφου από τοπικό δίσκο
    with Viewer("sample.docx") as viewer:
        html_options = HtmlViewOptions.for_embedded_resources("load_document_from_local_disk/document_from_local_disk_{0}.html")
        viewer.view(html_options)

if __name__ == "__main__":
    load_document_from_local_disk()
```
{{< /tab >}}
{{< tab "sample.docx" >}}

`sample.docx` είναι το αρχείο δείγμα που χρησιμοποιείται σε αυτό το παράδειγμα. Κάντε κλικ [εδώ](https://docs.groupdocs.com/viewer/python-net/_sample_files/developer-guide/loading-documents/load-document-from-local-disk/sample.docx) για να το κατεβάσετε.

{{< /tab >}}
{{< tab \"load-document-from-local-disk-outputs.zip\" >}}
```text
load_document_from_local_disk/document_from_local_disk_1.html (317 KB)
load_document_from_local_disk/document_from_local_disk_2.html (149 KB)
load_document_from_local_disk/document_from_local_disk_3.html (113 KB)
```
[Download full output](https://docs.groupdocs.com/viewer/python-net/_output_files/developer-guide/loading-documents/load-document-from-local-disk/load_document_from_local_disk/load-document-from-local-disk-outputs.zip)
{{< /tab >}}
{{< /tabs >}}
