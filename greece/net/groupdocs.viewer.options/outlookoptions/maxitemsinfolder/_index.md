---
title: "MaxItemsInFolder"
second_title: "Αναφορά API του GroupDocs.Viewer for .NET"
description: "Ο μέγιστος αριθμός μηνυμάτων ή στοιχείων που μπορούν να αποδοθούν από έναν φάκελο."
type: docs
weight: 40
url: /el/net/groupdocs.viewer.options/outlookoptions/maxitemsinfolder/
---

## OutlookOptions.MaxItemsInFolder property

Το μέγιστο πλήθος μηνυμάτων ή αντικειμένων που μπορούν να αποδοθούν από έναν φάκελο.

```csharp
public int MaxItemsInFolder { get; set; }
```

### Παρατηρήσεις

Τα αρχεία δεδομένων Outlook μπορεί να είναι μεγάλα και η ανάκτηση όλων των μηνυμάτων μπορεί να διαρκέσει σημαντικό χρόνο. Αυτή η ιδιότητα περιορίζει τον μέγιστο αριθμό μηνυμάτων ή στοιχείων που αποδίδονται. Η προεπιλεγμένη τιμή είναι `50`. Για να αποδοθούν όλα τα μηνύματα, ορίστε την τιμή σε `0`.

Για παράδειγμα κώδικα, δείτε την [τεκμηρίωση](https://docs.groupdocs.com/viewer/net/render-outlook-data-files/#limit-the-number-of-folder-items-to-render).

### Δείτε επίσης

* class [OutlookOptions](../../outlookoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

<!-- ΜΗΝ ΕΠΕΞΕΡΓΑΣΕΤΕ: δημιουργήθηκε από το xmldocmd για το GroupDocs.Viewer.dll -->
