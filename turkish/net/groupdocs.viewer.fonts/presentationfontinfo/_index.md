---
title: "PresentationFontInfo"
second_title: "GroupDocs.Viewer için .NET API Referansı"
description: "Presentation belgesinden bir yazı tipinin meta bilgilerini ve ikili verilerini Viewer../groupdocs.viewer/viewer örneğine yüklenmiş olarak kapsüller. Bu yazı tipi belge içeriğinde kullanılır ve belge içinde gömülü olarak bulunur veya GroupDocs.Viewer'ın çalıştığı işletim sistemine kuruludur."
type: docs
weight: 850
url: /tr/net/groupdocs.viewer.fonts/presentationfontinfo/
---

## PresentationFontInfo structure

Presentation belgesinden bir yazı tipinin meta bilgilerini ve ikili verilerini, [`Viewer`](../../groupdocs.viewer/viewer) örneğine yüklenmiş olarak kapsüller. Bu yazı tipi belge içeriğinde kullanılır ve belge içinde gömülü olarak bulunur veya GroupDocs.Viewer'ın çalıştığı işletim sistemine kuruludur.

```csharp
public struct PresentationFontInfo : IFontInfo
```

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [Content](../../groupdocs.viewer.fonts/presentationfontinfo/content) { get; } | Bu yazı tipinin içeriği bayt dizisi olarak. Yalnızca bu yazı tipi hakkında meta bilgi varsa ancak ikili içeriği mevcut değilse, bu özellik `null` döndürür. |
| [FamilyName](../../groupdocs.viewer.fonts/presentationfontinfo/familyname) { get; } | Stil olmadan yazı tipinin aile adı, hiçbir zaman null veya boş dize değildir |
| [Format](../../groupdocs.viewer.fonts/presentationfontinfo/format) { get; } | Bu yazı tipinin biçimi. Belgeler aşağıdaki biçimlerde yazı tipleri kullanabilir: TrueType, TrueType Collection, OpenType, Embedded OpenType. Yalnızca bu yazı tipi hakkında meta bilgi varsa ancak ikili içeriği mevcut değilse, bu özellik Unknown değerini döndürür. |
| [IsEmbedded](../../groupdocs.viewer.fonts/presentationfontinfo/isembedded) { get; } | Bu yazı tipinin belge içinde gömülü olup olmadığını, [`Viewer`](../../groupdocs.viewer/viewer) örneğine yüklendiğini (`true`) ya da sistem yazı tipi olduğunu (`false`) gösterir. Elektronik tablo belgeleri gömülü yazı tiplerini tutamaz, bu nedenle bu özellik onlar için her zaman `false` döner. |
| [Style](../../groupdocs.viewer.fonts/presentationfontinfo/style) { get; } | Yazı tipinin stili — Regular, Bold, Italic veya Bold Italic olabilir |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| [SerializeToCss](../../groupdocs.viewer.fonts/presentationfontinfo/serializetocss)(TextWriter) | Bu yazı tipi bilgisini @font-face at-rule olarak serileştirir ve belirtilen metin yazarına yazar. |

### Ayrıca Bakınız

* interface [IFontInfo](../ifontinfo)
* namespace [GroupDocs.Viewer.Fonts](../../groupdocs.viewer.fonts)
* assembly [GroupDocs.Viewer](../../)

<!-- DÜZENLEMEYİN: xmldocmd tarafından GroupDocs.Viewer.dll için oluşturuldu -->
