---
title: "ViewInfoOptions"
second_title: "GroupDocs.Viewer için .NET API Referansı"
description: "Görünüm hakkında bilgi alma seçeneklerini içerir."
type: docs
weight: 580
url: /tr/net/groupdocs.viewer.options/viewinfooptions/
---

## ViewInfoOptions class

Görünüm hakkında bilgi alma seçeneklerini içerir.

```csharp
public class ViewInfoOptions : BaseViewOptions, IMaxSizeOptions
```

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [ArchiveOptions](../../groupdocs.viewer.options/baseviewoptions/archiveoptions) { get; set; } | Arşiv dosyalarının görüntüleme seçenekleri. |
| [CadOptions](../../groupdocs.viewer.options/baseviewoptions/cadoptions) { get; set; } | CAD çizimlerinin görüntüleme seçenekleri. |
| [DefaultFontName](../../groupdocs.viewer.options/baseviewoptions/defaultfontname) { get; set; } | Bir belge için varsayılan yazı tipini ayarlar. |
| [EmailOptions](../../groupdocs.viewer.options/baseviewoptions/emailoptions) { get; set; } | E-posta mesajlarının görüntüleme seçenekleri. |
| [ExtractText](../../groupdocs.viewer.options/viewinfooptions/extracttext) { get; set; } | Metin çıkarımını etkinleştirir. |
| [Height](../../groupdocs.viewer.options/viewinfooptions/height) { get; set; } | Çıktı görüntüsünün yüksekliği (piksel cinsinden, yalnızca PNG/JPG renderleme için). |
| [MailStorageOptions](../../groupdocs.viewer.options/baseviewoptions/mailstorageoptions) { get; set; } | Posta depolama veri dosyalarının görüntüleme seçenekleri. |
| [MaxHeight](../../groupdocs.viewer.options/viewinfooptions/maxheight) { get; set; } | Çıktı görüntüsünün maksimum yüksekliğini ayarlar (piksel cinsinden, yalnızca PNG/JPG renderleme için). |
| [MaxWidth](../../groupdocs.viewer.options/viewinfooptions/maxwidth) { get; set; } | Çıktı görüntüsünün maksimum genişliğini ayarlar (piksel cinsinden, yalnızca PNG/JPG renderleme için). |
| [OutlookOptions](../../groupdocs.viewer.options/baseviewoptions/outlookoptions) { get; set; } | Microsoft Outlook veri dosyalarının görüntüleme seçenekleri. |
| [PdfOptions](../../groupdocs.viewer.options/baseviewoptions/pdfoptions) { get; set; } | PDF belge görüntüleme seçenekleri. |
| [PresentationOptions](../../groupdocs.viewer.options/baseviewoptions/presentationoptions) { get; set; } | Sunum dosyalarının görüntüleme seçenekleri. |
| [ProjectManagementOptions](../../groupdocs.viewer.options/baseviewoptions/projectmanagementoptions) { get; set; } | Proje yönetimi dosyalarının görüntüleme seçenekleri. |
| [RemoveComments](../../groupdocs.viewer.options/baseviewoptions/removecomments) { get; set; } | `true` olarak ayarlandığında yorumların işlenmesini devre dışı bırakır. Varsayılan olarak `false` — tüm yorumlar gösterilir. |
| [RenderHiddenPages](../../groupdocs.viewer.options/baseviewoptions/renderhiddenpages) { get; set; } | Gizli sayfaların işlenmesini etkinleştirir. |
| [RenderNotes](../../groupdocs.viewer.options/baseviewoptions/rendernotes) { get; set; } | Bazı formatlar için notların ve ek açıklamaların işlenmesini etkinleştirir |
| [SpreadsheetOptions](../../groupdocs.viewer.options/baseviewoptions/spreadsheetoptions) { get; set; } | Elektronik tablo dosyalarının görüntüleme seçenekleri. |
| [TextOptions](../../groupdocs.viewer.options/baseviewoptions/textoptions) { get; set; } | Metin dosyalarının görüntüleme seçenekleri. |
| [VisioRenderingOptions](../../groupdocs.viewer.options/baseviewoptions/visiorenderingoptions) { get; set; } | Visio dosyalarının görüntüleme seçenekleri. |
| [WebDocumentOptions](../../groupdocs.viewer.options/baseviewoptions/webdocumentoptions) { get; set; } | Web dosyalarının görüntüleme seçenekleri. |
| [Width](../../groupdocs.viewer.options/viewinfooptions/width) { get; set; } | Çıktı görüntüsünün genişliği (piksel cinsinden, yalnızca PNG/JPG renderleme için). |
| [WordProcessingOptions](../../groupdocs.viewer.options/baseviewoptions/wordprocessingoptions) { get; set; } | Kelime işlem dosyalarının görüntüleme seçenekleri. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| static [ForHtmlView](../../groupdocs.viewer.options/viewinfooptions/forhtmlview#forhtmlview)() | HTML'ye renderlendiğinde görünüm hakkında bilgi almak için bir [`ViewInfoOptions`](../viewinfooptions) sınıfının örneğini başlatır. |
| static [ForHtmlView](../../groupdocs.viewer.options/viewinfooptions/forhtmlview#forhtmlview_1)(bool) | HTML'ye renderlendiğinde görünüm hakkında bilgi almak için bir [`ViewInfoOptions`](../viewinfooptions) sınıfının örneğini başlatır. |
| static [ForJpgView](../../groupdocs.viewer.options/viewinfooptions/forjpgview#forjpgview)() | JPG'ye renderlendiğinde görünüm hakkında bilgi almak için bir [`ViewInfoOptions`](../viewinfooptions) sınıfının örneğini başlatır. |
| static [ForJpgView](../../groupdocs.viewer.options/viewinfooptions/forjpgview#forjpgview_1)(bool) | JPG'ye renderlendiğinde görünüm hakkında bilgi almak için bir [`ViewInfoOptions`](../viewinfooptions) sınıfının örneğini başlatır. |
| static [ForPdfView](../../groupdocs.viewer.options/viewinfooptions/forpdfview)() | PDF'ye renderlendiğinde görünüm hakkında bilgi almak için bir [`ViewInfoOptions`](../viewinfooptions) sınıfının örneğini başlatır. |
| static [ForPngView](../../groupdocs.viewer.options/viewinfooptions/forpngview#forpngview)() | PNG'ye renderlendiğinde görünüm hakkında bilgi almak için bir [`ViewInfoOptions`](../viewinfooptions) sınıfının örneğini başlatır. |
| static [ForPngView](../../groupdocs.viewer.options/viewinfooptions/forpngview#forpngview_1)(bool) | PNG'ye renderlendiğinde görünüm hakkında bilgi almak için bir [`ViewInfoOptions`](../viewinfooptions) sınıfının örneğini başlatır. |
| static [FromHtmlViewOptions](../../groupdocs.viewer.options/viewinfooptions/fromhtmlviewoptions)(HtmlViewOptions) | Bir [`HtmlViewOptions`](../htmlviewoptions) nesnesine dayanarak bir [`ViewInfoOptions`](../viewinfooptions) sınıfının örneğini başlatır. |
| static [FromJpgViewOptions](../../groupdocs.viewer.options/viewinfooptions/fromjpgviewoptions)(JpgViewOptions) | Bir [`JpgViewOptions`](../jpgviewoptions) nesnesine dayanarak bir [`ViewInfoOptions`](../viewinfooptions) sınıfının örneğini başlatır. |
| static [FromPdfViewOptions](../../groupdocs.viewer.options/viewinfooptions/frompdfviewoptions)(PdfViewOptions) | Bir [`PdfViewOptions`](../pdfviewoptions) nesnesine dayanarak bir [`ViewInfoOptions`](../viewinfooptions) sınıfının örneğini başlatır. |
| static [FromPngViewOptions](../../groupdocs.viewer.options/viewinfooptions/frompngviewoptions)(PngViewOptions) | Bir [`PngViewOptions`](../pngviewoptions) nesnesine dayanarak bir [`ViewInfoOptions`](../viewinfooptions) sınıfının örneğini başlatır. |

### Ayrıca Bakınız

* class [BaseViewOptions](../baseviewoptions)
* interface [IMaxSizeOptions](../imaxsizeoptions)
* namespace [GroupDocs.Viewer.Options](../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../)

<!-- DÜZENLEMEYİN: xmldocmd tarafından GroupDocs.Viewer.dll için oluşturuldu -->
