---
title: "HtmlViewOptions"
second_title: "GroupDocs.Viewer için .NET API Referansı"
description: "Belgeleri HTML formatına renderlemek için seçenekleri içerir. Ayrıntılar için topichttps//docs.groupdocs.com/viewer/net/renderingtohtml/ ve alt sayfalarına bakın."
type: docs
weight: 320
url: /tr/net/groupdocs.viewer.options/htmlviewoptions/
---

## HtmlViewOptions class

Belgeleri HTML formatına render etme seçeneklerini içerir. Ayrıntılar için [konuya](https://docs.groupdocs.com/viewer/net/rendering-to-html/) ve alt bölümlerine bakın.

```csharp
public class HtmlViewOptions : ViewOptions
```

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [ArchiveOptions](../../groupdocs.viewer.options/baseviewoptions/archiveoptions) { get; set; } | Arşiv dosyalarının görüntüleme seçenekleri. |
| [CadOptions](../../groupdocs.viewer.options/baseviewoptions/cadoptions) { get; set; } | CAD çizimlerinin görüntüleme seçenekleri. |
| [DefaultFontName](../../groupdocs.viewer.options/baseviewoptions/defaultfontname) { get; set; } | Bir belge için varsayılan yazı tipini ayarlar. |
| [EmailOptions](../../groupdocs.viewer.options/baseviewoptions/emailoptions) { get; set; } | E-posta mesajlarının görüntüleme seçenekleri. |
| [ExcludeFonts](../../groupdocs.viewer.options/htmlviewoptions/excludefonts) { get; set; } | HTML belgesine herhangi bir yazı tipinin eklenmesini devre dışı bırakır. |
| [FontsToExclude](../../groupdocs.viewer.options/htmlviewoptions/fontstoexclude) { get; set; } | HTML belgesinden hariç tutulacak yazı tipi adlarının listesi. |
| [ForPrinting](../../groupdocs.viewer.options/htmlviewoptions/forprinting) { get; set; } | Çıktı HTML'nin yazdırma için optimize edilmesini etkinleştirir. |
| [ImageHeight](../../groupdocs.viewer.options/htmlviewoptions/imageheight) { get; set; } | Çıktı görüntüsünün yüksekliği (piksel cinsinden). Bu özellik yalnızca tek görüntüyü HTML'ye dönüştürürken kullanılabilir. |
| [ImageMaxHeight](../../groupdocs.viewer.options/htmlviewoptions/imagemaxheight) { get; set; } | Çıktı görüntüsünün maksimum yüksekliği (piksel cinsinden). Bu özellik yalnızca tek görüntüyü HTML'ye dönüştürürken kullanılabilir. |
| [ImageMaxWidth](../../groupdocs.viewer.options/htmlviewoptions/imagemaxwidth) { get; set; } | Çıktı görüntüsünün maksimum genişliği (piksel cinsinden). Bu özellik yalnızca tek görüntüyü HTML'ye dönüştürürken kullanılabilir. |
| [ImageWidth](../../groupdocs.viewer.options/htmlviewoptions/imagewidth) { get; set; } | Çıktı görüntüsünün genişliği (piksel cinsinden). Bu özellik yalnızca tek görüntüyü HTML'ye dönüştürürken kullanılabilir. |
| [MailStorageOptions](../../groupdocs.viewer.options/baseviewoptions/mailstorageoptions) { get; set; } | Posta depolama veri dosyalarının görüntüleme seçenekleri. |
| [Minify](../../groupdocs.viewer.options/htmlviewoptions/minify) { get; set; } | HTML içeriği ve HTML kaynaklarının küçültülmesini etkinleştirir. |
| [OutlookOptions](../../groupdocs.viewer.options/baseviewoptions/outlookoptions) { get; set; } | Microsoft Outlook veri dosyalarının görüntüleme seçenekleri. |
| [PdfOptions](../../groupdocs.viewer.options/baseviewoptions/pdfoptions) { get; set; } | PDF belge görüntüleme seçenekleri. |
| [PresentationOptions](../../groupdocs.viewer.options/baseviewoptions/presentationoptions) { get; set; } | Sunum dosyalarının görüntüleme seçenekleri. |
| [ProjectManagementOptions](../../groupdocs.viewer.options/baseviewoptions/projectmanagementoptions) { get; set; } | Proje yönetimi dosyalarının görüntüleme seçenekleri. |
| [RemoveComments](../../groupdocs.viewer.options/baseviewoptions/removecomments) { get; set; } | `true` olarak ayarlandığında yorumların işlenmesini devre dışı bırakır. Varsayılan olarak `false` — tüm yorumlar gösterilir. |
| [RemoveJavaScript](../../groupdocs.viewer.options/htmlviewoptions/removejavascript) { get; set; } | Betik içeren giriş belgeleri işlenirken, sonuç HTML belgelerindeki bağlantılardan JavaScript kaynak kodunu kaldırmaya izin verir. Varsayılan olarak etkindir (`true`). |
| [RenderHiddenPages](../../groupdocs.viewer.options/baseviewoptions/renderhiddenpages) { get; set; } | Gizli sayfaların işlenmesini etkinleştirir. |
| [RenderNotes](../../groupdocs.viewer.options/baseviewoptions/rendernotes) { get; set; } | Bazı formatlar için notların ve ek açıklamaların işlenmesini etkinleştirir |
| [RenderResponsive](../../groupdocs.viewer.options/htmlviewoptions/renderresponsive) { get; set; } | Duyarlı renderlamayı etkinleştirir. |
| [RenderToSinglePage](../../groupdocs.viewer.options/htmlviewoptions/rendertosinglepage) { get; set; } | Tüm belgeyi tek bir HTML dosyasına renderlamayı etkinleştirir. |
| [SpreadsheetOptions](../../groupdocs.viewer.options/baseviewoptions/spreadsheetoptions) { get; set; } | Elektronik tablo dosyalarının görüntüleme seçenekleri. |
| [TextOptions](../../groupdocs.viewer.options/baseviewoptions/textoptions) { get; set; } | Metin dosyalarının görüntüleme seçenekleri. |
| [VisioRenderingOptions](../../groupdocs.viewer.options/baseviewoptions/visiorenderingoptions) { get; set; } | Visio dosyalarının görüntüleme seçenekleri. |
| [Watermark](../../groupdocs.viewer.options/viewoptions/watermark) { get; set; } | Her sayfaya uygulanacak metin filigranı. |
| [WebDocumentOptions](../../groupdocs.viewer.options/baseviewoptions/webdocumentoptions) { get; set; } | Web dosyalarının görüntüleme seçenekleri. |
| [WordProcessingOptions](../../groupdocs.viewer.options/baseviewoptions/wordprocessingoptions) { get; set; } | Kelime işlem dosyalarının görüntüleme seçenekleri. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| static [ForEmbeddedResources](../../groupdocs.viewer.options/htmlviewoptions/forembeddedresources#forembeddedresources)() | [`HtmlViewOptions`](../htmlviewoptions) sınıfının bir örneğini başlatır. |
| static [ForEmbeddedResources](../../groupdocs.viewer.options/htmlviewoptions/forembeddedresources#forembeddedresources_1)(CreatePageStream) | Gömülü kaynaklarla HTML'ye renderlamak için [`HtmlViewOptions`](../htmlviewoptions) sınıfının bir örneğini başlatır. |
| static [ForEmbeddedResources](../../groupdocs.viewer.options/htmlviewoptions/forembeddedresources#forembeddedresources_3)(IPageStreamFactory) | Gömülü kaynaklarla HTML'ye renderlamak için [`HtmlViewOptions`](../htmlviewoptions) sınıfının bir örneğini başlatır. |
| static [ForEmbeddedResources](../../groupdocs.viewer.options/htmlviewoptions/forembeddedresources#forembeddedresources_4)(string) | [`HtmlViewOptions`](../htmlviewoptions) sınıfının bir örneğini başlatır. |
| static [ForEmbeddedResources](../../groupdocs.viewer.options/htmlviewoptions/forembeddedresources#forembeddedresources_2)(CreatePageStream, ReleasePageStream) | Gömülü kaynaklarla HTML'ye renderlamak için [`HtmlViewOptions`](../htmlviewoptions) sınıfının bir örneğini başlatır. |
| static [ForExternalResources](../../groupdocs.viewer.options/htmlviewoptions/forexternalresources#forexternalresources)() | [`HtmlViewOptions`](../htmlviewoptions) sınıfının bir örneğini başlatır. |
| static [ForExternalResources](../../groupdocs.viewer.options/htmlviewoptions/forexternalresources#forexternalresources_3)(IPageStreamFactory, IResourceStreamFactory) | Harici kaynaklarla HTML'ye renderlamak için [`HtmlViewOptions`](../htmlviewoptions) sınıfının bir örneğini başlatır. |
| static [ForExternalResources](../../groupdocs.viewer.options/htmlviewoptions/forexternalresources#forexternalresources_1)(CreatePageStream, CreateResourceStream, CreateResourceUrl) | Harici kaynaklarla HTML'ye renderlamak için [`HtmlViewOptions`](../htmlviewoptions) sınıfının bir örneğini başlatır. |
| static [ForExternalResources](../../groupdocs.viewer.options/htmlviewoptions/forexternalresources#forexternalresources_4)(string, string, string) | [`HtmlViewOptions`](../htmlviewoptions) sınıfının bir örneğini başlatır. |
| static [ForExternalResources](../../groupdocs.viewer.options/htmlviewoptions/forexternalresources#forexternalresources_2)(CreatePageStream, CreateResourceStream, CreateResourceUrl, ReleasePageStream, ReleaseResourceStream) | Harici kaynaklarla HTML'ye renderlamak için [`HtmlViewOptions`](../htmlviewoptions) sınıfının bir örneğini başlatır. |
| [RotatePage](../../groupdocs.viewer.options/viewoptions/rotatepage)(int, Rotation) | Bir sayfaya saat yönünde dönüş uygular. |

## Alanlar

| Ad | Açıklama |
| --- | --- |
| readonly [PageRotations](../../groupdocs.viewer.options/viewoptions/pagerotations) | Sayfa dönüşü. |

### Ayrıca Bakınız

* class [ViewOptions](../viewoptions)
* namespace [GroupDocs.Viewer.Options](../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../)

<!-- DÜZENLEMEYİN: xmldocmd tarafından GroupDocs.Viewer.dll için oluşturuldu -->
