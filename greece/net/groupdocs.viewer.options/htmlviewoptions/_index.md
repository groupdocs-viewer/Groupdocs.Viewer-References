---
title: HtmlViewOptions
second_title: GroupDocs.Viewer για Αναφορά API .NET
description: Παρέχει επιλογές για απόδοση εγγράφων σε μορφή HTML.
type: docs
weight: 330
url: /el/net/groupdocs.viewer.options/htmlviewoptions/
---
## HtmlViewOptions class

Παρέχει επιλογές για απόδοση εγγράφων σε μορφή HTML.

```csharp
public class HtmlViewOptions : ViewOptions
```

## Ιδιότητες

| Ονομα | Περιγραφή |
| --- | --- |
| [ArchiveOptions](../../groupdocs.viewer.options/baseviewoptions/archiveoptions) { get; set; } | Οι επιλογές προβολής των αρχείων αρχειοθέτησης. |
| [CadOptions](../../groupdocs.viewer.options/baseviewoptions/cadoptions) { get; set; } | Οι επιλογές προβολής σχεδίασης CAD. |
| [DefaultFontName](../../groupdocs.viewer.options/baseviewoptions/defaultfontname) { get; set; } | Προεπιλεγμένη γραμματοσειρά που χρησιμοποιείται όταν δεν μπορεί να βρεθεί συγκεκριμένη γραμματοσειρά που χρησιμοποιείται στο έγγραφο. |
| [EmailOptions](../../groupdocs.viewer.options/baseviewoptions/emailoptions) { get; set; } | Οι επιλογές προβολής μηνυμάτων email. |
| [ExcludeFonts](../../groupdocs.viewer.options/htmlviewoptions/excludefonts) { get; set; } | Το Όταν είναι ενεργοποιημένο, αποτρέπει την προσθήκη γραμματοσειρών σε έγγραφο HTML. |
| [FontsToExclude](../../groupdocs.viewer.options/htmlviewoptions/fontstoexclude) { get; set; } | Η λίστα με τα ονόματα γραμματοσειρών, προς εξαίρεση από το έγγραφο HTML. |
| [ForPrinting](../../groupdocs.viewer.options/htmlviewoptions/forprinting) { get; set; } | Υποδεικνύει εάν θα βελτιστοποιηθεί η έξοδος HTML για εκτύπωση. |
| [ImageHeight](../../groupdocs.viewer.options/htmlviewoptions/imageheight) { get; set; } | Το ύψος μιας εικόνας εξόδου σε pixel. (Μόνο κατά τη μετατροπή μιας εικόνας σε HTML) |
| [ImageMaxHeight](../../groupdocs.viewer.options/htmlviewoptions/imagemaxheight) { get; set; } | Μέγιστο ύψος εικόνας εξόδου σε pixel. (Μόνο κατά τη μετατροπή μιας εικόνας σε HTML) |
| [ImageMaxWidth](../../groupdocs.viewer.options/htmlviewoptions/imagemaxwidth) { get; set; } | Μέγιστο πλάτος εικόνας εξόδου σε pixel. (Μόνο κατά τη μετατροπή μιας εικόνας σε HTML) |
| [ImageWidth](../../groupdocs.viewer.options/htmlviewoptions/imagewidth) { get; set; } | Το πλάτος της εικόνας εξόδου σε pixel. (Μόνο κατά τη μετατροπή μιας εικόνας σε HTML) |
| [MailStorageOptions](../../groupdocs.viewer.options/baseviewoptions/mailstorageoptions) { get; set; } | Επιλογές προβολής αρχείων δεδομένων αποθήκευσης αλληλογραφίας. |
| [Minify](../../groupdocs.viewer.options/htmlviewoptions/minify) { get; set; } | Ενεργοποιεί την ελαχιστοποίηση περιεχομένου HTML και πόρων HTML. |
| [OutlookOptions](../../groupdocs.viewer.options/baseviewoptions/outlookoptions) { get; set; } | Επιλογές προβολής αρχείων δεδομένων MS Outlook. |
| [PdfOptions](../../groupdocs.viewer.options/baseviewoptions/pdfoptions) { get; set; } | Οι επιλογές προβολής εγγράφων PDF. |
| [PresentationOptions](../../groupdocs.viewer.options/baseviewoptions/presentationoptions) { get; set; } | Οι επιλογές προβολής εγγράφων επεξεργασίας παρουσίασης. |
| [ProjectManagementOptions](../../groupdocs.viewer.options/baseviewoptions/projectmanagementoptions) { get; set; } | Επιλογές προβολής των αρχείων διαχείρισης έργου. |
| [RenderComments](../../groupdocs.viewer.options/baseviewoptions/rendercomments) { get; set; } | Ενεργοποιεί την απόδοση σχολίων. |
| [RenderHiddenPages](../../groupdocs.viewer.options/baseviewoptions/renderhiddenpages) { get; set; } | Ενεργοποιεί την απόδοση κρυφών σελίδων. |
| [RenderNotes](../../groupdocs.viewer.options/baseviewoptions/rendernotes) { get; set; } | Ενεργοποιεί την απόδοση σημειώσεων. |
| [RenderResponsive](../../groupdocs.viewer.options/htmlviewoptions/renderresponsive) { get; set; } | Ενεργοποιεί την αποκριτική απόδοση. Οι αποκριτικές ιστοσελίδες αποδίδονται καλά σε συσκευές με διαφορετικό μέγεθος οθόνης. |
| [RenderToSinglePage](../../groupdocs.viewer.options/htmlviewoptions/rendertosinglepage) { get; set; } | Επιτρέπει την απόδοση ολόκληρου του εγγράφου σε ένα αρχείο HTML. |
| [SpreadsheetOptions](../../groupdocs.viewer.options/baseviewoptions/spreadsheetoptions) { get; set; } | Οι επιλογές προβολής των αρχείων υπολογιστικού φύλλου. |
| [TextOptions](../../groupdocs.viewer.options/baseviewoptions/textoptions) { get; set; } | Αρχεία κειμένου που χωρίζονται σε σελίδες. |
| [VisioRenderingOptions](../../groupdocs.viewer.options/baseviewoptions/visiorenderingoptions) { get; set; } | Οι επιλογές προβολής των αρχείων Visio που επεξεργάζονται έγγραφα. |
| [Watermark](../../groupdocs.viewer.options/viewoptions/watermark) { get; set; } | Το υδατογράφημα κειμένου που εφαρμόζεται σε κάθε σελίδα. |
| [WebDocumentOptions](../../groupdocs.viewer.options/baseviewoptions/webdocumentoptions) { get; set; } | Αυτές οι επιλογές απόδοσης σάς επιτρέπουν να προσαρμόσετε την εμφάνιση της εξόδου HTML/PDF/PNG/JPEG κατά την απόδοση εγγράφων Ιστού. |
| [WordProcessingOptions](../../groupdocs.viewer.options/baseviewoptions/wordprocessingoptions) { get; set; } | Αυτές οι επιλογές απόδοσης σάς επιτρέπουν να προσαρμόσετε την εμφάνιση της εξόδου HTML/PDF/PNG/JPEG κατά την απόδοση εγγράφων του Word. |

## Μέθοδοι

| Ονομα | Περιγραφή |
| --- | --- |
| static [ForEmbeddedResources](../../groupdocs.viewer.options/htmlviewoptions/forembeddedresources#forembeddedresources)() | Αρχικοποιεί νέα παρουσία του[`HtmlViewOptions`](../htmlviewoptions) τάξη. |
| static [ForEmbeddedResources](../../groupdocs.viewer.options/htmlviewoptions/forembeddedresources#forembeddedresources_1)(CreatePageStream) | Αρχικοποιεί νέα παρουσία του[`HtmlViewOptions`](../htmlviewoptions) κλάση για απόδοση σε HTML με ενσωματωμένους πόρους. |
| static [ForEmbeddedResources](../../groupdocs.viewer.options/htmlviewoptions/forembeddedresources#forembeddedresources_3)(IPageStreamFactory) | Αρχικοποιεί νέα παρουσία του[`HtmlViewOptions`](../htmlviewoptions) κλάση για απόδοση σε HTML με ενσωματωμένους πόρους. |
| static [ForEmbeddedResources](../../groupdocs.viewer.options/htmlviewoptions/forembeddedresources#forembeddedresources_4)(string) | Αρχικοποιεί νέα παρουσία του[`HtmlViewOptions`](../htmlviewoptions) τάξη. |
| static [ForEmbeddedResources](../../groupdocs.viewer.options/htmlviewoptions/forembeddedresources#forembeddedresources_2)(CreatePageStream, ReleasePageStream) | Αρχικοποιεί νέα παρουσία του[`HtmlViewOptions`](../htmlviewoptions) κλάση για απόδοση σε HTML με ενσωματωμένους πόρους. |
| static [ForExternalResources](../../groupdocs.viewer.options/htmlviewoptions/forexternalresources#forexternalresources)() | Αρχικοποιεί νέα παρουσία του[`HtmlViewOptions`](../htmlviewoptions) τάξη. |
| static [ForExternalResources](../../groupdocs.viewer.options/htmlviewoptions/forexternalresources#forexternalresources_3)(IPageStreamFactory, IResourceStreamFactory) | Αρχικοποιεί νέα παρουσία του[`HtmlViewOptions`](../htmlviewoptions) κλάση για απόδοση σε HTML με εξωτερικούς πόρους. |
| static [ForExternalResources](../../groupdocs.viewer.options/htmlviewoptions/forexternalresources#forexternalresources_1)(CreatePageStream, CreateResourceStream, CreateResourceUrl) | Αρχικοποιεί νέα παρουσία του[`HtmlViewOptions`](../htmlviewoptions) κλάση για απόδοση σε HTML με εξωτερικούς πόρους. |
| static [ForExternalResources](../../groupdocs.viewer.options/htmlviewoptions/forexternalresources#forexternalresources_4)(string, string, string) | Αρχικοποιεί νέα παρουσία του[`HtmlViewOptions`](../htmlviewoptions) τάξη. |
| static [ForExternalResources](../../groupdocs.viewer.options/htmlviewoptions/forexternalresources#forexternalresources_2)(CreatePageStream, CreateResourceStream, CreateResourceUrl, ReleasePageStream, ReleaseResourceStream) | Αρχικοποιεί νέα παρουσία του[`HtmlViewOptions`](../htmlviewoptions) κλάση για απόδοση σε HTML με εξωτερικούς πόρους. |
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
