---
title: "IsSearchTermRegEx"
second_title: "Αναφορά API του GroupDocs.Viewer for .NET"
description: "Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν ο όρος αναζήτησης πρέπει να αντιμετωπίζεται ως κανονική έκφραση ή ως κυριολεκτικό κείμενο. Η προεπιλογή είναι false, αντιμετωπίζεται ως κυριολεκτικό κείμενο."
type: docs
weight: 40
url: /el/net/groupdocs.viewer.options/searchhighlightoptions/issearchtermregex/
---

## SearchHighlightOptions.IsSearchTermRegEx property

Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν ο όρος αναζήτησης πρέπει να αντιμετωπίζεται ως κανονική έκφραση ή ως κυριολεκτικό κείμενο. Η προεπιλογή είναι `false` — αντιμετωπίζεται ως κυριολεκτικό κείμενο.

```csharp
public bool IsSearchTermRegEx { get; set; }
```

### Παρατηρήσεις

Εάν είναι `true`, το [`SearchTerm`](../searchterm) ερμηνεύεται ως πρότυπο .NET Regex.

Εάν είναι `false`, το [`SearchTerm`](../searchterm) αναζητείται ως κυριολεκτικό κείμενο στο έγγραφο.

### Δείτε επίσης

* class [SearchHighlightOptions](../../searchhighlightoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

<!-- ΜΗΝ ΕΠΕΞΕΡΓΑΣΕΤΕ: δημιουργήθηκε από το xmldocmd για το GroupDocs.Viewer.dll -->
