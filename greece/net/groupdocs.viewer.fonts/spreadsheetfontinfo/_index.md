---
title: "SpreadsheetFontInfo"
second_title: "Αναφορά API του GroupDocs.Viewer for .NET"
description: "Περιέχει μεταπληροφορίες και δυαδικά δεδομένα μιας γραμματοσειράς από το έγγραφο Spreadsheet, φορτωμένο στην παρουσία Viewer../groupdocs.viewer/viewer. Τα έγγραφα Spreadsheet δεν μπορούν να έχουν ενσωματωμένες γραμματοσειρές, έτσι αυτή η συγκεκριμένη γραμματοσειρά, εάν επιστράφηκε από τη μέθοδο GetAllFonts../groupdocs.viewer/viewer/getallfonts, είναι εγκατεστημένη στο λειτουργικό σύστημα όπου εκτελείται το GroupDocs.Viewer."
type: docs
weight: 870
url: /el/net/groupdocs.viewer.fonts/spreadsheetfontinfo/
---

## SpreadsheetFontInfo structure

Περιέχει μεταπληροφορίες και δυαδικά δεδομένα μιας γραμματοσειράς από το έγγραφο Spreadsheet, φορτωμένο στην παρουσία [`Viewer`](../../groupdocs.viewer/viewer). Τα έγγραφα Spreadsheet δεν μπορούν να έχουν ενσωματωμένες γραμματοσειρές, έτσι αυτή η συγκεκριμένη γραμματοσειρά, εάν επιστράφηκε από τη μέθοδο [`GetAllFonts`](../../groupdocs.viewer/viewer/getallfonts), είναι εγκατεστημένη στο λειτουργικό σύστημα, όπου εκτελείται το GroupDocs.Viewer.

```csharp
public struct SpreadsheetFontInfo : IFontInfo
```

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [Charset](../../groupdocs.viewer.fonts/spreadsheetfontinfo/charset) { get; } | Σύνολο χαρακτήρων αυτής της γραμματοσειράς |
| [Color](../../groupdocs.viewer.fonts/spreadsheetfontinfo/color) { get; } | Χρώμα αυτής της γραμματοσειράς |
| [Content](../../groupdocs.viewer.fonts/spreadsheetfontinfo/content) { get; } | Περιεχόμενο αυτής της γραμματοσειράς ως πίνακας byte. Εάν υπάρχουν μόνο μεταπληροφορίες για αυτήν τη γραμματοσειρά, αλλά το δυαδικό της περιεχόμενο δεν είναι διαθέσιμο, αυτή η ιδιότητα επιστρέφει `null`. |
| [FamilyName](../../groupdocs.viewer.fonts/spreadsheetfontinfo/familyname) { get; } | Όνομα οικογένειας της γραμματοσειράς, χωρίς στυλ, ποτέ δεν είναι null ή κενή συμβολοσειρά. |
| [Format](../../groupdocs.viewer.fonts/spreadsheetfontinfo/format) { get; } | Μορφή αυτής της γραμματοσειράς |
| [IsStrikeout](../../groupdocs.viewer.fonts/spreadsheetfontinfo/isstrikeout) { get; } | Δείχνει εάν η γραμματοσειρά έχει μονή διαγράμμιση |
| [IsUnderline](../../groupdocs.viewer.fonts/spreadsheetfontinfo/isunderline) { get; } | Δείχνει εάν η γραμματοσειρά έχει υπογράμμιση |
| [Style](../../groupdocs.viewer.fonts/spreadsheetfontinfo/style) { get; } | Στυλ αυτής της γραμματοσειράς — μπορεί να είναι Regular, Bold, Italic ή Bold Italic |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [SerializeToCss](../../groupdocs.viewer.fonts/spreadsheetfontinfo/serializetocss)(TextWriter) | Σειριοποιεί αυτές τις πληροφορίες γραμματοσειράς ως κανόνα @font-face και τις γράφει στον καθορισμένο συγγραφέα κειμένου. |

### Δείτε επίσης

* interface [IFontInfo](../ifontinfo)
* namespace [GroupDocs.Viewer.Fonts](../../groupdocs.viewer.fonts)
* assembly [GroupDocs.Viewer](../../)

<!-- ΜΗΝ ΕΠΕΞΕΡΓΑΣΕΤΕ: δημιουργήθηκε από το xmldocmd για το GroupDocs.Viewer.dll -->
