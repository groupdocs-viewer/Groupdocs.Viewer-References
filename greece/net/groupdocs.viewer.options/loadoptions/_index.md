---
title: "LoadOptions"
second_title: "Αναφορά API του GroupDocs.Viewer for .NET"
description: "Περιέχει επιλογές που χρησιμοποιούνται για το άνοιγμα του αρχείου. Για λεπτομέρειες, δείτε αυτή τη σελίδα https//docs.groupdocs.com/viewer/net/loading/ και τα υποσέλιδά της."
type: docs
weight: 360
url: /el/net/groupdocs.viewer.options/loadoptions/
---

## LoadOptions class

Περιέχει επιλογές που χρησιμοποιούνται για το άνοιγμα του αρχείου. Για λεπτομέρειες, δείτε αυτή τη [σελίδα](https://docs.groupdocs.com/viewer/net/loading/) και τα υπο-στοιχεία της.

```csharp
public class LoadOptions
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [LoadOptions](loadoptions#constructor)() | Αρχικοποιεί ένα στιγμιότυπο της κλάσης [`LoadOptions`](../loadoptions). |
| [LoadOptions](loadoptions#constructor_1)(FileType) | Αρχικοποιεί ένα στιγμιότυπο της κλάσης [`LoadOptions`](../loadoptions). |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [DetectEncoding](../../groupdocs.viewer.options/loadoptions/detectencoding) { get; set; } | Ενεργοποιεί την ανίχνευση κωδικοποίησης για τα αρχεία [`TXT`](../../groupdocs.viewer/filetype/txt), [`CSV`](../../groupdocs.viewer/filetype/csv) και [`TSV`](../../groupdocs.viewer/filetype/tsv). |
| [Encoding](../../groupdocs.viewer.options/loadoptions/encoding) { get; set; } | Ορίζει την κωδικοποίηση που χρησιμοποιείται κατά το άνοιγμα αρχείων κειμένου ή μηνυμάτων ηλεκτρονικού ταχυδρομείου όπως [`CSV`](../../groupdocs.viewer/filetype/csv), [`TXT`](../../groupdocs.viewer/filetype/txt) και [`MSG`](../../groupdocs.viewer/filetype/msg). Η προεπιλεγμένη τιμή είναι UTF8. |
| [FileType](../../groupdocs.viewer.options/loadoptions/filetype) { get; set; } | Ορίζει τον τύπο του αρχείου που θα ανοίξει. |
| [Password](../../groupdocs.viewer.options/loadoptions/password) { get; set; } | Ορίζει τον κωδικό πρόσβασης για το άνοιγμα κρυπτογραφημένου αρχείου. |
| [ResourceLoadingTimeout](../../groupdocs.viewer.options/loadoptions/resourceloadingtimeout) { get; set; } | Ορίζει το χρονικό όριο για τη φόρτωση εξωτερικών πόρων. |
| [SkipExternalResources](../../groupdocs.viewer.options/loadoptions/skipexternalresources) { get; set; } | Απενεργοποιεί τη φόρτωση όλων των εξωτερικών πόρων, όπως εικόνες, εκτός από το [`WhitelistedResources`](./whitelistedresources). |
| [TryRepair](../../groupdocs.viewer.options/loadoptions/tryrepair) { get; set; } | Όταν είναι ενεργοποιημένο, το GroupDocs.Viewer προσπαθεί να επισκευάσει δομική αλλοίωση σε έγγραφα PDF. Η προεπιλεγμένη τιμή είναι `false`. |
| [WhitelistedResources](../../groupdocs.viewer.options/loadoptions/whitelistedresources) { get; set; } | Η λίστα των τμημάτων URL που αντιστοιχούν σε εξωτερικούς πόρους που πρέπει να φορτωθούν όταν το [`SkipExternalResources`](./skipexternalresources) είναι ορισμένο σε `true`. |

### Δείτε επίσης

* namespace [GroupDocs.Viewer.Options](../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../)

<!-- ΜΗΝ ΕΠΕΞΕΡΓΑΣΕΤΕ: δημιουργήθηκε από το xmldocmd για το GroupDocs.Viewer.dll -->
