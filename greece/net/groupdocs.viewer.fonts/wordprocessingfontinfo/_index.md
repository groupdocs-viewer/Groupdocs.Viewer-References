---
title: "WordProcessingFontInfo"
second_title: "Αναφορά API του GroupDocs.Viewer for .NET"
description: "Περιλαμβάνει μεταπληροφορίες και δυαδικά δεδομένα μιας γραμματοσειράς από το έγγραφο WordProcessing που φορτώθηκε στην Viewer../groupdocs.viewer/viewer παρουσία. Αυτή η γραμματοσειρά χρησιμοποιείται στο περιεχόμενο του εγγράφου και είναι ενσωματωμένη μέσα στο ίδιο το έγγραφο ή είναι εγκατεστημένη στο λειτουργικό σύστημα όπου εκτελείται το GroupDocs.Viewer."
type: docs
weight: 880
url: /el/net/groupdocs.viewer.fonts/wordprocessingfontinfo/
---

## WordProcessingFontInfo structure

Περιέχει μεταπληροφορίες και δυαδικά δεδομένα μιας γραμματοσειράς από το έγγραφο WordProcessing, φορτωμένο στην παρουσία [`Viewer`](../../groupdocs.viewer/viewer) instance. Αυτή η γραμματοσειρά χρησιμοποιείται στο περιεχόμενο του εγγράφου και είναι ενσωματωμένη μέσα στο ίδιο το έγγραφο ή είναι εγκατεστημένη στο λειτουργικό σύστημα, όπου εκτελείται το GroupDocs.Viewer.

```csharp
public struct WordProcessingFontInfo : IFontInfo
```

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [AltFamilyName](../../groupdocs.viewer.fonts/wordprocessingfontinfo/altfamilyname) { get; } | Εναλλακτικό όνομα οικογένειας της γραμματοσειράς. Εάν λείπει, τότε κενή συμβολοσειρά. |
| [Charset](../../groupdocs.viewer.fonts/wordprocessingfontinfo/charset) { get; } | Σύνολο χαρακτήρων αυτής της γραμματοσειράς |
| [Content](../../groupdocs.viewer.fonts/wordprocessingfontinfo/content) { get; } | Περιεχόμενο αυτής της γραμματοσειράς ως πίνακας byte. Εάν υπάρχουν μόνο μεταπληροφορίες για αυτήν τη γραμματοσειρά, αλλά το δυαδικό της περιεχόμενο δεν είναι διαθέσιμο, αυτή η ιδιότητα επιστρέφει `null`. |
| [FamilyName](../../groupdocs.viewer.fonts/wordprocessingfontinfo/familyname) { get; } | Όνομα οικογένειας της γραμματοσειράς, χωρίς στυλ, ποτέ δεν είναι null ή κενή συμβολοσειρά. |
| [Format](../../groupdocs.viewer.fonts/wordprocessingfontinfo/format) { get; } | Μορφή αυτής της γραμματοσειράς. Τα έγγραφα μπορεί να χρησιμοποιούν γραμματοσειρές στις ακόλουθες μορφές: TrueType, TrueType Collection, OpenType, Embedded OpenType. Εάν υπάρχουν μόνο μεταπληροφορίες για αυτήν τη γραμματοσειρά, αλλά το δυαδικό της περιεχόμενο δεν είναι διαθέσιμο, αυτή η ιδιότητα επιστρέφει τιμή Unknown. |
| [IsEmbedded](../../groupdocs.viewer.fonts/wordprocessingfontinfo/isembedded) { get; } | Δείχνει εάν αυτή η γραμματοσειρά είναι ενσωματωμένη μέσα στο έγγραφο, φορτωμένη στην παρουσία [`Viewer`](../../groupdocs.viewer/viewer) (`true`), ή είναι γραμματοσειρά συστήματος (`false`). |
| [Style](../../groupdocs.viewer.fonts/wordprocessingfontinfo/style) { get; } | Στυλ της γραμματοσειράς — μπορεί να είναι Regular, Bold, Italic ή Bold Italic. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [SerializeToCss](../../groupdocs.viewer.fonts/wordprocessingfontinfo/serializetocss)(TextWriter) | Σειριοποιεί αυτές τις πληροφορίες γραμματοσειράς ως κανόνα @font-face και τις γράφει στον καθορισμένο συγγραφέα κειμένου. |
| override [ToString](../../groupdocs.viewer.fonts/wordprocessingfontinfo/tostring)() | Επιστρέφει πληροφορίες αποσφαλμάτωσης για τα δεδομένα αυτής της γραμματοσειράς με το παρακάτω πρότυπο: "name style, embedded/system, format" |

### Παρατηρήσεις

Αμετάβλητη δομή. Τα στιγμιότυπά της παράγονται και επιστρέφονται από το δημόσιο API του GroupDocs.Viewer και κανονικά δεν πρέπει να δημιουργούνται από τον χρήστη. Για λεπτομέρειες, δείτε την [documentation](https://docs.groupdocs.com/viewer/net/getting-used-fonts/).

### Δείτε επίσης

* interface [IFontInfo](../ifontinfo)
* namespace [GroupDocs.Viewer.Fonts](../../groupdocs.viewer.fonts)
* assembly [GroupDocs.Viewer](../../)

<!-- ΜΗΝ ΕΠΕΞΕΡΓΑΣΕΤΕ: δημιουργήθηκε από το xmldocmd για το GroupDocs.Viewer.dll -->
