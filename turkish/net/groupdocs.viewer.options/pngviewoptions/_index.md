---
title: PngViewOptions
second_title: .NET API Başvurusu için GroupDocs.Viewer
description: Belgeleri PNG biçiminde işlemek için seçenekler sunar.
type: docs
weight: 440
url: /tr/net/groupdocs.viewer.options/pngviewoptions/
---
## PngViewOptions class

Belgeleri PNG biçiminde işlemek için seçenekler sunar.

```csharp
public class PngViewOptions : ViewOptions, IMaxSizeOptions
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [PngViewOptions](pngviewoptions#constructor)() | Yeni örneğini başlatır[`PngViewOptions`](../pngviewoptions) sınıf. |
| [PngViewOptions](pngviewoptions#constructor_1)(CreatePageStream) | Yeni örneğini başlatır[`PngViewOptions`](../pngviewoptions) sınıf. |
| [PngViewOptions](pngviewoptions#constructor_3)(IPageStreamFactory) | Yeni örneğini başlatır[`PngViewOptions`](../pngviewoptions) sınıf. |
| [PngViewOptions](pngviewoptions#constructor_4)(string) | Yeni örneğini başlatır[`PngViewOptions`](../pngviewoptions) sınıf. |
| [PngViewOptions](pngviewoptions#constructor_2)(CreatePageStream, ReleasePageStream) | Yeni örneğini başlatır[`PngViewOptions`](../pngviewoptions) sınıf. |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [ArchiveOptions](../../groupdocs.viewer.options/baseviewoptions/archiveoptions) { get; set; } | Arşiv dosyaları görüntüleme seçenekleri. |
| [CadOptions](../../groupdocs.viewer.options/baseviewoptions/cadoptions) { get; set; } | CAD çizim görünümü seçenekleri. |
| [DefaultFontName](../../groupdocs.viewer.options/baseviewoptions/defaultfontname) { get; set; } | Belgede kullanılan belirli yazı tipi bulunamadığında kullanılacak varsayılan yazı tipi. |
| [EmailOptions](../../groupdocs.viewer.options/baseviewoptions/emailoptions) { get; set; } | E-posta mesajları görüntüleme seçenekleri. |
| [ExtractText](../../groupdocs.viewer.options/pngviewoptions/extracttext) { get; set; } | Metin ayıklamayı etkinleştirir. |
| [Height](../../groupdocs.viewer.options/pngviewoptions/height) { get; set; } | Çıktı görüntüsünün piksel cinsinden yüksekliği. |
| [MailStorageOptions](../../groupdocs.viewer.options/baseviewoptions/mailstorageoptions) { get; set; } | Posta depolama veri dosyaları görüntüleme seçenekleri. |
| [MaxHeight](../../groupdocs.viewer.options/pngviewoptions/maxheight) { get; set; } | Çıktı görüntüsünün piksel cinsinden maksimum yüksekliği. |
| [MaxWidth](../../groupdocs.viewer.options/pngviewoptions/maxwidth) { get; set; } | Çıktı görüntüsünün piksel cinsinden maksimum genişliği. |
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
| [Watermark](../../groupdocs.viewer.options/viewoptions/watermark) { get; set; } | Her sayfaya uygulanan metin filigranı. |
| [WebDocumentOptions](../../groupdocs.viewer.options/baseviewoptions/webdocumentoptions) { get; set; } | Bu işleme seçenekleri, Web belgelerini işlerken HTML/PDF/PNG/JPEG çıktısının görünümünü özelleştirmenizi sağlar. |
| [Width](../../groupdocs.viewer.options/pngviewoptions/width) { get; set; } | Çıktı görüntüsünün piksel cinsinden genişliği. |
| [WordProcessingOptions](../../groupdocs.viewer.options/baseviewoptions/wordprocessingoptions) { get; set; } | Bu işleme seçenekleri, Word belgelerini işlerken HTML/PDF/PNG/JPEG çıktısının görünümünü özelleştirmenizi sağlar. |

## yöntemler

| İsim | Tanım |
| --- | --- |
| [RotatePage](../../groupdocs.viewer.options/viewoptions/rotatepage)(int, Rotation) | Sayfaya saat yönünde döndürme uygular. |

## Alanlar

| İsim | Tanım |
| --- | --- |
| readonly [PageRotations](../../groupdocs.viewer.options/viewoptions/pagerotations) | Sayfa döndürmeleri. |

### Ayrıca bakınız

* class [ViewOptions](../viewoptions)
* interface [IMaxSizeOptions](../imaxsizeoptions)
* ad alanı [GroupDocs.Viewer.Options](../../groupdocs.viewer.options)
* toplantı [GroupDocs.Viewer](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Viewer.dll -->
