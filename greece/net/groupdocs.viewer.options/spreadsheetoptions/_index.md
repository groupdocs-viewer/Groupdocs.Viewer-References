---
title: "SpreadsheetOptions"
second_title: "Αναφορά API του GroupDocs.Viewer for .NET"
description: "Περιέχει επιλογές για την απόδοση λογιστικών φύλλων. Για λεπτομέρειες δείτε τα υπο-αντικείμενα του θέματος Render spreadsheet files https//docs.groupdocs.com/viewer/net/renderspreadsheets/."
type: docs
weight: 530
url: /el/net/groupdocs.viewer.options/spreadsheetoptions/
---

## SpreadsheetOptions class

Περιέχει επιλογές για την απόδοση λογιστικών φύλλων. Για λεπτομέρειες, δείτε τα υπο-στοιχεία του [Απόδοση αρχείων λογιστικών φύλλων](https://docs.groupdocs.com/viewer/net/render-spreadsheets/) θέματος.

```csharp
public class SpreadsheetOptions
```

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [BottomMargin](../../groupdocs.viewer.options/spreadsheetoptions/bottommargin) { get; set; } | Ορίζει το κάτω περιθώριο μιας σελίδας κατά τη μετατροπή σε PDF. |
| [CountColumnsPerPage](../../groupdocs.viewer.options/spreadsheetoptions/countcolumnsperpage) { get; } | Ο αριθμός των στηλών που θα συμπεριληφθεί σε κάθε σελίδα κατά τη διαίρεση του φύλλου εργασίας σε σελίδες. |
| [CountRowsPerPage](../../groupdocs.viewer.options/spreadsheetoptions/countrowsperpage) { get; } | Ο αριθμός των γραμμών που θα συμπεριληφθεί σε κάθε σελίδα κατά τη διαίρεση του φύλλου εργασίας σε σελίδες. |
| [DetectSeparator](../../groupdocs.viewer.options/spreadsheetoptions/detectseparator) { get; set; } | Ανιχνεύει έναν διαχωριστή (για αρχεία CSV/TSV). |
| [HorizontalResolution](../../groupdocs.viewer.options/spreadsheetoptions/horizontalresolution) { get; set; } | Λαμβάνει ή ορίζει την οριζόντια ανάλυση για τις παραγόμενες εικόνες σε κουκκίδες ανά ίντσα. Αυτή η επιλογή χρησιμοποιείται μόνο κατά την απόδοση λογιστικών φύλλων σε μορφές PNG ή JPEG. |
| [LeftMargin](../../groupdocs.viewer.options/spreadsheetoptions/leftmargin) { get; set; } | Ορίζει το αριστερό περιθώριο μιας σελίδας κατά τη μετατροπή σε PDF. |
| [RenderGridLines](../../groupdocs.viewer.options/spreadsheetoptions/rendergridlines) { get; set; } | Επιτρέπει την απόδοση των γραμμών πλέγματος. |
| [RenderHeadings](../../groupdocs.viewer.options/spreadsheetoptions/renderheadings) { get; set; } | Επιτρέπει την απόδοση των επικεφαλίδων. |
| [RenderHiddenColumns](../../groupdocs.viewer.options/spreadsheetoptions/renderhiddencolumns) { get; set; } | Επιτρέπει την απόδοση των κρυφών στηλών. |
| [RenderHiddenRows](../../groupdocs.viewer.options/spreadsheetoptions/renderhiddenrows) { get; set; } | Επιτρέπει την απόδοση των κρυφών γραμμών. |
| [RightMargin](../../groupdocs.viewer.options/spreadsheetoptions/rightmargin) { get; set; } | Ορίζει το δεξιό περιθώριο μιας σελίδας κατά τη μετατροπή σε PDF. |
| [SkipEmptyColumns](../../groupdocs.viewer.options/spreadsheetoptions/skipemptycolumns) { get; set; } | Απενεργοποιεί την απόδοση κενών στηλών. |
| [SkipEmptyRows](../../groupdocs.viewer.options/spreadsheetoptions/skipemptyrows) { get; set; } | Απενεργοποιεί την απόδοση κενών γραμμών. |
| [TextOverflowMode](../../groupdocs.viewer.options/spreadsheetoptions/textoverflowmode) { get; set; } | Ορίζει τη λειτουργία υπερχείλισης κειμένου για την απόδοση εγγράφων λογιστικού φύλλου σε HTML. Από προεπιλογή είναι , που μιμείται τη προεπιλεγμένη συμπεριφορά του MS Excel. |
| [TopMargin](../../groupdocs.viewer.options/spreadsheetoptions/topmargin) { get; set; } | Ορίζει το επάνω περιθώριο μιας σελίδας κατά τη μετατροπή σε PDF. |
| [VerticalResolution](../../groupdocs.viewer.options/spreadsheetoptions/verticalresolution) { get; set; } | Ανακτά ή ορίζει την κάθετη ανάλυση για τις παραγόμενες εικόνες σε κουκκίδες ανά ίντσα. Αυτή η επιλογή χρησιμοποιείται μόνο κατά την απόδοση λογιστικών φύλλων σε μορφές PNG ή JPEG. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| static [ForOnePagePerSheet](../../groupdocs.viewer.options/spreadsheetoptions/foronepagepersheet)() | Αρχικοποιεί μια παρουσία της κλάσης [`SpreadsheetOptions`](../spreadsheetoptions) για την απόδοση ολόκληρου του φύλλου σε μία σελίδα. |
| static [ForRenderingByPageBreaks](../../groupdocs.viewer.options/spreadsheetoptions/forrenderingbypagebreaks)() | Αρχικοποιεί μια παρουσία της κλάσης [`SpreadsheetOptions`](../spreadsheetoptions) για το διαχωρισμό σε σελίδες με βάση τις αλλαγές σελίδας. |
| static [ForRenderingPrintArea](../../groupdocs.viewer.options/spreadsheetoptions/forrenderingprintarea)() | Αρχικοποιεί μια παρουσία της κλάσης [`SpreadsheetOptions`](../spreadsheetoptions) για την απόδοση μόνο των περιοχών εκτύπωσης. |
| static [ForRenderingPrintAreaAndPageBreaks](../../groupdocs.viewer.options/spreadsheetoptions/forrenderingprintareaandpagebreaks)() | Αρχικοποιεί μια παρουσία της κλάσης [`SpreadsheetOptions`](../spreadsheetoptions) για την απόδοση περιοχών εκτύπωσης και αλλαγών σελίδας. |
| static [ForSplitSheetIntoPages](../../groupdocs.viewer.options/spreadsheetoptions/forsplitsheetintopages#forsplitsheetintopages)(int) | Αρχικοποιεί μια παρουσία της κλάσης [`SpreadsheetOptions`](../spreadsheetoptions) για την απόδοση του φύλλου σε σελίδες. |
| static [ForSplitSheetIntoPages](../../groupdocs.viewer.options/spreadsheetoptions/forsplitsheetintopages#forsplitsheetintopages_1)(int, int) | Αρχικοποιεί μια παρουσία της κλάσης [`SpreadsheetOptions`](../spreadsheetoptions) για την απόδοση του φύλλου σε σελίδες. |

### Δείτε επίσης

* namespace [GroupDocs.Viewer.Options](../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../)

<!-- ΜΗΝ ΕΠΕΞΕΡΓΑΣΕΤΕ: δημιουργήθηκε από το xmldocmd για το GroupDocs.Viewer.dll -->
