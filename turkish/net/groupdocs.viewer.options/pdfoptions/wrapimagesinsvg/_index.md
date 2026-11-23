---
title: "WrapImagesInSvg"
second_title: "GroupDocs.Viewer için .NET API Referansı"
description: "Çıktı HTML belgesindeki her görüntüyü SVG etiketiyle sarmalayarak çıktı kalitesini artırır."
type: docs
weight: 110
url: /tr/net/groupdocs.viewer.options/pdfoptions/wrapimagesinsvg/
---

## PdfOptions.WrapImagesInSvg property

Çıktı HTML belgesindeki her görüntüyü SVG etiketiyle sarmalayarak çıktı kalitesini artırır.

```csharp
public bool WrapImagesInSvg { get; set; }
```

### Açıklamalar

Varsayılan olarak, PDF ve Sayfa Düzeni dosyaları HTML'ye render edildiğinde, tüm görseller tek bir PNG görüntüsü olarak render edilir. Oluşturulan PNG görüntüsü çıktı HTML belgesinin arka planı olarak kullanılır.

Bu seçenek, [PDF ve Sayfa Düzeni dosya formatları](https://docs.groupdocs.com/viewer/net/supported-document-formats/#pdf-and-page-layout-file-formats) gömülü ve harici kaynaklarla HTML'ye render edildiğinde kullanılabilir. Çıktı HTML belgesindeki her görseli SVG etiketi içinde sarmalamanızı sağlar. Varsayılan değer `false`dır.

Kod örneği için, [belgelere](https://docs.groupdocs.com/viewer/net/render-pdf-documents/#enclose-images-in-svg-when-rendering-pdf-and-page-layout-files) bakın.

### Ayrıca Bakınız

* class [PdfOptions](../../pdfoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

<!-- DÜZENLEMEYİN: xmldocmd tarafından GroupDocs.Viewer.dll için oluşturuldu -->
