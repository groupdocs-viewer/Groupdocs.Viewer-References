---
title: "View"
second_title: "Referensi API GroupDocs.Viewer untuk .NET"
description: "Membuat tampilan semua halaman dokumen."
type: docs
weight: 90
url: /id/net/groupdocs.viewer/viewer/view/
---

## View(ViewOptions) {#view}

Membuat tampilan semua halaman dokumen.

```csharp
public void View(ViewOptions options)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| opsi | ViewOptions | Opsi tampilan. |

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| ArgumentNullException | Dilemparkan ketika *options* bernilai null. |
| [PasswordRequiredException](../../../groupdocs.viewer.exceptions/passwordrequiredexception) | Dilempar ketika kata sandi diperlukan untuk membuka dokumen. |
| [IncorrectPasswordException](../../../groupdocs.viewer.exceptions/incorrectpasswordexception) | Dilempar ketika kata sandi yang ditentukan tidak benar. |
| [GroupDocsViewerException](../../../groupdocs.viewer.exceptions/groupdocsviewerexception) | Dilemparkan ketika lampiran tidak dapat ditemukan. |

### Catatan

**Learn more**

* More about different viewing options following this guide: [How to customize document viewing output using GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Viewing)

### Lihat Juga

* class [ViewOptions](../../../groupdocs.viewer.options/viewoptions)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## View(ViewOptions, CancellationToken) {#view_2}

Membuat tampilan semua halaman dokumen.

```csharp
public void View(ViewOptions options, CancellationToken cancellationToken)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| opsi | ViewOptions | Opsi tampilan. |
| cancellationToken | CancellationToken | Token pembatalan untuk mengirim permintaan membatalkan proses tampilan saat ini. |

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| ArgumentNullException | Dilemparkan ketika *options* bernilai null. |
| [PasswordRequiredException](../../../groupdocs.viewer.exceptions/passwordrequiredexception) | Dilempar ketika kata sandi diperlukan untuk membuka dokumen. |
| [IncorrectPasswordException](../../../groupdocs.viewer.exceptions/incorrectpasswordexception) | Dilempar ketika kata sandi yang ditentukan tidak benar. |
| [GroupDocsViewerException](../../../groupdocs.viewer.exceptions/groupdocsviewerexception) | Dilemparkan ketika lampiran tidak dapat ditemukan. |

### Catatan

**Learn more**

* More about different viewing options following this guide: [How to customize document viewing output using GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Viewing)

### Lihat Juga

* class [ViewOptions](../../../groupdocs.viewer.options/viewoptions)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## View(ViewOptions, params int[]) {#view_1}

Membuat tampilan halaman dokumen tertentu.

```csharp
public void View(ViewOptions options, params int[] pageNumbers)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| opsi | ViewOptions | Opsi tampilan. |
| pageNumbers | Int32[] | Nomor halaman untuk dilihat. |

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| ArgumentNullException | Dilemparkan ketika *options* bernilai null. |
| ArgumentNullException | Dilempar ketika *pageNumbers* bernilai null. |
| ArgumentException | Dilempar ketika *pageNumbers* kosong. |
| [PasswordRequiredException](../../../groupdocs.viewer.exceptions/passwordrequiredexception) | Dilempar ketika kata sandi diperlukan untuk membuka dokumen. |
| [IncorrectPasswordException](../../../groupdocs.viewer.exceptions/incorrectpasswordexception) | Dilempar ketika kata sandi yang ditentukan tidak benar. |
| [GroupDocsViewerException](../../../groupdocs.viewer.exceptions/groupdocsviewerexception) | Dilemparkan ketika lampiran tidak dapat ditemukan. |

### Catatan

**Learn more**

* More about different viewing options following this guide: [How to customize document viewing output using GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Viewing)

### Lihat Juga

* class [ViewOptions](../../../groupdocs.viewer.options/viewoptions)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## View(ViewOptions, CancellationToken, params int[]) {#view_3}

Membuat tampilan halaman dokumen tertentu.

```csharp
public void View(ViewOptions options, CancellationToken cancellationToken, params int[] pageNumbers)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| opsi | ViewOptions | Opsi tampilan. |
| pageNumbers | CancellationToken | Nomor halaman untuk dilihat. |
| cancellationToken | Int32[] | Token pembatalan untuk menghentikan pemrosesan. |

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| ArgumentNullException | Dilemparkan ketika *options* bernilai null. |
| ArgumentNullException | Dilempar ketika *pageNumbers* bernilai null. |
| ArgumentException | Dilempar ketika *pageNumbers* kosong. |
| [PasswordRequiredException](../../../groupdocs.viewer.exceptions/passwordrequiredexception) | Dilempar ketika kata sandi diperlukan untuk membuka dokumen. |
| [IncorrectPasswordException](../../../groupdocs.viewer.exceptions/incorrectpasswordexception) | Dilempar ketika kata sandi yang ditentukan tidak benar. |
| [GroupDocsViewerException](../../../groupdocs.viewer.exceptions/groupdocsviewerexception) | Dilemparkan ketika lampiran tidak dapat ditemukan. |

### Catatan

**Learn more**

* More about different viewing options following this guide: [How to customize document viewing output using GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Viewing)

### Lihat Juga

* class [ViewOptions](../../../groupdocs.viewer.options/viewoptions)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Viewer.dll -->
