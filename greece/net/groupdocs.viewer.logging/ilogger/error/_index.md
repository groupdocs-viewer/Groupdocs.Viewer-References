---
title: "Σφάλμα"
second_title: "Αναφορά API του GroupDocs.Viewer for .NET"
description: "Γράφει ένα μήνυμα σφάλματος. Τα μηνύματα καταγραφής σφαλμάτων παρέχουν πληροφορίες για μη ανακτήσιμα γεγονότα στη ροή της εφαρμογής."
type: docs
weight: 10
url: /el/net/groupdocs.viewer.logging/ilogger/error/
---

## ILogger.Error method

Γράφει ένα μήνυμα σφάλματος. Τα μηνύματα καταγραφής σφαλμάτων παρέχουν πληροφορίες για μη ανακτήσιμα γεγονότα στη ροή της εφαρμογής.

```csharp
public void Error(string message, Exception exception)
```

| Παράμετρος | Type | Περιγραφή |
| --- | --- | --- |
| μήνυμα | String | Το μήνυμα σφάλματος. |
| εξαίρεση | Εξαίρεση | Η εξαίρεση. |

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| ArgumentNullException | Εκτοπίζεται όταν *message* είναι null. |
| ArgumentNullException | Εκτοπίζεται όταν *exception* είναι null. |

### Δείτε επίσης

* interface [ILogger](../../ilogger)
* namespace [GroupDocs.Viewer.Logging](../../../groupdocs.viewer.logging)
* assembly [GroupDocs.Viewer](../../../)

<!-- ΜΗΝ ΕΠΕΞΕΡΓΑΣΕΤΕ: δημιουργήθηκε από το xmldocmd για το GroupDocs.Viewer.dll -->
