---
title: "CadOptions"
second_title: "GroupDocs.Viewer için .NET API Referansı"
description: "CAD çizimlerini renderlamak için seçenekleri içerir. Daha fazla bilgi ve kod örnekleri için Render CAD drawings and models as HTML PDF and image fileshttps//docs.groupdocs.com/viewer/net/rendercaddrawingsandmodels/ ve Specify rendering options for CAD fileshttps//docs.groupdocs.com/viewer/net/specifycadrenderingoptions/ sayfalarına bakın."
type: docs
weight: 280
url: /tr/net/groupdocs.viewer.options/cadoptions/
---

## CadOptions class

CAD çizimlerini render etme seçeneklerini içerir. Daha fazla bilgi ve kod örnekleri için [CAD çizimlerini ve modelleri HTML, PDF ve görüntü dosyaları olarak render etme](https://docs.groupdocs.com/viewer/net/render-cad-drawings-and-models/) ve [CAD dosyaları için render etme seçeneklerini belirtme](https://docs.groupdocs.com/viewer/net/specify-cad-rendering-options/) bağlantılarına bakın.

```csharp
public class CadOptions
```

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [BackgroundColor](../../groupdocs.viewer.options/cadoptions/backgroundcolor) { get; set; } | Görüntü arka plan rengi. |
| [EnablePerformanceConversionMode](../../groupdocs.viewer.options/cadoptions/enableperformanceconversionmode) { get; set; } | `true` olarak ayarlamak, CAD ailesindeki tüm formatlar için özel bir performans odaklı dönüşüm modunu etkinleştirir — bu modda dönüşüm hızı çok daha hızlıdır, ancak ortaya çıkan belgelerin kalitesi önemli ölçüde daha kötüdür. Varsayılan olarak devre dışıdır (`false`) — ortaya çıkan belgelerin kalitesi, performans pahasına mümkün olan en iyi seviyededir. |
| [Height](../../groupdocs.viewer.options/cadoptions/height) { get; } | Çıktı sonucunun yüksekliği (piksel cinsinden). |
| [Layers](../../groupdocs.viewer.options/cadoptions/layers) { get; set; } | Renderlanacak CAD çizim katmanları. |
| [LayoutName](../../groupdocs.viewer.options/cadoptions/layoutname) { get; set; } | Renderlanacak belirli yerleşimin adı. Yerleşim adı büyük/küçük harfe duyarlıdır. |
| [Pc3File](../../groupdocs.viewer.options/cadoptions/pc3file) { get; set; } | PC3 - plotter yapılandırma dosyası |
| [RenderLayouts](../../groupdocs.viewer.options/cadoptions/renderlayouts) { get; set; } | CAD belgesinden gelen düzenlerin render edilip edilmemesini işaretler. |
| [ScaleFactor](../../groupdocs.viewer.options/cadoptions/scalefactor) { get; } | 1'den büyük değer çıktı sonucunu büyütür; 0 ile 1 arasındaki değer çıktı sonucunu azaltır. |
| [Tiles](../../groupdocs.viewer.options/cadoptions/tiles) { get; set; } | Render edilecek çizim bölgeleri. |
| [Width](../../groupdocs.viewer.options/cadoptions/width) { get; } | Çıktı sonucunun genişliği (piksel cinsinden). |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| static [ForRenderingByHeight](../../groupdocs.viewer.options/cadoptions/forrenderingbyheight)(int) | Yükseğe göre render etmek için [`CadOptions`](../cadoptions) sınıfının bir örneğini başlatır. |
| static [ForRenderingByScaleFactor](../../groupdocs.viewer.options/cadoptions/forrenderingbyscalefactor)(float) | Ölçek faktörüne göre render etmek için [`CadOptions`](../cadoptions) sınıfının bir örneğini başlatır. |
| static [ForRenderingByWidth](../../groupdocs.viewer.options/cadoptions/forrenderingbywidth)(int) | Genişliğe göre render etmek için [`CadOptions`](../cadoptions) sınıfının bir örneğini başlatır. |
| static [ForRenderingByWidthAndHeight](../../groupdocs.viewer.options/cadoptions/forrenderingbywidthandheight)(int, int) | Genişlik ve yüksekliğe göre render etmek için [`CadOptions`](../cadoptions) sınıfının bir örneğini başlatır. |

### Ayrıca Bakınız

* namespace [GroupDocs.Viewer.Options](../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../)

<!-- DÜZENLEMEYİN: xmldocmd tarafından GroupDocs.Viewer.dll için oluşturuldu -->
