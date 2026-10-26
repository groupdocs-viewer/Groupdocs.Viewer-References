---
title: "PdfViewOptions"
second_title: "GroupDocs.Viewer için .NET API Referansı"
description: "PDF formatına belgeleri renderleme seçeneklerini içerir. Ayrıntılar için belgeleri https//docs.groupdocs.com/viewer/net/renderingtopdf/ adresinde inceleyin."
type: docs
weight: 420
url: /tr/net/groupdocs.viewer.options/pdfviewoptions/
---

## PdfViewOptions class

Belgeleri PDF formatına render etme seçeneklerini içerir. Ayrıntılar için [belgelere](https://docs.groupdocs.com/viewer/net/rendering-to-pdf/) bakın.

```csharp
public class PdfViewOptions : ViewOptions
```

## Yapıcılar

| Ad | Açıklama |
| --- | --- |
| [PdfViewOptions](pdfviewoptions#constructor)() | [`PdfViewOptions`](../pdfviewoptions) sınıfının bir örneğini başlatır. |
| [PdfViewOptions](pdfviewoptions#constructor_1)(CreateFileStream) | [`PdfViewOptions`](../pdfviewoptions) sınıfının bir örneğini başlatır. |
| [PdfViewOptions](pdfviewoptions#constructor_3)(IFileStreamFactory) | [`PdfViewOptions`](../pdfviewoptions) sınıfının bir örneğini başlatır. |
| [PdfViewOptions](pdfviewoptions#constructor_4)(string) | [`PdfViewOptions`](../pdfviewoptions) sınıfının bir örneğini başlatır. |
| [PdfViewOptions](pdfviewoptions#constructor_2)(CreateFileStream, ReleaseFileStream) | [`PdfViewOptions`](../pdfviewoptions) sınıfının bir örneğini başlatır. |

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [ArchiveOptions](../../groupdocs.viewer.options/baseviewoptions/archiveoptions) { get; set; } | Arşiv dosyalarının görüntüleme seçenekleri. |
| [CadOptions](../../groupdocs.viewer.options/baseviewoptions/cadoptions) { get; set; } | CAD çizimlerinin görüntüleme seçenekleri. |
| [DefaultFontName](../../groupdocs.viewer.options/baseviewoptions/defaultfontname) { get; set; } | Bir belge için varsayılan yazı tipini ayarlar. |
| [EmailOptions](../../groupdocs.viewer.options/baseviewoptions/emailoptions) { get; set; } | E-posta mesajlarının görüntüleme seçenekleri. |
| [ImageHeight](../../groupdocs.viewer.options/pdfviewoptions/imageheight) { get; set; } | Çıktı görüntüsünün yüksekliğini (piksel olarak) ayarlar. |
| [ImageMaxHeight](../../groupdocs.viewer.options/pdfviewoptions/imagemaxheight) { get; set; } | Çıktı görüntüsünün maksimum yüksekliğini (piksel cinsinden) ayarlar. |
| [ImageMaxWidth](../../groupdocs.viewer.options/pdfviewoptions/imagemaxwidth) { get; set; } | Çıktı görüntüsünün maksimum genişliğini (piksel cinsinden) ayarlar. |
| [ImageWidth](../../groupdocs.viewer.options/pdfviewoptions/imagewidth) { get; set; } | Çıktı görüntüsünün genişliğini (piksel cinsinden) ayarlar. |
| [MailStorageOptions](../../groupdocs.viewer.options/baseviewoptions/mailstorageoptions) { get; set; } | Posta depolama veri dosyalarının görüntüleme seçenekleri. |
| [OutlookOptions](../../groupdocs.viewer.options/baseviewoptions/outlookoptions) { get; set; } | Microsoft Outlook veri dosyalarının görüntüleme seçenekleri. |
| [PdfOptimizationOptions](../../groupdocs.viewer.options/pdfviewoptions/pdfoptimizationoptions) { get; set; } | Farklı seçeneklerle optimizasyon teknikleri uygulayarak çıktı PDF dosyasının boyutunu azaltır. |
| [PdfOptions](../../groupdocs.viewer.options/baseviewoptions/pdfoptions) { get; set; } | PDF belge görüntüleme seçenekleri. |
| [PresentationOptions](../../groupdocs.viewer.options/baseviewoptions/presentationoptions) { get; set; } | Sunum dosyalarının görüntüleme seçenekleri. |
| [ProjectManagementOptions](../../groupdocs.viewer.options/baseviewoptions/projectmanagementoptions) { get; set; } | Proje yönetimi dosyalarının görüntüleme seçenekleri. |
| [RemoveComments](../../groupdocs.viewer.options/baseviewoptions/removecomments) { get; set; } | `true` olarak ayarlandığında yorumların işlenmesini devre dışı bırakır. Varsayılan olarak `false` — tüm yorumlar gösterilir. |
| [RenderHiddenPages](../../groupdocs.viewer.options/baseviewoptions/renderhiddenpages) { get; set; } | Gizli sayfaların işlenmesini etkinleştirir. |
| [RenderNotes](../../groupdocs.viewer.options/baseviewoptions/rendernotes) { get; set; } | Bazı formatlar için notların ve ek açıklamaların işlenmesini etkinleştirir |
| [Security](../../groupdocs.viewer.options/pdfviewoptions/security) { get; set; } | Çıktı PDF belgesi güvenlik seçeneklerini ayarlar. |
| [SpreadsheetOptions](../../groupdocs.viewer.options/baseviewoptions/spreadsheetoptions) { get; set; } | Elektronik tablo dosyalarının görüntüleme seçenekleri. |
| [TextOptions](../../groupdocs.viewer.options/baseviewoptions/textoptions) { get; set; } | Metin dosyalarının görüntüleme seçenekleri. |
| [VisioRenderingOptions](../../groupdocs.viewer.options/baseviewoptions/visiorenderingoptions) { get; set; } | Visio dosyalarının görüntüleme seçenekleri. |
| [Watermark](../../groupdocs.viewer.options/viewoptions/watermark) { get; set; } | Her sayfaya uygulanacak metin filigranı. |
| [WebDocumentOptions](../../groupdocs.viewer.options/baseviewoptions/webdocumentoptions) { get; set; } | Web dosyalarının görüntüleme seçenekleri. |
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
* namespace [GroupDocs.Viewer.Options](../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../)

<!-- DÜZENLEMEYİN: xmldocmd tarafından GroupDocs.Viewer.dll için oluşturuldu -->
