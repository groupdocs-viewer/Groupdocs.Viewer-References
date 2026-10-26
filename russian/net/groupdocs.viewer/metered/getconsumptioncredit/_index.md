---
title: "GetConsumptionCredit"
second_title: "Справочник API GroupDocs.Viewer для .NET"
description: "Получает количество использованных кредитов."
type: docs
weight: 30
url: /ru/net/groupdocs.viewer/metered/getconsumptioncredit/
---

## Metered.GetConsumptionCredit method

Получает количество использованных кредитов.

```csharp
public static decimal GetConsumptionCredit()
```

### Примеры

В следующем примере демонстрируется, как получить количество использованных кредитов.

```csharp
string publicKey = "Public Key";
string privateKey = "Private Key";

Metered metered = new Metered();
metered.SetMeteredKey(publicKey, privateKey);

decimal creditsConsumed = Metered.GetConsumptionCredit();
```

### См. также

* class [Metered](../../metered)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.Viewer.dll -->
