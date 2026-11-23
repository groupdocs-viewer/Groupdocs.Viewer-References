---
title: "IFontInfo"
second_title: "Αναφορά API του GroupDocs.Viewer for .NET"
description: "Κοινή διεπαφή για όλες τις γραμματοσειρές που μπορούν να εξαχθούν από όλες τις υποστηριζόμενες οικογένειες μορφών εγγράφων PDF, WordProcessing, Spreadsheet και Presentation."
type: docs
weight: 820
url: /el/net/groupdocs.viewer.fonts/ifontinfo/
---

## IFontInfo interface

Κοινή διεπαφή για όλες τις γραμματοσειρές, η οποία μπορεί να εξαχθεί από όλες τις υποστηριζόμενες οικογένειες μορφών εγγράφων: PDF, WordProcessing, Spreadsheet και Presentation.

```csharp
public interface IFontInfo
```

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [Content](../../groupdocs.viewer.fonts/ifontinfo/content) { get; } | Δυαδικό περιεχόμενο της γραμματοσειράς ως πίνακας byte, εάν είναι διαθέσιμο, ή `null`, εάν όχι. |
| [FamilyName](../../groupdocs.viewer.fonts/ifontinfo/familyname) { get; } | Όνομα οικογένειας της γραμματοσειράς ως συμβολοσειρά. |
| [Format](../../groupdocs.viewer.fonts/ifontinfo/format) { get; } | Μορφή αυτής της γραμματοσειράς ως enum — TrueType, TrueType Collection, OpenType, Embedded OpenType ή Unknown. |
| [Style](../../groupdocs.viewer.fonts/ifontinfo/style) { get; } | Στυλ της γραμματοσειράς ως enum — Regular, Bold, Italic ή Bold Italic. Ορισμένες μορφές εγγράφων μπορεί να έχουν γραμματοσειρές μόνο με στυλ [`Regular`](../fontstyles/regular). |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [SerializeToCss](../../groupdocs.viewer.fonts/ifontinfo/serializetocss)(TextWriter) | Σειριοποιεί αυτές τις πληροφορίες γραμματοσειράς ως κανόνα @font-face και τις γράφει στον καθορισμένο συγγραφέα κειμένου. |

### Δείτε επίσης

* namespace [GroupDocs.Viewer.Fonts](../../groupdocs.viewer.fonts)
* assembly [GroupDocs.Viewer](../../)

<!-- ΜΗΝ ΕΠΕΞΕΡΓΑΣΕΤΕ: δημιουργήθηκε από το xmldocmd για το GroupDocs.Viewer.dll -->
