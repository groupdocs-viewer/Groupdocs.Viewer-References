---
title: Viewer
second_title: GroupDocs.Viewer untuk Referensi .NET API
description: Menginisialisasi instance baruViewergroupdocs.viewer/viewer kelas.
type: docs
weight: 10
url: /id/net/groupdocs.viewer/viewer/viewer/
---
## Viewer(Func&lt;Stream&gt;) {#constructor}

Menginisialisasi instance baru[`Viewer`](../../viewer) kelas.

```csharp
public Viewer(Func<Stream> getFileStream)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| getFileStream | Func`1 | Metode yang mengembalikan aliran yang dapat dibaca. |

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| ArgumentNullException | Dilempar kapan*getFileStream* adalah nol. |

### Perkataan

**Belajarlah lagi**

* Lebih lanjut tentang jenis file yang didukung oleh GroupDocs.Viewer: [Format dokumen didukung oleh GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* Lebih lanjut tentang GroupDocs.Viewer untuk fitur .NET: [Panduan Pengembang](https://docs.groupdocs.com/display/viewernet/Developer+Guide)

### Lihat juga

* class [Viewer](../../viewer)
* ruang nama [GroupDocs.Viewer](../../viewer)
* perakitan [GroupDocs.Viewer](../../../)

---

## Viewer(Func&lt;Stream&gt;, Func&lt;LoadOptions&gt;) {#constructor_2}

Menginisialisasi instance baru[`Viewer`](../../viewer) kelas.

```csharp
public Viewer(Func<Stream> getFileStream, Func<LoadOptions> getLoadOptions)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| getFileStream | Func`1 | Metode yang mengembalikan aliran yang dapat dibaca. |
| getLoadOptions | Func`1 | Metode yang mengembalikan opsi pemuatan dokumen. |

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| ArgumentNullException | Dilempar kapan*getFileStream* adalah nol. |
| ArgumentNullException | Dilempar kapan*getLoadOptions* adalah nol. |

### Perkataan

**Belajarlah lagi**

* Lebih lanjut tentang jenis file yang didukung oleh GroupDocs.Viewer: [Format dokumen didukung oleh GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* Lebih lanjut tentang GroupDocs.Viewer untuk fitur .NET: [Panduan Pengembang](https://docs.groupdocs.com/display/viewernet/Developer+Guide)
* Lebih lanjut tentang memuat dokumen terenkripsi dan melihat file dari penyimpanan pihak ketiga dengan GroupDocs.Viewer untuk .NET: [Cara memuat dan melihat dokumen dengan GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Loading)

### Lihat juga

* class [LoadOptions](../../../groupdocs.viewer.options/loadoptions)
* class [Viewer](../../viewer)
* ruang nama [GroupDocs.Viewer](../../viewer)
* perakitan [GroupDocs.Viewer](../../../)

---

## Viewer(Func&lt;Stream&gt;, ViewerSettings) {#constructor_1}

Menginisialisasi instance baru[`Viewer`](../../viewer) kelas.

```csharp
public Viewer(Func<Stream> getFileStream, ViewerSettings settings)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| getFileStream | Func`1 | Metode yang mengembalikan aliran yang dapat dibaca. |
| settings | ViewerSettings | Pengaturan Penampil. |

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| ArgumentNullException | Dilempar kapan*getFileStream* adalah nol. |
| ArgumentNullException | Dilempar kapan*settings* adalah nol. |

### Perkataan

**Belajarlah lagi**

* Lebih lanjut tentang jenis file yang didukung oleh GroupDocs.Viewer: [Format dokumen didukung oleh GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* Lebih lanjut tentang GroupDocs.Viewer untuk fitur .NET: [Panduan Pengembang](https://docs.groupdocs.com/display/viewernet/Developer+Guide)

### Lihat juga

* class [ViewerSettings](../../viewersettings)
* class [Viewer](../../viewer)
* ruang nama [GroupDocs.Viewer](../../viewer)
* perakitan [GroupDocs.Viewer](../../../)

---

## Viewer(Func&lt;Stream&gt;, Func&lt;LoadOptions&gt;, ViewerSettings) {#constructor_3}

Menginisialisasi instance baru[`Viewer`](../../viewer) kelas.

```csharp
public Viewer(Func<Stream> getFileStream, Func<LoadOptions> getLoadOptions, ViewerSettings settings)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| getFileStream | Func`1 | Metode yang mengembalikan aliran yang dapat dibaca. |
| getLoadOptions | Func`1 | Metode yang mengembalikan opsi pemuatan dokumen. |
| settings | ViewerSettings | Pengaturan Penampil. |

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| ArgumentNullException | Dilempar kapan*getFileStream* adalah nol. |
| ArgumentNullException | Dilempar kapan*getLoadOptions* adalah nol. |
| ArgumentNullException | Dilempar kapan*settings* adalah nol. |

### Perkataan

**Belajarlah lagi**

* Lebih lanjut tentang jenis file yang didukung oleh GroupDocs.Viewer: [Format dokumen didukung oleh GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* Lebih lanjut tentang GroupDocs.Viewer untuk fitur .NET: [Panduan Pengembang](https://docs.groupdocs.com/display/viewernet/Developer+Guide)
* Lebih lanjut tentang memuat dokumen terenkripsi dan melihat file dari penyimpanan pihak ketiga dengan GroupDocs.Viewer untuk .NET: [Cara memuat dan melihat dokumen dengan GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Loading)

### Lihat juga

* class [LoadOptions](../../../groupdocs.viewer.options/loadoptions)
* class [ViewerSettings](../../viewersettings)
* class [Viewer](../../viewer)
* ruang nama [GroupDocs.Viewer](../../viewer)
* perakitan [GroupDocs.Viewer](../../../)

---

## Viewer(Stream) {#constructor_4}

Menginisialisasi instance baru[`Viewer`](../../viewer) kelas.

```csharp
public Viewer(Stream stream)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| stream | Stream | Aliran file. |

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| ArgumentNullException | Dilempar kapan*stream* adalah nol. |

### Perkataan

**Belajarlah lagi**

* Lebih lanjut tentang jenis file yang didukung oleh GroupDocs.Viewer: [Format dokumen didukung oleh GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* Lebih lanjut tentang GroupDocs.Viewer untuk fitur .NET: [Panduan Pengembang](https://docs.groupdocs.com/display/viewernet/Developer+Guide)

### Lihat juga

* class [Viewer](../../viewer)
* ruang nama [GroupDocs.Viewer](../../viewer)
* perakitan [GroupDocs.Viewer](../../../)

---

## Viewer(Stream, bool) {#constructor_5}

Menginisialisasi instance baru[`Viewer`](../../viewer) kelas.

```csharp
public Viewer(Stream stream, bool leaveOpen)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| stream | Stream | Aliran file. |
| leaveOpen | Boolean | BENAR membiarkan aliran terbuka setelah objek Penampil dibuang; jika tidak,PALSU. |

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| ArgumentNullException | Dilempar kapan*stream* adalah nol. |

### Perkataan

**Belajarlah lagi**

* Lebih lanjut tentang jenis file yang didukung oleh GroupDocs.Viewer: [Format dokumen didukung oleh GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* Lebih lanjut tentang GroupDocs.Viewer untuk fitur .NET: [Panduan Pengembang](https://docs.groupdocs.com/display/viewernet/Developer+Guide)

### Lihat juga

* class [Viewer](../../viewer)
* ruang nama [GroupDocs.Viewer](../../viewer)
* perakitan [GroupDocs.Viewer](../../../)

---

## Viewer(Stream, LoadOptions) {#constructor_6}

Menginisialisasi instance baru[`Viewer`](../../viewer) kelas.

```csharp
public Viewer(Stream stream, LoadOptions loadOptions)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| stream | Stream | Aliran file. |
| loadOptions | LoadOptions | Opsi pemuatan dokumen. |

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| ArgumentNullException | Dilempar kapan*stream* adalah nol. |
| ArgumentNullException | Dilempar kapan*loadOptions* adalah nol. |

### Perkataan

**Belajarlah lagi**

* Lebih lanjut tentang jenis file yang didukung oleh GroupDocs.Viewer: [Format dokumen didukung oleh GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* Lebih lanjut tentang GroupDocs.Viewer untuk fitur .NET: [Panduan Pengembang](https://docs.groupdocs.com/display/viewernet/Developer+Guide)
* Lebih lanjut tentang memuat dokumen terenkripsi dan melihat file dari penyimpanan pihak ketiga dengan GroupDocs.Viewer untuk .NET: [Cara memuat dan melihat dokumen dengan GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Loading)

### Lihat juga

* class [LoadOptions](../../../groupdocs.viewer.options/loadoptions)
* class [Viewer](../../viewer)
* ruang nama [GroupDocs.Viewer](../../viewer)
* perakitan [GroupDocs.Viewer](../../../)

---

## Viewer(Stream, LoadOptions, bool) {#constructor_7}

Menginisialisasi instance baru[`Viewer`](../../viewer) kelas.

```csharp
public Viewer(Stream stream, LoadOptions loadOptions, bool leaveOpen)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| stream | Stream | Aliran file. |
| loadOptions | LoadOptions | Opsi pemuatan dokumen. |
| leaveOpen | Boolean | BENAR membiarkan aliran terbuka setelah objek Penampil dibuang; jika tidak,PALSU. |

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| ArgumentNullException | Dilempar kapan*stream* adalah nol. |
| ArgumentNullException | Dilempar kapan*loadOptions* adalah nol. |

### Perkataan

**Belajarlah lagi**

* Lebih lanjut tentang jenis file yang didukung oleh GroupDocs.Viewer: [Format dokumen didukung oleh GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* Lebih lanjut tentang GroupDocs.Viewer untuk fitur .NET: [Panduan Pengembang](https://docs.groupdocs.com/display/viewernet/Developer+Guide)
* Lebih lanjut tentang memuat dokumen terenkripsi dan melihat file dari penyimpanan pihak ketiga dengan GroupDocs.Viewer untuk .NET: [Cara memuat dan melihat dokumen dengan GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Loading)

### Lihat juga

* class [LoadOptions](../../../groupdocs.viewer.options/loadoptions)
* class [Viewer](../../viewer)
* ruang nama [GroupDocs.Viewer](../../viewer)
* perakitan [GroupDocs.Viewer](../../../)

---

## Viewer(Stream, ViewerSettings) {#constructor_10}

Menginisialisasi instance baru[`Viewer`](../../viewer) kelas.

```csharp
public Viewer(Stream stream, ViewerSettings settings)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| stream | Stream | Aliran file. |
| settings | ViewerSettings | Pengaturan Penampil. |

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| ArgumentNullException | Dilempar kapan*stream* adalah nol. |
| ArgumentNullException | Dilempar kapan*settings* adalah nol. |

### Perkataan

**Belajarlah lagi**

* Lebih lanjut tentang jenis file yang didukung oleh GroupDocs.Viewer: [Format dokumen didukung oleh GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* Lebih lanjut tentang GroupDocs.Viewer untuk fitur .NET: [Panduan Pengembang](https://docs.groupdocs.com/display/viewernet/Developer+Guide)

### Lihat juga

* class [ViewerSettings](../../viewersettings)
* class [Viewer](../../viewer)
* ruang nama [GroupDocs.Viewer](../../viewer)
* perakitan [GroupDocs.Viewer](../../../)

---

## Viewer(Stream, ViewerSettings, bool) {#constructor_11}

Menginisialisasi instance baru[`Viewer`](../../viewer) kelas.

```csharp
public Viewer(Stream stream, ViewerSettings settings, bool leaveOpen)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| stream | Stream | Aliran file. |
| settings | ViewerSettings | Pengaturan Penampil. |
| leaveOpen | Boolean | BENAR membiarkan aliran terbuka setelah objek Penampil dibuang; jika tidak,PALSU. |

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| ArgumentNullException | Dilempar kapan*stream* adalah nol. |
| ArgumentNullException | Dilempar kapan*settings* adalah nol. |

### Perkataan

**Belajarlah lagi**

* Lebih lanjut tentang jenis file yang didukung oleh GroupDocs.Viewer: [Format dokumen didukung oleh GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* Lebih lanjut tentang GroupDocs.Viewer untuk fitur .NET: [Panduan Pengembang](https://docs.groupdocs.com/display/viewernet/Developer+Guide)

### Lihat juga

* class [ViewerSettings](../../viewersettings)
* class [Viewer](../../viewer)
* ruang nama [GroupDocs.Viewer](../../viewer)
* perakitan [GroupDocs.Viewer](../../../)

---

## Viewer(Stream, LoadOptions, ViewerSettings) {#constructor_8}

Menginisialisasi instance baru[`Viewer`](../../viewer) kelas.

```csharp
public Viewer(Stream stream, LoadOptions loadOptions, ViewerSettings settings)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| stream | Stream | Aliran file. |
| loadOptions | LoadOptions | Opsi pemuatan dokumen. |
| settings | ViewerSettings | Pengaturan Penampil. |

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| ArgumentNullException | Dilempar kapan*stream* adalah nol. |
| ArgumentNullException | Dilempar kapan*loadOptions* adalah nol. |
| ArgumentNullException | Dilempar kapan*settings* adalah nol. |

### Perkataan

**Belajarlah lagi**

* Lebih lanjut tentang jenis file yang didukung oleh GroupDocs.Viewer: [Format dokumen didukung oleh GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* Lebih lanjut tentang GroupDocs.Viewer untuk fitur .NET: [Panduan Pengembang](https://docs.groupdocs.com/display/viewernet/Developer+Guide)
* Lebih lanjut tentang memuat dokumen terenkripsi dan melihat file dari penyimpanan pihak ketiga dengan GroupDocs.Viewer untuk .NET: [Cara memuat dan melihat dokumen dengan GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Loading)

### Lihat juga

* class [LoadOptions](../../../groupdocs.viewer.options/loadoptions)
* class [ViewerSettings](../../viewersettings)
* class [Viewer](../../viewer)
* ruang nama [GroupDocs.Viewer](../../viewer)
* perakitan [GroupDocs.Viewer](../../../)

---

## Viewer(Stream, LoadOptions, ViewerSettings, bool) {#constructor_9}

Menginisialisasi instance baru[`Viewer`](../../viewer) kelas.

```csharp
public Viewer(Stream stream, LoadOptions loadOptions, ViewerSettings settings, bool leaveOpen)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| stream | Stream | Aliran file. |
| loadOptions | LoadOptions | Opsi pemuatan dokumen. |
| settings | ViewerSettings | Pengaturan Penampil. |
| leaveOpen | Boolean | BENAR membiarkan aliran terbuka setelah objek Penampil dibuang; jika tidak,PALSU. |

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| ArgumentNullException | Dilempar kapan*stream* adalah nol. |
| ArgumentNullException | Dilempar kapan*loadOptions* adalah nol. |
| ArgumentNullException | Dilempar kapan*settings* adalah nol. |

### Perkataan

**Belajarlah lagi**

* Lebih lanjut tentang jenis file yang didukung oleh GroupDocs.Viewer: [Format dokumen didukung oleh GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* Lebih lanjut tentang GroupDocs.Viewer untuk fitur .NET: [Panduan Pengembang](https://docs.groupdocs.com/display/viewernet/Developer+Guide)
* Lebih lanjut tentang memuat dokumen terenkripsi dan melihat file dari penyimpanan pihak ketiga dengan GroupDocs.Viewer untuk .NET: [Cara memuat dan melihat dokumen dengan GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Loading)

### Lihat juga

* class [LoadOptions](../../../groupdocs.viewer.options/loadoptions)
* class [ViewerSettings](../../viewersettings)
* class [Viewer](../../viewer)
* ruang nama [GroupDocs.Viewer](../../viewer)
* perakitan [GroupDocs.Viewer](../../../)

---

## Viewer(string) {#constructor_12}

Menginisialisasi instance baru[`Viewer`](../../viewer) kelas.

```csharp
public Viewer(string filePath)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| filePath | String | Jalur ke file yang akan dirender. |

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| ArgumentException | Dilempar kapan*filePath* adalah null atau kosong. |

### Perkataan

**Belajarlah lagi**

* Lebih lanjut tentang jenis file yang didukung oleh GroupDocs.Viewer: [Format dokumen didukung oleh GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* Lebih lanjut tentang GroupDocs.Viewer untuk fitur .NET: [Panduan Pengembang](https://docs.groupdocs.com/display/viewernet/Developer+Guide)

### Lihat juga

* class [Viewer](../../viewer)
* ruang nama [GroupDocs.Viewer](../../viewer)
* perakitan [GroupDocs.Viewer](../../../)

---

## Viewer(string, ViewerSettings) {#constructor_15}

Menginisialisasi instance baru[`Viewer`](../../viewer) kelas.

```csharp
public Viewer(string filePath, ViewerSettings settings)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| filePath | String | Jalur ke file yang akan dirender. |
| settings | ViewerSettings | Pengaturan Penampil. |

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| ArgumentException | Dilempar kapan*filePath* adalah null atau kosong. |
| ArgumentNullException | Dilempar kapan*settings* adalah nol. |

### Perkataan

**Belajarlah lagi**

* Lebih lanjut tentang jenis file yang didukung oleh GroupDocs.Viewer: [Format dokumen didukung oleh GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* Lebih lanjut tentang GroupDocs.Viewer untuk fitur .NET: [Panduan Pengembang](https://docs.groupdocs.com/display/viewernet/Developer+Guide)

### Lihat juga

* class [ViewerSettings](../../viewersettings)
* class [Viewer](../../viewer)
* ruang nama [GroupDocs.Viewer](../../viewer)
* perakitan [GroupDocs.Viewer](../../../)

---

## Viewer(string, LoadOptions) {#constructor_13}

Menginisialisasi instance baru[`Viewer`](../../viewer) kelas.

```csharp
public Viewer(string filePath, LoadOptions loadOptions)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| filePath | String | Jalur ke file yang akan dirender. |
| loadOptions | LoadOptions | Opsi yang digunakan untuk membuka file. |

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| ArgumentException | Dilempar kapan*filePath* adalah null atau kosong. |
| ArgumentNullException | Dilempar kapan*loadOptions* adalah nol. |

### Perkataan

**Belajarlah lagi**

* Lebih lanjut tentang jenis file yang didukung oleh GroupDocs.Viewer: [Format dokumen didukung oleh GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* Lebih lanjut tentang GroupDocs.Viewer untuk fitur .NET: [Panduan Pengembang](https://docs.groupdocs.com/display/viewernet/Developer+Guide)
* Lebih lanjut tentang memuat dokumen terenkripsi dan melihat file dari penyimpanan pihak ketiga dengan GroupDocs.Viewer untuk .NET: [Cara memuat dan melihat dokumen dengan GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Loading)

### Lihat juga

* class [LoadOptions](../../../groupdocs.viewer.options/loadoptions)
* class [Viewer](../../viewer)
* ruang nama [GroupDocs.Viewer](../../viewer)
* perakitan [GroupDocs.Viewer](../../../)

---

## Viewer(string, LoadOptions, ViewerSettings) {#constructor_14}

Menginisialisasi instance baru[`Viewer`](../../viewer) kelas.

```csharp
public Viewer(string filePath, LoadOptions loadOptions, ViewerSettings settings)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| filePath | String | Jalur ke file yang akan dirender. |
| loadOptions | LoadOptions | Opsi yang digunakan untuk membuka file. |
| settings | ViewerSettings | Pengaturan Penampil. |

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| ArgumentException | Dilempar kapan*filePath* adalah null atau kosong. |
| ArgumentNullException | Dilempar kapan*loadOptions* adalah nol. |
| ArgumentNullException | Dilempar kapan*settings* adalah nol. |

### Perkataan

**Belajarlah lagi**

* Lebih lanjut tentang jenis file yang didukung oleh GroupDocs.Viewer: [Format dokumen didukung oleh GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* Lebih lanjut tentang GroupDocs.Viewer untuk fitur .NET: [Panduan Pengembang](https://docs.groupdocs.com/display/viewernet/Developer+Guide)
* Lebih lanjut tentang memuat dokumen terenkripsi dan melihat file dari penyimpanan pihak ketiga dengan GroupDocs.Viewer untuk .NET: [Cara memuat dan melihat dokumen dengan GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Loading)

### Lihat juga

* class [LoadOptions](../../../groupdocs.viewer.options/loadoptions)
* class [ViewerSettings](../../viewersettings)
* class [Viewer](../../viewer)
* ruang nama [GroupDocs.Viewer](../../viewer)
* perakitan [GroupDocs.Viewer](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Viewer.dll -->
