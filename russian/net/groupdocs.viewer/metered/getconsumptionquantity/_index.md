---
title: "GetConsumptionQuantity"
second_title: "Справочник API GroupDocs.Viewer для .NET"
description: "Получает объём обработанных мегабайт."
type: docs
weight: 40
url: /ru/net/groupdocs.viewer/metered/getconsumptionquantity/
---

## Metered.GetConsumptionQuantity method

Получает объём обработанных мегабайт.

```csharp
public static decimal GetConsumptionQuantity()
```

### Примеры

В следующем примере показано, как получить количество обработанных МБ.

```csharp
string publicKey = "Public Key";
string privateKey = "Private Key";

Metered metered = new Metered();
metered.SetMeteredKey(publicKey, privateKey);

decimal mbProcessed = Metered.GetConsumptionQuantity();
```

### См. также

* class [Metered](../../metered)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.Viewer.dll -->
