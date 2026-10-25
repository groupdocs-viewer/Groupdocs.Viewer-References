---
title: "IAuxDisposable"
second_title: "Αναφορά API του GroupDocs.Viewer for .NET"
description: "Επεκτείνει το πρότυπο περιβάλλον διεπαφής IDisposable, επιτρέποντας την απόκτηση της τρέχουσας κατάστασης ενός αντικειμένου και την εγγραφή σε γεγονός αποδέσμευσης."
type: docs
weight: 20
url: /el/net/groupdocs.viewer/iauxdisposable/
---

## IAuxDisposable interface

Επεκτείνει τη standard διεπαφή IDisposable, επιτρέπει την λήψη της τρέχουσας κατάστασης ενός αντικειμένου και την εγγραφή στο γεγονός διαγραφής.

```csharp
public interface IAuxDisposable : IDisposable
```

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [IsDisposed](../../groupdocs.viewer/iauxdisposable/isdisposed) { get; } | Δείχνει εάν ένας πόρος έχει ήδη αποδεσμευτεί (`true`) ή όχι (`false`). |

## Γεγονότα

| Όνομα | Περιγραφή |
| --- | --- |
| event [Disposed](../../groupdocs.viewer/iauxdisposable/disposed) | Συμβαίνει όταν το αντικείμενο αποδεσμεύεται, αμέσως μετά την επιτυχή ολοκλήρωση της αποδέσμευσης των πόρων. |

### Δείτε επίσης

* namespace [GroupDocs.Viewer](../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../)

<!-- ΜΗΝ ΕΠΕΞΕΡΓΑΣΕΤΕ: δημιουργήθηκε από το xmldocmd για το GroupDocs.Viewer.dll -->
