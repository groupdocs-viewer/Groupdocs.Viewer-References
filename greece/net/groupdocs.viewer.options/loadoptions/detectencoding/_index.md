---
title: DetectEncoding
second_title: GroupDocs.Viewer για Αναφορά API .NET
description: Αυτή η επιλογή ενεργοποιείTXTgroupdocs.viewer/filetype/txt TSVgroupdocs.viewer/filetype/tsv  καιCSVgroupdocs.viewer/filetype/csvεντοπισμός κωδικοποίησης αρχείων. Σε περίπτωση που δεν μπορεί να εντοπιστεί η κωδικοποίηση η προεπιλογήEncodinggroupdocs.viewer.options/loadoptions/encoding χρησιμοποιείται.
type: docs
weight: 20
url: /el/net/groupdocs.viewer.options/loadoptions/detectencoding/
---
## LoadOptions.DetectEncoding property

Αυτή η επιλογή ενεργοποιεί[`TXT`](../../../groupdocs.viewer/filetype/txt) ,[`TSV`](../../../groupdocs.viewer/filetype/tsv) , και[`CSV`](../../../groupdocs.viewer/filetype/csv)εντοπισμός κωδικοποίησης αρχείων. Σε περίπτωση που δεν μπορεί να εντοπιστεί η κωδικοποίηση, η προεπιλογή[`Encoding`](../encoding) χρησιμοποιείται.

```csharp
public bool DetectEncoding { get; set; }
```

### Παρατηρήσεις

**Μάθετε περισσότερα σχετικά με την απόδοση κειμένου και αρχείων οριοθετημένων καρτελών/κομμάτων**

* [Αποδώστε έγγραφα κειμένου ως αρχεία HTML, PDF και εικόνας](https://docs.groupdocs.com/viewer/net/render-text-files/)
* [Αποδώστε υπολογιστικά φύλλα Excel και Apple Numbers ως αρχεία HTML, PDF και εικόνας](https://docs.groupdocs.com/viewer/net/render-excel-and-apple-numbers-spreadsheets/)

### Παραδείγματα

Το παράδειγμα δείχνει μια τυπική χρήση αυτής της επιλογής.

```csharp
LoadOptions loadOptions = new LoadOptions();
loadOptions.DetectEncoding = true; // Ενεργοποίηση ανίχνευσης κωδικοποίησης

using (Viewer viewer = new Viewer("employees.csv", loadOptions))
{
    HtmlViewOptions viewOptions = 
        HtmlViewOptions.ForEmbeddedResources();

    viewer.View(viewOptions);
}
```

### Δείτε επίσης

* class [LoadOptions](../../loadoptions)
* χώρος ονομάτων [GroupDocs.Viewer.Options](../../loadoptions)
* συνέλευση [GroupDocs.Viewer](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Viewer.dll -->
