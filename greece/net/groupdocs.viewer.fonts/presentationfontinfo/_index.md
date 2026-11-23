---
title: "PresentationFontInfo"
second_title: "Αναφορά API του GroupDocs.Viewer for .NET"
description: "Περιέχει μεταπληροφορίες και δυαδικά δεδομένα μιας γραμματοσειράς από το έγγραφο Presentation, φορτωμένο στην παρουσία Viewer../groupdocs.viewer/viewer instance. Αυτή η γραμματοσειρά χρησιμοποιείται στο περιεχόμενο του εγγράφου και είναι ενσωματωμένη μέσα στο ίδιο το έγγραφο ή είναι εγκατεστημένη στο λειτουργικό σύστημα όπου εκτελείται το GroupDocs.Viewer."
type: docs
weight: 850
url: /el/net/groupdocs.viewer.fonts/presentationfontinfo/
---

## PresentationFontInfo structure

Περιέχει μεταπληροφορίες και δυαδικά δεδομένα μιας γραμματοσειράς από το έγγραφο Presentation, φορτωμένο στην παρουσία [`Viewer`](../../groupdocs.viewer/viewer) instance. Αυτή η γραμματοσειρά χρησιμοποιείται στο περιεχόμενο του εγγράφου και είναι ενσωματωμένη μέσα στο ίδιο το έγγραφο ή είναι εγκατεστημένη στο λειτουργικό σύστημα, όπου εκτελείται το GroupDocs.Viewer.

```csharp
public struct PresentationFontInfo : IFontInfo
```

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [Content](../../groupdocs.viewer.fonts/presentationfontinfo/content) { get; } | Περιεχόμενο αυτής της γραμματοσειράς ως πίνακας byte. Εάν υπάρχουν μόνο μεταπληροφορίες για αυτήν τη γραμματοσειρά, αλλά το δυαδικό της περιεχόμενο δεν είναι διαθέσιμο, αυτή η ιδιότητα επιστρέφει `null`. |
| [FamilyName](../../groupdocs.viewer.fonts/presentationfontinfo/familyname) { get; } | Όνομα οικογένειας της γραμματοσειράς, χωρίς στυλ, ποτέ δεν είναι null ή κενή συμβολοσειρά. |
| [Format](../../groupdocs.viewer.fonts/presentationfontinfo/format) { get; } | Μορφή αυτής της γραμματοσειράς. Τα έγγραφα μπορεί να χρησιμοποιούν γραμματοσειρές στις ακόλουθες μορφές: TrueType, TrueType Collection, OpenType, Embedded OpenType. Εάν υπάρχουν μόνο μεταπληροφορίες για αυτήν τη γραμματοσειρά, αλλά το δυαδικό της περιεχόμενο δεν είναι διαθέσιμο, αυτή η ιδιότητα επιστρέφει τιμή Unknown. |
| [IsEmbedded](../../groupdocs.viewer.fonts/presentationfontinfo/isembedded) { get; } | Δείχνει εάν αυτή η γραμματοσειρά είναι ενσωματωμένη μέσα στο έγγραφο, φορτωμένη στην παρουσία [`Viewer`](../../groupdocs.viewer/viewer) (`true`), ή είναι γραμματοσειρά συστήματος (`false`). Τα έγγραφα Spreadsheet δεν μπορούν να περιέχουν ενσωματωμένες γραμματοσειρές, επομένως για αυτά η ιδιότητα πάντα επιστρέφει `false`. |
| [Style](../../groupdocs.viewer.fonts/presentationfontinfo/style) { get; } | Στυλ της γραμματοσειράς — μπορεί να είναι Regular, Bold, Italic ή Bold Italic |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [SerializeToCss](../../groupdocs.viewer.fonts/presentationfontinfo/serializetocss)(TextWriter) | Σειριοποιεί αυτές τις πληροφορίες γραμματοσειράς ως κανόνα @font-face και τις γράφει στον καθορισμένο συγγραφέα κειμένου. |

### Δείτε επίσης

* interface [IFontInfo](../ifontinfo)
* namespace [GroupDocs.Viewer.Fonts](../../groupdocs.viewer.fonts)
* assembly [GroupDocs.Viewer](../../)

<!-- ΜΗΝ ΕΠΕΞΕΡΓΑΣΕΤΕ: δημιουργήθηκε από το xmldocmd για το GroupDocs.Viewer.dll -->
