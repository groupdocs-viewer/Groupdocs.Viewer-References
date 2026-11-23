---
title: "PdfFontInfo"
second_title: "Αναφορά API του GroupDocs.Viewer for .NET"
description: "Περιλαμβάνει μεταπληροφορίες και δυαδικά δεδομένα μιας γραμματοσειράς από το PDF έγγραφο που φορτώθηκε στην παρουσίαση Viewer../groupdocs.viewer/viewer. Αυτή η γραμματοσειρά χρησιμοποιείται στο περιεχόμενο του εγγράφου και είναι ενσωματωμένη μέσα στο έγγραφο ή εγκατεστημένη στο λειτουργικό σύστημα όπου εκτελείται το GroupDocs.Viewer."
type: docs
weight: 840
url: /el/net/groupdocs.viewer.fonts/pdffontinfo/
---

## PdfFontInfo structure

Περιλαμβάνει μεταπληροφορίες και δυαδικά δεδομένα μιας γραμματοσειράς από το PDF έγγραφο, φορτωμένο στην παρουσίαση [`Viewer`](../../groupdocs.viewer/viewer). Αυτή η γραμματοσειρά χρησιμοποιείται στο περιεχόμενο του εγγράφου και είναι ενσωματωμένη μέσα στο έγγραφο ή εγκατεστημένη στο λειτουργικό σύστημα, όπου εκτελείται το GroupDocs.Viewer.

```csharp
public struct PdfFontInfo : IFontInfo
```

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [Content](../../groupdocs.viewer.fonts/pdffontinfo/content) { get; } | Περιεχόμενο αυτής της γραμματοσειράς ως πίνακας byte. Εάν υπάρχουν μόνο μεταπληροφορίες για αυτήν τη γραμματοσειρά, αλλά το δυαδικό της περιεχόμενο δεν είναι διαθέσιμο, αυτή η ιδιότητα επιστρέφει `null`. |
| [FamilyName](../../groupdocs.viewer.fonts/pdffontinfo/familyname) { get; } | Όνομα οικογένειας της γραμματοσειράς, χωρίς στυλ, ποτέ δεν είναι null ή κενή συμβολοσειρά. |
| [Format](../../groupdocs.viewer.fonts/pdffontinfo/format) { get; } | Μορφή αυτής της γραμματοσειράς. Τα έγγραφα μπορεί να χρησιμοποιούν γραμματοσειρές στις ακόλουθες μορφές: TrueType, TrueType Collection, OpenType, Embedded OpenType. Εάν υπάρχουν μόνο μεταπληροφορίες για αυτήν τη γραμματοσειρά, αλλά το δυαδικό της περιεχόμενο δεν είναι διαθέσιμο, αυτή η ιδιότητα επιστρέφει τιμή Unknown. |
| [IsEmbedded](../../groupdocs.viewer.fonts/pdffontinfo/isembedded) { get; } | Δείχνει αν αυτή η γραμματοσειρά είναι ενσωματωμένη μέσα στο έγγραφο PDF, φορτωμένη στην [`Viewer`](../../groupdocs.viewer/viewer) παρουσία (`true`), ή όχι. |
| [IsInstalled](../../groupdocs.viewer.fonts/pdffontinfo/isinstalled) { get; } | Δείχνει αν αυτή η γραμματοσειρά είναι παρούσα (εγκατεστημένη) στο λειτουργικό σύστημα, όπου εκτελείται το GroupDocs.Viewer |
| [Style](../../groupdocs.viewer.fonts/pdffontinfo/style) { get; } | Στυλ της γραμματοσειράς — μπορεί να είναι Regular, Bold, Italic ή Bold Italic. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [SerializeToCss](../../groupdocs.viewer.fonts/pdffontinfo/serializetocss)(TextWriter) | Σειριοποιεί αυτές τις πληροφορίες γραμματοσειράς ως κανόνα @font-face και τις γράφει στον καθορισμένο συγγραφέα κειμένου. |

### Δείτε επίσης

* interface [IFontInfo](../ifontinfo)
* namespace [GroupDocs.Viewer.Fonts](../../groupdocs.viewer.fonts)
* assembly [GroupDocs.Viewer](../../)

<!-- ΜΗΝ ΕΠΕΞΕΡΓΑΣΕΤΕ: δημιουργήθηκε από το xmldocmd για το GroupDocs.Viewer.dll -->
