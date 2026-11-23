---
title: "ViewInfoOptions"
second_title: "Αναφορά API του GroupDocs.Viewer for .NET"
description: "Περιέχει επιλογές για την ανάκτηση πληροφοριών σχετικά με την προβολή."
type: docs
weight: 580
url: /el/net/groupdocs.viewer.options/viewinfooptions/
---

## ViewInfoOptions class

Περιέχει επιλογές για την ανάκτηση πληροφοριών σχετικά με την προβολή.

```csharp
public class ViewInfoOptions : BaseViewOptions, IMaxSizeOptions
```

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [ArchiveOptions](../../groupdocs.viewer.options/baseviewoptions/archiveoptions) { get; set; } | Οι επιλογές προβολής αρχείων αρχειοθέτησης. |
| [CadOptions](../../groupdocs.viewer.options/baseviewoptions/cadoptions) { get; set; } | Οι επιλογές προβολής σχεδίου CAD. |
| [DefaultFontName](../../groupdocs.viewer.options/baseviewoptions/defaultfontname) { get; set; } | Ορίζει τη προεπιλεγμένη γραμματοσειρά για ένα έγγραφο. |
| [EmailOptions](../../groupdocs.viewer.options/baseviewoptions/emailoptions) { get; set; } | Οι επιλογές προβολής μηνυμάτων email. |
| [ExtractText](../../groupdocs.viewer.options/viewinfooptions/extracttext) { get; set; } | Ενεργοποιεί την εξαγωγή κειμένου. |
| [Height](../../groupdocs.viewer.options/viewinfooptions/height) { get; set; } | Το ύψος της εξαγόμενης εικόνας (σε εικονοστοιχεία, μόνο για απόδοση σε PNG/JPG). |
| [MailStorageOptions](../../groupdocs.viewer.options/baseviewoptions/mailstorageoptions) { get; set; } | Οι επιλογές προβολής αρχείων δεδομένων αποθήκευσης αλληλογραφίας. |
| [MaxHeight](../../groupdocs.viewer.options/viewinfooptions/maxheight) { get; set; } | Ορίζει το μέγιστο ύψος μιας εξαγόμενης εικόνας (σε εικονοστοιχεία, μόνο για απόδοση σε PNG/JPG). |
| [MaxWidth](../../groupdocs.viewer.options/viewinfooptions/maxwidth) { get; set; } | Ορίζει το μέγιστο πλάτος μιας εξαγόμενης εικόνας (σε εικονοστοιχεία, μόνο για απόδοση σε PNG/JPG). |
| [OutlookOptions](../../groupdocs.viewer.options/baseviewoptions/outlookoptions) { get; set; } | Οι επιλογές προβολής αρχείων δεδομένων Microsoft Outlook. |
| [PdfOptions](../../groupdocs.viewer.options/baseviewoptions/pdfoptions) { get; set; } | Οι επιλογές προβολής εγγράφου PDF. |
| [PresentationOptions](../../groupdocs.viewer.options/baseviewoptions/presentationoptions) { get; set; } | Οι επιλογές προβολής αρχείων παρουσίασης. |
| [ProjectManagementOptions](../../groupdocs.viewer.options/baseviewoptions/projectmanagementoptions) { get; set; } | Οι επιλογές προβολής αρχείων διαχείρισης έργου. |
| [RemoveComments](../../groupdocs.viewer.options/baseviewoptions/removecomments) { get; set; } | Απενεργοποιεί την απόδοση σχολίων όταν ορίζεται σε `true`. Από προεπιλογή είναι `false` — όλα τα σχόλια εμφανίζονται. |
| [RenderHiddenPages](../../groupdocs.viewer.options/baseviewoptions/renderhiddenpages) { get; set; } | Ενεργοποιεί την απόδοση κρυφών σελίδων. |
| [RenderNotes](../../groupdocs.viewer.options/baseviewoptions/rendernotes) { get; set; } | Ενεργοποιεί την απόδοση σημειώσεων και σχολίων για ορισμένες μορφές. |
| [SpreadsheetOptions](../../groupdocs.viewer.options/baseviewoptions/spreadsheetoptions) { get; set; } | Οι επιλογές προβολής αρχείων λογιστικού φύλλου. |
| [TextOptions](../../groupdocs.viewer.options/baseviewoptions/textoptions) { get; set; } | Οι επιλογές προβολής αρχείων κειμένου. |
| [VisioRenderingOptions](../../groupdocs.viewer.options/baseviewoptions/visiorenderingoptions) { get; set; } | Οι επιλογές προβολής αρχείων Visio. |
| [WebDocumentOptions](../../groupdocs.viewer.options/baseviewoptions/webdocumentoptions) { get; set; } | Οι επιλογές προβολής αρχείων Web. |
| [Width](../../groupdocs.viewer.options/viewinfooptions/width) { get; set; } | Το πλάτος της εξαγόμενης εικόνας (σε εικονοστοιχεία, μόνο για απόδοση σε PNG/JPG). |
| [WordProcessingOptions](../../groupdocs.viewer.options/baseviewoptions/wordprocessingoptions) { get; set; } | Οι επιλογές προβολής αρχείων επεξεργασίας κειμένου. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| static [ForHtmlView](../../groupdocs.viewer.options/viewinfooptions/forhtmlview#forhtmlview)() | Αρχικοποιεί μια παρουσία της κλάσης [`ViewInfoOptions`](../viewinfooptions) για την ανάκτηση πληροφοριών προβολής κατά την απόδοση σε HTML. |
| static [ForHtmlView](../../groupdocs.viewer.options/viewinfooptions/forhtmlview#forhtmlview_1)(bool) | Αρχικοποιεί μια παρουσία της κλάσης [`ViewInfoOptions`](../viewinfooptions) για την ανάκτηση πληροφοριών προβολής κατά την απόδοση σε HTML. |
| static [ForJpgView](../../groupdocs.viewer.options/viewinfooptions/forjpgview#forjpgview)() | Αρχικοποιεί μια παρουσία της κλάσης [`ViewInfoOptions`](../viewinfooptions) για την ανάκτηση πληροφοριών προβολής κατά την απόδοση σε JPG. |
| static [ForJpgView](../../groupdocs.viewer.options/viewinfooptions/forjpgview#forjpgview_1)(bool) | Αρχικοποιεί μια παρουσία της κλάσης [`ViewInfoOptions`](../viewinfooptions) για την ανάκτηση πληροφοριών προβολής κατά την απόδοση σε JPG. |
| static [ForPdfView](../../groupdocs.viewer.options/viewinfooptions/forpdfview)() | Αρχικοποιεί μια παρουσία της κλάσης [`ViewInfoOptions`](../viewinfooptions) για την ανάκτηση πληροφοριών προβολής κατά την απόδοση σε PDF. |
| static [ForPngView](../../groupdocs.viewer.options/viewinfooptions/forpngview#forpngview)() | Αρχικοποιεί μια παρουσία της κλάσης [`ViewInfoOptions`](../viewinfooptions) για την ανάκτηση πληροφοριών προβολής κατά την απόδοση σε PNG. |
| static [ForPngView](../../groupdocs.viewer.options/viewinfooptions/forpngview#forpngview_1)(bool) | Αρχικοποιεί μια παρουσία της κλάσης [`ViewInfoOptions`](../viewinfooptions) για την ανάκτηση πληροφοριών προβολής κατά την απόδοση σε PNG. |
| static [FromHtmlViewOptions](../../groupdocs.viewer.options/viewinfooptions/fromhtmlviewoptions)(HtmlViewOptions) | Αρχικοποιεί μια παρουσία της κλάσης [`ViewInfoOptions`](../viewinfooptions) βασισμένη στο αντικείμενο [`HtmlViewOptions`](../htmlviewoptions). |
| static [FromJpgViewOptions](../../groupdocs.viewer.options/viewinfooptions/fromjpgviewoptions)(JpgViewOptions) | Αρχικοποιεί μια παρουσία της κλάσης [`ViewInfoOptions`](../viewinfooptions) βασισμένη στο αντικείμενο [`JpgViewOptions`](../jpgviewoptions). |
| static [FromPdfViewOptions](../../groupdocs.viewer.options/viewinfooptions/frompdfviewoptions)(PdfViewOptions) | Αρχικοποιεί μια παρουσία της κλάσης [`ViewInfoOptions`](../viewinfooptions) βασισμένη στο αντικείμενο [`PdfViewOptions`](../pdfviewoptions). |
| static [FromPngViewOptions](../../groupdocs.viewer.options/viewinfooptions/frompngviewoptions)(PngViewOptions) | Αρχικοποιεί μια παρουσία της κλάσης [`ViewInfoOptions`](../viewinfooptions) βασισμένη στο αντικείμενο [`PngViewOptions`](../pngviewoptions). |

### Δείτε επίσης

* class [BaseViewOptions](../baseviewoptions)
* interface [IMaxSizeOptions](../imaxsizeoptions)
* namespace [GroupDocs.Viewer.Options](../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../)

<!-- ΜΗΝ ΕΠΕΞΕΡΓΑΣΕΤΕ: δημιουργήθηκε από το xmldocmd για το GroupDocs.Viewer.dll -->
