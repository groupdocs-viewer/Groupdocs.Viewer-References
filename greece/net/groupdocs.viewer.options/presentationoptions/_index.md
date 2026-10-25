---
title: "PresentationOptions"
second_title: "Αναφορά API του GroupDocs.Viewer for .NET"
description: "Περιέχει επιλογές για την απόδοση παρουσιάσεων. Για λεπτομέρειες, δείτε την τεκμηρίωση https//docs.groupdocs.com/viewer/net/renderpresentations/."
type: docs
weight: 460
url: /el/net/groupdocs.viewer.options/presentationoptions/
---

## PresentationOptions class

Περιέχει επιλογές για την απόδοση παρουσιάσεων. Για λεπτομέρειες, δείτε την [τεκμηρίωση](https://docs.groupdocs.com/viewer/net/render-presentations/).

```csharp
public class PresentationOptions
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [PresentationOptions](presentationoptions)() | Ο προεπιλεγμένος κατασκευαστής. |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [RenderHeaderFooterPlaceholders](../../groupdocs.viewer.options/presentationoptions/renderheaderfooterplaceholders) { get; set; } | Ενεργοποιεί την απόδοση των δεσμευτικών θέσεων στην κεφαλίδα και το υποσέλιδο μιας διαφάνειας. Απενεργοποιημένο από προεπιλογή (`false`). Αυτή η επιλογή ισχύει για όλες τις 4 λειτουργίες απόδοσης παρουσιάσεων: HTML, PDF, PNG και JPEG. Δεν εφαρμόζεται όταν η παρουσίαση αποδίδεται σε καθαρό HTML/CSS markup χρησιμοποιώντας το [`RenderToPureHtml`](./rendertopurehtml). |
| [RenderToPureHtml](../../groupdocs.viewer.options/presentationoptions/rendertopurehtml) { get; set; } | Ενεργοποιεί μια νέα λειτουργία απόδοσης HTML για τα έγγραφα Presentation — σε αυτή τη λειτουργία τα αρχεία Presentation αποδίδονται σε **pure HTML/CSS markup**, χωρίς εικόνες SVG. Από προεπιλογή είναι απενεργοποιημένο (`false`) — χρησιμοποιείται ο υπάρχων HTML-renderer βασισμένος σε SVG. |
| [Resolution](../../groupdocs.viewer.options/presentationoptions/resolution) { get; set; } | Ανάλυση των εικόνων παρουσίασης (μόνο για απόδοση σε HTML/PDF). |

### Δείτε επίσης

* namespace [GroupDocs.Viewer.Options](../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../)

<!-- ΜΗΝ ΕΠΕΞΕΡΓΑΣΕΤΕ: δημιουργήθηκε από το xmldocmd για το GroupDocs.Viewer.dll -->
