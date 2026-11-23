---
title: "PngViewOptions"
second_title: "GroupDocs.Viewer için .NET API Referansı"
description: "Belgeleri PNG formatında renderlamak için seçenekler içerir. Ayrıntılar için bu sayfaya https://docs.groupdocs.com/viewer/net/renderingtopngorjpeg/ ve alt sayfalarına bakın."
type: docs
weight: 440
url: /tr/net/groupdocs.viewer.options/pngviewoptions/
---

## PngViewOptions class

Belgeleri PNG formatına render etme seçeneklerini içerir. Ayrıntılar için bu [sayfaya](https://docs.groupdocs.com/viewer/net/rendering-to-png-or-jpeg/) ve alt bölümlerine bakın.

```csharp
public class PngViewOptions : ViewOptions, IMaxSizeOptions
```

## Yapıcılar

| Ad | Açıklama |
| --- | --- |
| [PngViewOptions](pngviewoptions#constructor)() | [`PngViewOptions`](../pngviewoptions) sınıfının bir örneğini başlatır. |
| [PngViewOptions](pngviewoptions#constructor_1)(CreatePageStream) | [`PngViewOptions`](../pngviewoptions) sınıfının bir örneğini başlatır. |
| [PngViewOptions](pngviewoptions#constructor_3)(IPageStreamFactory) | [`PngViewOptions`](../pngviewoptions) sınıfının bir örneğini başlatır. |
| [PngViewOptions](pngviewoptions#constructor_4)(string) | [`PngViewOptions`](../pngviewoptions) sınıfının bir örneğini başlatır. |
| [PngViewOptions](pngviewoptions#constructor_2)(CreatePageStream, ReleasePageStream) | [`PngViewOptions`](../pngviewoptions) sınıfının bir örneğini başlatır. |

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [ArchiveOptions](../../groupdocs.viewer.options/baseviewoptions/archiveoptions) { get; set; } | Arşiv dosyalarının görüntüleme seçenekleri. |
| [CadOptions](../../groupdocs.viewer.options/baseviewoptions/cadoptions) { get; set; } | CAD çizimlerinin görüntüleme seçenekleri. |
| [DefaultFontName](../../groupdocs.viewer.options/baseviewoptions/defaultfontname) { get; set; } | Bir belge için varsayılan yazı tipini ayarlar. |
| [EmailOptions](../../groupdocs.viewer.options/baseviewoptions/emailoptions) { get; set; } | E-posta mesajlarının görüntüleme seçenekleri. |
| [ExtractText](../../groupdocs.viewer.options/pngviewoptions/extracttext) { get; set; } | Metin çıkarımını etkinleştirir. |
| [Height](../../groupdocs.viewer.options/pngviewoptions/height) { get; set; } | Çıktı görüntüsünün yüksekliğini (piksel olarak) ayarlar. |
| [MailStorageOptions](../../groupdocs.viewer.options/baseviewoptions/mailstorageoptions) { get; set; } | Posta depolama veri dosyalarının görüntüleme seçenekleri. |
| [MaxHeight](../../groupdocs.viewer.options/pngviewoptions/maxheight) { get; set; } | Çıktı görüntüsünün maksimum yüksekliğini (piksel cinsinden) ayarlar. |
| [MaxWidth](../../groupdocs.viewer.options/pngviewoptions/maxwidth) { get; set; } | Çıktı görüntüsünün maksimum genişliğini (piksel cinsinden) ayarlar. |
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
| [Watermark](../../groupdocs.viewer.options/viewoptions/watermark) { get; set; } | Her sayfaya uygulanacak metin filigranı. |
| [WebDocumentOptions](../../groupdocs.viewer.options/baseviewoptions/webdocumentoptions) { get; set; } | Web dosyalarının görüntüleme seçenekleri. |
| [Width](../../groupdocs.viewer.options/pngviewoptions/width) { get; set; } | Çıktı görüntüsünün genişliği (piksel cinsinden). |
| [WordProcessingOptions](../../groupdocs.viewer.options/baseviewoptions/wordprocessingoptions) { get; set; } | Kelime işlem dosyalarının görüntüleme seçenekleri. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| [RotatePage](../../groupdocs.viewer.options/viewoptions/rotatepage)(int, Rotation) | Bir sayfaya saat yönünde dönüş uygular. |

## Alanlar

| Ad | Açıklama |
| --- | --- |
| readonly [PageRotations](../../groupdocs.viewer.options/viewoptions/pagerotations) | Sayfa dönüşü. |

### Ayrıca Bakınız

* class [ViewOptions](../viewoptions)
* interface [IMaxSizeOptions](../imaxsizeoptions)
* namespace [GroupDocs.Viewer.Options](../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../)

<!-- DÜZENLEMEYİN: xmldocmd tarafından GroupDocs.Viewer.dll için oluşturuldu -->
