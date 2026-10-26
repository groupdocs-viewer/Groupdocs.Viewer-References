---
title: "Hata"
second_title: "GroupDocs.Viewer için .NET API Referansı"
description: "Konsola bir hata mesajı yazar. Hata günlük mesajları, uygulama akışındaki kurtarılamaz olaylar hakkında bilgi sağlar."
type: docs
weight: 20
url: /tr/net/groupdocs.viewer.logging/consolelogger/error/
---

## ConsoleLogger.Error method

Konsola bir hata mesajı yazar. Hata günlük mesajları, uygulama akışındaki kurtarılamaz olaylar hakkında bilgi sağlar.

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

* class [ConsoleLogger](../../consolelogger)
* namespace [GroupDocs.Viewer.Logging](../../../groupdocs.viewer.logging)
* assembly [GroupDocs.Viewer](../../../)

<!-- DÜZENLEMEYİN: xmldocmd tarafından GroupDocs.Viewer.dll için oluşturuldu -->
