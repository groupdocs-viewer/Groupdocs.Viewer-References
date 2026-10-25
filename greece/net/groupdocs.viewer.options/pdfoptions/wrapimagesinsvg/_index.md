---
title: "WrapImagesInSvg"
second_title: "Αναφορά API του GroupDocs.Viewer for .NET"
description: "Ενεργοποιεί την περιτύλιξη κάθε εικόνας στο έγγραφο HTML εξόδου με ετικέτα SVG για βελτίωση της ποιότητας εξόδου."
type: docs
weight: 110
url: /el/net/groupdocs.viewer.options/pdfoptions/wrapimagesinsvg/
---

## PdfOptions.WrapImagesInSvg property

Ενεργοποιεί την περιτύλιξη κάθε εικόνας στο έγγραφο HTML εξόδου με ετικέτα SVG για βελτίωση της ποιότητας εξόδου.

```csharp
public bool WrapImagesInSvg { get; set; }
```

### Παρατηρήσεις

Από προεπιλογή, κατά την απόδοση αρχείων PDF και Page Layout σε HTML, όλες οι εικόνες αποδίδονται ως μία εικόνα PNG. Η παραγόμενη εικόνα PNG χρησιμοποιείται ως φόντο για το έγγραφο HTML εξόδου.

Αυτή η επιλογή είναι διαθέσιμη όταν αποδίδονται [μορφές αρχείων PDF και Page Layout](https://docs.groupdocs.com/viewer/net/supported-document-formats/#pdf-and-page-layout-file-formats) σε HTML με ενσωματωμένους και εξωτερικούς πόρους. Επιτρέπει την περιτύλιξη κάθε εικόνας στο έγγραφο HTML εξόδου με ετικέτα SVG. Η προεπιλεγμένη τιμή είναι `false`.

Για παράδειγμα κώδικα, δείτε την [τεκμηρίωση](https://docs.groupdocs.com/viewer/net/render-pdf-documents/#enclose-images-in-svg-when-rendering-pdf-and-page-layout-files).

### Δείτε επίσης

* class [PdfOptions](../../pdfoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

<!-- ΜΗΝ ΕΠΕΞΕΡΓΑΣΕΤΕ: δημιουργήθηκε από το xmldocmd για το GroupDocs.Viewer.dll -->
