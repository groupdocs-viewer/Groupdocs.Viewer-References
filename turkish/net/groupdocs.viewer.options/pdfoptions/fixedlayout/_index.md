---
title: "FixedLayout"
second_title: "GroupDocs.Viewer için .NET API Referansı"
description: "PDF ve EPUB belgelerinin sabit bir düzenle HTML'ye renderlenmesini etkinleştirir."
type: docs
weight: 70
url: /tr/net/groupdocs.viewer.options/pdfoptions/fixedlayout/
---

## PdfOptions.FixedLayout property

PDF ve EPUB belgelerinin sabit bir düzenle HTML'ye renderlenmesini etkinleştirir.

```csharp
public bool FixedLayout { get; set; }
```

### Açıklamalar

PDF ve EPUB belgeleri, kaynak belgenin görünümünü korumak için başlangıçta sabit bir düzenle HTML'e render edilir. Bu sabit düzen, tüm HTML öğelerinin belirli bir boyutta konteyner içinde kesin konumlara sahip olduğu anlamına gelir. Tarayıcı penceresini yeniden boyutlandırmak, belgedeki öğelerin konum ve boyutunu etkilemez.

Bu seçenek yalnızca HTML'e render edilirken kullanılabilir. Varsayılan değer `true`. Akışkan bir düzenle render etmek için bu özelliği `false` olarak ayarlayın.

Akışkan düzenle render edildiğinde görüntüler atlanır. Metin içeriğine sahip PDF belgelerini render ederken akışkan düzeni kullanın.

Kod örneği için, [belgelere](https://docs.groupdocs.com/viewer/net/render-pdf-documents/#create-html-with-fluid-layout) bakın.

### Ayrıca Bakınız

* class [PdfOptions](../../pdfoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

<!-- DÜZENLEMEYİN: xmldocmd tarafından GroupDocs.Viewer.dll için oluşturuldu -->
