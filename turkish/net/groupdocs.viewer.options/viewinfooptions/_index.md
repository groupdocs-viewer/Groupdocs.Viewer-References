---
title: ViewInfoOptions
second_title: .NET API Başvurusu için GroupDocs.Viewer
description: Görünüm hakkında bilgi almak için kullanılan seçenekleri sağlar.
type: docs
weight: 570
url: /tr/net/groupdocs.viewer.options/viewinfooptions/
---
## ViewInfoOptions class

Görünüm hakkında bilgi almak için kullanılan seçenekleri sağlar.

```csharp
public class ViewInfoOptions : BaseViewOptions, IMaxSizeOptions
```

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [ArchiveOptions](../../groupdocs.viewer.options/baseviewoptions/archiveoptions) { get; set; } | Arşiv dosyaları görüntüleme seçenekleri. |
| [CadOptions](../../groupdocs.viewer.options/baseviewoptions/cadoptions) { get; set; } | CAD çizim görünümü seçenekleri. |
| [DefaultFontName](../../groupdocs.viewer.options/baseviewoptions/defaultfontname) { get; set; } | Belgede kullanılan belirli yazı tipi bulunamadığında kullanılacak varsayılan yazı tipi. |
| [EmailOptions](../../groupdocs.viewer.options/baseviewoptions/emailoptions) { get; set; } | E-posta mesajları görüntüleme seçenekleri. |
| [ExtractText](../../groupdocs.viewer.options/viewinfooptions/extracttext) { get; set; } | Metin çıkarmanın etkinleştirildiğini gösterir. |
| [Height](../../groupdocs.viewer.options/viewinfooptions/height) { get; set; } | Görüntü yüksekliği (yalnızca PNG/JPG'ye oluşturmak için) |
| [MailStorageOptions](../../groupdocs.viewer.options/baseviewoptions/mailstorageoptions) { get; set; } | Posta depolama veri dosyaları görüntüleme seçenekleri. |
| [MaxHeight](../../groupdocs.viewer.options/viewinfooptions/maxheight) { get; set; } | Çıktı görüntüsünün maksimum yüksekliği (yalnızca PNG/JPG'ye dönüştürme için) |
| [MaxWidth](../../groupdocs.viewer.options/viewinfooptions/maxwidth) { get; set; } | Çıktı görüntüsünün maksimum genişliği (yalnızca PNG/JPG'ye dönüştürme için) |
| [OutlookOptions](../../groupdocs.viewer.options/baseviewoptions/outlookoptions) { get; set; } | MS Outlook veri dosyaları görüntüleme seçenekleri. |
| [PdfOptions](../../groupdocs.viewer.options/baseviewoptions/pdfoptions) { get; set; } | PDF belgeleri görüntüleme seçenekleri. |
| [PresentationOptions](../../groupdocs.viewer.options/baseviewoptions/presentationoptions) { get; set; } | Sunum işleme belgeleri görüntüleme seçenekleri. |
| [ProjectManagementOptions](../../groupdocs.viewer.options/baseviewoptions/projectmanagementoptions) { get; set; } | Proje yönetimi dosyaları görüntüleme seçenekleri. |
| [RenderComments](../../groupdocs.viewer.options/baseviewoptions/rendercomments) { get; set; } | Yorumların işlenmesini etkinleştirir. |
| [RenderHiddenPages](../../groupdocs.viewer.options/baseviewoptions/renderhiddenpages) { get; set; } | Gizli sayfaların oluşturulmasını sağlar. |
| [RenderNotes](../../groupdocs.viewer.options/baseviewoptions/rendernotes) { get; set; } | Notların işlenmesini etkinleştirir. |
| [SpreadsheetOptions](../../groupdocs.viewer.options/baseviewoptions/spreadsheetoptions) { get; set; } | Elektronik tablo dosyaları görüntüleme seçenekleri. |
| [TextOptions](../../groupdocs.viewer.options/baseviewoptions/textoptions) { get; set; } | Sayfa seçeneklerine bölünen metin dosyaları. |
| [VisioRenderingOptions](../../groupdocs.viewer.options/baseviewoptions/visiorenderingoptions) { get; set; } | Belgeleri işleyen Visio dosyaları görüntüleme seçenekleri. |
| [WebDocumentOptions](../../groupdocs.viewer.options/baseviewoptions/webdocumentoptions) { get; set; } | Bu işleme seçenekleri, Web belgelerini işlerken HTML/PDF/PNG/JPEG çıktısının görünümünü özelleştirmenizi sağlar. |
| [Width](../../groupdocs.viewer.options/viewinfooptions/width) { get; set; } | Görüntü genişliği (yalnızca PNG/JPG'ye oluşturmak için) |
| [WordProcessingOptions](../../groupdocs.viewer.options/baseviewoptions/wordprocessingoptions) { get; set; } | Bu işleme seçenekleri, Word belgelerini işlerken HTML/PDF/PNG/JPEG çıktısının görünümünü özelleştirmenizi sağlar. |

## yöntemler

| İsim | Tanım |
| --- | --- |
| static [ForHtmlView](../../groupdocs.viewer.options/viewinfooptions/forhtmlview#forhtmlview)() | Yeni örneğini başlatır[`ViewInfoOptions`](../viewinfooptions) HTML. içine işlerken görünüm hakkında bilgi almak için sınıf |
| static [ForHtmlView](../../groupdocs.viewer.options/viewinfooptions/forhtmlview#forhtmlview_1)(bool) | Yeni örneğini başlatır[`ViewInfoOptions`](../viewinfooptions) HTML. içine işlerken görünüm hakkında bilgi almak için sınıf |
| static [ForJpgView](../../groupdocs.viewer.options/viewinfooptions/forjpgview#forjpgview)() | Yeni örneğini başlatır[`ViewInfoOptions`](../viewinfooptions) JPG. içine işlerken görünüm hakkında bilgi almak için sınıf |
| static [ForJpgView](../../groupdocs.viewer.options/viewinfooptions/forjpgview#forjpgview_1)(bool) | Yeni örneğini başlatır[`ViewInfoOptions`](../viewinfooptions) JPG. içine işlerken görünüm hakkında bilgi almak için sınıf |
| static [ForPngView](../../groupdocs.viewer.options/viewinfooptions/forpngview#forpngview)() | Yeni örneğini başlatır[`ViewInfoOptions`](../viewinfooptions) PNG. içine işlerken görünüm hakkında bilgi almak için sınıf |
| static [ForPngView](../../groupdocs.viewer.options/viewinfooptions/forpngview#forpngview_1)(bool) | Yeni örneğini başlatır[`ViewInfoOptions`](../viewinfooptions) PNG. içine işlerken görünüm hakkında bilgi almak için sınıf |
| static [FromHtmlViewOptions](../../groupdocs.viewer.options/viewinfooptions/fromhtmlviewoptions)(HtmlViewOptions) | Yeni örneğini başlatır[`ViewInfoOptions`](../viewinfooptions) dayalı sınıf[`HtmlViewOptions`](../htmlviewoptions) nesne. |
| static [FromJpgViewOptions](../../groupdocs.viewer.options/viewinfooptions/fromjpgviewoptions)(JpgViewOptions) | Yeni örneğini başlatır[`ViewInfoOptions`](../viewinfooptions) dayalı sınıf[`JpgViewOptions`](../jpgviewoptions) nesne. |
| static [FromPngViewOptions](../../groupdocs.viewer.options/viewinfooptions/frompngviewoptions)(PngViewOptions) | Yeni örneğini başlatır[`ViewInfoOptions`](../viewinfooptions) dayalı sınıf[`PngViewOptions`](../pngviewoptions) nesne. |

### Ayrıca bakınız

* class [BaseViewOptions](../baseviewoptions)
* interface [IMaxSizeOptions](../imaxsizeoptions)
* ad alanı [GroupDocs.Viewer.Options](../../groupdocs.viewer.options)
* toplantı [GroupDocs.Viewer](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Viewer.dll -->
