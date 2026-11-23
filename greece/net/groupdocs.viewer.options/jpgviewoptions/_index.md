---
title: "JpgViewOptions"
second_title: "Αναφορά API του GroupDocs.Viewer for .NET"
description: "Παρέχει επιλογές για την απόδοση εγγράφων σε μορφή JPG. Για λεπτομέρειες, δείτε αυτή τη σελίδα https//docs.groupdocs.com/viewer/net/renderingtopngorjpeg/ και τα υποσέλιδά της."
type: docs
weight: 350
url: /el/net/groupdocs.viewer.options/jpgviewoptions/
---

## JpgViewOptions class

Παρέχει επιλογές για την απόδοση εγγράφων σε μορφή JPG. Για λεπτομέρειες, δείτε αυτή τη [σελίδα](https://docs.groupdocs.com/viewer/net/rendering-to-png-or-jpeg/) και τα υπο-στοιχεία της.

```csharp
public class JpgViewOptions : ViewOptions, IMaxSizeOptions
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [JpgViewOptions](jpgviewoptions#constructor)() | Αρχικοποιεί ένα στιγμιότυπο της κλάσης [`JpgViewOptions`](../jpgviewoptions). |
| [JpgViewOptions](jpgviewoptions#constructor_1)(CreatePageStream) | Αρχικοποιεί ένα στιγμιότυπο της κλάσης [`JpgViewOptions`](../jpgviewoptions). |
| [JpgViewOptions](jpgviewoptions#constructor_3)(IPageStreamFactory) | Αρχικοποιεί ένα στιγμιότυπο της κλάσης [`JpgViewOptions`](../jpgviewoptions). |
| [JpgViewOptions](jpgviewoptions#constructor_4)(string) | Αρχικοποιεί ένα στιγμιότυπο της κλάσης [`JpgViewOptions`](../jpgviewoptions). |
| [JpgViewOptions](jpgviewoptions#constructor_2)(CreatePageStream, ReleasePageStream) | Αρχικοποιεί ένα στιγμιότυπο της κλάσης [`JpgViewOptions`](../jpgviewoptions). |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [ArchiveOptions](../../groupdocs.viewer.options/baseviewoptions/archiveoptions) { get; set; } | Οι επιλογές προβολής αρχείων αρχειοθέτησης. |
| [CadOptions](../../groupdocs.viewer.options/baseviewoptions/cadoptions) { get; set; } | Οι επιλογές προβολής σχεδίου CAD. |
| [DefaultFontName](../../groupdocs.viewer.options/baseviewoptions/defaultfontname) { get; set; } | Ορίζει τη προεπιλεγμένη γραμματοσειρά για ένα έγγραφο. |
| [EmailOptions](../../groupdocs.viewer.options/baseviewoptions/emailoptions) { get; set; } | Οι επιλογές προβολής μηνυμάτων email. |
| [ExtractText](../../groupdocs.viewer.options/jpgviewoptions/extracttext) { get; set; } | Ενεργοποιεί την εξαγωγή κειμένου. |
| [Height](../../groupdocs.viewer.options/jpgviewoptions/height) { get; set; } | Ορίζει το ύψος μιας εξόδου εικόνας (σε εικονοστοιχεία). |
| [MailStorageOptions](../../groupdocs.viewer.options/baseviewoptions/mailstorageoptions) { get; set; } | Οι επιλογές προβολής αρχείων δεδομένων αποθήκευσης αλληλογραφίας. |
| [MaxHeight](../../groupdocs.viewer.options/jpgviewoptions/maxheight) { get; set; } | Ορίζει το μέγιστο ύψος μιας εικόνας εξόδου (σε εικονοστοιχεία). |
| [MaxWidth](../../groupdocs.viewer.options/jpgviewoptions/maxwidth) { get; set; } | Ορίζει το μέγιστο πλάτος μιας εικόνας εξόδου (σε εικονοστοιχεία). |
| [OutlookOptions](../../groupdocs.viewer.options/baseviewoptions/outlookoptions) { get; set; } | Οι επιλογές προβολής αρχείων δεδομένων Microsoft Outlook. |
| [PdfOptions](../../groupdocs.viewer.options/baseviewoptions/pdfoptions) { get; set; } | Οι επιλογές προβολής εγγράφου PDF. |
| [PresentationOptions](../../groupdocs.viewer.options/baseviewoptions/presentationoptions) { get; set; } | Οι επιλογές προβολής αρχείων παρουσίασης. |
| [ProjectManagementOptions](../../groupdocs.viewer.options/baseviewoptions/projectmanagementoptions) { get; set; } | Οι επιλογές προβολής αρχείων διαχείρισης έργου. |
| [Quality](../../groupdocs.viewer.options/jpgviewoptions/quality) { get; set; } | Ορίζει την ποιότητα της εικόνας εξόδου. |
| [RemoveComments](../../groupdocs.viewer.options/baseviewoptions/removecomments) { get; set; } | Απενεργοποιεί την απόδοση σχολίων όταν ορίζεται σε `true`. Από προεπιλογή είναι `false` — όλα τα σχόλια εμφανίζονται. |
| [RenderHiddenPages](../../groupdocs.viewer.options/baseviewoptions/renderhiddenpages) { get; set; } | Ενεργοποιεί την απόδοση κρυφών σελίδων. |
| [RenderNotes](../../groupdocs.viewer.options/baseviewoptions/rendernotes) { get; set; } | Ενεργοποιεί την απόδοση σημειώσεων και σχολίων για ορισμένες μορφές. |
| [SpreadsheetOptions](../../groupdocs.viewer.options/baseviewoptions/spreadsheetoptions) { get; set; } | Οι επιλογές προβολής αρχείων λογιστικού φύλλου. |
| [TextOptions](../../groupdocs.viewer.options/baseviewoptions/textoptions) { get; set; } | Οι επιλογές προβολής αρχείων κειμένου. |
| [VisioRenderingOptions](../../groupdocs.viewer.options/baseviewoptions/visiorenderingoptions) { get; set; } | Οι επιλογές προβολής αρχείων Visio. |
| [Watermark](../../groupdocs.viewer.options/viewoptions/watermark) { get; set; } | Το υδατογράφημα κειμένου που θα εφαρμοστεί σε κάθε σελίδα. |
| [WebDocumentOptions](../../groupdocs.viewer.options/baseviewoptions/webdocumentoptions) { get; set; } | Οι επιλογές προβολής αρχείων Web. |
| [Width](../../groupdocs.viewer.options/jpgviewoptions/width) { get; set; } | Ορίζει το πλάτος της εικόνας εξόδου (σε εικονοστοιχεία). |
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
* interface [IMaxSizeOptions](../imaxsizeoptions)
* namespace [GroupDocs.Viewer.Options](../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../)

<!-- ΜΗΝ ΕΠΕΞΕΡΓΑΣΕΤΕ: δημιουργήθηκε από το xmldocmd για το GroupDocs.Viewer.dll -->
