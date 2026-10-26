---
title: "WordProcessingOptions"
second_title: "GroupDocs.Viewer için .NET API Referansı"
description: "Word belgelerini render etmek için seçenekler içerir. Ayrıntılar için belgeleri inceleyin https//docs.groupdocs.com/viewer/net/renderworddocuments/."
type: docs
weight: 630
url: /tr/net/groupdocs.viewer.options/wordprocessingoptions/
---

## WordProcessingOptions class

Word belgelerini renderlemek için seçenekleri içerir. Ayrıntılar için [documentation](https://docs.groupdocs.com/viewer/net/render-word-documents/).

```csharp
public class WordProcessingOptions : ICloneable, IEquatable<WordProcessingOptions>
```

## Yapıcılar

| Ad | Açıklama |
| --- | --- |
| [WordProcessingOptions](wordprocessingoptions)() | Kelime işlem belgelerini render etmek için seçenekler içerir. Ayrıntılar için [belgelere](https://docs.groupdocs.com/viewer/net/render-word-documents/) bakın. |

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [BottomMargin](../../groupdocs.viewer.options/wordprocessingoptions/bottommargin) { get; set; } | Bir sayfanın alt kenar boşluğunu ayarlar. |
| [EnableOpenTypeFeatures](../../groupdocs.viewer.options/wordprocessingoptions/enableopentypefeatures) { get; set; } | Bu seçenek, Arapça, İbranice, Hint Latin temelli veya Kiril temelli betiklerin işlenmesi sırasında kerning ve diğer OpenType Özelliklerini etkinleştirir. |
| [HorizontalResolution](../../groupdocs.viewer.options/wordprocessingoptions/horizontalresolution) { get; set; } | Oluşturulan görüntüler için inç başına nokta cinsinden yatay çözünürlüğü alır veya ayarlar. Bu seçenek yalnızca WordProcessing belgelerinin PNG veya JPEG formatlarına işlenmesi sırasında kullanılır. |
| [LeftMargin](../../groupdocs.viewer.options/wordprocessingoptions/leftmargin) { get; set; } | Bir sayfanın sol kenar boşluğunu ayarlar. |
| [PageNumberLocation](../../groupdocs.viewer.options/wordprocessingoptions/pagenumberlocation) { get; set; } | Yüklenen WordProcessing belgesi için sayfa numaralandırmasını zorla uygulamaya izin verir. Varsayılan olarak NotApply — belge bozulmaz. |
| [PageSize](../../groupdocs.viewer.options/wordprocessingoptions/pagesize) { get; set; } | Çıktı sayfasının boyutu. Varsayılan değer Unspecified'tır, bu da sayfa ayarlarında (Page Setup) bir sayfa boyutu ayarlandığında kullanıldığı anlamına gelir. HTM ve HTML dosyaları işlenirken varsayılan sayfa boyutu Letter 792 x 612 puan olarak ayarlanır. Sonuç olarak, içeriğin bir kısmı sayfa çerçevesine sığmayabilir. İçeriği sığdırmak için daha büyük bir sayfa boyutu, ör. A3, ayarlayın. |
| [RenderTrackedChanges](../../groupdocs.viewer.options/wordprocessingoptions/rendertrackedchanges) { get; set; } | İzlenen değişikliklerin (revizyonların) işlenmesini etkinleştirir. |
| [RightMargin](../../groupdocs.viewer.options/wordprocessingoptions/rightmargin) { get; set; } | Bir sayfanın sağ kenar boşluğunu ayarlar. |
| [TopMargin](../../groupdocs.viewer.options/wordprocessingoptions/topmargin) { get; set; } | Bir sayfanın üst kenar boşluğunu ayarlar. |
| [UnlinkTableOfContents](../../groupdocs.viewer.options/wordprocessingoptions/unlinktableofcontents) { get; set; } | HTML veya PDF'ye işlenirken, bu seçeneği `true` olarak ayarlayarak içindekiler tablosundan gezinmeyi devre dışı bırakabilirsiniz. HTML işlenmesi için, göreli bağlantılara sahip `a` etiketleri `span` etiketleriyle değiştirilecek, işlevsellik kaldırılacak ancak görsel görünüm korunacaktır. PDF işlenmesi için, içindekiler tablosu belge bölümlerine bağlantı olmadan düz metin olarak işlenecektir. |
| [UpdateFields](../../groupdocs.viewer.options/wordprocessingoptions/updatefields) { get; set; } | Belirli tipteki alanların, giriş WordProcessing belgesi HTML, PDF, PNG veya JPEG çıktı formatlarına kaydedilmeden önce güncellenip güncellenmeyeceğini belirleyen bir değeri alır veya ayarlar. Bu özelliğin varsayılan değeri `true` — alanlar kaydetmeden önce güncellenecektir. |
| [VerticalResolution](../../groupdocs.viewer.options/wordprocessingoptions/verticalresolution) { get; set; } | Oluşturulan görüntüler için inç başına nokta cinsinden dikey çözünürlüğü alır veya ayarlar. Bu seçenek yalnızca WordProcessing belgelerinin PNG veya JPEG formatlarına işlenmesi sırasında kullanılır. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| [Clone](../../groupdocs.viewer.options/wordprocessingoptions/clone)() | Bu seçeneklerin tam bir derin kopyasını oluşturur ve döndürür |
| [Equals](../../groupdocs.viewer.options/wordprocessingoptions/equals#equals)(WordProcessingOptions) | Belirtilen [`WordProcessingOptions`](../wordprocessingoptions) örneğinin buna eşit olup olmadığını belirler |

### Ayrıca Bakınız

* namespace [GroupDocs.Viewer.Options](../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../)

<!-- DÜZENLEMEYİN: xmldocmd tarafından GroupDocs.Viewer.dll için oluşturuldu -->
