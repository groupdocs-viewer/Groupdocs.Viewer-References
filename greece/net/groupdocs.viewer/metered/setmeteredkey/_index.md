---
title: "SetMeteredKey"
second_title: "Αναφορά API του GroupDocs.Viewer for .NET"
description: "Ενεργοποιεί το προϊόν με κλειδιά Metered."
type: docs
weight: 20
url: /el/net/groupdocs.viewer/metered/setmeteredkey/
---

## Metered.SetMeteredKey method

Ενεργοποιεί το προϊόν με κλειδιά Metered.

```csharp
public void SetMeteredKey(string publicKey, string privateKey)
```

| Παράμετρος | Type | Περιγραφή |
| --- | --- | --- |
| publicKey | String | Το δημόσιο κλειδί. |
| privateKey | String | Το ιδιωτικό κλειδί. |

### Παραδείγματα

Το παρακάτω παράδειγμα δείχνει πώς να ενεργοποιήσετε το προϊόν με Μετρημένα κλειδιά.

```csharp
string publicKey = "Public Key";
string privateKey = "Private Key";

Metered metered = new Metered();
metered.SetMeteredKey(publicKey, privateKey);
```

### Δείτε επίσης

* class [Metered](../../metered)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

<!-- ΜΗΝ ΕΠΕΞΕΡΓΑΣΕΤΕ: δημιουργήθηκε από το xmldocmd για το GroupDocs.Viewer.dll -->
