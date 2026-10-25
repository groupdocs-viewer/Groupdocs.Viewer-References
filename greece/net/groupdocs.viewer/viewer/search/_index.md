---
title: "Search"
second_title: "Αναφορά API του GroupDocs.Viewer for .NET"
description: "Εκτελεί αναζήτηση κειμένου και την επισήμανσή της εάν βρεθεί στο φορτωμένο έγγραφο σύμφωνα με τις φορτωμένες επιλογές"
type: docs
weight: 80
url: /el/net/groupdocs.viewer/viewer/search/
---

## Viewer.Search method

Εκτελεί αναζήτηση κειμένου και την επισήμανσή του (αν βρεθεί) στο φορτωμένο έγγραφο σύμφωνα με τις φορτωμένες επιλογές.

```csharp
public void Search(SearchHighlightOptions options)
```

| Παράμετρος | Type | Περιγραφή |
| --- | --- | --- |
| options | SearchHighlightOptions | Επιλογές αναζήτησης και επισήμανσης, περιλαμβάνει μια φράση κειμένου για αναζήτηση. Δεν μπορεί να είναι `null`. |

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| ArgumentNullException | Εκτοπίζεται όταν το όρισμα *options* είναι `null` |

### Δείτε επίσης

* class [SearchHighlightOptions](../../../groupdocs.viewer.options/searchhighlightoptions)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

<!-- ΜΗΝ ΕΠΕΞΕΡΓΑΣΕΤΕ: δημιουργήθηκε από το xmldocmd για το GroupDocs.Viewer.dll -->
