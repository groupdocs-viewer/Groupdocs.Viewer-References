---
title: JpgViewOptions
second_title: GroupDocs.Viewer για Αναφορά API .NET
description: Παρέχει επιλογές για απόδοση εγγράφων σε μορφή JPG.
type: docs
weight: 360
url: /el/net/groupdocs.viewer.options/jpgviewoptions/
---
## JpgViewOptions class

Παρέχει επιλογές για απόδοση εγγράφων σε μορφή JPG.

```csharp
public class JpgViewOptions : ViewOptions, IMaxSizeOptions
```

## Κατασκευαστές

| Ονομα | Περιγραφή |
| --- | --- |
| [JpgViewOptions](jpgviewoptions#constructor)() | Αρχικοποιεί νέα παρουσία του[`JpgViewOptions`](../jpgviewoptions) τάξη. |
| [JpgViewOptions](jpgviewoptions#constructor_1)(CreatePageStream) | Αρχικοποιεί νέα παρουσία του[`JpgViewOptions`](../jpgviewoptions) τάξη. |
| [JpgViewOptions](jpgviewoptions#constructor_3)(IPageStreamFactory) | Αρχικοποιεί νέα παρουσία του[`JpgViewOptions`](../jpgviewoptions) τάξη. |
| [JpgViewOptions](jpgviewoptions#constructor_4)(string) | Αρχικοποιεί νέα παρουσία του[`JpgViewOptions`](../jpgviewoptions) τάξη. |
| [JpgViewOptions](jpgviewoptions#constructor_2)(CreatePageStream, ReleasePageStream) | Αρχικοποιεί νέα παρουσία του[`JpgViewOptions`](../jpgviewoptions) τάξη. |

## Ιδιότητες

| Ονομα | Περιγραφή |
| --- | --- |
| [ArchiveOptions](../../groupdocs.viewer.options/baseviewoptions/archiveoptions) { get; set; } | Οι επιλογές προβολής των αρχείων αρχειοθέτησης. |
| [CadOptions](../../groupdocs.viewer.options/baseviewoptions/cadoptions) { get; set; } | Οι επιλογές προβολής σχεδίασης CAD. |
| [DefaultFontName](../../groupdocs.viewer.options/baseviewoptions/defaultfontname) { get; set; } | Προεπιλεγμένη γραμματοσειρά που χρησιμοποιείται όταν δεν μπορεί να βρεθεί συγκεκριμένη γραμματοσειρά που χρησιμοποιείται στο έγγραφο. |
| [EmailOptions](../../groupdocs.viewer.options/baseviewoptions/emailoptions) { get; set; } | Οι επιλογές προβολής μηνυμάτων email. |
| [ExtractText](../../groupdocs.viewer.options/jpgviewoptions/extracttext) { get; set; } | Ενεργοποιεί την εξαγωγή κειμένου. |
| [Height](../../groupdocs.viewer.options/jpgviewoptions/height) { get; set; } | Το ύψος μιας εικόνας εξόδου σε pixel. |
| [MailStorageOptions](../../groupdocs.viewer.options/baseviewoptions/mailstorageoptions) { get; set; } | Επιλογές προβολής αρχείων δεδομένων αποθήκευσης αλληλογραφίας. |
| [MaxHeight](../../groupdocs.viewer.options/jpgviewoptions/maxheight) { get; set; } | Μέγιστο ύψος εικόνας εξόδου σε pixel. |
| [MaxWidth](../../groupdocs.viewer.options/jpgviewoptions/maxwidth) { get; set; } | Μέγιστο πλάτος εικόνας εξόδου σε pixel. |
| [OutlookOptions](../../groupdocs.viewer.options/baseviewoptions/outlookoptions) { get; set; } | Επιλογές προβολής αρχείων δεδομένων MS Outlook. |
| [PdfOptions](../../groupdocs.viewer.options/baseviewoptions/pdfoptions) { get; set; } | Οι επιλογές προβολής εγγράφων PDF. |
| [PresentationOptions](../../groupdocs.viewer.options/baseviewoptions/presentationoptions) { get; set; } | Οι επιλογές προβολής εγγράφων επεξεργασίας παρουσίασης. |
| [ProjectManagementOptions](../../groupdocs.viewer.options/baseviewoptions/projectmanagementoptions) { get; set; } | Επιλογές προβολής των αρχείων διαχείρισης έργου. |
| [Quality](../../groupdocs.viewer.options/jpgviewoptions/quality) { get; set; } | Ποιότητα της εικόνας εξόδου; Οι έγκυρες τιμές είναι μεταξύ 1 και 100; Η προεπιλεγμένη τιμή είναι 90. |
| [RenderComments](../../groupdocs.viewer.options/baseviewoptions/rendercomments) { get; set; } | Ενεργοποιεί την απόδοση σχολίων. |
| [RenderHiddenPages](../../groupdocs.viewer.options/baseviewoptions/renderhiddenpages) { get; set; } | Ενεργοποιεί την απόδοση κρυφών σελίδων. |
| [RenderNotes](../../groupdocs.viewer.options/baseviewoptions/rendernotes) { get; set; } | Ενεργοποιεί την απόδοση σημειώσεων. |
| [SpreadsheetOptions](../../groupdocs.viewer.options/baseviewoptions/spreadsheetoptions) { get; set; } | Οι επιλογές προβολής των αρχείων υπολογιστικού φύλλου. |
| [TextOptions](../../groupdocs.viewer.options/baseviewoptions/textoptions) { get; set; } | Αρχεία κειμένου που χωρίζονται σε σελίδες. |
| [VisioRenderingOptions](../../groupdocs.viewer.options/baseviewoptions/visiorenderingoptions) { get; set; } | Οι επιλογές προβολής των αρχείων Visio που επεξεργάζονται έγγραφα. |
| [Watermark](../../groupdocs.viewer.options/viewoptions/watermark) { get; set; } | Το υδατογράφημα κειμένου που εφαρμόζεται σε κάθε σελίδα. |
| [WebDocumentOptions](../../groupdocs.viewer.options/baseviewoptions/webdocumentoptions) { get; set; } | Αυτές οι επιλογές απόδοσης σάς επιτρέπουν να προσαρμόσετε την εμφάνιση της εξόδου HTML/PDF/PNG/JPEG κατά την απόδοση εγγράφων Ιστού. |
| [Width](../../groupdocs.viewer.options/jpgviewoptions/width) { get; set; } | Το πλάτος της εικόνας εξόδου σε pixel. |
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
* interface [IMaxSizeOptions](../imaxsizeoptions)
* χώρος ονομάτων [GroupDocs.Viewer.Options](../../groupdocs.viewer.options)
* συνέλευση [GroupDocs.Viewer](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Viewer.dll -->
