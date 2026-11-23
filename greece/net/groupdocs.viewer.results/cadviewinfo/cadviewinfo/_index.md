---
title: "CadViewInfo"
second_title: "Αναφορά API του GroupDocs.Viewer for .NET"
description: "Αρχικοποιεί νέα παρουσία της κλάσης CadViewInfogroupdocs.viewer.results/cadviewinfo."
type: docs
weight: 10
url: /el/net/groupdocs.viewer.results/cadviewinfo/cadviewinfo/
---

## CadViewInfo constructor

Αρχικοποιεί νέα παρουσία της κλάσης [`CadViewInfo`](../../cadviewinfo).

```csharp
public CadViewInfo(FileType fileType, List<Page> pages, List<Layer> layers, List<Layout> layouts)
```

| Παράμετρος | Type | Περιγραφή |
| --- | --- | --- |
| fileType | FileType | Ο τύπος του αρχείου. |
| σελίδες | List`1 | Η λίστα των σελίδων προς προβολή. |
| layers | List`1 | Η λίστα των επιπέδων που περιέχονται στο σχέδιο CAD. |
| layouts | List`1 | Η λίστα των επιπέδων που περιέχονται στο σχέδιο CAD. |

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| ArgumentNullException | Εκτοπίζεται όταν το *fileType* είναι null. |
| ArgumentNullException | Ρίχνεται όταν *pages* είναι null. |
| ArgumentNullException | Εκτοπίζεται όταν το *layers* είναι null. |
| ArgumentNullException | Εκτοπίζεται όταν το *layouts* είναι null. |

### Δείτε επίσης

* class [FileType](../../../groupdocs.viewer/filetype)
* class [Page](../../page)
* class [Layer](../../layer)
* class [Layout](../../layout)
* class [CadViewInfo](../../cadviewinfo)
* namespace [GroupDocs.Viewer.Results](../../../groupdocs.viewer.results)
* assembly [GroupDocs.Viewer](../../../)

<!-- ΜΗΝ ΕΠΕΞΕΡΓΑΣΕΤΕ: δημιουργήθηκε από το xmldocmd για το GroupDocs.Viewer.dll -->
