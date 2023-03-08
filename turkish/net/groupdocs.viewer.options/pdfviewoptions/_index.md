---
title: PdfViewOptions
second_title: .NET API Başvurusu için GroupDocs.Viewer
description: Belgeleri PDF biçiminde işlemek için seçenekler sunar.
type: docs
weight: 420
url: /tr/net/groupdocs.viewer.options/pdfviewoptions/
---
## PdfViewOptions class

Belgeleri PDF biçiminde işlemek için seçenekler sunar.

```csharp
public class PdfViewOptions : ViewOptions
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [PdfViewOptions](pdfviewoptions#constructor)() | Yeni örneğini başlatır[`PdfViewOptions`](../pdfviewoptions) sınıf. |
| [PdfViewOptions](pdfviewoptions#constructor_1)(CreateFileStream) | Yeni örneğini başlatır[`PdfViewOptions`](../pdfviewoptions) sınıf. |
| [PdfViewOptions](pdfviewoptions#constructor_3)(IFileStreamFactory) | Yeni örneğini başlatır[`PdfViewOptions`](../pdfviewoptions) sınıf. |
| [PdfViewOptions](pdfviewoptions#constructor_4)(string) | Yeni örneğini başlatır[`PdfViewOptions`](../pdfviewoptions) sınıf. |
| [PdfViewOptions](pdfviewoptions#constructor_2)(CreateFileStream, ReleaseFileStream) | Yeni örneğini başlatır[`PdfViewOptions`](../pdfviewoptions) sınıf. |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [ArchiveOptions](../../groupdocs.viewer.options/baseviewoptions/archiveoptions) { get; set; } | Arşiv dosyaları görüntüleme seçenekleri. |
| [CadOptions](../../groupdocs.viewer.options/baseviewoptions/cadoptions) { get; set; } | CAD çizim görünümü seçenekleri. |
| [DefaultFontName](../../groupdocs.viewer.options/baseviewoptions/defaultfontname) { get; set; } | Belgede kullanılan belirli yazı tipi bulunamadığında kullanılacak varsayılan yazı tipi. |
| [EmailOptions](../../groupdocs.viewer.options/baseviewoptions/emailoptions) { get; set; } | E-posta mesajları görüntüleme seçenekleri. |
| [ImageHeight](../../groupdocs.viewer.options/pdfviewoptions/imageheight) { get; set; } | Çıktı görüntüsünün piksel cinsinden yüksekliği. (Yalnızca tek bir görüntüyü HTML'ye dönüştürürken) |
| [ImageMaxHeight](../../groupdocs.viewer.options/pdfviewoptions/imagemaxheight) { get; set; } | Çıktı görüntüsünün piksel cinsinden maksimum yüksekliği. (Yalnızca tek bir görüntüyü HTML'ye dönüştürürken) |
| [ImageMaxWidth](../../groupdocs.viewer.options/pdfviewoptions/imagemaxwidth) { get; set; } | Çıktı görüntüsünün piksel cinsinden maksimum genişliği. (Yalnızca tek bir görüntüyü HTML'ye dönüştürürken) |
| [ImageWidth](../../groupdocs.viewer.options/pdfviewoptions/imagewidth) { get; set; } | Çıktı görüntüsünün piksel cinsinden genişliği. (Yalnızca tek bir görüntüyü HTML'ye dönüştürürken) |
| [JpgQuality](../../groupdocs.viewer.options/pdfviewoptions/jpgquality) { get; set; } | Çıktı PDF belgesinin içerdiği JPG görüntülerin kalitesi; Geçerli değerler 1 ile 100 arasındadır; Varsayılan değer 90. |
| [MailStorageOptions](../../groupdocs.viewer.options/baseviewoptions/mailstorageoptions) { get; set; } | Posta depolama veri dosyaları görüntüleme seçenekleri. |
| [Optimize](../../groupdocs.viewer.options/pdfviewoptions/optimize) { get; set; } | Times New Roman ve Arial gibi yaygın kullanılan yazı tiplerini hariç tutarak ve diğer optimizasyon tekniklerini uygulayarak çıktı dosyası boyutunu azaltın. |
| [OutlookOptions](../../groupdocs.viewer.options/baseviewoptions/outlookoptions) { get; set; } | MS Outlook veri dosyaları görüntüleme seçenekleri. |
| [PdfOptions](../../groupdocs.viewer.options/baseviewoptions/pdfoptions) { get; set; } | PDF belgeleri görüntüleme seçenekleri. |
| [PresentationOptions](../../groupdocs.viewer.options/baseviewoptions/presentationoptions) { get; set; } | Sunum işleme belgeleri görüntüleme seçenekleri. |
| [ProjectManagementOptions](../../groupdocs.viewer.options/baseviewoptions/projectmanagementoptions) { get; set; } | Proje yönetimi dosyaları görüntüleme seçenekleri. |
| [RenderComments](../../groupdocs.viewer.options/baseviewoptions/rendercomments) { get; set; } | Yorumların işlenmesini etkinleştirir. |
| [RenderHiddenPages](../../groupdocs.viewer.options/baseviewoptions/renderhiddenpages) { get; set; } | Gizli sayfaların oluşturulmasını sağlar. |
| [RenderNotes](../../groupdocs.viewer.options/baseviewoptions/rendernotes) { get; set; } | Notların işlenmesini etkinleştirir. |
| [Security](../../groupdocs.viewer.options/pdfviewoptions/security) { get; set; } | Çıktı PDF belgesi güvenlik seçenekleri. |
| [SpreadsheetOptions](../../groupdocs.viewer.options/baseviewoptions/spreadsheetoptions) { get; set; } | Elektronik tablo dosyaları görüntüleme seçenekleri. |
| [TextOptions](../../groupdocs.viewer.options/baseviewoptions/textoptions) { get; set; } | Sayfa seçeneklerine bölünen metin dosyaları. |
| [VisioRenderingOptions](../../groupdocs.viewer.options/baseviewoptions/visiorenderingoptions) { get; set; } | Belgeleri işleyen Visio dosyaları görüntüleme seçenekleri. |
| [Watermark](../../groupdocs.viewer.options/viewoptions/watermark) { get; set; } | Her sayfaya uygulanan metin filigranı. |
| [WebDocumentOptions](../../groupdocs.viewer.options/baseviewoptions/webdocumentoptions) { get; set; } | Bu işleme seçenekleri, Web belgelerini işlerken HTML/PDF/PNG/JPEG çıktısının görünümünü özelleştirmenizi sağlar. |
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
* ad alanı [GroupDocs.Viewer.Options](../../groupdocs.viewer.options)
* toplantı [GroupDocs.Viewer](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Viewer.dll -->
