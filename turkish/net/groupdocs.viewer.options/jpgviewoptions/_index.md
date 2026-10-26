---
title: "JpgViewOptions"
second_title: "GroupDocs.Viewer için .NET API Referansı"
description: "Belgeleri JPG formatında render etmek için seçenekler sağlar. Ayrıntılar için bu sayfaya https//docs.groupdocs.com/viewer/net/renderingtopngorjpeg/ ve alt sayfalara bakın."
type: docs
weight: 350
url: /tr/net/groupdocs.viewer.options/jpgviewoptions/
---

## JpgViewOptions class

Belgeleri JPG formatına render etme seçeneklerini sağlar. Ayrıntılar için bu [sayfaya](https://docs.groupdocs.com/viewer/net/rendering-to-png-or-jpeg/) ve alt bölümlerine bakın.

```csharp
public class JpgViewOptions : ViewOptions, IMaxSizeOptions
```

## Yapıcılar

| Ad | Açıklama |
| --- | --- |
| [JpgViewOptions](jpgviewoptions#constructor)() | [`JpgViewOptions`](../jpgviewoptions) sınıfının bir örneğini başlatır. |
| [JpgViewOptions](jpgviewoptions#constructor_1)(CreatePageStream) | [`JpgViewOptions`](../jpgviewoptions) sınıfının bir örneğini başlatır. |
| [JpgViewOptions](jpgviewoptions#constructor_3)(IPageStreamFactory) | [`JpgViewOptions`](../jpgviewoptions) sınıfının bir örneğini başlatır. |
| [JpgViewOptions](jpgviewoptions#constructor_4)(string) | [`JpgViewOptions`](../jpgviewoptions) sınıfının bir örneğini başlatır. |
| [JpgViewOptions](jpgviewoptions#constructor_2)(CreatePageStream, ReleasePageStream) | [`JpgViewOptions`](../jpgviewoptions) sınıfının bir örneğini başlatır. |

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [ArchiveOptions](../../groupdocs.viewer.options/baseviewoptions/archiveoptions) { get; set; } | Arşiv dosyalarının görüntüleme seçenekleri. |
| [CadOptions](../../groupdocs.viewer.options/baseviewoptions/cadoptions) { get; set; } | CAD çizimlerinin görüntüleme seçenekleri. |
| [DefaultFontName](../../groupdocs.viewer.options/baseviewoptions/defaultfontname) { get; set; } | Bir belge için varsayılan yazı tipini ayarlar. |
| [EmailOptions](../../groupdocs.viewer.options/baseviewoptions/emailoptions) { get; set; } | E-posta mesajlarının görüntüleme seçenekleri. |
| [ExtractText](../../groupdocs.viewer.options/jpgviewoptions/extracttext) { get; set; } | Metin çıkarımını etkinleştirir. |
| [Height](../../groupdocs.viewer.options/jpgviewoptions/height) { get; set; } | Çıktı görüntüsünün yüksekliğini (piksel olarak) ayarlar. |
| [MailStorageOptions](../../groupdocs.viewer.options/baseviewoptions/mailstorageoptions) { get; set; } | Posta depolama veri dosyalarının görüntüleme seçenekleri. |
| [MaxHeight](../../groupdocs.viewer.options/jpgviewoptions/maxheight) { get; set; } | Çıktı görüntüsünün maksimum yüksekliğini (piksel cinsinden) ayarlar. |
| [MaxWidth](../../groupdocs.viewer.options/jpgviewoptions/maxwidth) { get; set; } | Çıktı görüntüsünün maksimum genişliğini (piksel cinsinden) ayarlar. |
| [OutlookOptions](../../groupdocs.viewer.options/baseviewoptions/outlookoptions) { get; set; } | Microsoft Outlook veri dosyalarının görüntüleme seçenekleri. |
| [PdfOptions](../../groupdocs.viewer.options/baseviewoptions/pdfoptions) { get; set; } | PDF belge görüntüleme seçenekleri. |
| [PresentationOptions](../../groupdocs.viewer.options/baseviewoptions/presentationoptions) { get; set; } | Sunum dosyalarının görüntüleme seçenekleri. |
| [ProjectManagementOptions](../../groupdocs.viewer.options/baseviewoptions/projectmanagementoptions) { get; set; } | Proje yönetimi dosyalarının görüntüleme seçenekleri. |
| [Quality](../../groupdocs.viewer.options/jpgviewoptions/quality) { get; set; } | Çıktı görüntüsünün kalitesini ayarlar. |
| [RemoveComments](../../groupdocs.viewer.options/baseviewoptions/removecomments) { get; set; } | `true` olarak ayarlandığında yorumların işlenmesini devre dışı bırakır. Varsayılan olarak `false` — tüm yorumlar gösterilir. |
| [RenderHiddenPages](../../groupdocs.viewer.options/baseviewoptions/renderhiddenpages) { get; set; } | Gizli sayfaların işlenmesini etkinleştirir. |
| [RenderNotes](../../groupdocs.viewer.options/baseviewoptions/rendernotes) { get; set; } | Bazı formatlar için notların ve ek açıklamaların işlenmesini etkinleştirir |
| [SpreadsheetOptions](../../groupdocs.viewer.options/baseviewoptions/spreadsheetoptions) { get; set; } | Elektronik tablo dosyalarının görüntüleme seçenekleri. |
| [TextOptions](../../groupdocs.viewer.options/baseviewoptions/textoptions) { get; set; } | Metin dosyalarının görüntüleme seçenekleri. |
| [VisioRenderingOptions](../../groupdocs.viewer.options/baseviewoptions/visiorenderingoptions) { get; set; } | Visio dosyalarının görüntüleme seçenekleri. |
| [Watermark](../../groupdocs.viewer.options/viewoptions/watermark) { get; set; } | Her sayfaya uygulanacak metin filigranı. |
| [WebDocumentOptions](../../groupdocs.viewer.options/baseviewoptions/webdocumentoptions) { get; set; } | Web dosyalarının görüntüleme seçenekleri. |
| [Width](../../groupdocs.viewer.options/jpgviewoptions/width) { get; set; } | Çıktı görüntüsünün genişliğini (piksel cinsinden) ayarlar. |
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
