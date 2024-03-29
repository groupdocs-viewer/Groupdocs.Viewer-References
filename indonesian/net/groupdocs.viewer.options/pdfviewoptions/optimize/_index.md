---
title: Optimize
second_title: GroupDocs.Viewer untuk Referensi .NET API
description: Kurangi ukuran file keluaran dengan mengecualikan font umum seperti Times New Roman dan Arial dan menerapkan teknik pengoptimalan lainnya.
type: docs
weight: 70
url: /id/net/groupdocs.viewer.options/pdfviewoptions/optimize/
---
## PdfViewOptions.Optimize property

Kurangi ukuran file keluaran dengan mengecualikan font umum seperti Times New Roman dan Arial, dan menerapkan teknik pengoptimalan lainnya.

```csharp
public bool Optimize { get; set; }
```

### Perkataan

Dalam versi 23.1 opsi ini didukung untuk[Format file lembar bentang](https://docs.groupdocs.com/viewer/net/supported-document-formats/#spreadsheet-file-formats) hanya.

Pelajari lebih lanjut cara mengekspor spreadsheet Excel dan Apple Numbers ke PDF

* [Render spreadsheet sebagai PDF](https://docs.groupdocs.com/viewer/net/render-excel-and-apple-numbers-spreadsheets/#render-spreadsheets-as-pdf)

### Contoh

Contoh menunjukkan penggunaan umum opsi ini.

```csharp
using (var viewer = new Viewer("employees.xlsx"))
{
    PdfViewOptions viewOptions = new PdfViewOptions();
    viewOptions.Optimize = true;

    viewer.View(viewOptions);
}
```

### Lihat juga

* class [PdfViewOptions](../../pdfviewoptions)
* ruang nama [GroupDocs.Viewer.Options](../../pdfviewoptions)
* perakitan [GroupDocs.Viewer](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Viewer.dll -->
