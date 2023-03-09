---
title: PdfViewOptions
second_title: GroupDocs.Viewer untuk Referensi .NET API
description: Memberikan pilihan untuk merender dokumen ke dalam format PDF.
type: docs
weight: 420
url: /id/net/groupdocs.viewer.options/pdfviewoptions/
---
## PdfViewOptions class

Memberikan pilihan untuk merender dokumen ke dalam format PDF.

```csharp
public class PdfViewOptions : ViewOptions
```

## Konstruktor

| Nama | Keterangan |
| --- | --- |
| [PdfViewOptions](pdfviewoptions#constructor)() | Menginisialisasi instance baru[`PdfViewOptions`](../pdfviewoptions) kelas. |
| [PdfViewOptions](pdfviewoptions#constructor_1)(CreateFileStream) | Menginisialisasi instance baru[`PdfViewOptions`](../pdfviewoptions) kelas. |
| [PdfViewOptions](pdfviewoptions#constructor_3)(IFileStreamFactory) | Menginisialisasi instance baru[`PdfViewOptions`](../pdfviewoptions) kelas. |
| [PdfViewOptions](pdfviewoptions#constructor_4)(string) | Menginisialisasi instance baru[`PdfViewOptions`](../pdfviewoptions) kelas. |
| [PdfViewOptions](pdfviewoptions#constructor_2)(CreateFileStream, ReleaseFileStream) | Menginisialisasi instance baru[`PdfViewOptions`](../pdfviewoptions) kelas. |

## Properti

| Nama | Keterangan |
| --- | --- |
| [ArchiveOptions](../../groupdocs.viewer.options/baseviewoptions/archiveoptions) { get; set; } | Opsi tampilan file arsip. |
| [CadOptions](../../groupdocs.viewer.options/baseviewoptions/cadoptions) { get; set; } | Opsi tampilan gambar CAD. |
| [DefaultFontName](../../groupdocs.viewer.options/baseviewoptions/defaultfontname) { get; set; } | Font default untuk digunakan ketika font tertentu yang digunakan dalam dokumen tidak dapat ditemukan. |
| [EmailOptions](../../groupdocs.viewer.options/baseviewoptions/emailoptions) { get; set; } | Opsi tampilan pesan email. |
| [ImageHeight](../../groupdocs.viewer.options/pdfviewoptions/imageheight) { get; set; } | Ketinggian gambar keluaran dalam piksel. (Saat mengonversi gambar tunggal ke HTML saja) |
| [ImageMaxHeight](../../groupdocs.viewer.options/pdfviewoptions/imagemaxheight) { get; set; } | Tinggi maksimum gambar keluaran dalam piksel. (Saat mengonversi gambar tunggal ke HTML saja) |
| [ImageMaxWidth](../../groupdocs.viewer.options/pdfviewoptions/imagemaxwidth) { get; set; } | Lebar maksimum gambar keluaran dalam piksel. (Saat mengonversi gambar tunggal ke HTML saja) |
| [ImageWidth](../../groupdocs.viewer.options/pdfviewoptions/imagewidth) { get; set; } | Lebar gambar keluaran dalam piksel. (Saat mengonversi gambar tunggal ke HTML saja) |
| [JpgQuality](../../groupdocs.viewer.options/pdfviewoptions/jpgquality) { get; set; } | Kualitas gambar JPG yang terkandung dalam dokumen PDF keluaran; Nilai yang valid antara 1 dan 100; Nilai default adalah 90. |
| [MailStorageOptions](../../groupdocs.viewer.options/baseviewoptions/mailstorageoptions) { get; set; } | Opsi tampilan file data penyimpanan email. |
| [Optimize](../../groupdocs.viewer.options/pdfviewoptions/optimize) { get; set; } | Kurangi ukuran file keluaran dengan mengecualikan font umum seperti Times New Roman dan Arial, dan menerapkan teknik pengoptimalan lainnya. |
| [OutlookOptions](../../groupdocs.viewer.options/baseviewoptions/outlookoptions) { get; set; } | Opsi tampilan file data MS Outlook. |
| [PdfOptions](../../groupdocs.viewer.options/baseviewoptions/pdfoptions) { get; set; } | Opsi tampilan dokumen PDF. |
| [PresentationOptions](../../groupdocs.viewer.options/baseviewoptions/presentationoptions) { get; set; } | Opsi tampilan dokumen pemrosesan presentasi. |
| [ProjectManagementOptions](../../groupdocs.viewer.options/baseviewoptions/projectmanagementoptions) { get; set; } | Opsi tampilan file manajemen proyek. |
| [RenderComments](../../groupdocs.viewer.options/baseviewoptions/rendercomments) { get; set; } | Mengaktifkan rendering komentar. |
| [RenderHiddenPages](../../groupdocs.viewer.options/baseviewoptions/renderhiddenpages) { get; set; } | Mengaktifkan rendering halaman tersembunyi. |
| [RenderNotes](../../groupdocs.viewer.options/baseviewoptions/rendernotes) { get; set; } | Mengaktifkan rendering catatan. |
| [Security](../../groupdocs.viewer.options/pdfviewoptions/security) { get; set; } | Keluaran opsi keamanan dokumen PDF. |
| [SpreadsheetOptions](../../groupdocs.viewer.options/baseviewoptions/spreadsheetoptions) { get; set; } | Opsi tampilan file spreadsheet. |
| [TextOptions](../../groupdocs.viewer.options/baseviewoptions/textoptions) { get; set; } | Pemisahan file teks ke opsi halaman. |
| [VisioRenderingOptions](../../groupdocs.viewer.options/baseviewoptions/visiorenderingoptions) { get; set; } | Opsi tampilan dokumen pemrosesan file Visio. |
| [Watermark](../../groupdocs.viewer.options/viewoptions/watermark) { get; set; } | Watermark teks diterapkan ke setiap halaman. |
| [WebDocumentOptions](../../groupdocs.viewer.options/baseviewoptions/webdocumentoptions) { get; set; } | Opsi rendering ini memungkinkan Anda menyesuaikan tampilan output HTML/PDF/PNG/JPEG saat merender dokumen Web. |
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
* ruang nama [GroupDocs.Viewer.Options](../../groupdocs.viewer.options)
* perakitan [GroupDocs.Viewer](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Viewer.dll -->
