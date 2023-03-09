---
title: HtmlViewOptions
second_title: .NET API Başvurusu için GroupDocs.Viewer
description: Belgeleri HTML biçiminde işlemek için seçenekler sunar.
type: docs
weight: 330
url: /tr/net/groupdocs.viewer.options/htmlviewoptions/
---
## HtmlViewOptions class

Belgeleri HTML biçiminde işlemek için seçenekler sunar.

```csharp
public class HtmlViewOptions : ViewOptions
```

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [ArchiveOptions](../../groupdocs.viewer.options/baseviewoptions/archiveoptions) { get; set; } | Arşiv dosyaları görüntüleme seçenekleri. |
| [CadOptions](../../groupdocs.viewer.options/baseviewoptions/cadoptions) { get; set; } | CAD çizim görünümü seçenekleri. |
| [DefaultFontName](../../groupdocs.viewer.options/baseviewoptions/defaultfontname) { get; set; } | Belgede kullanılan belirli yazı tipi bulunamadığında kullanılacak varsayılan yazı tipi. |
| [EmailOptions](../../groupdocs.viewer.options/baseviewoptions/emailoptions) { get; set; } | E-posta mesajları görüntüleme seçenekleri. |
| [ExcludeFonts](../../groupdocs.viewer.options/htmlviewoptions/excludefonts) { get; set; } | Etkinleştirildiğinde, HTML belgesine herhangi bir yazı tipi eklenmesini engeller. |
| [FontsToExclude](../../groupdocs.viewer.options/htmlviewoptions/fontstoexclude) { get; set; } | HTML belgesinden hariç tutulacak yazı tipi adlarının listesi. |
| [ForPrinting](../../groupdocs.viewer.options/htmlviewoptions/forprinting) { get; set; } | Çıktı HTML'sinin yazdırma için optimize edilip edilmeyeceğini gösterir. |
| [ImageHeight](../../groupdocs.viewer.options/htmlviewoptions/imageheight) { get; set; } | Çıktı görüntüsünün piksel cinsinden yüksekliği. (Yalnızca tek bir görüntüyü HTML'ye dönüştürürken) |
| [ImageMaxHeight](../../groupdocs.viewer.options/htmlviewoptions/imagemaxheight) { get; set; } | Çıktı görüntüsünün piksel cinsinden maksimum yüksekliği. (Yalnızca tek bir görüntüyü HTML'ye dönüştürürken) |
| [ImageMaxWidth](../../groupdocs.viewer.options/htmlviewoptions/imagemaxwidth) { get; set; } | Çıktı görüntüsünün piksel cinsinden maksimum genişliği. (Yalnızca tek bir görüntüyü HTML'ye dönüştürürken) |
| [ImageWidth](../../groupdocs.viewer.options/htmlviewoptions/imagewidth) { get; set; } | Çıktı görüntüsünün piksel cinsinden genişliği. (Yalnızca tek bir görüntüyü HTML'ye dönüştürürken) |
| [MailStorageOptions](../../groupdocs.viewer.options/baseviewoptions/mailstorageoptions) { get; set; } | Posta depolama veri dosyaları görüntüleme seçenekleri. |
| [Minify](../../groupdocs.viewer.options/htmlviewoptions/minify) { get; set; } | HTML içeriğini ve HTML kaynaklarını küçültmeyi etkinleştirir. |
| [OutlookOptions](../../groupdocs.viewer.options/baseviewoptions/outlookoptions) { get; set; } | MS Outlook veri dosyaları görüntüleme seçenekleri. |
| [PdfOptions](../../groupdocs.viewer.options/baseviewoptions/pdfoptions) { get; set; } | PDF belgeleri görüntüleme seçenekleri. |
| [PresentationOptions](../../groupdocs.viewer.options/baseviewoptions/presentationoptions) { get; set; } | Sunum işleme belgeleri görüntüleme seçenekleri. |
| [ProjectManagementOptions](../../groupdocs.viewer.options/baseviewoptions/projectmanagementoptions) { get; set; } | Proje yönetimi dosyaları görüntüleme seçenekleri. |
| [RenderComments](../../groupdocs.viewer.options/baseviewoptions/rendercomments) { get; set; } | Yorumların işlenmesini etkinleştirir. |
| [RenderHiddenPages](../../groupdocs.viewer.options/baseviewoptions/renderhiddenpages) { get; set; } | Gizli sayfaların oluşturulmasını sağlar. |
| [RenderNotes](../../groupdocs.viewer.options/baseviewoptions/rendernotes) { get; set; } | Notların işlenmesini etkinleştirir. |
| [RenderResponsive](../../groupdocs.viewer.options/htmlviewoptions/renderresponsive) { get; set; } | Duyarlı oluşturmayı etkinleştirir; Duyarlı web sayfaları, farklı ekran boyutuna sahip cihazlarda iyi bir şekilde oluşturulur. |
| [RenderToSinglePage](../../groupdocs.viewer.options/htmlviewoptions/rendertosinglepage) { get; set; } | Belgenin tamamını tek bir HTML dosyasına dönüştürmeyi etkinleştirir. |
| [SpreadsheetOptions](../../groupdocs.viewer.options/baseviewoptions/spreadsheetoptions) { get; set; } | Elektronik tablo dosyaları görüntüleme seçenekleri. |
| [TextOptions](../../groupdocs.viewer.options/baseviewoptions/textoptions) { get; set; } | Sayfa seçeneklerine bölünen metin dosyaları. |
| [VisioRenderingOptions](../../groupdocs.viewer.options/baseviewoptions/visiorenderingoptions) { get; set; } | Belgeleri işleyen Visio dosyaları görüntüleme seçenekleri. |
| [Watermark](../../groupdocs.viewer.options/viewoptions/watermark) { get; set; } | Her sayfaya uygulanan metin filigranı. |
| [WebDocumentOptions](../../groupdocs.viewer.options/baseviewoptions/webdocumentoptions) { get; set; } | Bu işleme seçenekleri, Web belgelerini işlerken HTML/PDF/PNG/JPEG çıktısının görünümünü özelleştirmenizi sağlar. |
| [WordProcessingOptions](../../groupdocs.viewer.options/baseviewoptions/wordprocessingoptions) { get; set; } | Bu işleme seçenekleri, Word belgelerini işlerken HTML/PDF/PNG/JPEG çıktısının görünümünü özelleştirmenizi sağlar. |

## yöntemler

| İsim | Tanım |
| --- | --- |
| static [ForEmbeddedResources](../../groupdocs.viewer.options/htmlviewoptions/forembeddedresources#forembeddedresources)() | Yeni örneğini başlatır[`HtmlViewOptions`](../htmlviewoptions) sınıf. |
| static [ForEmbeddedResources](../../groupdocs.viewer.options/htmlviewoptions/forembeddedresources#forembeddedresources_1)(CreatePageStream) | Yeni örneğini başlatır[`HtmlViewOptions`](../htmlviewoptions) katıştırılmış kaynaklarla HTML'ye dönüştürmek için sınıf. |
| static [ForEmbeddedResources](../../groupdocs.viewer.options/htmlviewoptions/forembeddedresources#forembeddedresources_3)(IPageStreamFactory) | Yeni örneğini başlatır[`HtmlViewOptions`](../htmlviewoptions) katıştırılmış kaynaklarla HTML'ye dönüştürmek için sınıf. |
| static [ForEmbeddedResources](../../groupdocs.viewer.options/htmlviewoptions/forembeddedresources#forembeddedresources_4)(string) | Yeni örneğini başlatır[`HtmlViewOptions`](../htmlviewoptions) sınıf. |
| static [ForEmbeddedResources](../../groupdocs.viewer.options/htmlviewoptions/forembeddedresources#forembeddedresources_2)(CreatePageStream, ReleasePageStream) | Yeni örneğini başlatır[`HtmlViewOptions`](../htmlviewoptions) katıştırılmış kaynaklarla HTML'ye dönüştürmek için sınıf. |
| static [ForExternalResources](../../groupdocs.viewer.options/htmlviewoptions/forexternalresources#forexternalresources)() | Yeni örneğini başlatır[`HtmlViewOptions`](../htmlviewoptions) sınıf. |
| static [ForExternalResources](../../groupdocs.viewer.options/htmlviewoptions/forexternalresources#forexternalresources_3)(IPageStreamFactory, IResourceStreamFactory) | Yeni örneğini başlatır[`HtmlViewOptions`](../htmlviewoptions) harici kaynaklarla HTML'ye dönüştürmek için sınıf. |
| static [ForExternalResources](../../groupdocs.viewer.options/htmlviewoptions/forexternalresources#forexternalresources_1)(CreatePageStream, CreateResourceStream, CreateResourceUrl) | Yeni örneğini başlatır[`HtmlViewOptions`](../htmlviewoptions) harici kaynaklarla HTML'ye dönüştürmek için sınıf. |
| static [ForExternalResources](../../groupdocs.viewer.options/htmlviewoptions/forexternalresources#forexternalresources_4)(string, string, string) | Yeni örneğini başlatır[`HtmlViewOptions`](../htmlviewoptions) sınıf. |
| static [ForExternalResources](../../groupdocs.viewer.options/htmlviewoptions/forexternalresources#forexternalresources_2)(CreatePageStream, CreateResourceStream, CreateResourceUrl, ReleasePageStream, ReleaseResourceStream) | Yeni örneğini başlatır[`HtmlViewOptions`](../htmlviewoptions) harici kaynaklarla HTML'ye dönüştürmek için sınıf. |
| [RotatePage](../../groupdocs.viewer.options/viewoptions/rotatepage)(int, Rotation) | Sayfaya saat yönünde döndürme uygular. |

## Alanlar

| İsim | Tanım |
| --- | --- |
| readonly [PageRotations](../../groupdocs.viewer.options/viewoptions/pagerotations) | Sayfa döndürmeleri. |

### Ayrıca bakınız

* class [ViewOptions](../viewoptions)
* ad alanı [GroupDocs.Viewer.Options](../../groupdocs.viewer.options)
* toplantı [GroupDocs.Viewer](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Viewer.dll -->
