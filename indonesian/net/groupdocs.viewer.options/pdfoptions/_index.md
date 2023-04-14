---
title: PdfOptions
second_title: GroupDocs.Viewer untuk Referensi .NET API
description: Menyediakan opsi untuk merender dokumen PDF.
type: docs
weight: 410
url: /id/net/groupdocs.viewer.options/pdfoptions/
---
## PdfOptions class

Menyediakan opsi untuk merender dokumen PDF.

```csharp
public class PdfOptions
```

## Konstruktor

| Nama | Keterangan |
| --- | --- |
| [PdfOptions](pdfoptions)() | Menginisialisasi instance baru[`PdfOptions`](../pdfoptions) kelas. |

## Properti

| Nama | Keterangan |
| --- | --- |
| [DisableCharsGrouping](../../groupdocs.viewer.options/pdfoptions/disablecharsgrouping) { get; set; } | Menonaktifkan pengelompokan karakter untuk menjaga presisi maksimum selama pemosisian karakter saat merender halaman. |
| [EnableFontHinting](../../groupdocs.viewer.options/pdfoptions/enablefonthinting) { get; set; } | Mengaktifkan petunjuk font. Petunjuk font menyesuaikan tampilan font garis besar. Hanya didukung untuk font TTF saat font ini digunakan dalam dokumen sumber. |
| [EnableLayeredRendering](../../groupdocs.viewer.options/pdfoptions/enablelayeredrendering) { get; set; } | Mengaktifkan rendering teks dan grafik menurut z-order dalam dokumen PDF asli saat merender ke dalam HTML. |
| [FixedLayout](../../groupdocs.viewer.options/pdfoptions/fixedlayout) { get; set; } | PDF adalah format tetap sehingga semua elemen memiliki tempat khusus pada halaman. Untuk memastikan bahwa HTML keluaran terlihat sama dengan PDF sumber, dokumen dirender ke HTML dengan tata letak tetap secara default. Saat merender dengan fixed layout output HTML memiliki ukuran tetap sehingga elemen akan tetap berada di tempat yang sama terlepas dari ukuran jendela. Untuk merender ke HTML dengan fluid layout setel properti ini ke`PALSU` . |
| [ImageQuality](../../groupdocs.viewer.options/pdfoptions/imagequality) { get; set; } | Menentukan kualitas gambar keluaran untuk sumber daya gambar saat merender ke HTML. Nilai defaultnya adalah Rendah. |
| [RenderOriginalPageSize](../../groupdocs.viewer.options/pdfoptions/renderoriginalpagesize) { get; set; } | Ketika opsi ini diaktifkan, halaman keluaran akan memiliki ukuran yang sama dalam piksel seperti ukuran halaman dalam dokumen PDF sumber. Secara default GroupDocs.Viewer menghitung ukuran halaman gambar keluaran untuk kualitas perenderan yang lebih baik. |
| [RenderTextAsImage](../../groupdocs.viewer.options/pdfoptions/rendertextasimage) { get; set; } | Saat opsi ini disetel keBENAR , teks dirender sebagai gambar dalam output HTML. Aktifkan opsi ini untuk membuat teks tidak dapat dipilih atau untuk memperbaiki perenderan karakter dan membuat HTML terlihat seperti PDF. Nilai defaultnya adalahPALSU . |

### Lihat juga

* ruang nama [GroupDocs.Viewer.Options](../../groupdocs.viewer.options)
* perakitan [GroupDocs.Viewer](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Viewer.dll -->