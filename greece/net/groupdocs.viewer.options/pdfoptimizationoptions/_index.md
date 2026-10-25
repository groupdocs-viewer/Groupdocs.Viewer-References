---
title: "PdfOptimizationOptions"
second_title: "Αναφορά API του GroupDocs.Viewer for .NET"
description: "Περιέχει τις επιλογές βελτιστοποίησης PDF που θα εφαρμοστούν στο αρχείο PDF εξόδου. Για λεπτομέρειες και παραδείγματα κώδικα δείτε αυτή τη σελίδα https//docs.groupdocs.com/viewer/net/optimizationpdfoptions/ και τα υποσέλφια της."
type: docs
weight: 400
url: /el/net/groupdocs.viewer.options/pdfoptimizationoptions/
---

## PdfOptimizationOptions class

Περιέχει τις επιλογές βελτιστοποίησης PDF που εφαρμόζονται στο αρχείο PDF εξόδου. Για λεπτομέρειες και παραδείγματα κώδικα, δείτε αυτή τη [σελίδα](https://docs.groupdocs.com/viewer/net/optimization-pdf-options/) και τα υπο-στοιχεία της.

```csharp
public class PdfOptimizationOptions
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [PdfOptimizationOptions](pdfoptimizationoptions)() | Ορίζει τις προεπιλεγμένες τιμές της επιλογής MaxResolution σε 300 και της επιλογής ImageQuality σε 100. |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [CompressImages](../../groupdocs.viewer.options/pdfoptimizationoptions/compressimages) { get; set; } | Ενεργοποιεί τη συμπίεση εικόνων στο αρχείο PDF εξόδου. |
| [ConvertToGrayScale](../../groupdocs.viewer.options/pdfoptimizationoptions/converttograyscale) { get; set; } | Ενεργοποιεί τη μετατροπή του αρχείου PDF εξόδου σε αποχρώσεις του γκρι. |
| [ImageQuality](../../groupdocs.viewer.options/pdfoptimizationoptions/imagequality) { get; set; } | Ορίζει την ποιότητα εικόνας στο αρχείο PDF εξόδου (σε ποσοστό). |
| [Lineriaze](../../groupdocs.viewer.options/pdfoptimizationoptions/lineriaze) { get; set; } | Ενεργοποιεί τη βελτιστοποίηση του αρχείου PDF εξόδου για προβολή online με έναν web browser. |
| [MaxResolution](../../groupdocs.viewer.options/pdfoptimizationoptions/maxresolution) { get; set; } | Ορίζει τη μέγιστη ανάλυση στο αρχείο PDF εξόδου. |
| [OptimizeSpreadsheets](../../groupdocs.viewer.options/pdfoptimizationoptions/optimizespreadsheets) { get; set; } | Ενεργοποιεί τη βελτιστοποίηση των υπολογιστικών φύλλων στα αρχεία PDF. |
| [RemoveAnnotations](../../groupdocs.viewer.options/pdfoptimizationoptions/removeannotations) { get; set; } | Ενεργοποιεί την αφαίρεση σχολίων από το αρχείο PDF εξόδου. |
| [RemoveFormFields](../../groupdocs.viewer.options/pdfoptimizationoptions/removeformfields) { get; set; } | Επιτρέπει την αφαίρεση πεδίων φόρμας από ένα αρχείο PDF. |
| [RemoveUnusedObjects](../../groupdocs.viewer.options/pdfoptimizationoptions/removeunusedobjects) { get; set; } | Αφαιρεί αχρησιμοποίητα (ορφανά) αντικείμενα από ένα αρχείο PDF, τα οποία τοποθετούνται στο έγγραφο PDF, αλλά δεν αναφέρονται από τα λεξικά πόρων καμίας σελίδας και έτσι δεν χρησιμοποιούνται καθόλου. Η ενεργοποίηση αυτής της ιδιότητας (`true`) θα μειώσει το μέγεθος του παραγόμενου εγγράφου PDF. Από προεπιλογή είναι απενεργοποιημένη (`false`). |
| [RemoveUnusedStreams](../../groupdocs.viewer.options/pdfoptimizationoptions/removeunusedstreams) { get; set; } | Αφαιρεί αχρησιμοποίητες (ορφανές) ροές από ένα αρχείο PDF, οι οποίες εξακολουθούν να αναφέρονται από το λεξικό πόρων της σελίδας, αλλά στην πραγματικότητα δεν χρησιμοποιούνται ποτέ στο περιεχόμενο της σελίδας. Από προεπιλογή είναι απενεργοποιημένη (`false`), η ενεργοποίησή της (`true`) θα μειώσει το μέγεθος του παραγόμενου εγγράφου PDF. |
| [ResizeImages](../../groupdocs.viewer.options/pdfoptimizationoptions/resizeimages) { get; set; } | Επιτρέπει τον ορισμό της μέγιστης ανάλυσης στο παραγόμενο αρχείο PDF. |
| [SubsetFonts](../../groupdocs.viewer.options/pdfoptimizationoptions/subsetfonts) { get; set; } | Δημιουργεί υποσύνολα γραμματοσειρών στο παραγόμενο αρχείο PDF. |

### Δείτε επίσης

* namespace [GroupDocs.Viewer.Options](../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../)

<!-- ΜΗΝ ΕΠΕΞΕΡΓΑΣΕΤΕ: δημιουργήθηκε από το xmldocmd για το GroupDocs.Viewer.dll -->
