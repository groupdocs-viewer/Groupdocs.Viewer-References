---
title: HtmlViewOptions
second_title: GroupDocs.Viewer untuk Referensi .NET API
description: Memberikan opsi untuk merender dokumen ke dalam format HTML.
type: docs
weight: 330
url: /id/net/groupdocs.viewer.options/htmlviewoptions/
---
## HtmlViewOptions class

Memberikan opsi untuk merender dokumen ke dalam format HTML.

```csharp
public class HtmlViewOptions : ViewOptions
```

## Properti

| Nama | Keterangan |
| --- | --- |
| [ArchiveOptions](../../groupdocs.viewer.options/baseviewoptions/archiveoptions) { get; set; } | Opsi tampilan file arsip. |
| [CadOptions](../../groupdocs.viewer.options/baseviewoptions/cadoptions) { get; set; } | Opsi tampilan gambar CAD. |
| [DefaultFontName](../../groupdocs.viewer.options/baseviewoptions/defaultfontname) { get; set; } | Font default untuk digunakan ketika font tertentu yang digunakan dalam dokumen tidak dapat ditemukan. |
| [EmailOptions](../../groupdocs.viewer.options/baseviewoptions/emailoptions) { get; set; } | Opsi tampilan pesan email. |
| [ExcludeFonts](../../groupdocs.viewer.options/htmlviewoptions/excludefonts) { get; set; } | Saat diaktifkan mencegah penambahan font apa pun ke dalam dokumen HTML. |
| [FontsToExclude](../../groupdocs.viewer.options/htmlviewoptions/fontstoexclude) { get; set; } | Daftar nama font, untuk dikecualikan dari dokumen HTML. |
| [ForPrinting](../../groupdocs.viewer.options/htmlviewoptions/forprinting) { get; set; } | Menunjukkan apakah akan mengoptimalkan keluaran HTML untuk pencetakan. |
| [ImageHeight](../../groupdocs.viewer.options/htmlviewoptions/imageheight) { get; set; } | Ketinggian gambar keluaran dalam piksel. (Saat mengonversi gambar tunggal ke HTML saja) |
| [ImageMaxHeight](../../groupdocs.viewer.options/htmlviewoptions/imagemaxheight) { get; set; } | Tinggi maksimum gambar keluaran dalam piksel. (Saat mengonversi gambar tunggal ke HTML saja) |
| [ImageMaxWidth](../../groupdocs.viewer.options/htmlviewoptions/imagemaxwidth) { get; set; } | Lebar maksimum gambar keluaran dalam piksel. (Saat mengonversi gambar tunggal ke HTML saja) |
| [ImageWidth](../../groupdocs.viewer.options/htmlviewoptions/imagewidth) { get; set; } | Lebar gambar keluaran dalam piksel. (Saat mengonversi gambar tunggal ke HTML saja) |
| [MailStorageOptions](../../groupdocs.viewer.options/baseviewoptions/mailstorageoptions) { get; set; } | Opsi tampilan file data penyimpanan email. |
| [Minify](../../groupdocs.viewer.options/htmlviewoptions/minify) { get; set; } | Mengaktifkan konten HTML dan minifikasi sumber daya HTML. |
| [OutlookOptions](../../groupdocs.viewer.options/baseviewoptions/outlookoptions) { get; set; } | Opsi tampilan file data MS Outlook. |
| [PdfOptions](../../groupdocs.viewer.options/baseviewoptions/pdfoptions) { get; set; } | Opsi tampilan dokumen PDF. |
| [PresentationOptions](../../groupdocs.viewer.options/baseviewoptions/presentationoptions) { get; set; } | Opsi tampilan dokumen pemrosesan presentasi. |
| [ProjectManagementOptions](../../groupdocs.viewer.options/baseviewoptions/projectmanagementoptions) { get; set; } | Opsi tampilan file manajemen proyek. |
| [RenderComments](../../groupdocs.viewer.options/baseviewoptions/rendercomments) { get; set; } | Mengaktifkan rendering komentar. |
| [RenderHiddenPages](../../groupdocs.viewer.options/baseviewoptions/renderhiddenpages) { get; set; } | Mengaktifkan rendering halaman tersembunyi. |
| [RenderNotes](../../groupdocs.viewer.options/baseviewoptions/rendernotes) { get; set; } | Mengaktifkan rendering catatan. |
| [RenderResponsive](../../groupdocs.viewer.options/htmlviewoptions/renderresponsive) { get; set; } | Mengaktifkan rendering responsif; Halaman web responsif merender dengan baik pada perangkat dengan ukuran layar berbeda. |
| [RenderToSinglePage](../../groupdocs.viewer.options/htmlviewoptions/rendertosinglepage) { get; set; } | Memungkinkan rendering seluruh dokumen ke satu file HTML. |
| [SpreadsheetOptions](../../groupdocs.viewer.options/baseviewoptions/spreadsheetoptions) { get; set; } | Opsi tampilan file spreadsheet. |
| [TextOptions](../../groupdocs.viewer.options/baseviewoptions/textoptions) { get; set; } | Pemisahan file teks ke opsi halaman. |
| [VisioRenderingOptions](../../groupdocs.viewer.options/baseviewoptions/visiorenderingoptions) { get; set; } | Opsi tampilan dokumen pemrosesan file Visio. |
| [Watermark](../../groupdocs.viewer.options/viewoptions/watermark) { get; set; } | Watermark teks diterapkan ke setiap halaman. |
| [WebDocumentOptions](../../groupdocs.viewer.options/baseviewoptions/webdocumentoptions) { get; set; } | Opsi rendering ini memungkinkan Anda menyesuaikan tampilan output HTML/PDF/PNG/JPEG saat merender dokumen Web. |
| [WordProcessingOptions](../../groupdocs.viewer.options/baseviewoptions/wordprocessingoptions) { get; set; } | Opsi rendering ini memungkinkan Anda menyesuaikan tampilan output HTML/PDF/PNG/JPEG saat merender dokumen Word. |

## Metode

| Nama | Keterangan |
| --- | --- |
| static [ForEmbeddedResources](../../groupdocs.viewer.options/htmlviewoptions/forembeddedresources#forembeddedresources)() | Menginisialisasi instance baru[`HtmlViewOptions`](../htmlviewoptions) kelas. |
| static [ForEmbeddedResources](../../groupdocs.viewer.options/htmlviewoptions/forembeddedresources#forembeddedresources_1)(CreatePageStream) | Menginisialisasi instance baru[`HtmlViewOptions`](../htmlviewoptions) kelas untuk merender ke dalam HTML dengan sumber daya tersemat. |
| static [ForEmbeddedResources](../../groupdocs.viewer.options/htmlviewoptions/forembeddedresources#forembeddedresources_3)(IPageStreamFactory) | Menginisialisasi instance baru[`HtmlViewOptions`](../htmlviewoptions) kelas untuk merender ke dalam HTML dengan sumber daya tersemat. |
| static [ForEmbeddedResources](../../groupdocs.viewer.options/htmlviewoptions/forembeddedresources#forembeddedresources_4)(string) | Menginisialisasi instance baru[`HtmlViewOptions`](../htmlviewoptions) kelas. |
| static [ForEmbeddedResources](../../groupdocs.viewer.options/htmlviewoptions/forembeddedresources#forembeddedresources_2)(CreatePageStream, ReleasePageStream) | Menginisialisasi instance baru[`HtmlViewOptions`](../htmlviewoptions) kelas untuk merender ke dalam HTML dengan sumber daya tersemat. |
| static [ForExternalResources](../../groupdocs.viewer.options/htmlviewoptions/forexternalresources#forexternalresources)() | Menginisialisasi instance baru[`HtmlViewOptions`](../htmlviewoptions) kelas. |
| static [ForExternalResources](../../groupdocs.viewer.options/htmlviewoptions/forexternalresources#forexternalresources_3)(IPageStreamFactory, IResourceStreamFactory) | Menginisialisasi instance baru[`HtmlViewOptions`](../htmlviewoptions) kelas untuk merender ke dalam HTML dengan sumber daya eksternal. |
| static [ForExternalResources](../../groupdocs.viewer.options/htmlviewoptions/forexternalresources#forexternalresources_1)(CreatePageStream, CreateResourceStream, CreateResourceUrl) | Menginisialisasi instance baru[`HtmlViewOptions`](../htmlviewoptions) kelas untuk merender ke dalam HTML dengan sumber daya eksternal. |
| static [ForExternalResources](../../groupdocs.viewer.options/htmlviewoptions/forexternalresources#forexternalresources_4)(string, string, string) | Menginisialisasi instance baru[`HtmlViewOptions`](../htmlviewoptions) kelas. |
| static [ForExternalResources](../../groupdocs.viewer.options/htmlviewoptions/forexternalresources#forexternalresources_2)(CreatePageStream, CreateResourceStream, CreateResourceUrl, ReleasePageStream, ReleaseResourceStream) | Menginisialisasi instance baru[`HtmlViewOptions`](../htmlviewoptions) kelas untuk merender ke dalam HTML dengan sumber daya eksternal. |
| [RotatePage](../../groupdocs.viewer.options/viewoptions/rotatepage)(int, Rotation) | Menerapkan rotasi searah jarum jam ke halaman. |

## Bidang

| Nama | Keterangan |
| --- | --- |
| readonly [PageRotations](../../groupdocs.viewer.options/viewoptions/pagerotations) | Perputaran halaman. |

### Lihat juga

* class [ViewOptions](../viewoptions)
* ruang nama [GroupDocs.Viewer.Options](../../groupdocs.viewer.options)
* perakitan [GroupDocs.Viewer](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Viewer.dll -->
