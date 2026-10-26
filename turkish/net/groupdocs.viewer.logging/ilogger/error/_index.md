---
title: "Hata"
second_title: "GroupDocs.Viewer için .NET API Referansı"
description: "Bir hata mesajı yazar. Hata günlük mesajları, uygulama akışındaki geri alınamaz olaylar hakkında bilgi sağlar."
type: docs
weight: 10
url: /tr/net/groupdocs.viewer.logging/ilogger/error/
---

## ILogger.Error method

Bir hata mesajı yazar. Hata günlük mesajları, uygulama akışındaki geri alınamaz olaylar hakkında bilgi sağlar.

```csharp
public void Error(string message, Exception exception)
```

| Parametre | Type | Açıklama |
| --- | --- | --- |
| mesaj | String | Hata mesajı. |
| istisna | İstisna | İstisna. |

### İstisnalar

| istisna | koşul |
| --- | --- |
| ArgumentNullException | *message* null olduğunda fırlatılır. |
| ArgumentNullException | *exception* null olduğunda fırlatılır. |

### Ayrıca Bakınız

* interface [ILogger](../../ilogger)
* namespace [GroupDocs.Viewer.Logging](../../../groupdocs.viewer.logging)
* assembly [GroupDocs.Viewer](../../../)

<!-- DÜZENLEMEYİN: xmldocmd tarafından GroupDocs.Viewer.dll için oluşturuldu -->
