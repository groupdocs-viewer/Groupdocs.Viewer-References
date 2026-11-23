---
title: "JpgViewOptions"
second_title: "Referensi API GroupDocs.Viewer untuk .NET"
description: "Menyediakan opsi untuk merender dokumen ke format JPG. Untuk detail lihat halaman inihttps//docs.groupdocs.com/viewer/net/renderingtopngorjpeg/ dan turunannya."
type: docs
weight: 350
url: /id/net/groupdocs.viewer.options/jpgviewoptions/
---

## JpgViewOptions class

Menyediakan opsi untuk merender dokumen ke format JPG. Untuk detail, lihat [halaman](https://docs.groupdocs.com/viewer/net/rendering-to-png-or-jpeg/) ini dan turunannya.

```csharp
public class JpgViewOptions : ViewOptions, IMaxSizeOptions
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [JpgViewOptions](jpgviewoptions#constructor)() | Menginisialisasi sebuah instance dari kelas [`JpgViewOptions`](../jpgviewoptions). |
| [JpgViewOptions](jpgviewoptions#constructor_1)(CreatePageStream) | Menginisialisasi sebuah instance dari kelas [`JpgViewOptions`](../jpgviewoptions). |
| [JpgViewOptions](jpgviewoptions#constructor_3)(IPageStreamFactory) | Menginisialisasi sebuah instance dari kelas [`JpgViewOptions`](../jpgviewoptions). |
| [JpgViewOptions](jpgviewoptions#constructor_4)(string) | Menginisialisasi sebuah instance dari kelas [`JpgViewOptions`](../jpgviewoptions). |
| [JpgViewOptions](jpgviewoptions#constructor_2)(CreatePageStream, ReleasePageStream) | Menginisialisasi sebuah instance dari kelas [`JpgViewOptions`](../jpgviewoptions). |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [ArchiveOptions](../../groupdocs.viewer.options/baseviewoptions/archiveoptions) { get; set; } | Opsi tampilan file arsip. |
| [CadOptions](../../groupdocs.viewer.options/baseviewoptions/cadoptions) { get; set; } | Opsi tampilan gambar CAD. |
| [DefaultFontName](../../groupdocs.viewer.options/baseviewoptions/defaultfontname) { get; set; } | Menetapkan font default untuk sebuah dokumen. |
| [EmailOptions](../../groupdocs.viewer.options/baseviewoptions/emailoptions) { get; set; } | Opsi tampilan pesan email. |
| [ExtractText](../../groupdocs.viewer.options/jpgviewoptions/extracttext) { get; set; } | Mengaktifkan ekstraksi teks. |
| [Height](../../groupdocs.viewer.options/jpgviewoptions/height) { get; set; } | Mengatur tinggi gambar output (dalam piksel). |
| [MailStorageOptions](../../groupdocs.viewer.options/baseviewoptions/mailstorageoptions) { get; set; } | Opsi tampilan file data penyimpanan surat. |
| [MaxHeight](../../groupdocs.viewer.options/jpgviewoptions/maxheight) { get; set; } | Mengatur tinggi maksimum gambar output (dalam piksel). |
| [MaxWidth](../../groupdocs.viewer.options/jpgviewoptions/maxwidth) { get; set; } | Mengatur lebar maksimum gambar output (dalam piksel). |
| [OutlookOptions](../../groupdocs.viewer.options/baseviewoptions/outlookoptions) { get; set; } | Opsi tampilan file data Microsoft Outlook. |
| [PdfOptions](../../groupdocs.viewer.options/baseviewoptions/pdfoptions) { get; set; } | Opsi tampilan dokumen PDF. |
| [PresentationOptions](../../groupdocs.viewer.options/baseviewoptions/presentationoptions) { get; set; } | Opsi tampilan file presentasi. |
| [ProjectManagementOptions](../../groupdocs.viewer.options/baseviewoptions/projectmanagementoptions) { get; set; } | Opsi tampilan file manajemen proyek. |
| [Quality](../../groupdocs.viewer.options/jpgviewoptions/quality) { get; set; } | Mengatur kualitas gambar keluaran. |
| [RemoveComments](../../groupdocs.viewer.options/baseviewoptions/removecomments) { get; set; } | Menonaktifkan rendering komentar ketika disetel ke `true`. Secara default adalah `false` — semua komentar ditampilkan. |
| [RenderHiddenPages](../../groupdocs.viewer.options/baseviewoptions/renderhiddenpages) { get; set; } | Mengaktifkan rendering halaman tersembunyi. |
| [RenderNotes](../../groupdocs.viewer.options/baseviewoptions/rendernotes) { get; set; } | Mengaktifkan rendering catatan dan anotasi untuk beberapa format |
| [SpreadsheetOptions](../../groupdocs.viewer.options/baseviewoptions/spreadsheetoptions) { get; set; } | Opsi tampilan file spreadsheet. |
| [TextOptions](../../groupdocs.viewer.options/baseviewoptions/textoptions) { get; set; } | Opsi tampilan file teks. |
| [VisioRenderingOptions](../../groupdocs.viewer.options/baseviewoptions/visiorenderingoptions) { get; set; } | Opsi tampilan file Visio. |
| [Watermark](../../groupdocs.viewer.options/viewoptions/watermark) { get; set; } | Watermark teks yang akan diterapkan pada setiap halaman. |
| [WebDocumentOptions](../../groupdocs.viewer.options/baseviewoptions/webdocumentoptions) { get; set; } | Opsi tampilan file Web. |
| [Width](../../groupdocs.viewer.options/jpgviewoptions/width) { get; set; } | Mengatur lebar gambar keluaran (dalam piksel). |
| [WordProcessingOptions](../../groupdocs.viewer.options/baseviewoptions/wordprocessingoptions) { get; set; } | Opsi tampilan file pengolah kata. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [RotatePage](../../groupdocs.viewer.options/viewoptions/rotatepage)(int, Rotation) | Menerapkan rotasi searah jarum jam pada halaman. |

## Bidang

| Nama | Deskripsi |
| --- | --- |
| readonly [PageRotations](../../groupdocs.viewer.options/viewoptions/pagerotations) | Rotasi halaman. |

### Lihat Juga

* class [ViewOptions](../viewoptions)
* interface [IMaxSizeOptions](../imaxsizeoptions)
* namespace [GroupDocs.Viewer.Options](../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Viewer.dll -->
