---
title: RotatePage
second_title: GroupDocs.Viewer untuk Referensi .NET API
description: Menerapkan rotasi searah jarum jam ke halaman.
type: docs
weight: 30
url: /id/net/groupdocs.viewer.options/viewoptions/rotatepage/
---
## ViewOptions.RotatePage method

Menerapkan rotasi searah jarum jam ke halaman.

```csharp
public void RotatePage(int pageNumber, Rotation rotation)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| pageNumber | Int32 | Nomor halaman. |
| rotation | Rotation | Nilai rotasi. |

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| ArgumentException | Dilempar kapan*pageNumber* kurang atau sama dengan nol. |
| ArgumentException | Dilempar saat rotasi untuk halaman dengan nomor*pageNumber* sudah ditambahkan. |

### Lihat juga

* enum [Rotation](../../rotation)
* class [ViewOptions](../../viewoptions)
* ruang nama [GroupDocs.Viewer.Options](../../viewoptions)
* perakitan [GroupDocs.Viewer](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Viewer.dll -->