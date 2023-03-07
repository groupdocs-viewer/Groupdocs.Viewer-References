---
title: View
second_title: GroupDocs.Viewer untuk Referensi .NET API
description: Membuat tampilan semua halaman dokumen.
type: docs
weight: 70
url: /id/net/groupdocs.viewer/viewer/view/
---
## View(ViewOptions) {#view}

Membuat tampilan semua halaman dokumen.

```csharp
public void View(ViewOptions options)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| options | ViewOptions | Opsi tampilan. |

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| ArgumentNullException | Dilempar kapan*options* adalah nol. |
| [PasswordRequiredException](../../../groupdocs.viewer.exceptions/passwordrequiredexception) | Dilempar saat kata sandi diperlukan untuk membuka dokumen. |
| [IncorrectPasswordException](../../../groupdocs.viewer.exceptions/incorrectpasswordexception) | Dilempar ketika kata sandi yang ditentukan salah. |
| [GroupDocsViewerException](../../../groupdocs.viewer.exceptions/groupdocsviewerexception) | Dilempar saat lampiran tidak dapat ditemukan. |

### Perkataan

**Belajarlah lagi**

* Lebih lanjut tentang berbagai opsi tampilan mengikuti panduan ini: [Cara menyesuaikan keluaran tampilan dokumen menggunakan GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Viewing)

### Lihat juga

* class [ViewOptions](../../../groupdocs.viewer.options/viewoptions)
* class [Viewer](../../viewer)
* ruang nama [GroupDocs.Viewer](../../viewer)
* perakitan [GroupDocs.Viewer](../../../)

---

## View(ViewOptions, CancellationToken) {#view_2}

Membuat tampilan semua halaman dokumen.

```csharp
public void View(ViewOptions options, CancellationToken cancellationToken)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| options | ViewOptions | Opsi tampilan. |
| cancellationToken | CancellationToken | Token pembatalan untuk mengirim permintaan untuk membatalkan proses tampilan saat ini. |

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| ArgumentNullException | Dilempar kapan*options* adalah nol. |
| [PasswordRequiredException](../../../groupdocs.viewer.exceptions/passwordrequiredexception) | Dilempar saat kata sandi diperlukan untuk membuka dokumen. |
| [IncorrectPasswordException](../../../groupdocs.viewer.exceptions/incorrectpasswordexception) | Dilempar ketika kata sandi yang ditentukan salah. |
| [GroupDocsViewerException](../../../groupdocs.viewer.exceptions/groupdocsviewerexception) | Dilempar saat lampiran tidak dapat ditemukan. |

### Perkataan

**Belajarlah lagi**

* Lebih lanjut tentang berbagai opsi tampilan mengikuti panduan ini: [Cara menyesuaikan keluaran tampilan dokumen menggunakan GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Viewing)

### Lihat juga

* class [ViewOptions](../../../groupdocs.viewer.options/viewoptions)
* class [Viewer](../../viewer)
* ruang nama [GroupDocs.Viewer](../../viewer)
* perakitan [GroupDocs.Viewer](../../../)

---

## View(ViewOptions, params int[]) {#view_1}

Membuat tampilan halaman dokumen tertentu.

```csharp
public void View(ViewOptions options, params int[] pageNumbers)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| options | ViewOptions | Opsi tampilan. |
| pageNumbers | Int32[] | Nomor halaman yang akan dilihat. |

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| ArgumentNullException | Dilempar kapan*options* adalah nol. |
| ArgumentNullException | Dilempar kapan*pageNumbers* adalah nol. |
| ArgumentException | Dilempar kapan*pageNumbers* kosong. |
| [PasswordRequiredException](../../../groupdocs.viewer.exceptions/passwordrequiredexception) | Dilempar saat kata sandi diperlukan untuk membuka dokumen. |
| [IncorrectPasswordException](../../../groupdocs.viewer.exceptions/incorrectpasswordexception) | Dilempar ketika kata sandi yang ditentukan salah. |
| [GroupDocsViewerException](../../../groupdocs.viewer.exceptions/groupdocsviewerexception) | Dilempar saat lampiran tidak dapat ditemukan. |

### Perkataan

**Belajarlah lagi**

* Lebih lanjut tentang berbagai opsi tampilan mengikuti panduan ini: [Cara menyesuaikan keluaran tampilan dokumen menggunakan GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Viewing)

### Lihat juga

* class [ViewOptions](../../../groupdocs.viewer.options/viewoptions)
* class [Viewer](../../viewer)
* ruang nama [GroupDocs.Viewer](../../viewer)
* perakitan [GroupDocs.Viewer](../../../)

---

## View(ViewOptions, CancellationToken, params int[]) {#view_3}

Membuat tampilan halaman dokumen tertentu.

```csharp
public void View(ViewOptions options, CancellationToken cancellationToken, params int[] pageNumbers)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| options | ViewOptions | Opsi tampilan. |
| pageNumbers | CancellationToken | Nomor halaman yang akan dilihat. |
| cancellationToken | Int32[] | Token pembatalan untuk membatalkan pemrosesan. |

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| ArgumentNullException | Dilempar kapan*options* adalah nol. |
| ArgumentNullException | Dilempar kapan*pageNumbers* adalah nol. |
| ArgumentException | Dilempar kapan*pageNumbers* kosong. |
| [PasswordRequiredException](../../../groupdocs.viewer.exceptions/passwordrequiredexception) | Dilempar saat kata sandi diperlukan untuk membuka dokumen. |
| [IncorrectPasswordException](../../../groupdocs.viewer.exceptions/incorrectpasswordexception) | Dilempar ketika kata sandi yang ditentukan salah. |
| [GroupDocsViewerException](../../../groupdocs.viewer.exceptions/groupdocsviewerexception) | Dilempar saat lampiran tidak dapat ditemukan. |

### Perkataan

**Belajarlah lagi**

* Lebih lanjut tentang berbagai opsi tampilan mengikuti panduan ini: [Cara menyesuaikan keluaran tampilan dokumen menggunakan GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Viewing)

### Lihat juga

* class [ViewOptions](../../../groupdocs.viewer.options/viewoptions)
* class [Viewer](../../viewer)
* ruang nama [GroupDocs.Viewer](../../viewer)
* perakitan [GroupDocs.Viewer](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Viewer.dll -->
