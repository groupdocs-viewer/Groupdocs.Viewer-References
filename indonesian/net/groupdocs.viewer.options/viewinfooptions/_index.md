---
title: "ViewInfoOptions"
second_title: "Referensi API GroupDocs.Viewer untuk .NET"
description: "Berisi opsi untuk mengambil informasi tentang tampilan."
type: docs
weight: 580
url: /id/net/groupdocs.viewer.options/viewinfooptions/
---

## ViewInfoOptions class

Berisi opsi untuk mengambil informasi tentang tampilan.

```csharp
public class ViewInfoOptions : BaseViewOptions, IMaxSizeOptions
```

## Properti

| Nama | Deskripsi |
| --- | --- |
| [ArchiveOptions](../../groupdocs.viewer.options/baseviewoptions/archiveoptions) { get; set; } | Opsi tampilan file arsip. |
| [CadOptions](../../groupdocs.viewer.options/baseviewoptions/cadoptions) { get; set; } | Opsi tampilan gambar CAD. |
| [DefaultFontName](../../groupdocs.viewer.options/baseviewoptions/defaultfontname) { get; set; } | Menetapkan font default untuk sebuah dokumen. |
| [EmailOptions](../../groupdocs.viewer.options/baseviewoptions/emailoptions) { get; set; } | Opsi tampilan pesan email. |
| [ExtractText](../../groupdocs.viewer.options/viewinfooptions/extracttext) { get; set; } | Mengaktifkan ekstraksi teks. |
| [Height](../../groupdocs.viewer.options/viewinfooptions/height) { get; set; } | Tinggi gambar output (dalam piksel, hanya untuk merender ke PNG/JPG). |
| [MailStorageOptions](../../groupdocs.viewer.options/baseviewoptions/mailstorageoptions) { get; set; } | Opsi tampilan file data penyimpanan surat. |
| [MaxHeight](../../groupdocs.viewer.options/viewinfooptions/maxheight) { get; set; } | Mengatur tinggi maksimum gambar output (dalam piksel, hanya untuk merender ke PNG/JPG). |
| [MaxWidth](../../groupdocs.viewer.options/viewinfooptions/maxwidth) { get; set; } | Mengatur lebar maksimum gambar output (dalam piksel, hanya untuk merender ke PNG/JPG). |
| [OutlookOptions](../../groupdocs.viewer.options/baseviewoptions/outlookoptions) { get; set; } | Opsi tampilan file data Microsoft Outlook. |
| [PdfOptions](../../groupdocs.viewer.options/baseviewoptions/pdfoptions) { get; set; } | Opsi tampilan dokumen PDF. |
| [PresentationOptions](../../groupdocs.viewer.options/baseviewoptions/presentationoptions) { get; set; } | Opsi tampilan file presentasi. |
| [ProjectManagementOptions](../../groupdocs.viewer.options/baseviewoptions/projectmanagementoptions) { get; set; } | Opsi tampilan file manajemen proyek. |
| [RemoveComments](../../groupdocs.viewer.options/baseviewoptions/removecomments) { get; set; } | Menonaktifkan rendering komentar ketika disetel ke `true`. Secara default adalah `false` — semua komentar ditampilkan. |
| [RenderHiddenPages](../../groupdocs.viewer.options/baseviewoptions/renderhiddenpages) { get; set; } | Mengaktifkan rendering halaman tersembunyi. |
| [RenderNotes](../../groupdocs.viewer.options/baseviewoptions/rendernotes) { get; set; } | Mengaktifkan rendering catatan dan anotasi untuk beberapa format |
| [SpreadsheetOptions](../../groupdocs.viewer.options/baseviewoptions/spreadsheetoptions) { get; set; } | Opsi tampilan file spreadsheet. |
| [TextOptions](../../groupdocs.viewer.options/baseviewoptions/textoptions) { get; set; } | Opsi tampilan file teks. |
| [VisioRenderingOptions](../../groupdocs.viewer.options/baseviewoptions/visiorenderingoptions) { get; set; } | Opsi tampilan file Visio. |
| [WebDocumentOptions](../../groupdocs.viewer.options/baseviewoptions/webdocumentoptions) { get; set; } | Opsi tampilan file Web. |
| [Width](../../groupdocs.viewer.options/viewinfooptions/width) { get; set; } | Lebar gambar output (dalam piksel, hanya untuk merender ke PNG/JPG). |
| [WordProcessingOptions](../../groupdocs.viewer.options/baseviewoptions/wordprocessingoptions) { get; set; } | Opsi tampilan file pengolah kata. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| static [ForHtmlView](../../groupdocs.viewer.options/viewinfooptions/forhtmlview#forhtmlview)() | Menginisialisasi sebuah instance dari kelas [`ViewInfoOptions`](../viewinfooptions) untuk mengambil informasi tampilan saat merender ke HTML. |
| static [ForHtmlView](../../groupdocs.viewer.options/viewinfooptions/forhtmlview#forhtmlview_1)(bool) | Menginisialisasi sebuah instance dari kelas [`ViewInfoOptions`](../viewinfooptions) untuk mengambil informasi tampilan saat merender ke HTML. |
| static [ForJpgView](../../groupdocs.viewer.options/viewinfooptions/forjpgview#forjpgview)() | Menginisialisasi sebuah instance dari kelas [`ViewInfoOptions`](../viewinfooptions) untuk mengambil informasi tampilan saat merender ke JPG. |
| static [ForJpgView](../../groupdocs.viewer.options/viewinfooptions/forjpgview#forjpgview_1)(bool) | Menginisialisasi sebuah instance dari kelas [`ViewInfoOptions`](../viewinfooptions) untuk mengambil informasi tampilan saat merender ke JPG. |
| static [ForPdfView](../../groupdocs.viewer.options/viewinfooptions/forpdfview)() | Menginisialisasi sebuah instance dari kelas [`ViewInfoOptions`](../viewinfooptions) untuk mengambil informasi tampilan saat merender ke PDF. |
| static [ForPngView](../../groupdocs.viewer.options/viewinfooptions/forpngview#forpngview)() | Menginisialisasi sebuah instance dari kelas [`ViewInfoOptions`](../viewinfooptions) untuk mengambil informasi tampilan saat merender ke PNG. |
| static [ForPngView](../../groupdocs.viewer.options/viewinfooptions/forpngview#forpngview_1)(bool) | Menginisialisasi sebuah instance dari kelas [`ViewInfoOptions`](../viewinfooptions) untuk mengambil informasi tampilan saat merender ke PNG. |
| static [FromHtmlViewOptions](../../groupdocs.viewer.options/viewinfooptions/fromhtmlviewoptions)(HtmlViewOptions) | Menginisialisasi sebuah instance dari kelas [`ViewInfoOptions`](../viewinfooptions) berdasarkan objek [`HtmlViewOptions`](../htmlviewoptions). |
| static [FromJpgViewOptions](../../groupdocs.viewer.options/viewinfooptions/fromjpgviewoptions)(JpgViewOptions) | Menginisialisasi sebuah instance dari kelas [`ViewInfoOptions`](../viewinfooptions) berdasarkan objek [`JpgViewOptions`](../jpgviewoptions). |
| static [FromPdfViewOptions](../../groupdocs.viewer.options/viewinfooptions/frompdfviewoptions)(PdfViewOptions) | Menginisialisasi sebuah instance dari kelas [`ViewInfoOptions`](../viewinfooptions) berdasarkan objek [`PdfViewOptions`](../pdfviewoptions). |
| static [FromPngViewOptions](../../groupdocs.viewer.options/viewinfooptions/frompngviewoptions)(PngViewOptions) | Menginisialisasi sebuah instance dari kelas [`ViewInfoOptions`](../viewinfooptions) berdasarkan objek [`PngViewOptions`](../pngviewoptions). |

### Lihat Juga

* class [BaseViewOptions](../baseviewoptions)
* interface [IMaxSizeOptions](../imaxsizeoptions)
* namespace [GroupDocs.Viewer.Options](../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Viewer.dll -->
