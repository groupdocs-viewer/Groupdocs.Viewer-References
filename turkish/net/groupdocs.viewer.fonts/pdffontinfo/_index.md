---
title: "PdfFontInfo"
second_title: "GroupDocs.Viewer için .NET API Referansı"
description: "PDF belgesinden Viewer../groupdocs.viewer/viewer örneğine yüklenen bir yazı tipinin meta bilgilerini ve ikili verilerini kapsüller. Bu yazı tipi belge içeriğinde kullanılır ve belgenin içinde gömülü ya da GroupDocs.Viewer'ın çalıştığı işletim sistemine kuruludur."
type: docs
weight: 840
url: /tr/net/groupdocs.viewer.fonts/pdffontinfo/
---

## PdfFontInfo structure

PDF belgesinden bir yazı tipinin meta bilgilerini ve ikili verilerini, [`Viewer`](../../groupdocs.viewer/viewer) örneğine yüklenmiş olarak kapsüller. Bu yazı tipi belge içeriğinde kullanılır ve belgenin içinde gömülü ya da GroupDocs.Viewer'ın çalıştığı işletim sistemine kuruludur.

```csharp
public struct PdfFontInfo : IFontInfo
```

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [Content](../../groupdocs.viewer.fonts/pdffontinfo/content) { get; } | Bu yazı tipinin içeriği bayt dizisi olarak. Yalnızca bu yazı tipi hakkında meta bilgi varsa ancak ikili içeriği mevcut değilse, bu özellik `null` döndürür. |
| [FamilyName](../../groupdocs.viewer.fonts/pdffontinfo/familyname) { get; } | Stil olmadan yazı tipinin aile adı, hiçbir zaman null veya boş dize değildir |
| [Format](../../groupdocs.viewer.fonts/pdffontinfo/format) { get; } | Bu yazı tipinin biçimi. Belgeler aşağıdaki biçimlerde yazı tipleri kullanabilir: TrueType, TrueType Collection, OpenType, Embedded OpenType. Yalnızca bu yazı tipi hakkında meta bilgi varsa ancak ikili içeriği mevcut değilse, bu özellik Unknown değerini döndürür. |
| [IsEmbedded](../../groupdocs.viewer.fonts/pdffontinfo/isembedded) { get; } | Bu yazı tipinin PDF belgesi içinde gömülü olup olmadığını, [`Viewer`](../../groupdocs.viewer/viewer) örneğine yüklendiğini (`true`), gösterir ya da göstermez. |
| [IsInstalled](../../groupdocs.viewer.fonts/pdffontinfo/isinstalled) { get; } | Bu yazı tipinin GroupDocs.Viewer'ın çalıştığı işletim sisteminde mevcut (kurulu) olup olmadığını gösterir. |
| [Style](../../groupdocs.viewer.fonts/pdffontinfo/style) { get; } | Yazı tipinin stili — Regular, Bold, Italic veya Bold Italic olabilir. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| [SerializeToCss](../../groupdocs.viewer.fonts/pdffontinfo/serializetocss)(TextWriter) | Bu yazı tipi bilgisini @font-face at-rule olarak serileştirir ve belirtilen metin yazarına yazar. |

### Ayrıca Bakınız

* interface [IFontInfo](../ifontinfo)
* namespace [GroupDocs.Viewer.Fonts](../../groupdocs.viewer.fonts)
* assembly [GroupDocs.Viewer](../../)

<!-- DÜZENLEMEYİN: xmldocmd tarafından GroupDocs.Viewer.dll için oluşturuldu -->
