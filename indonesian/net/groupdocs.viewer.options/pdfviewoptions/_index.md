---
title: "PdfViewOptions"
second_title: "Referensi API GroupDocs.Viewer untuk .NET"
description: "Berisi opsi untuk merender dokumen ke format PDF. Untuk detail lihat dokumentasihttps//docs.groupdocs.com/viewer/net/renderingtopdf/."
type: docs
weight: 420
url: /id/net/groupdocs.viewer.options/pdfviewoptions/
---

## PdfViewOptions class

Berisi opsi untuk merender dokumen ke format PDF. Untuk detail, lihat [dokumentasi](https://docs.groupdocs.com/viewer/net/rendering-to-pdf/).

```csharp
public class PdfViewOptions : ViewOptions
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [PdfViewOptions](pdfviewoptions#constructor)() | Menginisialisasi sebuah instance dari kelas [`PdfViewOptions`](../pdfviewoptions). |
| [PdfViewOptions](pdfviewoptions#constructor_1)(CreateFileStream) | Menginisialisasi sebuah instance dari kelas [`PdfViewOptions`](../pdfviewoptions). |
| [PdfViewOptions](pdfviewoptions#constructor_3)(IFileStreamFactory) | Menginisialisasi sebuah instance dari kelas [`PdfViewOptions`](../pdfviewoptions). |
| [PdfViewOptions](pdfviewoptions#constructor_4)(string) | Menginisialisasi sebuah instance dari kelas [`PdfViewOptions`](../pdfviewoptions). |
| [PdfViewOptions](pdfviewoptions#constructor_2)(CreateFileStream, ReleaseFileStream) | Menginisialisasi sebuah instance dari kelas [`PdfViewOptions`](../pdfviewoptions). |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [ArchiveOptions](../../groupdocs.viewer.options/baseviewoptions/archiveoptions) { get; set; } | Opsi tampilan file arsip. |
| [CadOptions](../../groupdocs.viewer.options/baseviewoptions/cadoptions) { get; set; } | Opsi tampilan gambar CAD. |
| [DefaultFontName](../../groupdocs.viewer.options/baseviewoptions/defaultfontname) { get; set; } | Menetapkan font default untuk sebuah dokumen. |
| [EmailOptions](../../groupdocs.viewer.options/baseviewoptions/emailoptions) { get; set; } | Opsi tampilan pesan email. |
| [ImageHeight](../../groupdocs.viewer.options/pdfviewoptions/imageheight) { get; set; } | Mengatur tinggi gambar output (dalam piksel). |
| [ImageMaxHeight](../../groupdocs.viewer.options/pdfviewoptions/imagemaxheight) { get; set; } | Mengatur tinggi maksimum gambar output (dalam piksel). |
| [ImageMaxWidth](../../groupdocs.viewer.options/pdfviewoptions/imagemaxwidth) { get; set; } | Mengatur lebar maksimum gambar output (dalam piksel). |
| [ImageWidth](../../groupdocs.viewer.options/pdfviewoptions/imagewidth) { get; set; } | Mengatur lebar gambar output (dalam piksel). |
| [MailStorageOptions](../../groupdocs.viewer.options/baseviewoptions/mailstorageoptions) { get; set; } | Opsi tampilan file data penyimpanan surat. |
| [OutlookOptions](../../groupdocs.viewer.options/baseviewoptions/outlookoptions) { get; set; } | Opsi tampilan file data Microsoft Outlook. |
| [PdfOptimizationOptions](../../groupdocs.viewer.options/pdfviewoptions/pdfoptimizationoptions) { get; set; } | Mengurangi ukuran file PDF output dengan menerapkan teknik optimasi dengan berbagai opsi. |
| [PdfOptions](../../groupdocs.viewer.options/baseviewoptions/pdfoptions) { get; set; } | Opsi tampilan dokumen PDF. |
| [PresentationOptions](../../groupdocs.viewer.options/baseviewoptions/presentationoptions) { get; set; } | Opsi tampilan file presentasi. |
| [ProjectManagementOptions](../../groupdocs.viewer.options/baseviewoptions/projectmanagementoptions) { get; set; } | Opsi tampilan file manajemen proyek. |
| [RemoveComments](../../groupdocs.viewer.options/baseviewoptions/removecomments) { get; set; } | Menonaktifkan rendering komentar ketika disetel ke `true`. Secara default adalah `false` — semua komentar ditampilkan. |
| [RenderHiddenPages](../../groupdocs.viewer.options/baseviewoptions/renderhiddenpages) { get; set; } | Mengaktifkan rendering halaman tersembunyi. |
| [RenderNotes](../../groupdocs.viewer.options/baseviewoptions/rendernotes) { get; set; } | Mengaktifkan rendering catatan dan anotasi untuk beberapa format |
| [Security](../../groupdocs.viewer.options/pdfviewoptions/security) { get; set; } | Mengatur opsi keamanan dokumen PDF output. |
| [SpreadsheetOptions](../../groupdocs.viewer.options/baseviewoptions/spreadsheetoptions) { get; set; } | Opsi tampilan file spreadsheet. |
| [TextOptions](../../groupdocs.viewer.options/baseviewoptions/textoptions) { get; set; } | Opsi tampilan file teks. |
| [VisioRenderingOptions](../../groupdocs.viewer.options/baseviewoptions/visiorenderingoptions) { get; set; } | Opsi tampilan file Visio. |
| [Watermark](../../groupdocs.viewer.options/viewoptions/watermark) { get; set; } | Watermark teks yang akan diterapkan pada setiap halaman. |
| [WebDocumentOptions](../../groupdocs.viewer.options/baseviewoptions/webdocumentoptions) { get; set; } | Opsi tampilan file Web. |
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
* namespace [GroupDocs.Viewer.Options](../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Viewer.dll -->
