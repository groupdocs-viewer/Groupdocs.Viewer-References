---
title: "DisableCopyProtection"
second_title: "GroupDocs.Viewer için .NET API Referansı"
description: "HTML'ye renderleme sırasında içerik kopya korumasını kapatır."
type: docs
weight: 30
url: /tr/net/groupdocs.viewer.options/pdfoptions/disablecopyprotection/
---

## PdfOptions.DisableCopyProtection property

HTML'ye renderleme sırasında içerik kopya korumasını kapatır.

```csharp
public bool DisableCopyProtection { get; set; }
```

### Açıklamalar

PDF dosyalarını metin ve görüntü kopyalamaya karşı koruma ile HTML'e render ederken, GroupDocs.Viewer HTML BODY etiketine 'inert' adlı bir HTML özniteliği ekler. Bu seçeneğin varsayılan değeri `false` olup, 'intent' HTML özniteliğinin yalnızca PDF belgesi korumalıysa ekleneceğini gösterir.

Kod örneği için, [belgelere](https://docs.groupdocs.com/viewer/net/render-pdf-documents/#disable-copy-protection) bakın.

### Ayrıca Bakınız

* class [PdfOptions](../../pdfoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

<!-- DÜZENLEMEYİN: xmldocmd tarafından GroupDocs.Viewer.dll için oluşturuldu -->
