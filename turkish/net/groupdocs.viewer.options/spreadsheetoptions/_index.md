---
title: "SpreadsheetOptions"
second_title: "GroupDocs.Viewer için .NET API Referansı"
description: "Elektronik tablo renderleme seçeneklerini içerir. Ayrıntılar için Render spreadsheet dosyalarının alt öğelerine bakın https://docs.groupdocs.com/viewer/net/renderspreadsheets/ konusunu."
type: docs
weight: 530
url: /tr/net/groupdocs.viewer.options/spreadsheetoptions/
---

## SpreadsheetOptions class

Elektronik tablo dosyalarını render etme seçeneklerini içerir. Ayrıntılar için [Elektronik tablo dosyalarını render etme](https://docs.groupdocs.com/viewer/net/render-spreadsheets/) konusunun alt bölümlerine bakın.

```csharp
public class SpreadsheetOptions
```

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [BottomMargin](../../groupdocs.viewer.options/spreadsheetoptions/bottommargin) { get; set; } | PDF'ye dönüştürürken bir sayfanın alt kenar boşluğunu ayarlar. |
| [CountColumnsPerPage](../../groupdocs.viewer.options/spreadsheetoptions/countcolumnsperpage) { get; } | Çalışma sayfasını sayfalara bölerken her sayfada dahil edilecek sütun sayısı. |
| [CountRowsPerPage](../../groupdocs.viewer.options/spreadsheetoptions/countrowsperpage) { get; } | Çalışma sayfasını sayfalara bölerken her sayfada dahil edilecek satır sayısı. |
| [DetectSeparator](../../groupdocs.viewer.options/spreadsheetoptions/detectseparator) { get; set; } | Bir ayırıcıyı algıla (CSV/TSV dosyaları için). |
| [HorizontalResolution](../../groupdocs.viewer.options/spreadsheetoptions/horizontalresolution) { get; set; } | Oluşturulan görüntüler için inç başına nokta cinsinden yatay çözünürlüğü alır veya ayarlar. Bu seçenek yalnızca elektronik tablolar PNG veya JPEG formatına render edilirken kullanılır. |
| [LeftMargin](../../groupdocs.viewer.options/spreadsheetoptions/leftmargin) { get; set; } | PDF'ye dönüştürürken bir sayfanın sol kenar boşluğunu ayarlar. |
| [RenderGridLines](../../groupdocs.viewer.options/spreadsheetoptions/rendergridlines) { get; set; } | Kılavuz çizgilerinin render edilmesini etkinleştirir. |
| [RenderHeadings](../../groupdocs.viewer.options/spreadsheetoptions/renderheadings) { get; set; } | Başlıkların render edilmesini etkinleştirir. |
| [RenderHiddenColumns](../../groupdocs.viewer.options/spreadsheetoptions/renderhiddencolumns) { get; set; } | Gizli sütunların render edilmesini etkinleştirir. |
| [RenderHiddenRows](../../groupdocs.viewer.options/spreadsheetoptions/renderhiddenrows) { get; set; } | Gizli satırların render edilmesini etkinleştirir. |
| [RightMargin](../../groupdocs.viewer.options/spreadsheetoptions/rightmargin) { get; set; } | PDF'ye dönüştürürken bir sayfanın sağ kenar boşluğunu ayarlar. |
| [SkipEmptyColumns](../../groupdocs.viewer.options/spreadsheetoptions/skipemptycolumns) { get; set; } | Boş sütunların render edilmesini devre dışı bırakır. |
| [SkipEmptyRows](../../groupdocs.viewer.options/spreadsheetoptions/skipemptyrows) { get; set; } | Boş satırların render edilmesini devre dışı bırakır. |
| [TextOverflowMode](../../groupdocs.viewer.options/spreadsheetoptions/textoverflowmode) { get; set; } | Elektronik tablo belgelerinin HTML'ye render edilmesi için metin taşma modunu ayarlar. Varsayılan olarak , MS Excel'in varsayılan davranışını taklit eder. |
| [TopMargin](../../groupdocs.viewer.options/spreadsheetoptions/topmargin) { get; set; } | PDF'ye dönüştürürken bir sayfanın üst kenar boşluğunu ayarlar. |
| [VerticalResolution](../../groupdocs.viewer.options/spreadsheetoptions/verticalresolution) { get; set; } | Oluşturulan görüntüler için dikey çözünürlüğü dpi cinsinden alır veya ayarlar. Bu seçenek yalnızca elektronik tablolar PNG veya JPEG formatlarına render edildiğinde kullanılır. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| static [ForOnePagePerSheet](../../groupdocs.viewer.options/spreadsheetoptions/foronepagepersheet)() | Tüm sayfayı tek bir sayfaya render etmek için [`SpreadsheetOptions`](../spreadsheetoptions) sınıfının bir örneğini başlatır. |
| static [ForRenderingByPageBreaks](../../groupdocs.viewer.options/spreadsheetoptions/forrenderingbypagebreaks)() | Sayfa sonlarına göre sayfalara bölmek için [`SpreadsheetOptions`](../spreadsheetoptions) sınıfının bir örneğini başlatır. |
| static [ForRenderingPrintArea](../../groupdocs.viewer.options/spreadsheetoptions/forrenderingprintarea)() | Yalnızca yazdırma alanlarını render etmek için [`SpreadsheetOptions`](../spreadsheetoptions) sınıfının bir örneğini başlatır. |
| static [ForRenderingPrintAreaAndPageBreaks](../../groupdocs.viewer.options/spreadsheetoptions/forrenderingprintareaandpagebreaks)() | Yazdırma alanlarını ve sayfa sonlarını render etmek için [`SpreadsheetOptions`](../spreadsheetoptions) sınıfının bir örneğini başlatır. |
| static [ForSplitSheetIntoPages](../../groupdocs.viewer.options/spreadsheetoptions/forsplitsheetintopages#forsplitsheetintopages)(int) | Sayfayı sayfalara render etmek için [`SpreadsheetOptions`](../spreadsheetoptions) sınıfının bir örneğini başlatır. |
| static [ForSplitSheetIntoPages](../../groupdocs.viewer.options/spreadsheetoptions/forsplitsheetintopages#forsplitsheetintopages_1)(int, int) | Sayfayı sayfalara render etmek için [`SpreadsheetOptions`](../spreadsheetoptions) sınıfının bir örneğini başlatır. |

### Ayrıca Bakınız

* namespace [GroupDocs.Viewer.Options](../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../)

<!-- DÜZENLEMEYİN: xmldocmd tarafından GroupDocs.Viewer.dll için oluşturuldu -->
