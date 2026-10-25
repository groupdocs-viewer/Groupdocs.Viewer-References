---
title: "WordProcessingSubstitutedFontInfo"
second_title: "Αναφορά API του GroupDocs.Viewer for .NET"
description: "Περιλαμβάνει μεταπληροφορίες και δυαδικά δεδομένα μιας γραμματοσειράς από έγγραφο WordProcessing που αρχικά δεν χρησιμοποιείται στο έγγραφο που φορτώθηκε στην Viewer../groupdocs.viewer/viewer παρουσία, αλλά λειτουργεί ως γραμματοσειρά αντικατάστασης για εκείνες που δεν μπορούν να βρεθούν στο στόχο μηχάνημα. Οι αντικατασταθείσες γραμματοσειρές υπάρχουν μόνο για την οικογένεια μορφών WordProcessing."
type: docs
weight: 890
url: /el/net/groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/
---

## WordProcessingSubstitutedFontInfo structure

Περιλαμβάνει μεταπληροφορίες και δυαδικά δεδομένα μιας γραμματοσειράς από έγγραφο WordProcessing, που αρχικά δεν χρησιμοποιείται στο έγγραφο που φορτώθηκε στην [`Viewer`](../../groupdocs.viewer/viewer) παρουσία, αλλά λειτουργεί ως γραμματοσειρά αντικατάστασης για εκείνες που δεν μπορούν να βρεθούν στο στόχο μηχάνημα. Οι αντικατασταθείσες γραμματοσειρές υπάρχουν μόνο για την οικογένεια μορφών WordProcessing.

```csharp
public struct WordProcessingSubstitutedFontInfo : IFontInfo
```

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [Content](../../groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/content) { get; } | Περιεχόμενο αυτής της αντικατασταθείσας γραμματοσειράς ως πίνακας byte. Ποτέ δεν είναι `null`. |
| [FamilyName](../../groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/familyname) { get; } | Όνομα οικογένειας της **αντικατασταθείσας** γραμματοσειράς, χωρίς στυλ, ποτέ δεν είναι null ή κενή συμβολοσειρά |
| [Format](../../groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/format) { get; } | Μορφή αυτής της αντικατασταθείσας (μη αρχικής) γραμματοσειράς. Μπορεί να είναι TrueType, TrueType Collection, OpenType, Embedded OpenType. Για την αντικατασταθείσα γραμματοσειρά, επειδή το δυαδικό της περιεχόμενο είναι διαθέσιμο από ορισμού, αυτή η ιδιότητα ποτέ δεν επιστρέφει τιμή Unknown. |
| [OriginalFamilyName](../../groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/originalfamilyname) { get; } | Όνομα οικογένειας της αρχικής γραμματοσειράς, η οποία δεν μπορεί να βρεθεί σε στόχο μηχάνημα, χωρίς στυλ, ποτέ δεν είναι null ή κενή συμβολοσειρά |
| [Style](../../groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/style) { get; } | Στυλ της αρχικής γραμματοσειράς — μπορεί να είναι Regular, Bold, Italic ή Bold Italic. Η αντικατασταθείσα γραμματοσειρά είναι συνήθως (αλλά όχι πάντα) του ίδιου στυλ. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [SerializeToCss](../../groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/serializetocss)(TextWriter) | Σειριοποιεί αυτές τις πληροφορίες γραμματοσειράς ως κανόνα @font-face και τις γράφει στον καθορισμένο συγγραφέα κειμένου. |
| override [ToString](../../groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/tostring)() | Επιστρέφει πληροφορίες αποσφαλμάτωσης για αυτά τα δεδομένα γραμματοσειράς με το παρακάτω πρότυπο: "original-name -&gt; substituted-name style, format" |

### Παρατηρήσεις

Αμετάβλητη δομή. Τα στιγμιότυπά της παράγονται και επιστρέφονται από το δημόσιο API του GroupDocs.Viewer και κανονικά δεν πρέπει να δημιουργούνται από τον χρήστη. Για λεπτομέρειες, δείτε την [documentation](https://docs.groupdocs.com/viewer/net/getting-used-fonts/).

### Δείτε επίσης

* interface [IFontInfo](../ifontinfo)
* namespace [GroupDocs.Viewer.Fonts](../../groupdocs.viewer.fonts)
* assembly [GroupDocs.Viewer](../../)

<!-- ΜΗΝ ΕΠΕΞΕΡΓΑΣΕΤΕ: δημιουργήθηκε από το xmldocmd για το GroupDocs.Viewer.dll -->
