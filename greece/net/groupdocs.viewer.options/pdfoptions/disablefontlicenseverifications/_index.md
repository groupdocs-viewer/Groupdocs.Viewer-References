---
title: "DisableFontLicenseVerifications"
second_title: "Αναφορά API του GroupDocs.Viewer for .NET"
description: "Απενεργοποιεί τυχόν περιορισμούς άδειας για όλες τις γραμματοσειρές στο τρέχον έγγραφο XPS/OXPS."
type: docs
weight: 40
url: /el/net/groupdocs.viewer.options/pdfoptions/disablefontlicenseverifications/
---

## PdfOptions.DisableFontLicenseVerifications property

Απενεργοποιεί τυχόν περιορισμούς άδειας για όλες τις γραμματοσειρές στο τρέχον έγγραφο XPS/OXPS.

```csharp
public bool DisableFontLicenseVerifications { get; set; }
```

### Παρατηρήσεις

Πολλές λειτουργίες με γραμματοσειρά δεν μπορούν να εκτελεστούν εάν απαγορεύονται από την άδεια αυτής της γραμματοσειράς. Για παράδειγμα, ορισμένες γραμματοσειρές δεν μπορούν να ενσωματωθούν σε έγγραφο PDF εάν οι κανόνες άδειας απενεργοποιούν την ενσωμάτωση για αυτή τη γραμματοσειρά. Αυτή η επιλογή σας επιτρέπει να παραλείψετε την επαλήθευση αυτών των κανόνων.

Να είστε προσεκτικοί όταν χρησιμοποιείτε αυτή τη σημαία. Όταν είναι ενεργοποιημένη, σημαίνει ότι το άτομο που τη θέτει αναλαμβάνει όλη την ευθύνη για πιθανές παραβιάσεις άδειας/νόμου. Έτσι το αναλαμβάνει με δικό του ρίσκο. Συνιστάται έντονα να χρησιμοποιείτε αυτή τη σημαία μόνο όταν είστε πλήρως σίγουροι ότι δεν παραβιάζετε το νόμο περί πνευματικών δικαιωμάτων. Η προεπιλεγμένη τιμή είναι `false`.

Για παράδειγμα κώδικα, δείτε την [τεκμηρίωση](https://docs.groupdocs.com/viewer/net/render-pdf-documents/#skip-font-license-verification-when-rendering-xps-and-oxps-files).

### Δείτε επίσης

* class [PdfOptions](../../pdfoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

<!-- ΜΗΝ ΕΠΕΞΕΡΓΑΣΕΤΕ: δημιουργήθηκε από το xmldocmd για το GroupDocs.Viewer.dll -->
