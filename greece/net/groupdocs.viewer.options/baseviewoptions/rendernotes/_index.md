---
title: "RenderNotes"
second_title: "Αναφορά API του GroupDocs.Viewer for .NET"
description: "Ενεργοποιεί την απόδοση σημειώσεων και σχολίων για ορισμένες μορφές."
type: docs
weight: 120
url: /el/net/groupdocs.viewer.options/baseviewoptions/rendernotes/
---

## BaseViewOptions.RenderNotes property

Ενεργοποιεί την απόδοση σημειώσεων και σχολίων για ορισμένες μορφές.

```csharp
public bool RenderNotes { get; set; }
```

### Παρατηρήσεις

Ορισμένες μορφές, όπως παρουσιάσεις ή αρχεία Microsoft Project, ενδέχεται να περιέχουν σημειώσεις. Επίσης, τα αρχεία PDF μπορεί να έχουν αναδυόμενες σημειώσεις (baloon hints), που είναι κρυμμένες από προεπιλογή και είναι ορατές σε έναν προβολέα PDF μόνο όταν δείχνετε τον κέρσορα του ποντικιού πάνω τους. Από προεπιλογή, το GroupDocs.Viewer δεν αποδίδει τέτοιες σημειώσεις και επεξηγήσεις (`false`). Για να το κάνετε αυτό, ορίστε αυτήν την ιδιότητα σε `true`.

Για παράδειγμα κώδικα, δείτε την [τεκμηρίωση](https://docs.groupdocs.com/viewer/net/render-presentations/#render-speaker-notes).

### Δείτε επίσης

* class [BaseViewOptions](../../baseviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

<!-- ΜΗΝ ΕΠΕΞΕΡΓΑΣΕΤΕ: δημιουργήθηκε από το xmldocmd για το GroupDocs.Viewer.dll -->
