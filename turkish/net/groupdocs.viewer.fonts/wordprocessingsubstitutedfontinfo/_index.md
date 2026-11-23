---
title: "WordProcessingSubstitutedFontInfo"
second_title: "GroupDocs.Viewer için .NET API Referansı"
description: "WordProcessing belgesinden bir yazı tipinin meta bilgisini ve ikili verilerini kapsüller; bu yazı tipi başlangıçta Viewer../groupdocs.viewer/viewer örneğine yüklenen belgede kullanılmaz, ancak hedef makinede bulunamayanlar için bir ikame yazı tipi olarak hizmet eder. İkame yazı tipleri yalnızca WordProcessing formatları ailesi için mevcuttur."
type: docs
weight: 890
url: /tr/net/groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/
---

## WordProcessingSubstitutedFontInfo structure

WordProcessing belgesinden bir yazı tipinin meta bilgisini ve ikili verilerini kapsüller; bu yazı tipi başlangıçta [`Viewer`](../../groupdocs.viewer/viewer) örneğine yüklenen belgede kullanılmaz, ancak hedef makinede bulunamayanlar için bir ikame yazı tipi olarak hizmet eder. İkame yazı tipleri yalnızca WordProcessing formatları ailesi için mevcuttur.

```csharp
public struct WordProcessingSubstitutedFontInfo : IFontInfo
```

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [Content](../../groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/content) { get; } | Bu ikame yazı tipinin içeriği bayt dizisi olarak bulunur. Asla `null` değildir. |
| [FamilyName](../../groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/familyname) { get; } | **substituted** yazı tipinin stil içermeyen aile adı, asla null veya boş string değildir. |
| [Format](../../groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/format) { get; } | Bu ikame (orijinal olmayan) yazı tipinin formatı. TrueType, TrueType Collection, OpenType veya Embedded OpenType olabilir. İkame yazı tipinin ikili içeriği tanım gereği mevcut olduğundan, bu özellik asla Unknown değerini döndürmez. |
| [OriginalFamilyName](../../groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/originalfamilyname) { get; } | Hedef makinede bulunamayan orijinal yazı tipinin stil içermeyen aile adı, asla null veya boş string değildir. |
| [Style](../../groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/style) { get; } | Orijinal yazı tipinin stili — Regular, Bold, Italic veya Bold Italic olabilir. İkame yazı tipi genellikle (her zaman olmayabilir) aynı stile sahiptir. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| [SerializeToCss](../../groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/serializetocss)(TextWriter) | Bu yazı tipi bilgisini @font-face at-rule olarak serileştirir ve belirtilen metin yazarına yazar. |
| override [ToString](../../groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/tostring)() | Bu yazı tipi verileri hakkında hata ayıklama bilgisini şu şablonla döndürür: "original-name -&gt; substituted-name style, format" |

### Açıklamalar

Değiştirilemez yapı. Örnekleri GroupDocs.Viewer genel API'si tarafından üretilir ve döndürülür; normalde kullanıcı tarafından oluşturulmamalıdır. Ayrıntılar için [documentation](https://docs.groupdocs.com/viewer/net/getting-used-fonts/) sayfasına bakın.

### Ayrıca Bakınız

* interface [IFontInfo](../ifontinfo)
* namespace [GroupDocs.Viewer.Fonts](../../groupdocs.viewer.fonts)
* assembly [GroupDocs.Viewer](../../)

<!-- DÜZENLEMEYİN: xmldocmd tarafından GroupDocs.Viewer.dll için oluşturuldu -->
