---
title: LoadOptions
second_title: GroupDocs.Viewer για Αναφορά API .NET
description: Παρέχει επιλογές που χρησιμοποιήθηκαν για το άνοιγμα του αρχείου.
type: docs
weight: 370
url: /el/net/groupdocs.viewer.options/loadoptions/
---
## LoadOptions class

Παρέχει επιλογές που χρησιμοποιήθηκαν για το άνοιγμα του αρχείου.

```csharp
public class LoadOptions
```

## Κατασκευαστές

| Ονομα | Περιγραφή |
| --- | --- |
| [LoadOptions](loadoptions#constructor)() | Αρχικοποιεί νέα παρουσία του[`LoadOptions`](../loadoptions) τάξη. |
| [LoadOptions](loadoptions#constructor_1)(FileType) | Αρχικοποιεί νέα παρουσία του[`LoadOptions`](../loadoptions) τάξη. |

## Ιδιότητες

| Ονομα | Περιγραφή |
| --- | --- |
| [DetectEncoding](../../groupdocs.viewer.options/loadoptions/detectencoding) { get; set; } | Αυτή η επιλογή ενεργοποιεί[`TXT`](../../groupdocs.viewer/filetype/txt) ,[`TSV`](../../groupdocs.viewer/filetype/tsv) , και[`CSV`](../../groupdocs.viewer/filetype/csv)εντοπισμός κωδικοποίησης αρχείων. Σε περίπτωση που δεν μπορεί να εντοπιστεί η κωδικοποίηση, η προεπιλογή[`Encoding`](./encoding) χρησιμοποιείται. |
| [Encoding](../../groupdocs.viewer.options/loadoptions/encoding) { get; set; } | Η κωδικοποίηση που χρησιμοποιείται κατά το άνοιγμα αρχείων κειμένου ή μηνυμάτων email όπως [`CSV`](../../groupdocs.viewer/filetype/csv) , [`TXT`](../../groupdocs.viewer/filetype/txt) , και[`MSG`](../../groupdocs.viewer/filetype/msg) . Η προεπιλεγμένη τιμή είναιUTF8 . |
| [FileType](../../groupdocs.viewer.options/loadoptions/filetype) { get; set; } | Ο τύπος του αρχείου που θα ανοίξει. |
| [Password](../../groupdocs.viewer.options/loadoptions/password) { get; set; } | Ο κωδικός πρόσβασης για το άνοιγμα κρυπτογραφημένου αρχείου. |
| [ResourceLoadingTimeout](../../groupdocs.viewer.options/loadoptions/resourceloadingtimeout) { get; set; } | Οι εξωτερικοί πόροι π.χ. λήξη χρονικού ορίου φόρτωσης γραφικών. Η προεπιλεγμένη τιμή είναι 30 δευτερόλεπτα. Αυτή η επιλογή υποστηρίζεται για έγγραφα επεξεργασίας κειμένου που περιέχουν εξωτερικούς πόρους. |

### Δείτε επίσης

* χώρος ονομάτων [GroupDocs.Viewer.Options](../../groupdocs.viewer.options)
* συνέλευση [GroupDocs.Viewer](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Viewer.dll -->