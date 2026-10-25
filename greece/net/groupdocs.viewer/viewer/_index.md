---
title: "Προβολέας"
second_title: "Αναφορά API του GroupDocs.Viewer for .NET"
description: "Αντιπροσωπεύει την κύρια κλάση που ελέγχει τη διαδικασία απόδοσης εγγράφων."
type: docs
weight: 50
url: /el/net/groupdocs.viewer/viewer/
---

## Viewer class

Αντιπροσωπεύει την κύρια κλάση που ελέγχει τη διαδικασία απόδοσης εγγράφων.

```csharp
public class Viewer : IDisposable
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [Viewer](viewer#constructor)(Func&lt;Stream&gt;) | Αρχικοποιεί νέα παρουσία της κλάσης [`Viewer`](../viewer). |
| [Viewer](viewer#constructor_4)(Stream) | Αρχικοποιεί νέα παρουσία της κλάσης [`Viewer`](../viewer). |
| [Viewer](viewer#constructor_12)(string) | Αρχικοποιεί νέα παρουσία της κλάσης [`Viewer`](../viewer). |
| [Viewer](viewer#constructor_2)(Func&lt;Stream&gt;, Func&lt;LoadOptions&gt;) | Αρχικοποιεί νέα παρουσία της κλάσης [`Viewer`](../viewer). |
| [Viewer](viewer#constructor_1)(Func&lt;Stream&gt;, ViewerSettings) | Αρχικοποιεί νέα παρουσία της κλάσης [`Viewer`](../viewer). |
| [Viewer](viewer#constructor_5)(Stream, bool) | Αρχικοποιεί νέα παρουσία της κλάσης [`Viewer`](../viewer). |
| [Viewer](viewer#constructor_6)(Stream, LoadOptions) | Αρχικοποιεί νέα παρουσία της κλάσης [`Viewer`](../viewer). |
| [Viewer](viewer#constructor_10)(Stream, ViewerSettings) | Αρχικοποιεί νέα παρουσία της κλάσης [`Viewer`](../viewer). |
| [Viewer](viewer#constructor_13)(string, LoadOptions) | Αρχικοποιεί νέα παρουσία της κλάσης [`Viewer`](../viewer). |
| [Viewer](viewer#constructor_15)(string, ViewerSettings) | Αρχικοποιεί νέα παρουσία της κλάσης [`Viewer`](../viewer). |
| [Viewer](viewer#constructor_3)(Func&lt;Stream&gt;, Func&lt;LoadOptions&gt;, ViewerSettings) | Αρχικοποιεί νέα παρουσία της κλάσης [`Viewer`](../viewer). |
| [Viewer](viewer#constructor_7)(Stream, LoadOptions, bool) | Αρχικοποιεί νέα παρουσία της κλάσης [`Viewer`](../viewer). |
| [Viewer](viewer#constructor_8)(Stream, LoadOptions, ViewerSettings) | Αρχικοποιεί νέα παρουσία της κλάσης [`Viewer`](../viewer). |
| [Viewer](viewer#constructor_11)(Stream, ViewerSettings, bool) | Αρχικοποιεί νέα παρουσία της κλάσης [`Viewer`](../viewer). |
| [Viewer](viewer#constructor_14)(string, LoadOptions, ViewerSettings) | Αρχικοποιεί νέα παρουσία της κλάσης [`Viewer`](../viewer). |
| [Viewer](viewer#constructor_9)(Stream, LoadOptions, ViewerSettings, bool) | Αρχικοποιεί νέα παρουσία της κλάσης [`Viewer`](../viewer). |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [Dispose](../../groupdocs.viewer/viewer/dispose)() | Αποδεσμεύει τη ροή αρχείου και τους διαχειριζόμενους εσωτερικούς πόρους. |
| [GetAllFonts](../../groupdocs.viewer/viewer/getallfonts)() | Επιστρέφει όλες τις γραμματοσειρές που χρησιμοποιούνται στα φορτωμένα έγγραφα, συμπεριλαμβανομένων εκείνων που είναι ενσωματωμένες μέσα στο ίδιο το έγγραφο και των γραμματοσειρών συστήματος που είναι εγκατεστημένες στο λειτουργικό σύστημα και χρησιμοποιούνται στο έγγραφο. |
| [GetAttachments](../../groupdocs.viewer/viewer/getattachments#getattachments)() | Επιστρέφει τα συνημμένα που περιέχονται στο έγγραφο. |
| [GetAttachments](../../groupdocs.viewer/viewer/getattachments#getattachments_1)(CancellationToken) | Επιστρέφει τα συνημμένα που περιέχονται στο έγγραφο. |
| [GetFileInfo](../../groupdocs.viewer/viewer/getfileinfo)() | Επιστρέφει πληροφορίες για το αρχείο, όπως τύπο αρχείου και σημαία που υποδεικνύει αν το αρχείο είναι κρυπτογραφημένο. |
| [GetViewInfo](../../groupdocs.viewer/viewer/getviewinfo#getviewinfo)(ViewInfoOptions) | Επιστρέφει πληροφορίες σχετικά με την προβολή και συγκεκριμένες πληροφορίες εγγράφου. |
| [GetViewInfo](../../groupdocs.viewer/viewer/getviewinfo#getviewinfo_1)(ViewInfoOptions, CancellationToken) | Επιστρέφει πληροφορίες σχετικά με την προβολή και συγκεκριμένες πληροφορίες εγγράφου. |
| [SaveAttachment](../../groupdocs.viewer/viewer/saveattachment#saveattachment)(Attachment, Stream) | Αποθηκεύει το αρχείο συνημμένου στη ροή *προορισμού*. |
| [SaveAttachment](../../groupdocs.viewer/viewer/saveattachment#saveattachment_1)(Attachment, Stream, CancellationToken) | Αποθηκεύει το αρχείο συνημμένου στη ροή *προορισμού*. |
| [Search](../../groupdocs.viewer/viewer/search)(SearchHighlightOptions) | Εκτελεί αναζήτηση κειμένου και την επισήμανσή του (αν βρεθεί) στο φορτωμένο έγγραφο σύμφωνα με τις φορτωμένες επιλογές. |
| [View](../../groupdocs.viewer/viewer/view#view)(ViewOptions) | Δημιουργεί προβολή όλων των σελίδων του εγγράφου. |
| [View](../../groupdocs.viewer/viewer/view#view_2)(ViewOptions, CancellationToken) | Δημιουργεί προβολή όλων των σελίδων του εγγράφου. |
| [View](../../groupdocs.viewer/viewer/view#view_1)(ViewOptions, params int[]) | Δημιουργεί προβολή συγκεκριμένων σελίδων του εγγράφου. |
| [View](../../groupdocs.viewer/viewer/view#view_3)(ViewOptions, CancellationToken, params int[]) | Δημιουργεί προβολή συγκεκριμένων σελίδων του εγγράφου. |

### Δείτε επίσης

* namespace [GroupDocs.Viewer](../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../)

<!-- ΜΗΝ ΕΠΕΞΕΡΓΑΣΕΤΕ: δημιουργήθηκε από το xmldocmd για το GroupDocs.Viewer.dll -->
