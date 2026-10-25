---
title: "SpreadsheetOptions"
second_title: "Referensi API GroupDocs.Viewer untuk .NET"
description: "Berisi opsi untuk merender spreadsheet. Untuk detail, lihat anak-anak dari topik Render spreadsheet fileshttps//docs.groupdocs.com/viewer/net/renderspreadsheets/."
type: docs
weight: 530
url: /id/net/groupdocs.viewer.options/spreadsheetoptions/
---

## SpreadsheetOptions class

Berisi opsi untuk merender spreadsheet. Untuk detail, lihat turunan dari topik [Render file spreadsheet](https://docs.groupdocs.com/viewer/net/render-spreadsheets/).

```csharp
public class SpreadsheetOptions
```

## Properti

| Nama | Deskripsi |
| --- | --- |
| [BottomMargin](../../groupdocs.viewer.options/spreadsheetoptions/bottommargin) { get; set; } | Mengatur margin bawah halaman saat mengonversi ke PDF. |
| [CountColumnsPerPage](../../groupdocs.viewer.options/spreadsheetoptions/countcolumnsperpage) { get; } | Jumlah kolom yang akan disertakan pada setiap halaman saat membagi lembar kerja menjadi halaman. |
| [CountRowsPerPage](../../groupdocs.viewer.options/spreadsheetoptions/countrowsperpage) { get; } | Jumlah baris yang akan disertakan pada setiap halaman saat membagi lembar kerja menjadi halaman. |
| [DetectSeparator](../../groupdocs.viewer.options/spreadsheetoptions/detectseparator) { get; set; } | Mendeteksi pemisah (untuk file CSV/TSV). |
| [HorizontalResolution](../../groupdocs.viewer.options/spreadsheetoptions/horizontalresolution) { get; set; } | Mendapatkan atau mengatur resolusi horizontal untuk gambar yang dihasilkan dalam dot per inci. Opsi ini hanya digunakan saat merender spreadsheet ke format PNG atau JPEG. |
| [LeftMargin](../../groupdocs.viewer.options/spreadsheetoptions/leftmargin) { get; set; } | Mengatur margin kiri halaman saat mengonversi ke PDF. |
| [RenderGridLines](../../groupdocs.viewer.options/spreadsheetoptions/rendergridlines) { get; set; } | Mengaktifkan render garis kisi. |
| [RenderHeadings](../../groupdocs.viewer.options/spreadsheetoptions/renderheadings) { get; set; } | Mengaktifkan render judul. |
| [RenderHiddenColumns](../../groupdocs.viewer.options/spreadsheetoptions/renderhiddencolumns) { get; set; } | Mengaktifkan render kolom tersembunyi. |
| [RenderHiddenRows](../../groupdocs.viewer.options/spreadsheetoptions/renderhiddenrows) { get; set; } | Mengaktifkan render baris tersembunyi. |
| [RightMargin](../../groupdocs.viewer.options/spreadsheetoptions/rightmargin) { get; set; } | Mengatur margin kanan halaman saat mengonversi ke PDF. |
| [SkipEmptyColumns](../../groupdocs.viewer.options/spreadsheetoptions/skipemptycolumns) { get; set; } | Menonaktifkan rendering kolom kosong. |
| [SkipEmptyRows](../../groupdocs.viewer.options/spreadsheetoptions/skipemptyrows) { get; set; } | Menonaktifkan rendering baris kosong. |
| [TextOverflowMode](../../groupdocs.viewer.options/spreadsheetoptions/textoverflowmode) { get; set; } | Mengatur mode overflow teks untuk merender dokumen spreadsheet menjadi HTML. Secara default adalah , yang meniru perilaku default MS Excel. |
| [TopMargin](../../groupdocs.viewer.options/spreadsheetoptions/topmargin) { get; set; } | Mengatur margin atas halaman saat mengonversi ke PDF. |
| [VerticalResolution](../../groupdocs.viewer.options/spreadsheetoptions/verticalresolution) { get; set; } | Mendapatkan atau mengatur resolusi vertikal untuk gambar yang dihasilkan dalam dot per inci. Opsi ini hanya digunakan saat merender spreadsheet ke format PNG atau JPEG. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| static [ForOnePagePerSheet](../../groupdocs.viewer.options/spreadsheetoptions/foronepagepersheet)() | Menginisialisasi instance dari kelas [`SpreadsheetOptions`](../spreadsheetoptions) untuk merender seluruh lembar menjadi satu halaman. |
| static [ForRenderingByPageBreaks](../../groupdocs.viewer.options/spreadsheetoptions/forrenderingbypagebreaks)() | Menginisialisasi instance dari kelas [`SpreadsheetOptions`](../spreadsheetoptions) untuk membagi menjadi halaman berdasarkan pemisah halaman. |
| static [ForRenderingPrintArea](../../groupdocs.viewer.options/spreadsheetoptions/forrenderingprintarea)() | Menginisialisasi instance dari kelas [`SpreadsheetOptions`](../spreadsheetoptions) untuk merender hanya area cetak. |
| static [ForRenderingPrintAreaAndPageBreaks](../../groupdocs.viewer.options/spreadsheetoptions/forrenderingprintareaandpagebreaks)() | Menginisialisasi instance dari kelas [`SpreadsheetOptions`](../spreadsheetoptions) untuk merender area cetak dan pemisah halaman. |
| static [ForSplitSheetIntoPages](../../groupdocs.viewer.options/spreadsheetoptions/forsplitsheetintopages#forsplitsheetintopages)(int) | Menginisialisasi instance dari kelas [`SpreadsheetOptions`](../spreadsheetoptions) untuk merender lembar menjadi halaman. |
| static [ForSplitSheetIntoPages](../../groupdocs.viewer.options/spreadsheetoptions/forsplitsheetintopages#forsplitsheetintopages_1)(int, int) | Menginisialisasi instance dari kelas [`SpreadsheetOptions`](../spreadsheetoptions) untuk merender lembar menjadi halaman. |

### Lihat Juga

* namespace [GroupDocs.Viewer.Options](../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Viewer.dll -->
