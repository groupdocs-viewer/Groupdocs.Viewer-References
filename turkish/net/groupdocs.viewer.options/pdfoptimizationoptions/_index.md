---
title: "PdfOptimizationOptions"
second_title: "GroupDocs.Viewer için .NET API Referansı"
description: "Çıktı PDF dosyasına uygulanacak PDF optimizasyon seçeneklerini içerir. Ayrıntılar ve kod örnekleri için bu sayfaya https//docs.groupdocs.com/viewer/net/optimizationpdfoptions/ ve alt sayfalarına bakın."
type: docs
weight: 400
url: /tr/net/groupdocs.viewer.options/pdfoptimizationoptions/
---

## PdfOptimizationOptions class

Çıktı PDF dosyasına uygulanacak PDF optimizasyon seçeneklerini içerir. Ayrıntılar ve kod örnekleri için bu [sayfaya](https://docs.groupdocs.com/viewer/net/optimization-pdf-options/) ve alt bölümlerine bakın.

```csharp
public class PdfOptimizationOptions
```

## Yapıcılar

| Ad | Açıklama |
| --- | --- |
| [PdfOptimizationOptions](pdfoptimizationoptions)() | MaxResolution seçeneğinin varsayılan değerini 300, ImageQuality seçeneğinin varsayılan değerini ise 100 olarak ayarlar. |

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [CompressImages](../../groupdocs.viewer.options/pdfoptimizationoptions/compressimages) { get; set; } | Çıktı PDF dosyasındaki görüntülerin sıkıştırılmasını etkinleştirir. |
| [ConvertToGrayScale](../../groupdocs.viewer.options/pdfoptimizationoptions/converttograyscale) { get; set; } | Çıktı PDF dosyasını gri tonlamaya dönüştürmeyi etkinleştirir. |
| [ImageQuality](../../groupdocs.viewer.options/pdfoptimizationoptions/imagequality) { get; set; } | Çıktı PDF dosyasındaki görüntü kalitesini (yüzde olarak) ayarlar. |
| [Lineriaze](../../groupdocs.viewer.options/pdfoptimizationoptions/lineriaze) { get; set; } | Çıktı PDF dosyasının bir web tarayıcısında çevrimiçi görüntülenmesi için optimizasyonunu etkinleştirir. |
| [MaxResolution](../../groupdocs.viewer.options/pdfoptimizationoptions/maxresolution) { get; set; } | Çıktı PDF dosyasındaki maksimum çözünürlüğü ayarlar. |
| [OptimizeSpreadsheets](../../groupdocs.viewer.options/pdfoptimizationoptions/optimizespreadsheets) { get; set; } | PDF dosyalarındaki elektronik tabloların optimizasyonunu etkinleştirir. |
| [RemoveAnnotations](../../groupdocs.viewer.options/pdfoptimizationoptions/removeannotations) { get; set; } | Çıktı PDF dosyasından ek açıklamaların kaldırılmasını etkinleştirir. |
| [RemoveFormFields](../../groupdocs.viewer.options/pdfoptimizationoptions/removeformfields) { get; set; } | PDF dosyasından form alanlarını kaldırmayı etkinleştirir. |
| [RemoveUnusedObjects](../../groupdocs.viewer.options/pdfoptimizationoptions/removeunusedobjects) { get; set; } | PDF dosyasından kullanılmayan (sahipsiz) nesneleri kaldırır; bu nesneler PDF belgesine yerleştirilmiş, ancak herhangi bir sayfanın kaynak sözlüklerinden referans alınmamış ve bu yüzden hiç kullanılmamaktadır. Bu özellik (`true`) etkinleştirildiğinde çıktı PDF belgesinin boyutu azalır. Varsayılan olarak devre dışıdır (`false`). |
| [RemoveUnusedStreams](../../groupdocs.viewer.options/pdfoptimizationoptions/removeunusedstreams) { get; set; } | PDF dosyasından kullanılmayan (sahipsiz) akışları kaldırır; bu akışlar sayfanın kaynak sözlüğünden hâlâ referans alınmış olsa da sayfa içeriğinde hiç kullanılmaz. Varsayılan olarak devre dışıdır (`false`); etkinleştirildiğinde (`true`) çıktı PDF belgesinin boyutu azalır. |
| [ResizeImages](../../groupdocs.viewer.options/pdfoptimizationoptions/resizeimages) { get; set; } | Çıktı PDF dosyasında maksimum çözünürlüğün ayarlanmasını etkinleştirir. |
| [SubsetFonts](../../groupdocs.viewer.options/pdfoptimizationoptions/subsetfonts) { get; set; } | Çıktı PDF dosyasındaki yazı tiplerini alt kümelere ayırır. |

### Ayrıca Bakınız

* namespace [GroupDocs.Viewer.Options](../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../)

<!-- DÜZENLEMEYİN: xmldocmd tarafından GroupDocs.Viewer.dll için oluşturuldu -->
