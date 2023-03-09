---
title: JpgViewOptions
second_title: GroupDocs.Viewer untuk Referensi .NET API
description: Memberikan opsi untuk merender dokumen ke dalam format JPG.
type: docs
weight: 360
url: /id/net/groupdocs.viewer.options/jpgviewoptions/
---
## JpgViewOptions class

Memberikan opsi untuk merender dokumen ke dalam format JPG.

```csharp
public class JpgViewOptions : ViewOptions, IMaxSizeOptions
```

## Konstruktor

| Nama | Keterangan |
| --- | --- |
| [JpgViewOptions](jpgviewoptions#constructor)() | Menginisialisasi instance baru[`JpgViewOptions`](../jpgviewoptions) kelas. |
| [JpgViewOptions](jpgviewoptions#constructor_1)(CreatePageStream) | Menginisialisasi instance baru[`JpgViewOptions`](../jpgviewoptions) kelas. |
| [JpgViewOptions](jpgviewoptions#constructor_3)(IPageStreamFactory) | Menginisialisasi instance baru[`JpgViewOptions`](../jpgviewoptions) kelas. |
| [JpgViewOptions](jpgviewoptions#constructor_4)(string) | Menginisialisasi instance baru[`JpgViewOptions`](../jpgviewoptions) kelas. |
| [JpgViewOptions](jpgviewoptions#constructor_2)(CreatePageStream, ReleasePageStream) | Menginisialisasi instance baru[`JpgViewOptions`](../jpgviewoptions) kelas. |

## Properti

| Nama | Keterangan |
| --- | --- |
| [ArchiveOptions](../../groupdocs.viewer.options/baseviewoptions/archiveoptions) { get; set; } | Opsi tampilan file arsip. |
| [CadOptions](../../groupdocs.viewer.options/baseviewoptions/cadoptions) { get; set; } | Opsi tampilan gambar CAD. |
| [DefaultFontName](../../groupdocs.viewer.options/baseviewoptions/defaultfontname) { get; set; } | Font default untuk digunakan ketika font tertentu yang digunakan dalam dokumen tidak dapat ditemukan. |
| [EmailOptions](../../groupdocs.viewer.options/baseviewoptions/emailoptions) { get; set; } | Opsi tampilan pesan email. |
| [ExtractText](../../groupdocs.viewer.options/jpgviewoptions/extracttext) { get; set; } | Mengaktifkan ekstraksi teks. |
| [Height](../../groupdocs.viewer.options/jpgviewoptions/height) { get; set; } | Tinggi gambar keluaran dalam piksel. |
| [MailStorageOptions](../../groupdocs.viewer.options/baseviewoptions/mailstorageoptions) { get; set; } | Opsi tampilan file data penyimpanan email. |
| [MaxHeight](../../groupdocs.viewer.options/jpgviewoptions/maxheight) { get; set; } | Tinggi maksimum gambar keluaran dalam piksel. |
| [MaxWidth](../../groupdocs.viewer.options/jpgviewoptions/maxwidth) { get; set; } | Lebar maksimum gambar keluaran dalam piksel. |
| [OutlookOptions](../../groupdocs.viewer.options/baseviewoptions/outlookoptions) { get; set; } | Opsi tampilan file data MS Outlook. |
| [PdfOptions](../../groupdocs.viewer.options/baseviewoptions/pdfoptions) { get; set; } | Opsi tampilan dokumen PDF. |
| [PresentationOptions](../../groupdocs.viewer.options/baseviewoptions/presentationoptions) { get; set; } | Opsi tampilan dokumen pemrosesan presentasi. |
| [ProjectManagementOptions](../../groupdocs.viewer.options/baseviewoptions/projectmanagementoptions) { get; set; } | Opsi tampilan file manajemen proyek. |
| [Quality](../../groupdocs.viewer.options/jpgviewoptions/quality) { get; set; } | Kualitas gambar keluaran; Nilai yang valid antara 1 dan 100; Nilai default adalah 90. |
| [RenderComments](../../groupdocs.viewer.options/baseviewoptions/rendercomments) { get; set; } | Mengaktifkan rendering komentar. |
| [RenderHiddenPages](../../groupdocs.viewer.options/baseviewoptions/renderhiddenpages) { get; set; } | Mengaktifkan rendering halaman tersembunyi. |
| [RenderNotes](../../groupdocs.viewer.options/baseviewoptions/rendernotes) { get; set; } | Mengaktifkan rendering catatan. |
| [SpreadsheetOptions](../../groupdocs.viewer.options/baseviewoptions/spreadsheetoptions) { get; set; } | Opsi tampilan file spreadsheet. |
| [TextOptions](../../groupdocs.viewer.options/baseviewoptions/textoptions) { get; set; } | Pemisahan file teks ke opsi halaman. |
| [VisioRenderingOptions](../../groupdocs.viewer.options/baseviewoptions/visiorenderingoptions) { get; set; } | Opsi tampilan dokumen pemrosesan file Visio. |
| [Watermark](../../groupdocs.viewer.options/viewoptions/watermark) { get; set; } | Watermark teks diterapkan ke setiap halaman. |
| [WebDocumentOptions](../../groupdocs.viewer.options/baseviewoptions/webdocumentoptions) { get; set; } | Opsi rendering ini memungkinkan Anda menyesuaikan tampilan output HTML/PDF/PNG/JPEG saat merender dokumen Web. |
| [Width](../../groupdocs.viewer.options/jpgviewoptions/width) { get; set; } | Lebar gambar keluaran dalam piksel. |
| [WordProcessingOptions](../../groupdocs.viewer.options/baseviewoptions/wordprocessingoptions) { get; set; } | Opsi rendering ini memungkinkan Anda menyesuaikan tampilan output HTML/PDF/PNG/JPEG saat merender dokumen Word. |

## Metode

| Nama | Keterangan |
| --- | --- |
| [RotatePage](../../groupdocs.viewer.options/viewoptions/rotatepage)(int, Rotation) | Menerapkan rotasi searah jarum jam ke halaman. |

## Bidang

| Nama | Keterangan |
| --- | --- |
| readonly [PageRotations](../../groupdocs.viewer.options/viewoptions/pagerotations) | Perputaran halaman. |

### Lihat juga

* class [ViewOptions](../viewoptions)
* interface [IMaxSizeOptions](../imaxsizeoptions)
* ruang nama [GroupDocs.Viewer.Options](../../groupdocs.viewer.options)
* perakitan [GroupDocs.Viewer](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Viewer.dll -->
