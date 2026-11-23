---
title: "HtmlViewOptions"
second_title: "Αναφορά API του GroupDocs.Viewer for .NET"
description: "Περιέχει επιλογές για την απόδοση εγγράφων σε μορφή HTML. Για λεπτομέρειες δείτε το topichttps//docs.groupdocs.com/viewer/net/renderingtohtml/ και τα υπο-στοιχεία του."
type: docs
weight: 320
url: /el/net/groupdocs.viewer.options/htmlviewoptions/
---

## HtmlViewOptions class

Περιέχει επιλογές για την απόδοση εγγράφων σε μορφή HTML. Για λεπτομέρειες, δείτε το [θέμα](https://docs.groupdocs.com/viewer/net/rendering-to-html/) και τα υπο-στοιχεία του.

```csharp
public class HtmlViewOptions : ViewOptions
```

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [ArchiveOptions](../../groupdocs.viewer.options/baseviewoptions/archiveoptions) { get; set; } | Οι επιλογές προβολής αρχείων αρχειοθέτησης. |
| [CadOptions](../../groupdocs.viewer.options/baseviewoptions/cadoptions) { get; set; } | Οι επιλογές προβολής σχεδίου CAD. |
| [DefaultFontName](../../groupdocs.viewer.options/baseviewoptions/defaultfontname) { get; set; } | Ορίζει τη προεπιλεγμένη γραμματοσειρά για ένα έγγραφο. |
| [EmailOptions](../../groupdocs.viewer.options/baseviewoptions/emailoptions) { get; set; } | Οι επιλογές προβολής μηνυμάτων email. |
| [ExcludeFonts](../../groupdocs.viewer.options/htmlviewoptions/excludefonts) { get; set; } | Απενεργοποιεί την προσθήκη οποιασδήποτε γραμματοσειράς στο έγγραφο HTML. |
| [FontsToExclude](../../groupdocs.viewer.options/htmlviewoptions/fontstoexclude) { get; set; } | Η λίστα με τα ονόματα γραμματοσειρών που θα εξαλειφθούν από το έγγραφο HTML. |
| [ForPrinting](../../groupdocs.viewer.options/htmlviewoptions/forprinting) { get; set; } | Ενεργοποιεί τη βελτιστοποίηση του παραγόμενου HTML για εκτύπωση. |
| [ImageHeight](../../groupdocs.viewer.options/htmlviewoptions/imageheight) { get; set; } | Το ύψος μιας εικόνας εξόδου (σε εικονοστοιχεία). Η ιδιότητα είναι διαθέσιμη μόνο όταν γίνεται μετατροπή μιας μόνο εικόνας σε HTML. |
| [ImageMaxHeight](../../groupdocs.viewer.options/htmlviewoptions/imagemaxheight) { get; set; } | Μέγιστο ύψος εξόδου εικόνας (σε pixel). Η ιδιότητα είναι διαθέσιμη μόνο κατά τη μετατροπή μιας μόνο εικόνας σε HTML. |
| [ImageMaxWidth](../../groupdocs.viewer.options/htmlviewoptions/imagemaxwidth) { get; set; } | Μέγιστο πλάτος εξόδου εικόνας (σε pixel). Η ιδιότητα είναι διαθέσιμη μόνο κατά τη μετατροπή μιας μόνο εικόνας σε HTML. |
| [ImageWidth](../../groupdocs.viewer.options/htmlviewoptions/imagewidth) { get; set; } | Το πλάτος της εξόδου εικόνας (σε pixel). Η ιδιότητα είναι διαθέσιμη μόνο κατά τη μετατροπή μιας μόνο εικόνας σε HTML. |
| [MailStorageOptions](../../groupdocs.viewer.options/baseviewoptions/mailstorageoptions) { get; set; } | Οι επιλογές προβολής αρχείων δεδομένων αποθήκευσης αλληλογραφίας. |
| [Minify](../../groupdocs.viewer.options/htmlviewoptions/minify) { get; set; } | Ενεργοποιεί τη συμπίεση περιεχομένου HTML και πόρων HTML. |
| [OutlookOptions](../../groupdocs.viewer.options/baseviewoptions/outlookoptions) { get; set; } | Οι επιλογές προβολής αρχείων δεδομένων Microsoft Outlook. |
| [PdfOptions](../../groupdocs.viewer.options/baseviewoptions/pdfoptions) { get; set; } | Οι επιλογές προβολής εγγράφου PDF. |
| [PresentationOptions](../../groupdocs.viewer.options/baseviewoptions/presentationoptions) { get; set; } | Οι επιλογές προβολής αρχείων παρουσίασης. |
| [ProjectManagementOptions](../../groupdocs.viewer.options/baseviewoptions/projectmanagementoptions) { get; set; } | Οι επιλογές προβολής αρχείων διαχείρισης έργου. |
| [RemoveComments](../../groupdocs.viewer.options/baseviewoptions/removecomments) { get; set; } | Απενεργοποιεί την απόδοση σχολίων όταν ορίζεται σε `true`. Από προεπιλογή είναι `false` — όλα τα σχόλια εμφανίζονται. |
| [RemoveJavaScript](../../groupdocs.viewer.options/htmlviewoptions/removejavascript) { get; set; } | Επιτρέπει την αφαίρεση του κώδικα πηγαίου JavaScript από τους συνδέσμους στα τελικά έγγραφα HTML, κατά την απόδοση των εισερχόμενων εγγράφων που περιέχουν τα σενάρια. Από προεπιλογή είναι ενεργοποιημένο (`true`). |
| [RenderHiddenPages](../../groupdocs.viewer.options/baseviewoptions/renderhiddenpages) { get; set; } | Ενεργοποιεί την απόδοση κρυφών σελίδων. |
| [RenderNotes](../../groupdocs.viewer.options/baseviewoptions/rendernotes) { get; set; } | Ενεργοποιεί την απόδοση σημειώσεων και σχολίων για ορισμένες μορφές. |
| [RenderResponsive](../../groupdocs.viewer.options/htmlviewoptions/renderresponsive) { get; set; } | Ενεργοποιεί την ανταποκρινόμενη απόδοση. |
| [RenderToSinglePage](../../groupdocs.viewer.options/htmlviewoptions/rendertosinglepage) { get; set; } | Ενεργοποιεί την απόδοση ολόκληρου εγγράφου σε ένα αρχείο HTML. |
| [SpreadsheetOptions](../../groupdocs.viewer.options/baseviewoptions/spreadsheetoptions) { get; set; } | Οι επιλογές προβολής αρχείων λογιστικού φύλλου. |
| [TextOptions](../../groupdocs.viewer.options/baseviewoptions/textoptions) { get; set; } | Οι επιλογές προβολής αρχείων κειμένου. |
| [VisioRenderingOptions](../../groupdocs.viewer.options/baseviewoptions/visiorenderingoptions) { get; set; } | Οι επιλογές προβολής αρχείων Visio. |
| [Watermark](../../groupdocs.viewer.options/viewoptions/watermark) { get; set; } | Το υδατογράφημα κειμένου που θα εφαρμοστεί σε κάθε σελίδα. |
| [WebDocumentOptions](../../groupdocs.viewer.options/baseviewoptions/webdocumentoptions) { get; set; } | Οι επιλογές προβολής αρχείων Web. |
| [WordProcessingOptions](../../groupdocs.viewer.options/baseviewoptions/wordprocessingoptions) { get; set; } | Οι επιλογές προβολής αρχείων επεξεργασίας κειμένου. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| static [ForEmbeddedResources](../../groupdocs.viewer.options/htmlviewoptions/forembeddedresources#forembeddedresources)() | Αρχικοποιεί μια παρουσία της κλάσης [`HtmlViewOptions`](../htmlviewoptions). |
| static [ForEmbeddedResources](../../groupdocs.viewer.options/htmlviewoptions/forembeddedresources#forembeddedresources_1)(CreatePageStream) | Αρχικοποιεί μια παρουσία της κλάσης [`HtmlViewOptions`](../htmlviewoptions) για απόδοση σε HTML με ενσωματωμένους πόρους. |
| static [ForEmbeddedResources](../../groupdocs.viewer.options/htmlviewoptions/forembeddedresources#forembeddedresources_3)(IPageStreamFactory) | Αρχικοποιεί μια παρουσία της κλάσης [`HtmlViewOptions`](../htmlviewoptions) για απόδοση σε HTML με ενσωματωμένους πόρους. |
| static [ForEmbeddedResources](../../groupdocs.viewer.options/htmlviewoptions/forembeddedresources#forembeddedresources_4)(string) | Αρχικοποιεί μια παρουσία της κλάσης [`HtmlViewOptions`](../htmlviewoptions). |
| static [ForEmbeddedResources](../../groupdocs.viewer.options/htmlviewoptions/forembeddedresources#forembeddedresources_2)(CreatePageStream, ReleasePageStream) | Αρχικοποιεί μια παρουσία της κλάσης [`HtmlViewOptions`](../htmlviewoptions) για απόδοση σε HTML με ενσωματωμένους πόρους. |
| static [ForExternalResources](../../groupdocs.viewer.options/htmlviewoptions/forexternalresources#forexternalresources)() | Αρχικοποιεί μια παρουσία της κλάσης [`HtmlViewOptions`](../htmlviewoptions). |
| static [ForExternalResources](../../groupdocs.viewer.options/htmlviewoptions/forexternalresources#forexternalresources_3)(IPageStreamFactory, IResourceStreamFactory) | Αρχικοποιεί μια παρουσία της κλάσης [`HtmlViewOptions`](../htmlviewoptions) για απόδοση σε HTML με εξωτερικούς πόρους. |
| static [ForExternalResources](../../groupdocs.viewer.options/htmlviewoptions/forexternalresources#forexternalresources_1)(CreatePageStream, CreateResourceStream, CreateResourceUrl) | Αρχικοποιεί μια παρουσία της κλάσης [`HtmlViewOptions`](../htmlviewoptions) για απόδοση σε HTML με εξωτερικούς πόρους. |
| static [ForExternalResources](../../groupdocs.viewer.options/htmlviewoptions/forexternalresources#forexternalresources_4)(string, string, string) | Αρχικοποιεί μια παρουσία της κλάσης [`HtmlViewOptions`](../htmlviewoptions). |
| static [ForExternalResources](../../groupdocs.viewer.options/htmlviewoptions/forexternalresources#forexternalresources_2)(CreatePageStream, CreateResourceStream, CreateResourceUrl, ReleasePageStream, ReleaseResourceStream) | Αρχικοποιεί μια παρουσία της κλάσης [`HtmlViewOptions`](../htmlviewoptions) για απόδοση σε HTML με εξωτερικούς πόρους. |
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
