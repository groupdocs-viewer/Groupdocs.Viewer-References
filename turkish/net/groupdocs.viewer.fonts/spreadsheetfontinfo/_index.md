---
title: "SpreadsheetFontInfo"
second_title: "GroupDocs.Viewer için .NET API Referansı"
description: "Spreadsheet belgesinden bir yazı tipinin meta bilgilerini ve ikili verilerini Viewer../groupdocs.viewer/viewer örneğine yüklenmiş olarak kapsüller. Elektronik tablo belgeleri gömülü yazı tiplerine sahip olamaz, bu nedenle bu belirli yazı tipi GetAllFonts../groupdocs.viewer/viewer/getallfonts yöntemiyle döndürüldüyse, GroupDocs.Viewer'ın çalıştığı işletim sistemine kuruludur."
type: docs
weight: 870
url: /tr/net/groupdocs.viewer.fonts/spreadsheetfontinfo/
---

## SpreadsheetFontInfo structure

Spreadsheet belgesinden bir yazı tipinin meta bilgilerini ve ikili verilerini, [`Viewer`](../../groupdocs.viewer/viewer) örneğine yüklenmiş olarak kapsüller. Elektronik tablo belgeleri gömülü yazı tiplerine sahip olamaz, bu nedenle bu belirli yazı tipi, [`GetAllFonts`](../../groupdocs.viewer/viewer/getallfonts) yöntemiyle döndürüldüyse, GroupDocs.Viewer'ın çalıştığı işletim sistemine kuruludur.

```csharp
public struct SpreadsheetFontInfo : IFontInfo
```

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [Charset](../../groupdocs.viewer.fonts/spreadsheetfontinfo/charset) { get; } | Bu yazı tipinin karakter kümesi |
| [Color](../../groupdocs.viewer.fonts/spreadsheetfontinfo/color) { get; } | Bu yazı tipinin rengi |
| [Content](../../groupdocs.viewer.fonts/spreadsheetfontinfo/content) { get; } | Bu yazı tipinin içeriği bayt dizisi olarak. Yalnızca bu yazı tipi hakkında meta bilgi varsa ancak ikili içeriği mevcut değilse, bu özellik `null` döndürür. |
| [FamilyName](../../groupdocs.viewer.fonts/spreadsheetfontinfo/familyname) { get; } | Stil olmadan yazı tipinin aile adı, hiçbir zaman null veya boş dize değildir |
| [Format](../../groupdocs.viewer.fonts/spreadsheetfontinfo/format) { get; } | Bu yazı tipinin formatı |
| [IsStrikeout](../../groupdocs.viewer.fonts/spreadsheetfontinfo/isstrikeout) { get; } | Yazı tipinin tek bir üstü çizili olup olmadığını gösterir |
| [IsUnderline](../../groupdocs.viewer.fonts/spreadsheetfontinfo/isunderline) { get; } | Yazı tipinin altı çizili olup olmadığını gösterir |
| [Style](../../groupdocs.viewer.fonts/spreadsheetfontinfo/style) { get; } | Bu yazı tipinin stili — Regular, Bold, Italic veya Bold Italic olabilir |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| [SerializeToCss](../../groupdocs.viewer.fonts/spreadsheetfontinfo/serializetocss)(TextWriter) | Bu yazı tipi bilgisini @font-face at-rule olarak serileştirir ve belirtilen metin yazarına yazar. |

### Ayrıca Bakınız

* interface [IFontInfo](../ifontinfo)
* namespace [GroupDocs.Viewer.Fonts](../../groupdocs.viewer.fonts)
* assembly [GroupDocs.Viewer](../../)

<!-- DÜZENLEMEYİN: xmldocmd tarafından GroupDocs.Viewer.dll için oluşturuldu -->
