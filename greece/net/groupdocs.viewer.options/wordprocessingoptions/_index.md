---
title: "WordProcessingOptions"
second_title: "Αναφορά API του GroupDocs.Viewer for .NET"
description: "Περιέχει επιλογές για την απόδοση εγγράφων Word. Για λεπτομέρειες, δείτε την τεκμηρίωση https//docs.groupdocs.com/viewer/net/renderworddocuments/."
type: docs
weight: 630
url: /el/net/groupdocs.viewer.options/wordprocessingoptions/
---

## WordProcessingOptions class

Περιέχει επιλογές για την απόδοση εγγράφων Word. Για λεπτομέρειες, δείτε την [τεκμηρίωση](https://docs.groupdocs.com/viewer/net/render-word-documents/).

```csharp
public class WordProcessingOptions : ICloneable, IEquatable<WordProcessingOptions>
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [WordProcessingOptions](wordprocessingoptions)() | Περιέχει επιλογές για την απόδοση εγγράφων επεξεργασίας κειμένου. Για λεπτομέρειες, δείτε την [τεκμηρίωση](https://docs.groupdocs.com/viewer/net/render-word-documents/). |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [BottomMargin](../../groupdocs.viewer.options/wordprocessingoptions/bottommargin) { get; set; } | Ορίζει το κάτω περιθώριο μιας σελίδας. |
| [EnableOpenTypeFeatures](../../groupdocs.viewer.options/wordprocessingoptions/enableopentypefeatures) { get; set; } | Αυτή η επιλογή ενεργοποιεί το kerning και άλλα χαρακτηριστικά OpenType κατά την απόδοση αραβικών, εβραϊκών, ινδικών βασισμένων σε λατινικό αλφάβητο ή κυριλλικών γραφών. |
| [HorizontalResolution](../../groupdocs.viewer.options/wordprocessingoptions/horizontalresolution) { get; set; } | Αποκτά ή ορίζει την οριζόντια ανάλυση για τις παραγόμενες εικόνες σε κουκίδες ανά ίντσα. Αυτή η επιλογή χρησιμοποιείται μόνο κατά την απόδοση εγγράφων WordProcessing σε μορφές PNG ή JPEG. |
| [LeftMargin](../../groupdocs.viewer.options/wordprocessingoptions/leftmargin) { get; set; } | Ορίζει το αριστερό περιθώριο μιας σελίδας. |
| [PageNumberLocation](../../groupdocs.viewer.options/wordprocessingoptions/pagenumberlocation) { get; set; } | Επιτρέπει την εξαναγκαστική εφαρμογή της αρίθμησης σελίδων στο φορτωμένο έγγραφο WordProcessing. Από προεπιλογή είναι NotApply — το έγγραφο παραμένει αμετάβλητο. |
| [PageSize](../../groupdocs.viewer.options/wordprocessingoptions/pagesize) { get; set; } | Το μέγεθος της σελίδας εξόδου. Η προεπιλεγμένη τιμή είναι Unspecified, που σημαίνει ότι χρησιμοποιείται ένα μέγεθος σελίδας που ορίζεται στις ρυθμίσεις σελίδας (Page Setup). Κατά την απόδοση αρχείων HTM και HTML, το προεπιλεγμένο μέγεθος σελίδας ορίζεται σε Letter 792 x 612 σημεία. Ως αποτέλεσμα, ορισμένο περιεχόμενο μπορεί να μην χωράει στο πλαίσιο της σελίδας. Ορίστε μεγαλύτερο μέγεθος σελίδας, π.χ. A3, για να χωρέσει το περιεχόμενο. |
| [RenderTrackedChanges](../../groupdocs.viewer.options/wordprocessingoptions/rendertrackedchanges) { get; set; } | Ενεργοποιεί την απόδοση των παρακολουθούμενων αλλαγών (αναθεωρήσεων). |
| [RightMargin](../../groupdocs.viewer.options/wordprocessingoptions/rightmargin) { get; set; } | Ορίζει το δεξί περιθώριο μιας σελίδας. |
| [TopMargin](../../groupdocs.viewer.options/wordprocessingoptions/topmargin) { get; set; } | Ορίζει το επάνω περιθώριο μιας σελίδας. |
| [UnlinkTableOfContents](../../groupdocs.viewer.options/wordprocessingoptions/unlinktableofcontents) { get; set; } | Κατά την απόδοση σε HTML ή PDF, μπορείτε να ορίσετε αυτήν την επιλογή σε `true` για να απενεργοποιήσετε την πλοήγηση από τον πίνακα περιεχομένων. Για την απόδοση HTML, οι ετικέτες `a` με σχετικούς συνδέσμους θα αντικατασταθούν με ετικέτες `span`, αφαιρώντας τη λειτουργικότητα αλλά διατηρώντας την οπτική εμφάνιση. Για την απόδοση PDF, ο πίνακας περιεχομένων θα αποδοθεί ως απλό κείμενο χωρίς συνδέσμους προς τις ενότητες του εγγράφου. |
| [UpdateFields](../../groupdocs.viewer.options/wordprocessingoptions/updatefields) { get; set; } | Αποκτά ή ορίζει μια τιμή που καθορίζει εάν τα πεδία ορισμένων τύπων πρέπει να ενημερωθούν πριν από την αποθήκευση του εισερχόμενου εγγράφου WordProcessing σε μορφές εξόδου HTML, PDF, PNG ή JPEG. Η προεπιλεγμένη τιμή για αυτήν την ιδιότητα είναι `true` — τα πεδία θα ενημερωθούν πριν από την αποθήκευση. |
| [VerticalResolution](../../groupdocs.viewer.options/wordprocessingoptions/verticalresolution) { get; set; } | Αποκτά ή ορίζει την κάθετη ανάλυση για τις παραγόμενες εικόνες σε κουκίδες ανά ίντσα. Αυτή η επιλογή χρησιμοποιείται μόνο κατά την απόδοση εγγράφων WordProcessing σε μορφές PNG ή JPEG. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [Clone](../../groupdocs.viewer.options/wordprocessingoptions/clone)() | Δημιουργεί και επιστρέφει ένα πλήρες βαθύ αντίγραφο αυτών των επιλογών |
| [Equals](../../groupdocs.viewer.options/wordprocessingoptions/equals#equals)(WordProcessingOptions) | Καθορίζει εάν η συγκεκριμένη παρουσία του [`WordProcessingOptions`](../wordprocessingoptions) είναι ίση με αυτήν |

### Δείτε επίσης

* namespace [GroupDocs.Viewer.Options](../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../)

<!-- ΜΗΝ ΕΠΕΞΕΡΓΑΣΕΤΕ: δημιουργήθηκε από το xmldocmd για το GroupDocs.Viewer.dll -->
