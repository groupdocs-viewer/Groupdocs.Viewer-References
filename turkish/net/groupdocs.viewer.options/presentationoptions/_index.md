---
title: "PresentationOptions"
second_title: "GroupDocs.Viewer için .NET API Referansı"
description: "Sunumları render etmek için seçenekler içerir. Ayrıntılar için belgeleri inceleyin https//docs.groupdocs.com/viewer/net/renderpresentations/."
type: docs
weight: 460
url: /tr/net/groupdocs.viewer.options/presentationoptions/
---

## PresentationOptions class

Sunumları render etme seçeneklerini içerir. Ayrıntılar için [belgelere](https://docs.groupdocs.com/viewer/net/render-presentations/) bakın.

```csharp
public class PresentationOptions
```

## Yapıcılar

| Ad | Açıklama |
| --- | --- |
| [PresentationOptions](presentationoptions)() | Varsayılan yapıcı. |

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [RenderHeaderFooterPlaceholders](../../groupdocs.viewer.options/presentationoptions/renderheaderfooterplaceholders) { get; set; } | Bir slaytın başlık ve altbilgisindeki yer tutucuların render edilmesini etkinleştirir. Varsayılan olarak devre dışı (`false`). Bu seçenek sunumların tüm 4 render modunda uygulanır: HTML, PDF, PNG ve JPEG. [`RenderToPureHtml`](./rendertopurehtml) kullanılarak sunumun saf HTML/CSS işaretlemesine render edilmesi durumunda uygulanmaz. |
| [RenderToPureHtml](../../groupdocs.viewer.options/presentationoptions/rendertopurehtml) { get; set; } | Sunum belgeleri için yeni bir HTML render modunu etkinleştirir — bu modda Sunum dosyaları **saf HTML/CSS markup** olarak render edilir, SVG görüntüsü olmadan. Varsayılan olarak devre dışı (`false`) — mevcut SVG tabanlı HTML-renderer kullanılır. |
| [Resolution](../../groupdocs.viewer.options/presentationoptions/resolution) { get; set; } | Sunum görüntülerinin çözünürlüğü (yalnızca HTML/PDF render için). |

### Ayrıca Bakınız

* namespace [GroupDocs.Viewer.Options](../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../)

<!-- DÜZENLEMEYİN: xmldocmd tarafından GroupDocs.Viewer.dll için oluşturuldu -->
