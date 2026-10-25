---
title: "GetConsumptionQuantity"
second_title: "Αναφορά API του GroupDocs.Viewer for .NET"
description: "Ανακτά το ποσό των επεξεργασμένων MB."
type: docs
weight: 40
url: /el/net/groupdocs.viewer/metered/getconsumptionquantity/
---

## Metered.GetConsumptionQuantity method

Ανακτά το ποσό των επεξεργασμένων MB.

```csharp
public static decimal GetConsumptionQuantity()
```

### Παραδείγματα

Το παρακάτω παράδειγμα δείχνει πώς να ανακτήσετε το ποσό των επεξεργασμένων MB.

```csharp
string publicKey = "Public Key";
string privateKey = "Private Key";

Metered metered = new Metered();
metered.SetMeteredKey(publicKey, privateKey);

decimal mbProcessed = Metered.GetConsumptionQuantity();
```

### Δείτε επίσης

* class [Metered](../../metered)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

<!-- ΜΗΝ ΕΠΕΞΕΡΓΑΣΕΤΕ: δημιουργήθηκε από το xmldocmd για το GroupDocs.Viewer.dll -->
