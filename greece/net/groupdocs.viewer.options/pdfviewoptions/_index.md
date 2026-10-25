---
title: "PdfViewOptions"
second_title: "Αναφορά API του GroupDocs.Viewer for .NET"
description: "Περιέχει επιλογές για απόδοση εγγράφων σε μορφή PDF. Για λεπτομέρειες δείτε την τεκμηρίωσηhttps//docs.groupdocs.com/viewer/net/renderingtopdf/."
type: docs
weight: 420
url: /el/net/groupdocs.viewer.options/pdfviewoptions/
---

## PdfViewOptions class

Περιέχει επιλογές για την απόδοση εγγράφων σε μορφή PDF. Για λεπτομέρειες, δείτε την [τεκμηρίωση](https://docs.groupdocs.com/viewer/net/rendering-to-pdf/).

```csharp
public class PdfViewOptions : ViewOptions
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [PdfViewOptions](pdfviewoptions#constructor)() | Αρχικοποιεί μια παρουσία της κλάσης [`PdfViewOptions`](../pdfviewoptions). |
| [PdfViewOptions](pdfviewoptions#constructor_1)(CreateFileStream) | Αρχικοποιεί μια παρουσία της κλάσης [`PdfViewOptions`](../pdfviewoptions). |
| [PdfViewOptions](pdfviewoptions#constructor_3)(IFileStreamFactory) | Αρχικοποιεί μια παρουσία της κλάσης [`PdfViewOptions`](../pdfviewoptions). |
| [PdfViewOptions](pdfviewoptions#constructor_4)(string) | Αρχικοποιεί μια παρουσία της κλάσης [`PdfViewOptions`](../pdfviewoptions). |
| [PdfViewOptions](pdfviewoptions#constructor_2)(CreateFileStream, ReleaseFileStream) | Αρχικοποιεί μια παρουσία της κλάσης [`PdfViewOptions`](../pdfviewoptions). |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [ArchiveOptions](../../groupdocs.viewer.options/baseviewoptions/archiveoptions) { get; set; } | Οι επιλογές προβολής αρχείων αρχειοθέτησης. |
| [CadOptions](../../groupdocs.viewer.options/baseviewoptions/cadoptions) { get; set; } | Οι επιλογές προβολής σχεδίου CAD. |
| [DefaultFontName](../../groupdocs.viewer.options/baseviewoptions/defaultfontname) { get; set; } | Ορίζει τη προεπιλεγμένη γραμματοσειρά για ένα έγγραφο. |
| [EmailOptions](../../groupdocs.viewer.options/baseviewoptions/emailoptions) { get; set; } | Οι επιλογές προβολής μηνυμάτων email. |
| [ImageHeight](../../groupdocs.viewer.options/pdfviewoptions/imageheight) { get; set; } | Ορίζει το ύψος μιας εξόδου εικόνας (σε εικονοστοιχεία). |
| [ImageMaxHeight](../../groupdocs.viewer.options/pdfviewoptions/imagemaxheight) { get; set; } | Ορίζει το μέγιστο ύψος μιας εικόνας εξόδου (σε εικονοστοιχεία). |
| [ImageMaxWidth](../../groupdocs.viewer.options/pdfviewoptions/imagemaxwidth) { get; set; } | Ορίζει το μέγιστο πλάτος μιας εικόνας εξόδου (σε εικονοστοιχεία). |
| [ImageWidth](../../groupdocs.viewer.options/pdfviewoptions/imagewidth) { get; set; } | Ορίζει το πλάτος μιας εικόνας εξόδου (σε εικονοστοιχεία). |
| [MailStorageOptions](../../groupdocs.viewer.options/baseviewoptions/mailstorageoptions) { get; set; } | Οι επιλογές προβολής αρχείων δεδομένων αποθήκευσης αλληλογραφίας. |
| [OutlookOptions](../../groupdocs.viewer.options/baseviewoptions/outlookoptions) { get; set; } | Οι επιλογές προβολής αρχείων δεδομένων Microsoft Outlook. |
| [PdfOptimizationOptions](../../groupdocs.viewer.options/pdfviewoptions/pdfoptimizationoptions) { get; set; } | Μειώνει το μέγεθος του αρχείου PDF εξόδου εφαρμόζοντας τεχνικές βελτιστοποίησης με διαφορετικές επιλογές. |
| [PdfOptions](../../groupdocs.viewer.options/baseviewoptions/pdfoptions) { get; set; } | Οι επιλογές προβολής εγγράφου PDF. |
| [PresentationOptions](../../groupdocs.viewer.options/baseviewoptions/presentationoptions) { get; set; } | Οι επιλογές προβολής αρχείων παρουσίασης. |
| [ProjectManagementOptions](../../groupdocs.viewer.options/baseviewoptions/projectmanagementoptions) { get; set; } | Οι επιλογές προβολής αρχείων διαχείρισης έργου. |
| [RemoveComments](../../groupdocs.viewer.options/baseviewoptions/removecomments) { get; set; } | Απενεργοποιεί την απόδοση σχολίων όταν ορίζεται σε `true`. Από προεπιλογή είναι `false` — όλα τα σχόλια εμφανίζονται. |
| [RenderHiddenPages](../../groupdocs.viewer.options/baseviewoptions/renderhiddenpages) { get; set; } | Ενεργοποιεί την απόδοση κρυφών σελίδων. |
| [RenderNotes](../../groupdocs.viewer.options/baseviewoptions/rendernotes) { get; set; } | Ενεργοποιεί την απόδοση σημειώσεων και σχολίων για ορισμένες μορφές. |
| [Security](../../groupdocs.viewer.options/pdfviewoptions/security) { get; set; } | Ορίζει τις επιλογές ασφαλείας του εγγράφου PDF εξόδου. |
| [SpreadsheetOptions](../../groupdocs.viewer.options/baseviewoptions/spreadsheetoptions) { get; set; } | Οι επιλογές προβολής αρχείων λογιστικού φύλλου. |
| [TextOptions](../../groupdocs.viewer.options/baseviewoptions/textoptions) { get; set; } | Οι επιλογές προβολής αρχείων κειμένου. |
| [VisioRenderingOptions](../../groupdocs.viewer.options/baseviewoptions/visiorenderingoptions) { get; set; } | Οι επιλογές προβολής αρχείων Visio. |
| [Watermark](../../groupdocs.viewer.options/viewoptions/watermark) { get; set; } | Το υδατογράφημα κειμένου που θα εφαρμοστεί σε κάθε σελίδα. |
| [WebDocumentOptions](../../groupdocs.viewer.options/baseviewoptions/webdocumentoptions) { get; set; } | Οι επιλογές προβολής αρχείων Web. |
| [WordProcessingOptions](../../groupdocs.viewer.options/baseviewoptions/wordprocessingoptions) { get; set; } | Οι επιλογές προβολής αρχείων επεξεργασίας κειμένου. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [RotatePage](../../groupdocs.viewer.options/viewoptions/rotatepage)(int, Rotation) | Εφαρμόζει τη δεξιόστροφη περιστροφή σε μια σελίδα. |

## Πεδία

| Όνομα | Περιγραφή |
| --- | --- |
| readonly [PageRotations](../../groupdocs.viewer.options/viewoptions/pagerotations) | Η περιστροφή της σελίδας. |

### Δείτε επίσης

* class [ViewOptions](../viewoptions)
* namespace [GroupDocs.Viewer.Options](../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../)

<!-- ΜΗΝ ΕΠΕΞΕΡΓΑΣΕΤΕ: δημιουργήθηκε από το xmldocmd για το GroupDocs.Viewer.dll -->
