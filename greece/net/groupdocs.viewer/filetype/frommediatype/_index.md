---
title: "FromMediaType"
second_title: "Αναφορά API του GroupDocs.Viewer for .NET"
description: "Χαρτογραφεί τον τύπο μέσου αρχείου σε τύπο αρχείου π.χ. application/pdf θα αντιστοιχιστεί σε PDFgroupdocs.viewer/filetype/pdf."
type: docs
weight: 1990
url: /el/net/groupdocs.viewer/filetype/frommediatype/
---

## FileType.FromMediaType method

Maps file media type to file type e.g. 'application/pdf' will be mapped to [`PDF`](../pdf).

```csharp
public static FileType FromMediaType(string mediaType)
```

| Παράμετρος | Type | Περιγραφή |
| --- | --- | --- |
| mediaType | String | Τύπος μέσου αρχείου π.χ. application/pdf. |

### Τιμή Επιστροφής

Returns corresponding media type when found, otherwise returns default [`Unknown`](../unknown) file type.

### Δείτε επίσης

* class [FileType](../../filetype)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

<!-- ΜΗΝ ΕΠΕΞΕΡΓΑΣΕΤΕ: δημιουργήθηκε από το xmldocmd για το GroupDocs.Viewer.dll -->
