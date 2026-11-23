---
title: "JpgViewOptions"
second_title: "Referensi API GroupDocs.Viewer untuk .NET"
description: "Menginisialisasi sebuah instance dari kelas JpgViewOptionsgroupdocs.viewer.options/jpgviewoptions."
type: docs
weight: 10
url: /id/net/groupdocs.viewer.options/jpgviewoptions/jpgviewoptions/
---

## JpgViewOptions(CreatePageStream) {#constructor_1}

Menginisialisasi sebuah instance dari kelas [`JpgViewOptions`](../../jpgviewoptions).

```csharp
public JpgViewOptions(CreatePageStream createPageStream)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| createPageStream | CreatePageStream | Metode yang menginstansiasi aliran yang digunakan untuk menulis data halaman output. |

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| ArgumentNullException | Dilempar ketika *createPageStream* bernilai null. |

### Catatan

Untuk contoh kode, lihat [dokumentasi](https://docs.groupdocs.com/viewer/net/rendering-to-png-or-jpeg/#rendering-to-jpeg).

### Lihat Juga

* delegate [CreatePageStream](../../../groupdocs.viewer.interfaces/createpagestream)
* class [JpgViewOptions](../../jpgviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

---

## JpgViewOptions(CreatePageStream, ReleasePageStream) {#constructor_2}

Menginisialisasi sebuah instance dari kelas [`JpgViewOptions`](../../jpgviewoptions).

```csharp
public JpgViewOptions(CreatePageStream createPageStream, ReleasePageStream releasePageStream)
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

Untuk contoh kode, lihat [dokumentasi](https://docs.groupdocs.com/viewer/net/rendering-to-png-or-jpeg/#rendering-to-jpeg).

### Lihat Juga

* delegate [CreatePageStream](../../../groupdocs.viewer.interfaces/createpagestream)
* delegate [ReleasePageStream](../../../groupdocs.viewer.interfaces/releasepagestream)
* class [JpgViewOptions](../../jpgviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

---

## JpgViewOptions(IPageStreamFactory) {#constructor_3}

Menginisialisasi sebuah instance dari kelas [`JpgViewOptions`](../../jpgviewoptions).

```csharp
public JpgViewOptions(IPageStreamFactory pageStreamFactory)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pageStreamFactory | IPageStreamFactory | Fabrik yang mengimplementasikan metode untuk membuat dan melepaskan aliran halaman output. |

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| ArgumentNullException | Dilempar ketika *pageStreamFactory* bernilai null. |

### Catatan

Untuk contoh kode, lihat [dokumentasi](https://docs.groupdocs.com/viewer/net/rendering-to-png-or-jpeg/#rendering-to-jpeg).

### Lihat Juga

* interface [IPageStreamFactory](../../../groupdocs.viewer.interfaces/ipagestreamfactory)
* class [JpgViewOptions](../../jpgviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

---

## JpgViewOptions() {#constructor}

Menginisialisasi sebuah instance dari kelas [`JpgViewOptions`](../../jpgviewoptions).

```csharp
public JpgViewOptions()
```

### Catatan

Konstruktor ini menginisialisasi sebuah instance dari [`JpgViewOptions`](../../jpgviewoptions) dengan "p_{0}.jpg" sebagai format jalur file untuk file output. File output ditempatkan di direktori kerja saat ini dari aplikasi.

Untuk contoh kode, lihat [dokumentasi](https://docs.groupdocs.com/viewer/net/rendering-to-png-or-jpeg/#rendering-to-jpeg).

### Lihat Juga

* class [JpgViewOptions](../../jpgviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

---

## JpgViewOptions(string) {#constructor_4}

Menginisialisasi sebuah instance dari kelas [`JpgViewOptions`](../../jpgviewoptions).

```csharp
public JpgViewOptions(string filePathFormat)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| filePathFormat | String | Format jalur file, misalnya 'page_{0}.jpg'. |

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| ArgumentException | Dilempar ketika *filePathFormat* bernilai null atau kosong. |

### Catatan

Untuk contoh kode, lihat [dokumentasi](https://docs.groupdocs.com/viewer/net/rendering-to-png-or-jpeg/#rendering-to-jpeg).

### Lihat Juga

* class [JpgViewOptions](../../jpgviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Viewer.dll -->
