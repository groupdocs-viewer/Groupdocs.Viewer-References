---
title: "Αποθήκευση συνημμένων"
linkTitle: "Save attachments"
second_title: "GroupDocs.Viewer για Python μέσω .NET Αναφορές API"
description: "Ανακτήστε και αποθηκεύστε συνημμένα από email, αρχεία Outlook, αρχειοθήκες και PDF."
type: docs
url: /el/python-net/guides/how-to-extract-and-save-attachments/
is_root: false
weight: 110
---


Για να λάβετε και να αποθηκεύσετε συνημμένα, ακολουθήστε τα παρακάτω βήματα:

1. Δημιουργήστε το αντικείμενο [Viewer](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer/viewer/). Καθορίστε ένα αρχείο που περιέχει συνημμένα.
2. Καλέστε τη μέθοδο [get_attachments](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer/viewer/#methods). Επιστρέφει τη συλλογή των συνημμένων.
3. Επανάληψη στη συλλογή. Για να αποθηκεύσετε ένα συνημμένο, καλέστε τη μέθοδο [save_attachment](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer/viewer/#methods).

Το παρακάτω απόσπασμα κώδικα δείχνει πώς να λάβετε και να αποθηκεύσετε όλα τα συνημμένα από το αρχείο MSG:

ΣΗΜΕΙΩΣΗ: Το παρεχόμενο απόσπασμα κώδικα ισχύει για όλες τις οικογένειες μορφών που υποστηρίζουν συνημμένα: email, αρχεία δεδομένων Outlook, αρχειοθήκες και έγγραφα PDF.

{{< tabs "example1">}}
{{< tab "Python" >}}
```python
from groupdocs.viewer import Viewer

def extract_and_save_attachments():
    # Φόρτωση εγγράφου με συνημμένα
    with Viewer("with_attachments.msg") as viewer:
        attachments = viewer.get_attachments()

        print("\nAttachments:")
        for attachment in attachments:
            print(attachment)
            # Αποθήκευση συνημμένου στο δίσκο
            viewer.save_attachment(attachment, f"./attachments/{attachment.file_name}")

    print(f"\nAttachments retrieved successfully.")

if __name__ == "__main__":
    extract_and_save_attachments()
```
{{< /tab >}}
{{< tab "with_attachments.msg" >}}

`with_attachments.msg` είναι το δείγμα αρχείου που χρησιμοποιείται σε αυτό το παράδειγμα. Κάντε κλικ [εδώ](https://docs.groupdocs.com/viewer/python-net/_sample_files/developer-guide/processing-attachments/with_attachments.msg) για να το κατεβάσετε.

{{< /tab >}}
{{< tab "extract-and-save-attachments-outputs.zip" >}}
```text
attachments/attachment-image.png (26 KB)
attachments/attachment-word.doc (220 KB)
```
[Download full output](https://docs.groupdocs.com/viewer/python-net/_output_files/developer-guide/processing-attachments/how-to-extract-and-save-attachments/extract_and_save_attachments/extract-and-save-attachments-outputs.zip)
{{< /tab >}}
{{< /tabs >}}
