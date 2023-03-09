---
title: ViewInfoOptions
second_title: GroupDocs.Viewer για Αναφορά API .NET
description: Παρέχει επιλογές που χρησιμοποιούνται για την ανάκτηση πληροφοριών σχετικά με την προβολή.
type: docs
weight: 570
url: /el/net/groupdocs.viewer.options/viewinfooptions/
---
## ViewInfoOptions class

Παρέχει επιλογές που χρησιμοποιούνται για την ανάκτηση πληροφοριών σχετικά με την προβολή.

```csharp
public class ViewInfoOptions : BaseViewOptions, IMaxSizeOptions
```

## Ιδιότητες

| Ονομα | Περιγραφή |
| --- | --- |
| [ArchiveOptions](../../groupdocs.viewer.options/baseviewoptions/archiveoptions) { get; set; } | Οι επιλογές προβολής των αρχείων αρχειοθέτησης. |
| [CadOptions](../../groupdocs.viewer.options/baseviewoptions/cadoptions) { get; set; } | Οι επιλογές προβολής σχεδίασης CAD. |
| [DefaultFontName](../../groupdocs.viewer.options/baseviewoptions/defaultfontname) { get; set; } | Προεπιλεγμένη γραμματοσειρά που χρησιμοποιείται όταν δεν μπορεί να βρεθεί συγκεκριμένη γραμματοσειρά που χρησιμοποιείται στο έγγραφο. |
| [EmailOptions](../../groupdocs.viewer.options/baseviewoptions/emailoptions) { get; set; } | Οι επιλογές προβολής μηνυμάτων email. |
| [ExtractText](../../groupdocs.viewer.options/viewinfooptions/extracttext) { get; set; } | Υποδεικνύει ότι η εξαγωγή κειμένου είναι ενεργοποιημένη. |
| [Height](../../groupdocs.viewer.options/viewinfooptions/height) { get; set; } | Ύψος εικόνας (μόνο για απόδοση σε PNG/JPG) |
| [MailStorageOptions](../../groupdocs.viewer.options/baseviewoptions/mailstorageoptions) { get; set; } | Επιλογές προβολής αρχείων δεδομένων αποθήκευσης αλληλογραφίας. |
| [MaxHeight](../../groupdocs.viewer.options/viewinfooptions/maxheight) { get; set; } | Μέγιστο ύψος της εικόνας εξόδου (μόνο για απόδοση σε PNG/JPG) |
| [MaxWidth](../../groupdocs.viewer.options/viewinfooptions/maxwidth) { get; set; } | Μέγιστο πλάτος της εικόνας εξόδου (μόνο για απόδοση σε PNG/JPG) |
| [OutlookOptions](../../groupdocs.viewer.options/baseviewoptions/outlookoptions) { get; set; } | Επιλογές προβολής αρχείων δεδομένων MS Outlook. |
| [PdfOptions](../../groupdocs.viewer.options/baseviewoptions/pdfoptions) { get; set; } | Οι επιλογές προβολής εγγράφων PDF. |
| [PresentationOptions](../../groupdocs.viewer.options/baseviewoptions/presentationoptions) { get; set; } | Οι επιλογές προβολής εγγράφων επεξεργασίας παρουσίασης. |
| [ProjectManagementOptions](../../groupdocs.viewer.options/baseviewoptions/projectmanagementoptions) { get; set; } | Επιλογές προβολής των αρχείων διαχείρισης έργου. |
| [RenderComments](../../groupdocs.viewer.options/baseviewoptions/rendercomments) { get; set; } | Ενεργοποιεί την απόδοση σχολίων. |
| [RenderHiddenPages](../../groupdocs.viewer.options/baseviewoptions/renderhiddenpages) { get; set; } | Ενεργοποιεί την απόδοση κρυφών σελίδων. |
| [RenderNotes](../../groupdocs.viewer.options/baseviewoptions/rendernotes) { get; set; } | Ενεργοποιεί την απόδοση σημειώσεων. |
| [SpreadsheetOptions](../../groupdocs.viewer.options/baseviewoptions/spreadsheetoptions) { get; set; } | Οι επιλογές προβολής των αρχείων υπολογιστικού φύλλου. |
| [TextOptions](../../groupdocs.viewer.options/baseviewoptions/textoptions) { get; set; } | Αρχεία κειμένου που χωρίζονται σε σελίδες. |
| [VisioRenderingOptions](../../groupdocs.viewer.options/baseviewoptions/visiorenderingoptions) { get; set; } | Οι επιλογές προβολής των αρχείων Visio που επεξεργάζονται έγγραφα. |
| [WebDocumentOptions](../../groupdocs.viewer.options/baseviewoptions/webdocumentoptions) { get; set; } | Αυτές οι επιλογές απόδοσης σάς επιτρέπουν να προσαρμόσετε την εμφάνιση της εξόδου HTML/PDF/PNG/JPEG κατά την απόδοση εγγράφων Ιστού. |
| [Width](../../groupdocs.viewer.options/viewinfooptions/width) { get; set; } | Πλάτος εικόνας (μόνο για απόδοση σε PNG/JPG) |
| [WordProcessingOptions](../../groupdocs.viewer.options/baseviewoptions/wordprocessingoptions) { get; set; } | Αυτές οι επιλογές απόδοσης σάς επιτρέπουν να προσαρμόσετε την εμφάνιση της εξόδου HTML/PDF/PNG/JPEG κατά την απόδοση εγγράφων του Word. |

## Μέθοδοι

| Ονομα | Περιγραφή |
| --- | --- |
| static [ForHtmlView](../../groupdocs.viewer.options/viewinfooptions/forhtmlview#forhtmlview)() | Αρχικοποιεί νέα παρουσία του[`ViewInfoOptions`](../viewinfooptions) κλάση για ανάκτηση πληροφοριών σχετικά με την προβολή κατά την απόδοση σε HTML. |
| static [ForHtmlView](../../groupdocs.viewer.options/viewinfooptions/forhtmlview#forhtmlview_1)(bool) | Αρχικοποιεί νέα παρουσία του[`ViewInfoOptions`](../viewinfooptions) κλάση για ανάκτηση πληροφοριών σχετικά με την προβολή κατά την απόδοση σε HTML. |
| static [ForJpgView](../../groupdocs.viewer.options/viewinfooptions/forjpgview#forjpgview)() | Αρχικοποιεί νέα παρουσία του[`ViewInfoOptions`](../viewinfooptions) κλάση για ανάκτηση πληροφοριών σχετικά με την προβολή κατά την απόδοση σε JPG. |
| static [ForJpgView](../../groupdocs.viewer.options/viewinfooptions/forjpgview#forjpgview_1)(bool) | Αρχικοποιεί νέα παρουσία του[`ViewInfoOptions`](../viewinfooptions) κλάση για ανάκτηση πληροφοριών σχετικά με την προβολή κατά την απόδοση σε JPG. |
| static [ForPngView](../../groupdocs.viewer.options/viewinfooptions/forpngview#forpngview)() | Αρχικοποιεί νέα παρουσία του[`ViewInfoOptions`](../viewinfooptions) κλάση για ανάκτηση πληροφοριών σχετικά με την προβολή κατά την απόδοση σε PNG. |
| static [ForPngView](../../groupdocs.viewer.options/viewinfooptions/forpngview#forpngview_1)(bool) | Αρχικοποιεί νέα παρουσία του[`ViewInfoOptions`](../viewinfooptions) κλάση για ανάκτηση πληροφοριών σχετικά με την προβολή κατά την απόδοση σε PNG. |
| static [FromHtmlViewOptions](../../groupdocs.viewer.options/viewinfooptions/fromhtmlviewoptions)(HtmlViewOptions) | Αρχικοποιεί νέα παρουσία του[`ViewInfoOptions`](../viewinfooptions) τάξη με βάση[`HtmlViewOptions`](../htmlviewoptions) αντικείμενο. |
| static [FromJpgViewOptions](../../groupdocs.viewer.options/viewinfooptions/fromjpgviewoptions)(JpgViewOptions) | Αρχικοποιεί νέα παρουσία του[`ViewInfoOptions`](../viewinfooptions) τάξη με βάση[`JpgViewOptions`](../jpgviewoptions) αντικείμενο. |
| static [FromPngViewOptions](../../groupdocs.viewer.options/viewinfooptions/frompngviewoptions)(PngViewOptions) | Αρχικοποιεί νέα παρουσία του[`ViewInfoOptions`](../viewinfooptions) τάξη με βάση[`PngViewOptions`](../pngviewoptions) αντικείμενο. |

### Δείτε επίσης

* class [BaseViewOptions](../baseviewoptions)
* interface [IMaxSizeOptions](../imaxsizeoptions)
* χώρος ονομάτων [GroupDocs.Viewer.Options](../../groupdocs.viewer.options)
* συνέλευση [GroupDocs.Viewer](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Viewer.dll -->
