---
title: "CadOptions"
second_title: "Αναφορά API του GroupDocs.Viewer for .NET"
description: "Περιέχει επιλογές για την απόδοση σχεδίων CAD. Για περισσότερες πληροφορίες και παραδείγματα κώδικα δείτε το Render CAD drawings and models as HTML PDF and image fileshttps//docs.groupdocs.com/viewer/net/rendercaddrawingsandmodels/ και το Specify rendering options for CAD fileshttps//docs.groupdocs.com/viewer/net/specifycadrenderingoptions/."
type: docs
weight: 280
url: /el/net/groupdocs.viewer.options/cadoptions/
---

## CadOptions class

Περιέχει επιλογές για την απόδοση σχεδίων CAD. Για περισσότερες πληροφορίες και παραδείγματα κώδικα, δείτε το [Απόδοση σχεδίων CAD και μοντέλων ως HTML, PDF και αρχεία εικόνας](https://docs.groupdocs.com/viewer/net/render-cad-drawings-and-models/) και το [Καθορισμός επιλογών απόδοσης για αρχεία CAD](https://docs.groupdocs.com/viewer/net/specify-cad-rendering-options/).

```csharp
public class CadOptions
```

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [BackgroundColor](../../groupdocs.viewer.options/cadoptions/backgroundcolor) { get; set; } | Χρώμα φόντου εικόνας. |
| [EnablePerformanceConversionMode](../../groupdocs.viewer.options/cadoptions/enableperformanceconversionmode) { get; set; } | Ορίζοντας αυτή τη σημαία σε `true` ενεργοποιεί μια ειδική λειτουργία μετατροπής προσανατολισμένη στην απόδοση για όλες τις μορφές της οικογένειας CAD — σε αυτή τη λειτουργία η ταχύτητα μετατροπής είναι πολύ πιο γρήγορη, αλλά η ποιότητα των παραγόμενων εγγράφων είναι σημαντικά χειρότερη. Από προεπιλογή είναι απενεργοποιημένη (`false`) — η ποιότητα των παραγόμενων εγγράφων είναι η καλύτερη δυνατή με κόστος στην απόδοση. |
| [Height](../../groupdocs.viewer.options/cadoptions/height) { get; } | Το ύψος του αποτελέσματος εξόδου (σε εικονοστοιχεία). |
| [Layers](../../groupdocs.viewer.options/cadoptions/layers) { get; set; } | Τα επίπεδα σχεδίου CAD που θα αποδοθούν. |
| [LayoutName](../../groupdocs.viewer.options/cadoptions/layoutname) { get; set; } | Το όνομα της συγκεκριμένης διάταξης που θα αποδοθεί. Το όνομα διάταξης είναι ευαίσθητο σε πεζά-κεφαλαία. |
| [Pc3File](../../groupdocs.viewer.options/cadoptions/pc3file) { get; set; } | PC3 - αρχείο ρυθμίσεων εκτυπωτή |
| [RenderLayouts](../../groupdocs.viewer.options/cadoptions/renderlayouts) { get; set; } | Σημαία εάν τα διατάγματα από το έγγραφο CAD πρέπει να αποδοθούν. |
| [ScaleFactor](../../groupdocs.viewer.options/cadoptions/scalefactor) { get; } | Τιμή μεγαλύτερη από 1 μεγεθύνει το αποτέλεσμα εξόδου· τιμή μεταξύ 0 και 1 μειώνει το αποτέλεσμα εξόδου. |
| [Tiles](../../groupdocs.viewer.options/cadoptions/tiles) { get; set; } | Οι περιοχές σχεδίασης που θα αποδοθούν. |
| [Width](../../groupdocs.viewer.options/cadoptions/width) { get; } | Το πλάτος του αποτελέσματος εξόδου (σε εικονοστοιχεία). |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| static [ForRenderingByHeight](../../groupdocs.viewer.options/cadoptions/forrenderingbyheight)(int) | Αρχικοποιεί μια παρουσία της κλάσης [`CadOptions`](../cadoptions) για απόδοση βάσει ύψους. |
| static [ForRenderingByScaleFactor](../../groupdocs.viewer.options/cadoptions/forrenderingbyscalefactor)(float) | Αρχικοποιεί μια παρουσία της κλάσης [`CadOptions`](../cadoptions) για απόδοση βάσει συντελεστή κλίμακας. |
| static [ForRenderingByWidth](../../groupdocs.viewer.options/cadoptions/forrenderingbywidth)(int) | Αρχικοποιεί μια παρουσία της κλάσης [`CadOptions`](../cadoptions) για απόδοση βάσει πλάτους. |
| static [ForRenderingByWidthAndHeight](../../groupdocs.viewer.options/cadoptions/forrenderingbywidthandheight)(int, int) | Αρχικοποιεί μια παρουσία της κλάσης [`CadOptions`](../cadoptions) για απόδοση βάσει πλάτους και ύψους. |

### Δείτε επίσης

* namespace [GroupDocs.Viewer.Options](../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../)

<!-- ΜΗΝ ΕΠΕΞΕΡΓΑΣΕΤΕ: δημιουργήθηκε από το xmldocmd για το GroupDocs.Viewer.dll -->
