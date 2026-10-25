---
title: "DisableCopyProtection"
second_title: "Αναφορά API του GroupDocs.Viewer for .NET"
description: "Απενεργοποιεί την προστασία αντιγραφής περιεχομένου κατά την απόδοση σε HTML."
type: docs
weight: 30
url: /el/net/groupdocs.viewer.options/pdfoptions/disablecopyprotection/
---

## PdfOptions.DisableCopyProtection property

Απενεργοποιεί την προστασία αντιγραφής περιεχομένου κατά την απόδοση σε HTML.

```csharp
public bool DisableCopyProtection { get; set; }
```

### Παρατηρήσεις

Κατά την απόδοση αρχείων PDF με προστασία κατά της αντιγραφής κειμένου και εικόνων σε HTML, το GroupDocs.Viewer προσθέτει ένα χαρακτηριστικό HTML 'inert' στην ετικέτα HTML BODY. Η προεπιλεγμένη τιμή αυτής της επιλογής είναι `false`, υποδεικνύοντας ότι το χαρακτηριστικό HTML 'intent' προστίθεται μόνο εάν το έγγραφο PDF είναι προστατευμένο.

Για παράδειγμα κώδικα, δείτε την [τεκμηρίωση](https://docs.groupdocs.com/viewer/net/render-pdf-documents/#disable-copy-protection).

### Δείτε επίσης

* class [PdfOptions](../../pdfoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

<!-- ΜΗΝ ΕΠΕΞΕΡΓΑΣΕΤΕ: δημιουργήθηκε από το xmldocmd για το GroupDocs.Viewer.dll -->
