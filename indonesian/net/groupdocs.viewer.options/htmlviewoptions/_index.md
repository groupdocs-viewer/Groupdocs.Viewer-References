---
title: "HtmlViewOptions"
second_title: "Referensi API GroupDocs.Viewer untuk .NET"
description: "Berisi opsi untuk merender dokumen ke format HTML. Untuk detail lihat topichttps//docs.groupdocs.com/viewer/net/renderingtohtml/ dan turunannya."
type: docs
weight: 320
url: /id/net/groupdocs.viewer.options/htmlviewoptions/
---

## HtmlViewOptions class

Berisi opsi untuk merender dokumen ke format HTML. Untuk detail, lihat [topik](https://docs.groupdocs.com/viewer/net/rendering-to-html/) dan turunannya.

```csharp
public class HtmlViewOptions : ViewOptions
```

## Properti

| Nama | Deskripsi |
| --- | --- |
| [ArchiveOptions](../../groupdocs.viewer.options/baseviewoptions/archiveoptions) { get; set; } | Opsi tampilan file arsip. |
| [CadOptions](../../groupdocs.viewer.options/baseviewoptions/cadoptions) { get; set; } | Opsi tampilan gambar CAD. |
| [DefaultFontName](../../groupdocs.viewer.options/baseviewoptions/defaultfontname) { get; set; } | Menetapkan font default untuk sebuah dokumen. |
| [EmailOptions](../../groupdocs.viewer.options/baseviewoptions/emailoptions) { get; set; } | Opsi tampilan pesan email. |
| [ExcludeFonts](../../groupdocs.viewer.options/htmlviewoptions/excludefonts) { get; set; } | Menonaktifkan penambahan font apa pun ke dokumen HTML. |
| [FontsToExclude](../../groupdocs.viewer.options/htmlviewoptions/fontstoexclude) { get; set; } | Daftar nama font yang akan dikecualikan dari dokumen HTML. |
| [ForPrinting](../../groupdocs.viewer.options/htmlviewoptions/forprinting) { get; set; } | Mengaktifkan optimasi HTML output untuk pencetakan. |
| [ImageHeight](../../groupdocs.viewer.options/htmlviewoptions/imageheight) { get; set; } | Tinggi gambar output (dalam piksel). Properti ini tersedia hanya saat mengonversi satu gambar ke HTML. |
| [ImageMaxHeight](../../groupdocs.viewer.options/htmlviewoptions/imagemaxheight) { get; set; } | Tinggi maksimum gambar output (dalam piksel). Properti ini tersedia saat mengonversi satu gambar ke HTML saja. |
| [ImageMaxWidth](../../groupdocs.viewer.options/htmlviewoptions/imagemaxwidth) { get; set; } | Lebar maksimum gambar output (dalam piksel). Properti ini tersedia saat mengonversi satu gambar ke HTML saja. |
| [ImageWidth](../../groupdocs.viewer.options/htmlviewoptions/imagewidth) { get; set; } | Lebar gambar output (dalam piksel). Properti ini tersedia saat mengonversi satu gambar ke HTML saja. |
| [MailStorageOptions](../../groupdocs.viewer.options/baseviewoptions/mailstorageoptions) { get; set; } | Opsi tampilan file data penyimpanan surat. |
| [Minify](../../groupdocs.viewer.options/htmlviewoptions/minify) { get; set; } | Mengaktifkan minifikasi konten HTML dan sumber daya HTML. |
| [OutlookOptions](../../groupdocs.viewer.options/baseviewoptions/outlookoptions) { get; set; } | Opsi tampilan file data Microsoft Outlook. |
| [PdfOptions](../../groupdocs.viewer.options/baseviewoptions/pdfoptions) { get; set; } | Opsi tampilan dokumen PDF. |
| [PresentationOptions](../../groupdocs.viewer.options/baseviewoptions/presentationoptions) { get; set; } | Opsi tampilan file presentasi. |
| [ProjectManagementOptions](../../groupdocs.viewer.options/baseviewoptions/projectmanagementoptions) { get; set; } | Opsi tampilan file manajemen proyek. |
| [RemoveComments](../../groupdocs.viewer.options/baseviewoptions/removecomments) { get; set; } | Menonaktifkan rendering komentar ketika disetel ke `true`. Secara default adalah `false` — semua komentar ditampilkan. |
| [RemoveJavaScript](../../groupdocs.viewer.options/htmlviewoptions/removejavascript) { get; set; } | Mengizinkan penghapusan kode sumber JavaScript dari tautan dalam dokumen HTML hasil, saat merender dokumen input yang memiliki skrip. Secara default diaktifkan (`true`). |
| [RenderHiddenPages](../../groupdocs.viewer.options/baseviewoptions/renderhiddenpages) { get; set; } | Mengaktifkan rendering halaman tersembunyi. |
| [RenderNotes](../../groupdocs.viewer.options/baseviewoptions/rendernotes) { get; set; } | Mengaktifkan rendering catatan dan anotasi untuk beberapa format |
| [RenderResponsive](../../groupdocs.viewer.options/htmlviewoptions/renderresponsive) { get; set; } | Mengaktifkan rendering responsif. |
| [RenderToSinglePage](../../groupdocs.viewer.options/htmlviewoptions/rendertosinglepage) { get; set; } | Mengaktifkan rendering seluruh dokumen menjadi satu file HTML. |
| [SpreadsheetOptions](../../groupdocs.viewer.options/baseviewoptions/spreadsheetoptions) { get; set; } | Opsi tampilan file spreadsheet. |
| [TextOptions](../../groupdocs.viewer.options/baseviewoptions/textoptions) { get; set; } | Opsi tampilan file teks. |
| [VisioRenderingOptions](../../groupdocs.viewer.options/baseviewoptions/visiorenderingoptions) { get; set; } | Opsi tampilan file Visio. |
| [Watermark](../../groupdocs.viewer.options/viewoptions/watermark) { get; set; } | Watermark teks yang akan diterapkan pada setiap halaman. |
| [WebDocumentOptions](../../groupdocs.viewer.options/baseviewoptions/webdocumentoptions) { get; set; } | Opsi tampilan file Web. |
| [WordProcessingOptions](../../groupdocs.viewer.options/baseviewoptions/wordprocessingoptions) { get; set; } | Opsi tampilan file pengolah kata. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| static [ForEmbeddedResources](../../groupdocs.viewer.options/htmlviewoptions/forembeddedresources#forembeddedresources)() | Menginisialisasi sebuah instance dari kelas [`HtmlViewOptions`](../htmlviewoptions). |
| static [ForEmbeddedResources](../../groupdocs.viewer.options/htmlviewoptions/forembeddedresources#forembeddedresources_1)(CreatePageStream) | Menginisialisasi sebuah instance dari kelas [`HtmlViewOptions`](../htmlviewoptions) untuk merender ke HTML dengan sumber daya tersemat. |
| static [ForEmbeddedResources](../../groupdocs.viewer.options/htmlviewoptions/forembeddedresources#forembeddedresources_3)(IPageStreamFactory) | Menginisialisasi sebuah instance dari kelas [`HtmlViewOptions`](../htmlviewoptions) untuk merender ke HTML dengan sumber daya tersemat. |
| static [ForEmbeddedResources](../../groupdocs.viewer.options/htmlviewoptions/forembeddedresources#forembeddedresources_4)(string) | Menginisialisasi sebuah instance dari kelas [`HtmlViewOptions`](../htmlviewoptions). |
| static [ForEmbeddedResources](../../groupdocs.viewer.options/htmlviewoptions/forembeddedresources#forembeddedresources_2)(CreatePageStream, ReleasePageStream) | Menginisialisasi sebuah instance dari kelas [`HtmlViewOptions`](../htmlviewoptions) untuk merender ke HTML dengan sumber daya tersemat. |
| static [ForExternalResources](../../groupdocs.viewer.options/htmlviewoptions/forexternalresources#forexternalresources)() | Menginisialisasi sebuah instance dari kelas [`HtmlViewOptions`](../htmlviewoptions). |
| static [ForExternalResources](../../groupdocs.viewer.options/htmlviewoptions/forexternalresources#forexternalresources_3)(IPageStreamFactory, IResourceStreamFactory) | Menginisialisasi sebuah instance dari kelas [`HtmlViewOptions`](../htmlviewoptions) untuk merender ke HTML dengan sumber daya eksternal. |
| static [ForExternalResources](../../groupdocs.viewer.options/htmlviewoptions/forexternalresources#forexternalresources_1)(CreatePageStream, CreateResourceStream, CreateResourceUrl) | Menginisialisasi sebuah instance dari kelas [`HtmlViewOptions`](../htmlviewoptions) untuk merender ke HTML dengan sumber daya eksternal. |
| static [ForExternalResources](../../groupdocs.viewer.options/htmlviewoptions/forexternalresources#forexternalresources_4)(string, string, string) | Menginisialisasi sebuah instance dari kelas [`HtmlViewOptions`](../htmlviewoptions). |
| static [ForExternalResources](../../groupdocs.viewer.options/htmlviewoptions/forexternalresources#forexternalresources_2)(CreatePageStream, CreateResourceStream, CreateResourceUrl, ReleasePageStream, ReleaseResourceStream) | Menginisialisasi sebuah instance dari kelas [`HtmlViewOptions`](../htmlviewoptions) untuk merender ke HTML dengan sumber daya eksternal. |
| [RotatePage](../../groupdocs.viewer.options/viewoptions/rotatepage)(int, Rotation) | Menerapkan rotasi searah jarum jam pada halaman. |

## Bidang

| Nama | Deskripsi |
| --- | --- |
| readonly [PageRotations](../../groupdocs.viewer.options/viewoptions/pagerotations) | Rotasi halaman. |

### Lihat Juga

* class [ViewOptions](../viewoptions)
* namespace [GroupDocs.Viewer.Options](../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Viewer.dll -->
