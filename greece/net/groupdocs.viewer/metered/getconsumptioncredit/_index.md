---
title: "GetConsumptionCredit"
second_title: "Αναφορά API του GroupDocs.Viewer for .NET"
description: "Ανακτά τον αριθμό των καταναλωμένων πιστώσεων."
type: docs
weight: 30
url: /el/net/groupdocs.viewer/metered/getconsumptioncredit/
---

## Metered.GetConsumptionCredit method

Ανακτά τον αριθμό των καταναλωμένων πιστώσεων.

```csharp
public static decimal GetConsumptionCredit()
```

### Παραδείγματα

Το παρακάτω παράδειγμα δείχνει πώς να ανακτήσετε τον αριθμό των καταναλωμένων πιστώσεων.

```csharp
string publicKey = "Public Key";
string privateKey = "Private Key";

Metered metered = new Metered();
metered.SetMeteredKey(publicKey, privateKey);

decimal creditsConsumed = Metered.GetConsumptionCredit();
```

### Δείτε επίσης

* class [Metered](../../metered)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

<!-- ΜΗΝ ΕΠΕΞΕΡΓΑΣΕΤΕ: δημιουργήθηκε από το xmldocmd για το GroupDocs.Viewer.dll -->
