---
title: "Permissions"
second_title: "Αναφορά API του GroupDocs.Viewer for .NET"
description: "Ορίζει τα δικαιώματα εγγράφου PDF."
type: docs
weight: 430
url: /el/net/groupdocs.viewer.options/permissions/
---

## Permissions enumeration

Ορίζει τα δικαιώματα εγγράφου PDF.

```csharp
[Flags]
public enum Permissions
```

### Τιμές

| Όνομα | Τιμή | Περιγραφή |
| --- | --- | --- |
| AllowAll | `0` | Να επιτρέπεται η εκτύπωση, η τροποποίηση και η εξαγωγή δεδομένων. |
| DenyPrinting | `1` | Απαγόρευση εκτύπωσης. |
| DenyModification | `2` | Απαγόρευση τροποποίησης περιεχομένου, συμπλήρωσης φορμών, προσθήκης ή τροποποίησης σχολίων. |
| DenyDataExtraction | `4` | Απαγόρευση εξαγωγής κειμένου και γραφικών. |
| DenyAll | `7` | Απαγόρευση εκτύπωσης, τροποποίησης περιεχομένου και εξαγωγής δεδομένων. |

### Δείτε επίσης

* namespace [GroupDocs.Viewer.Options](../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../)

<!-- ΜΗΝ ΕΠΕΞΕΡΓΑΣΕΤΕ: δημιουργήθηκε από το xmldocmd για το GroupDocs.Viewer.dll -->
