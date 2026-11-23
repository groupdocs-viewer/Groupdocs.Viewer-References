---
title: "TryRepair"
second_title: "Αναφορά API του GroupDocs.Viewer for .NET"
description: "Όταν είναι ενεργοποιημένο, το GroupDocs.Viewer προσπαθεί να επισκευάσει τη δομική αλλοίωση σε έγγραφα PDF. Η προεπιλεγμένη τιμή είναι ψευδής."
type: docs
weight: 80
url: /el/net/groupdocs.viewer.options/loadoptions/tryrepair/
---

## LoadOptions.TryRepair property

Όταν είναι ενεργοποιημένο, το GroupDocs.Viewer προσπαθεί να επισκευάσει δομική αλλοίωση σε έγγραφα PDF. Η προεπιλεγμένη τιμή είναι `false`.

```csharp
public bool TryRepair { get; set; }
```

### Παρατηρήσεις

Αυτή η λειτουργία αντιμετωπίζει τα ακόλουθα ζητήματα σε ένα έγγραφο PDF:

* Broken references within the document (incorrect object offsets in the Cross-reference list).
* Missing critical elements like root object, page object, or page content.
* Circular references (Form X-object referencing itself).

### Δείτε επίσης

* class [LoadOptions](../../loadoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

<!-- ΜΗΝ ΕΠΕΞΕΡΓΑΣΕΤΕ: δημιουργήθηκε από το xmldocmd για το GroupDocs.Viewer.dll -->
