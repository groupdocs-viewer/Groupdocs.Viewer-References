---
title: "WordProcessingFontInfo"
second_title: "GroupDocs.Viewer için .NET API Referansı"
description: "Viewer../groupdocs.viewer/viewer örneğine yüklü WordProcessing belgesinden bir yazı tipinin meta bilgisini ve ikili verilerini kapsüller. Bu yazı tipi belge içeriğinde kullanılır ve belgenin içinde gömülüdür veya GroupDocs.Viewer'ın çalıştığı işletim sistemine kurulu durumdadır."
type: docs
weight: 880
url: /tr/net/groupdocs.viewer.fonts/wordprocessingfontinfo/
---

## WordProcessingFontInfo structure

WordProcessing belgesinden bir yazı tipinin meta bilgilerini ve ikili verilerini, [`Viewer`](../../groupdocs.viewer/viewer) örneğine yüklenmiş olarak kapsüller. Bu yazı tipi belge içeriğinde kullanılır ve belge içinde gömülü olarak bulunur veya GroupDocs.Viewer'ın çalıştığı işletim sistemine kuruludur.

```csharp
public struct WordProcessingFontInfo : IFontInfo
```

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [AltFamilyName](../../groupdocs.viewer.fonts/wordprocessingfontinfo/altfamilyname) { get; } | Yazı tipinin alternatif aile adı. Eksikse, boş dize döner. |
| [Charset](../../groupdocs.viewer.fonts/wordprocessingfontinfo/charset) { get; } | Bu yazı tipinin karakter kümesi |
| [Content](../../groupdocs.viewer.fonts/wordprocessingfontinfo/content) { get; } | Bu yazı tipinin içeriği bayt dizisi olarak. Yalnızca bu yazı tipi hakkında meta bilgi varsa ancak ikili içeriği mevcut değilse, bu özellik `null` döndürür. |
| [FamilyName](../../groupdocs.viewer.fonts/wordprocessingfontinfo/familyname) { get; } | Stil olmadan yazı tipinin aile adı, hiçbir zaman null veya boş dize değildir |
| [Format](../../groupdocs.viewer.fonts/wordprocessingfontinfo/format) { get; } | Bu yazı tipinin biçimi. Belgeler aşağıdaki biçimlerde yazı tipleri kullanabilir: TrueType, TrueType Collection, OpenType, Embedded OpenType. Yalnızca bu yazı tipi hakkında meta bilgi varsa ancak ikili içeriği mevcut değilse, bu özellik Unknown değerini döndürür. |
| [IsEmbedded](../../groupdocs.viewer.fonts/wordprocessingfontinfo/isembedded) { get; } | Bu yazı tipinin belge içinde gömülü olup olmadığını, [`Viewer`](../../groupdocs.viewer/viewer) örneğine yüklendiğini (`true`) ya da sistem yazı tipi olduğunu (`false`) gösterir. |
| [Style](../../groupdocs.viewer.fonts/wordprocessingfontinfo/style) { get; } | Yazı tipinin stili — Regular, Bold, Italic veya Bold Italic olabilir. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| [SerializeToCss](../../groupdocs.viewer.fonts/wordprocessingfontinfo/serializetocss)(TextWriter) | Bu yazı tipi bilgisini @font-face at-rule olarak serileştirir ve belirtilen metin yazarına yazar. |
| override [ToString](../../groupdocs.viewer.fonts/wordprocessingfontinfo/tostring)() | Bu yazı tipi verileri hakkında hata ayıklama bilgisi döndürür; şablon şu şekildedir: "name style, embedded/system, format" |

### Açıklamalar

Değiştirilemez yapı. Örnekleri GroupDocs.Viewer genel API'si tarafından üretilir ve döndürülür; normalde kullanıcı tarafından oluşturulmamalıdır. Ayrıntılar için [documentation](https://docs.groupdocs.com/viewer/net/getting-used-fonts/) sayfasına bakın.

### Ayrıca Bakınız

* interface [IFontInfo](../ifontinfo)
* namespace [GroupDocs.Viewer.Fonts](../../groupdocs.viewer.fonts)
* assembly [GroupDocs.Viewer](../../)

<!-- DÜZENLEMEYİN: xmldocmd tarafından GroupDocs.Viewer.dll için oluşturuldu -->
