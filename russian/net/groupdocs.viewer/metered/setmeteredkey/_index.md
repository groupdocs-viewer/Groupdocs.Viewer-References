---
title: "SetMeteredKey"
second_title: "Справочник API GroupDocs.Viewer для .NET"
description: "Активирует продукт с Metered ключами."
type: docs
weight: 20
url: /ru/net/groupdocs.viewer/metered/setmeteredkey/
---

## Metered.SetMeteredKey method

Активирует продукт с Metered ключами.

```csharp
public void SetMeteredKey(string publicKey, string privateKey)
```

| Параметр | Type | Описание |
| --- | --- | --- |
| publicKey | String | Публичный ключ. |
| privateKey | String | Приватный ключ. |

### Примеры

В следующем примере показано, как активировать продукт с помощью Metered-ключей.

```csharp
string publicKey = "Public Key";
string privateKey = "Private Key";

Metered metered = new Metered();
metered.SetMeteredKey(publicKey, privateKey);
```

### См. также

* class [Metered](../../metered)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.Viewer.dll -->
