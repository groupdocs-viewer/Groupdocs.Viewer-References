---
title: "Permissions"
second_title: "GroupDocs.Viewer için .NET API Referansı"
description: "PDF belge izinlerini tanımlar."
type: docs
weight: 430
url: /tr/net/groupdocs.viewer.options/permissions/
---

## Permissions enumeration

PDF belge izinlerini tanımlar.

```csharp
[Flags]
public enum Permissions
```

### Değerler

| Ad | Değer | Açıklama |
| --- | --- | --- |
| AllowAll | `0` | Yazdırma, değiştirme ve veri çıkarımına izin verir. |
| DenyPrinting | `1` | Yazdırmayı reddeder. |
| DenyModification | `2` | İçerik değişikliğini, form doldurmayı, ek açıklama eklemeyi veya değiştirmeyi reddeder. |
| DenyDataExtraction | `4` | Metin ve grafik çıkarımını reddeder. |
| DenyAll | `7` | Yazdırmayı, içerik değişikliğini ve veri çıkarımını reddeder. |

### Ayrıca Bakınız

* namespace [GroupDocs.Viewer.Options](../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../)

<!-- DÜZENLEMEYİN: xmldocmd tarafından GroupDocs.Viewer.dll için oluşturuldu -->
