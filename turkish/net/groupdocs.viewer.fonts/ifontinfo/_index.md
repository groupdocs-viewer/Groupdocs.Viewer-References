---
title: "IFontInfo"
second_title: "GroupDocs.Viewer için .NET API Referansı"
description: "PDF, WordProcessing, Spreadsheet ve Presentation belge formatlarının tüm desteklenen ailelerinden çıkarılabilen tüm yazı tipleri için ortak arayüz."
type: docs
weight: 820
url: /tr/net/groupdocs.viewer.fonts/ifontinfo/
---

## IFontInfo interface

Tüm yazı tipleri için ortak arayüz, PDF, WordProcessing, Spreadsheet ve Presentation gibi desteklenen tüm belge formatı ailelerinden çıkarılabilir.

```csharp
public interface IFontInfo
```

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [Content](../../groupdocs.viewer.fonts/ifontinfo/content) { get; } | Yazı tipinin ikili içeriği bayt dizisi olarak, mevcutsa, aksi takdirde `null`. |
| [FamilyName](../../groupdocs.viewer.fonts/ifontinfo/familyname) { get; } | Yazı tipinin aile adı dize olarak |
| [Format](../../groupdocs.viewer.fonts/ifontinfo/format) { get; } | Bu yazı tipinin biçimi enum olarak — TrueType, TrueType Collection, OpenType, Embedded OpenType veya Unknown. |
| [Style](../../groupdocs.viewer.fonts/ifontinfo/style) { get; } | Yazı tipinin stili enum olarak — Regular, Bold, Italic veya Bold Italic. Bazı belge formatları yalnızca bir [`Regular`](../fontstyles/regular) stilinde yazı tipine sahip olabilir. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| [SerializeToCss](../../groupdocs.viewer.fonts/ifontinfo/serializetocss)(TextWriter) | Bu yazı tipi bilgisini @font-face at-rule olarak serileştirir ve belirtilen metin yazarına yazar. |

### Ayrıca Bakınız

* namespace [GroupDocs.Viewer.Fonts](../../groupdocs.viewer.fonts)
* assembly [GroupDocs.Viewer](../../)

<!-- DÜZENLEMEYİN: xmldocmd tarafından GroupDocs.Viewer.dll için oluşturuldu -->
