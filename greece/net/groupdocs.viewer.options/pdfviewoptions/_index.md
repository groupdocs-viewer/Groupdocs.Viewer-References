---
title: PdfViewOptions
second_title: GroupDocs.Viewer για Αναφορά API .NET
description: Παρέχει επιλογές για απόδοση εγγράφων σε μορφή PDF.
type: docs
weight: 420
url: /el/net/groupdocs.viewer.options/pdfviewoptions/
---
## PdfViewOptions class

Παρέχει επιλογές για απόδοση εγγράφων σε μορφή PDF.

```csharp
public class PdfViewOptions : ViewOptions
```

## Κατασκευαστές

| Ονομα | Περιγραφή |
| --- | --- |
| [PdfViewOptions](pdfviewoptions#constructor)() | Αρχικοποιεί νέα παρουσία του[`PdfViewOptions`](../pdfviewoptions) τάξη. |
| [PdfViewOptions](pdfviewoptions#constructor_1)(CreateFileStream) | Αρχικοποιεί νέα παρουσία του[`PdfViewOptions`](../pdfviewoptions) τάξη. |
| [PdfViewOptions](pdfviewoptions#constructor_3)(IFileStreamFactory) | Αρχικοποιεί νέα παρουσία του[`PdfViewOptions`](../pdfviewoptions) τάξη. |
| [PdfViewOptions](pdfviewoptions#constructor_4)(string) | Αρχικοποιεί νέα παρουσία του[`PdfViewOptions`](../pdfviewoptions) τάξη. |
| [PdfViewOptions](pdfviewoptions#constructor_2)(CreateFileStream, ReleaseFileStream) | Αρχικοποιεί νέα παρουσία του[`PdfViewOptions`](../pdfviewoptions) τάξη. |

## Ιδιότητες

| Ονομα | Περιγραφή |
| --- | --- |
| [ArchiveOptions](../../groupdocs.viewer.options/baseviewoptions/archiveoptions) { get; set; } | Οι επιλογές προβολής των αρχείων αρχειοθέτησης. |
| [CadOptions](../../groupdocs.viewer.options/baseviewoptions/cadoptions) { get; set; } | Οι επιλογές προβολής σχεδίασης CAD. |
| [DefaultFontName](../../groupdocs.viewer.options/baseviewoptions/defaultfontname) { get; set; } | Προεπιλεγμένη γραμματοσειρά που χρησιμοποιείται όταν δεν μπορεί να βρεθεί συγκεκριμένη γραμματοσειρά που χρησιμοποιείται στο έγγραφο. |
| [EmailOptions](../../groupdocs.viewer.options/baseviewoptions/emailoptions) { get; set; } | Οι επιλογές προβολής μηνυμάτων email. |
| [ImageHeight](../../groupdocs.viewer.options/pdfviewoptions/imageheight) { get; set; } | Το ύψος μιας εικόνας εξόδου σε pixel. (Μόνο κατά τη μετατροπή μιας εικόνας σε HTML) |
| [ImageMaxHeight](../../groupdocs.viewer.options/pdfviewoptions/imagemaxheight) { get; set; } | Μέγιστο ύψος εικόνας εξόδου σε pixel. (Μόνο κατά τη μετατροπή μιας εικόνας σε HTML) |
| [ImageMaxWidth](../../groupdocs.viewer.options/pdfviewoptions/imagemaxwidth) { get; set; } | Μέγιστο πλάτος εικόνας εξόδου σε pixel. (Μόνο κατά τη μετατροπή μιας εικόνας σε HTML) |
| [ImageWidth](../../groupdocs.viewer.options/pdfviewoptions/imagewidth) { get; set; } | Το πλάτος της εικόνας εξόδου σε pixel. (Μόνο κατά τη μετατροπή μιας εικόνας σε HTML) |
| [JpgQuality](../../groupdocs.viewer.options/pdfviewoptions/jpgquality) { get; set; } | Η ποιότητα των εικόνων JPG που περιέχονται στο έγγραφο PDF εξόδου; Οι έγκυρες τιμές είναι μεταξύ 1 και 100; Η προεπιλεγμένη τιμή είναι 90. |
| [MailStorageOptions](../../groupdocs.viewer.options/baseviewoptions/mailstorageoptions) { get; set; } | Επιλογές προβολής αρχείων δεδομένων αποθήκευσης αλληλογραφίας. |
| [Optimize](../../groupdocs.viewer.options/pdfviewoptions/optimize) { get; set; } | Μειώστε το μέγεθος του αρχείου εξόδου εξαιρώντας κοινές γραμματοσειρές όπως το Times New Roman και το Arial και εφαρμόζοντας άλλες τεχνικές βελτιστοποίησης. |
| [OutlookOptions](../../groupdocs.viewer.options/baseviewoptions/outlookoptions) { get; set; } | Επιλογές προβολής αρχείων δεδομένων MS Outlook. |
| [PdfOptions](../../groupdocs.viewer.options/baseviewoptions/pdfoptions) { get; set; } | Οι επιλογές προβολής εγγράφων PDF. |
| [PresentationOptions](../../groupdocs.viewer.options/baseviewoptions/presentationoptions) { get; set; } | Οι επιλογές προβολής εγγράφων επεξεργασίας παρουσίασης. |
| [ProjectManagementOptions](../../groupdocs.viewer.options/baseviewoptions/projectmanagementoptions) { get; set; } | Επιλογές προβολής των αρχείων διαχείρισης έργου. |
| [RenderComments](../../groupdocs.viewer.options/baseviewoptions/rendercomments) { get; set; } | Ενεργοποιεί την απόδοση σχολίων. |
| [RenderHiddenPages](../../groupdocs.viewer.options/baseviewoptions/renderhiddenpages) { get; set; } | Ενεργοποιεί την απόδοση κρυφών σελίδων. |
| [RenderNotes](../../groupdocs.viewer.options/baseviewoptions/rendernotes) { get; set; } | Ενεργοποιεί την απόδοση σημειώσεων. |
| [Security](../../groupdocs.viewer.options/pdfviewoptions/security) { get; set; } | Οι επιλογές ασφαλείας του εγγράφου PDF εξόδου. |
| [SpreadsheetOptions](../../groupdocs.viewer.options/baseviewoptions/spreadsheetoptions) { get; set; } | Οι επιλογές προβολής των αρχείων υπολογιστικού φύλλου. |
| [TextOptions](../../groupdocs.viewer.options/baseviewoptions/textoptions) { get; set; } | Αρχεία κειμένου που χωρίζονται σε σελίδες. |
| [VisioRenderingOptions](../../groupdocs.viewer.options/baseviewoptions/visiorenderingoptions) { get; set; } | Οι επιλογές προβολής των αρχείων Visio που επεξεργάζονται έγγραφα. |
| [Watermark](../../groupdocs.viewer.options/viewoptions/watermark) { get; set; } | Το υδατογράφημα κειμένου που εφαρμόζεται σε κάθε σελίδα. |
| [WebDocumentOptions](../../groupdocs.viewer.options/baseviewoptions/webdocumentoptions) { get; set; } | Αυτές οι επιλογές απόδοσης σάς επιτρέπουν να προσαρμόσετε την εμφάνιση της εξόδου HTML/PDF/PNG/JPEG κατά την απόδοση εγγράφων Ιστού. |
| [WordProcessingOptions](../../groupdocs.viewer.options/baseviewoptions/wordprocessingoptions) { get; set; } | Αυτές οι επιλογές απόδοσης σάς επιτρέπουν να προσαρμόσετε την εμφάνιση της εξόδου HTML/PDF/PNG/JPEG κατά την απόδοση εγγράφων του Word. |

## Μέθοδοι

| Ονομα | Περιγραφή |
| --- | --- |
| [RotatePage](../../groupdocs.viewer.options/viewoptions/rotatepage)(int, Rotation) | Εφαρμόζει δεξιόστροφη περιστροφή στη σελίδα. |

## Πεδία

| Ονομα | Περιγραφή |
| --- | --- |
| readonly [PageRotations](../../groupdocs.viewer.options/viewoptions/pagerotations) | Οι περιστροφές σελίδων. |

### Δείτε επίσης

* class [ViewOptions](../viewoptions)
* χώρος ονομάτων [GroupDocs.Viewer.Options](../../groupdocs.viewer.options)
* συνέλευση [GroupDocs.Viewer](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Viewer.dll -->
