---
title: "IAuxDisposable"
second_title: "GroupDocs.Viewer için .NET API Referansı"
description: "Standart IDisposable arayüzünü genişleterek bir nesnenin mevcut durumunu elde etmeyi ve imha olayı için abone olmayı sağlar"
type: docs
weight: 20
url: /tr/net/groupdocs.viewer/iauxdisposable/
---

## IAuxDisposable interface

Standart IDisposable arayüzünü genişletir, bir nesnenin mevcut durumunu elde etmeyi ve imha olayı için abone olmayı sağlar.

```csharp
public interface IAuxDisposable : IDisposable
```

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [IsDisposed](../../groupdocs.viewer/iauxdisposable/isdisposed) { get; } | Bir kaynağın zaten imha edilip edilmediğini (`true`) veya (`false`) gösterir |

## Olaylar

| Ad | Açıklama |
| --- | --- |
| event [Disposed](../../groupdocs.viewer/iauxdisposable/disposed) | Nesne imha edildiğinde, kaynakların imhası başarıyla tamamlandıktan hemen sonra gerçekleşir |

### Ayrıca Bakınız

* namespace [GroupDocs.Viewer](../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../)

<!-- DÜZENLEMEYİN: xmldocmd tarafından GroupDocs.Viewer.dll için oluşturuldu -->
