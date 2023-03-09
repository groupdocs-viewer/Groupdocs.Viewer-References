---
title: ViewInfoOptions
second_title: GroupDocs.Viewer untuk Referensi .NET API
description: Menyediakan opsi yang digunakan untuk mengambil informasi tentang view.
type: docs
weight: 570
url: /id/net/groupdocs.viewer.options/viewinfooptions/
---
## ViewInfoOptions class

Menyediakan opsi yang digunakan untuk mengambil informasi tentang view.

```csharp
public class ViewInfoOptions : BaseViewOptions, IMaxSizeOptions
```

## Properti

| Nama | Keterangan |
| --- | --- |
| [ArchiveOptions](../../groupdocs.viewer.options/baseviewoptions/archiveoptions) { get; set; } | Opsi tampilan file arsip. |
| [CadOptions](../../groupdocs.viewer.options/baseviewoptions/cadoptions) { get; set; } | Opsi tampilan gambar CAD. |
| [DefaultFontName](../../groupdocs.viewer.options/baseviewoptions/defaultfontname) { get; set; } | Font default untuk digunakan ketika font tertentu yang digunakan dalam dokumen tidak dapat ditemukan. |
| [EmailOptions](../../groupdocs.viewer.options/baseviewoptions/emailoptions) { get; set; } | Opsi tampilan pesan email. |
| [ExtractText](../../groupdocs.viewer.options/viewinfooptions/extracttext) { get; set; } | Menunjukkan bahwa ekstraksi teks diaktifkan. |
| [Height](../../groupdocs.viewer.options/viewinfooptions/height) { get; set; } | Tinggi gambar (hanya untuk merender ke PNG/JPG) |
| [MailStorageOptions](../../groupdocs.viewer.options/baseviewoptions/mailstorageoptions) { get; set; } | Opsi tampilan file data penyimpanan email. |
| [MaxHeight](../../groupdocs.viewer.options/viewinfooptions/maxheight) { get; set; } | Tinggi maksimum gambar keluaran (hanya untuk merender ke PNG/JPG) |
| [MaxWidth](../../groupdocs.viewer.options/viewinfooptions/maxwidth) { get; set; } | Lebar maksimum gambar keluaran (hanya untuk merender ke PNG/JPG) |
| [OutlookOptions](../../groupdocs.viewer.options/baseviewoptions/outlookoptions) { get; set; } | Opsi tampilan file data MS Outlook. |
| [PdfOptions](../../groupdocs.viewer.options/baseviewoptions/pdfoptions) { get; set; } | Opsi tampilan dokumen PDF. |
| [PresentationOptions](../../groupdocs.viewer.options/baseviewoptions/presentationoptions) { get; set; } | Opsi tampilan dokumen pemrosesan presentasi. |
| [ProjectManagementOptions](../../groupdocs.viewer.options/baseviewoptions/projectmanagementoptions) { get; set; } | Opsi tampilan file manajemen proyek. |
| [RenderComments](../../groupdocs.viewer.options/baseviewoptions/rendercomments) { get; set; } | Mengaktifkan rendering komentar. |
| [RenderHiddenPages](../../groupdocs.viewer.options/baseviewoptions/renderhiddenpages) { get; set; } | Mengaktifkan rendering halaman tersembunyi. |
| [RenderNotes](../../groupdocs.viewer.options/baseviewoptions/rendernotes) { get; set; } | Mengaktifkan rendering catatan. |
| [SpreadsheetOptions](../../groupdocs.viewer.options/baseviewoptions/spreadsheetoptions) { get; set; } | Opsi tampilan file spreadsheet. |
| [TextOptions](../../groupdocs.viewer.options/baseviewoptions/textoptions) { get; set; } | Pemisahan file teks ke opsi halaman. |
| [VisioRenderingOptions](../../groupdocs.viewer.options/baseviewoptions/visiorenderingoptions) { get; set; } | Opsi tampilan dokumen pemrosesan file Visio. |
| [WebDocumentOptions](../../groupdocs.viewer.options/baseviewoptions/webdocumentoptions) { get; set; } | Opsi rendering ini memungkinkan Anda menyesuaikan tampilan output HTML/PDF/PNG/JPEG saat merender dokumen Web. |
| [Width](../../groupdocs.viewer.options/viewinfooptions/width) { get; set; } | Lebar gambar (hanya untuk merender ke PNG/JPG) |
| [WordProcessingOptions](../../groupdocs.viewer.options/baseviewoptions/wordprocessingoptions) { get; set; } | Opsi rendering ini memungkinkan Anda menyesuaikan tampilan output HTML/PDF/PNG/JPEG saat merender dokumen Word. |

## Metode

| Nama | Keterangan |
| --- | --- |
| static [ForHtmlView](../../groupdocs.viewer.options/viewinfooptions/forhtmlview#forhtmlview)() | Menginisialisasi instance baru[`ViewInfoOptions`](../viewinfooptions) kelas untuk mengambil informasi tentang tampilan saat merender ke HTML. |
| static [ForHtmlView](../../groupdocs.viewer.options/viewinfooptions/forhtmlview#forhtmlview_1)(bool) | Menginisialisasi instance baru[`ViewInfoOptions`](../viewinfooptions) kelas untuk mengambil informasi tentang tampilan saat merender ke HTML. |
| static [ForJpgView](../../groupdocs.viewer.options/viewinfooptions/forjpgview#forjpgview)() | Menginisialisasi instance baru[`ViewInfoOptions`](../viewinfooptions) kelas untuk mengambil informasi tentang tampilan saat merender ke JPG. |
| static [ForJpgView](../../groupdocs.viewer.options/viewinfooptions/forjpgview#forjpgview_1)(bool) | Menginisialisasi instance baru[`ViewInfoOptions`](../viewinfooptions) kelas untuk mengambil informasi tentang tampilan saat merender ke JPG. |
| static [ForPngView](../../groupdocs.viewer.options/viewinfooptions/forpngview#forpngview)() | Menginisialisasi instance baru[`ViewInfoOptions`](../viewinfooptions) kelas untuk mengambil informasi tentang tampilan saat merender ke PNG. |
| static [ForPngView](../../groupdocs.viewer.options/viewinfooptions/forpngview#forpngview_1)(bool) | Menginisialisasi instance baru[`ViewInfoOptions`](../viewinfooptions) kelas untuk mengambil informasi tentang tampilan saat merender ke PNG. |
| static [FromHtmlViewOptions](../../groupdocs.viewer.options/viewinfooptions/fromhtmlviewoptions)(HtmlViewOptions) | Menginisialisasi instance baru[`ViewInfoOptions`](../viewinfooptions) kelas berdasarkan[`HtmlViewOptions`](../htmlviewoptions) objek. |
| static [FromJpgViewOptions](../../groupdocs.viewer.options/viewinfooptions/fromjpgviewoptions)(JpgViewOptions) | Menginisialisasi instance baru[`ViewInfoOptions`](../viewinfooptions) kelas berdasarkan[`JpgViewOptions`](../jpgviewoptions) objek. |
| static [FromPngViewOptions](../../groupdocs.viewer.options/viewinfooptions/frompngviewoptions)(PngViewOptions) | Menginisialisasi instance baru[`ViewInfoOptions`](../viewinfooptions) kelas berdasarkan[`PngViewOptions`](../pngviewoptions) objek. |

### Lihat juga

* class [BaseViewOptions](../baseviewoptions)
* interface [IMaxSizeOptions](../imaxsizeoptions)
* ruang nama [GroupDocs.Viewer.Options](../../groupdocs.viewer.options)
* perakitan [GroupDocs.Viewer](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Viewer.dll -->
