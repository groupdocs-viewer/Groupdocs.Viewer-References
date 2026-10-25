---
title: "PngViewOptions"
second_title: "Referensi API GroupDocs.Viewer untuk .NET"
description: "Menginisialisasi sebuah instance dari kelas PngViewOptionsgroupdocs.viewer.options/pngviewoptions."
type: docs
weight: 10
url: /id/net/groupdocs.viewer.options/pngviewoptions/pngviewoptions/
---

## PngViewOptions(CreatePageStream) {#constructor_1}

Menginisialisasi sebuah instance dari kelas [`PngViewOptions`](../../pngviewoptions).

```csharp
public PngViewOptions(CreatePageStream createPageStream)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| createPageStream | CreatePageStream | Metode yang menginstansiasi aliran yang digunakan untuk menulis data halaman output. |

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| ArgumentNullException | Dilempar ketika *createPageStream* bernilai null. |

### Catatan

Untuk contoh kode, lihat [dokumentasi](https://docs.groupdocs.com/viewer/net/rendering-to-png-or-jpeg/#rendering-to-png).

### Lihat Juga

* delegate [CreatePageStream](../../../groupdocs.viewer.interfaces/createpagestream)
* class [PngViewOptions](../../pngviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

---

## PngViewOptions(CreatePageStream, ReleasePageStream) {#constructor_2}

Menginisialisasi sebuah instance dari kelas [`PngViewOptions`](../../pngviewoptions).

```csharp
public PngViewOptions(CreatePageStream createPageStream, ReleasePageStream releasePageStream)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| createPageStream | CreatePageStream | Metode yang menginstansiasi aliran yang digunakan untuk menulis data halaman output. |
| releasePageStream | ReleasePageStream | Metode yang melepaskan aliran yang dibuat oleh metode yang ditetapkan ke delegasi yang diberikan ke parameter *createPageStream*. |

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| ArgumentNullException | Dilempar ketika *createPageStream* bernilai null. |
| ArgumentNullException | Dilempar ketika *releasePageStream* bernilai null. |

### Catatan

Untuk contoh kode, lihat [dokumentasi](https://docs.groupdocs.com/viewer/net/rendering-to-png-or-jpeg/#rendering-to-png).

### Lihat Juga

* delegate [CreatePageStream](../../../groupdocs.viewer.interfaces/createpagestream)
* delegate [ReleasePageStream](../../../groupdocs.viewer.interfaces/releasepagestream)
* class [PngViewOptions](../../pngviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

---

## PngViewOptions(IPageStreamFactory) {#constructor_3}

Menginisialisasi sebuah instance dari kelas [`PngViewOptions`](../../pngviewoptions).

```csharp
public PngViewOptions(IPageStreamFactory pageStreamFactory)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pageStreamFactory | IPageStreamFactory | Fabrik yang mengimplementasikan metode untuk membuat dan melepaskan aliran halaman output. |

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| ArgumentNullException | Dilempar ketika *pageStreamFactory* bernilai null. |

### Catatan

Untuk contoh kode, lihat [dokumentasi](https://docs.groupdocs.com/viewer/net/rendering-to-png-or-jpeg/#rendering-to-png).

### Lihat Juga

* interface [IPageStreamFactory](../../../groupdocs.viewer.interfaces/ipagestreamfactory)
* class [PngViewOptions](../../pngviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

---

## PngViewOptions() {#constructor}

Menginisialisasi sebuah instance dari kelas [`PngViewOptions`](../../pngviewoptions).

```csharp
public PngViewOptions()
```

### Catatan

Konstruktor ini menginisialisasi sebuah instance dari [`PngViewOptions`](../../pngviewoptions) dengan "p_{0}.png" sebagai format jalur file untuk file output. File output ditempatkan di direktori kerja saat ini dari aplikasi.

Untuk contoh kode, lihat [dokumentasi](https://docs.groupdocs.com/viewer/net/rendering-to-png-or-jpeg/#rendering-to-png).

### Lihat Juga

* class [PngViewOptions](../../pngviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

---

## PngViewOptions(string) {#constructor_4}

Menginisialisasi sebuah instance dari kelas [`PngViewOptions`](../../pngviewoptions).

```csharp
public PngViewOptions(string filePathFormat)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| filePathFormat | String | Format jalur file, misalnya 'page_{0}.png'. |

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| ArgumentException | Dilempar ketika *filePathFormat* bernilai null atau kosong. |

### Catatan

Untuk contoh kode, lihat [dokumentasi](https://docs.groupdocs.com/viewer/net/rendering-to-png-or-jpeg/#rendering-to-png).

### Lihat Juga

* class [PngViewOptions](../../pngviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Viewer.dll -->
