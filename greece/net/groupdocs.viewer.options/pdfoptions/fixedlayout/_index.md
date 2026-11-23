---
title: "FixedLayout"
second_title: "Αναφορά API του GroupDocs.Viewer for .NET"
description: "Ενεργοποιεί την απόδοση των εγγράφων PDF και EPUB σε HTML με σταθερή διάταξη."
type: docs
weight: 70
url: /el/net/groupdocs.viewer.options/pdfoptions/fixedlayout/
---

## PdfOptions.FixedLayout property

Ενεργοποιεί την απόδοση των εγγράφων PDF και EPUB σε HTML με σταθερή διάταξη.

```csharp
public bool FixedLayout { get; set; }
```

### Παρατηρήσεις

Τα έγγραφα PDF και EPUB αρχικά αποδίδονται σε HTML με σταθερή διάταξη για να διατηρηθεί η εμφάνιση του πηγαίου εγγράφου. Αυτή η σταθερή διάταξη σημαίνει ότι όλα τα στοιχεία HTML έχουν ακριβείς θέσεις μέσα σε ένα κοντέινερ με καθορισμένο μέγεθος. Η αλλαγή μεγέθους του παραθύρου του προγράμματος περιήγησης δεν επηρεάζει τη θέση και το μέγεθος των στοιχείων στο έγγραφο.

Αυτή η επιλογή είναι διαθέσιμη μόνο κατά την απόδοση σε HTML. Η προεπιλεγμένη τιμή είναι `true`. Για απόδοση με ρευστή διάταξη, ορίστε αυτή την ιδιότητα σε `false`.

Κατά την απόδοση με ρευστή διάταξη, οι εικόνες παραλείπονται. Χρησιμοποιήστε ρευστή διάταξη όταν αποδίδετε έγγραφα PDF με περιεχόμενο κειμένου.

Για παράδειγμα κώδικα, δείτε την [τεκμηρίωση](https://docs.groupdocs.com/viewer/net/render-pdf-documents/#create-html-with-fluid-layout).

### Δείτε επίσης

* class [PdfOptions](../../pdfoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

<!-- ΜΗΝ ΕΠΕΞΕΡΓΑΣΕΤΕ: δημιουργήθηκε από το xmldocmd για το GroupDocs.Viewer.dll -->
