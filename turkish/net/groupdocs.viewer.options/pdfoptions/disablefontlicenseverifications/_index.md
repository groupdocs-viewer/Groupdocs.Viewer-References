---
title: "DisableFontLicenseVerifications"
second_title: "GroupDocs.Viewer için .NET API Referansı"
description: "Mevcut XPS/OXPS belgesindeki tüm yazı tipleri için lisans kısıtlamalarını devre dışı bırakır."
type: docs
weight: 40
url: /tr/net/groupdocs.viewer.options/pdfoptions/disablefontlicenseverifications/
---

## PdfOptions.DisableFontLicenseVerifications property

Mevcut XPS/OXPS belgesindeki tüm yazı tipleri için lisans kısıtlamalarını devre dışı bırakır.

```csharp
public bool DisableFontLicenseVerifications { get; set; }
```

### Açıklamalar

Bir fontun lisansı tarafından yasaklanmışsa, fontla ilgili birçok işlem gerçekleştirilemez. Örneğin, bazı fontlar lisans kuralları bu font için gömmeyi devre dışı bırakıyorsa PDF belgesine gömülemez. Bu seçenek, bu kuralların doğrulamasını atlamanızı sağlar.

Bu bayrağı kullanırken dikkatli olun. Ayarlandığında, bu bayrağı ayarlayan kişinin olası lisans/yasa ihlallerinin tüm sorumluluğunu üstlendiği anlamına gelir. Yani riski kendi üzerine alır. Telif hakkı yasasını ihlal etmediğinizden tamamen emin olduğunuz durumlarda bu bayrağı kullanmanız şiddetle tavsiye edilir. Varsayılan değer `false`.

Kod örneği için, [belgelere](https://docs.groupdocs.com/viewer/net/render-pdf-documents/#skip-font-license-verification-when-rendering-xps-and-oxps-files) bakın.

### Ayrıca Bakınız

* class [PdfOptions](../../pdfoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

<!-- DÜZENLEMEYİN: xmldocmd tarafından GroupDocs.Viewer.dll için oluşturuldu -->
