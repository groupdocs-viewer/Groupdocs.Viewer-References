---
title: "PngViewOptions"
second_title: "Αναφορά API του GroupDocs.Viewer for .NET"
description: "Περιέχει επιλογές για απόδοση εγγράφων σε μορφή PNG. Για λεπτομέρειες δείτε αυτή τη σελίδα https//docs.groupdocs.com/viewer/net/renderingtopngorjpeg/ και τα υποσέλιδά της."
type: docs
weight: 440
url: /el/net/groupdocs.viewer.options/pngviewoptions/
---

## PngViewOptions class

Περιέχει επιλογές για την απόδοση εγγράφων σε μορφή PNG. Για λεπτομέρειες, δείτε αυτή τη [σελίδα](https://docs.groupdocs.com/viewer/net/rendering-to-png-or-jpeg/) και τα υπο-στοιχεία της.

```csharp
public class PngViewOptions : ViewOptions, IMaxSizeOptions
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [PngViewOptions](pngviewoptions#constructor)() | Αρχικοποιεί μια παρουσία της κλάσης [`PngViewOptions`](../pngviewoptions). |
| [PngViewOptions](pngviewoptions#constructor_1)(CreatePageStream) | Αρχικοποιεί μια παρουσία της κλάσης [`PngViewOptions`](../pngviewoptions). |
| [PngViewOptions](pngviewoptions#constructor_3)(IPageStreamFactory) | Αρχικοποιεί μια παρουσία της κλάσης [`PngViewOptions`](../pngviewoptions). |
| [PngViewOptions](pngviewoptions#constructor_4)(string) | Αρχικοποιεί μια παρουσία της κλάσης [`PngViewOptions`](../pngviewoptions). |
| [PngViewOptions](pngviewoptions#constructor_2)(CreatePageStream, ReleasePageStream) | Αρχικοποιεί μια παρουσία της κλάσης [`PngViewOptions`](../pngviewoptions). |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [ArchiveOptions](../../groupdocs.viewer.options/baseviewoptions/archiveoptions) { get; set; } | Οι επιλογές προβολής αρχείων αρχειοθέτησης. |
| [CadOptions](../../groupdocs.viewer.options/baseviewoptions/cadoptions) { get; set; } | Οι επιλογές προβολής σχεδίου CAD. |
| [DefaultFontName](../../groupdocs.viewer.options/baseviewoptions/defaultfontname) { get; set; } | Ορίζει τη προεπιλεγμένη γραμματοσειρά για ένα έγγραφο. |
| [EmailOptions](../../groupdocs.viewer.options/baseviewoptions/emailoptions) { get; set; } | Οι επιλογές προβολής μηνυμάτων email. |
| [ExtractText](../../groupdocs.viewer.options/pngviewoptions/extracttext) { get; set; } | Ενεργοποιεί την εξαγωγή κειμένου. |
| [Height](../../groupdocs.viewer.options/pngviewoptions/height) { get; set; } | Ορίζει το ύψος μιας εξόδου εικόνας (σε εικονοστοιχεία). |
| [MailStorageOptions](../../groupdocs.viewer.options/baseviewoptions/mailstorageoptions) { get; set; } | Οι επιλογές προβολής αρχείων δεδομένων αποθήκευσης αλληλογραφίας. |
| [MaxHeight](../../groupdocs.viewer.options/pngviewoptions/maxheight) { get; set; } | Ορίζει το μέγιστο ύψος μιας εικόνας εξόδου (σε εικονοστοιχεία). |
| [MaxWidth](../../groupdocs.viewer.options/pngviewoptions/maxwidth) { get; set; } | Ορίζει το μέγιστο πλάτος μιας εικόνας εξόδου (σε εικονοστοιχεία). |
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
| [Watermark](../../groupdocs.viewer.options/viewoptions/watermark) { get; set; } | Το υδατογράφημα κειμένου που θα εφαρμοστεί σε κάθε σελίδα. |
| [WebDocumentOptions](../../groupdocs.viewer.options/baseviewoptions/webdocumentoptions) { get; set; } | Οι επιλογές προβολής αρχείων Web. |
| [Width](../../groupdocs.viewer.options/pngviewoptions/width) { get; set; } | Το πλάτος της εξόδου εικόνας (σε pixel). |
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
