---
title: "Page"
second_title: "Referensi API GroupDocs.Viewer untuk .NET"
description: "Menginisialisasi instance baru dari kelas Pagegroupdocs.viewer.results/page."
type: docs
weight: 10
url: /id/net/groupdocs.viewer.results/page/page/
---

## Page() {#constructor}

Menginisialisasi instance baru dari kelas [`Page`](../../page).

```csharp
public Page()
```

### Lihat Juga

* class [Page](../../page)
* namespace [GroupDocs.Viewer.Results](../../../groupdocs.viewer.results)
* assembly [GroupDocs.Viewer](../../../)

---

## Page(int, bool) {#constructor_1}

Menginisialisasi instance baru dari kelas [`Page`](../../page).

```csharp
public Page(int number, bool visible)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| number | Int32 | Nomor halaman. |
| visible | Boolean | Indikator visibilitas halaman. |

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| ArgumentException | Dilempar ketika *number* kurang dari atau sama dengan nol. |

### Lihat Juga

* class [Page](../../page)
* namespace [GroupDocs.Viewer.Results](../../../groupdocs.viewer.results)
* assembly [GroupDocs.Viewer](../../../)

---

## Page(int, string, bool) {#constructor_4}

Menginisialisasi instance baru dari kelas [`Page`](../../page).

```csharp
public Page(int number, string name, bool visible)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| number | Int32 | Nomor halaman. |
| nama | String | Nama lembar kerja atau halaman. |
| visible | Boolean | Indikator visibilitas halaman. |

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| ArgumentException | Dilempar ketika *number* kurang dari atau sama dengan nol. |

### Lihat Juga

* class [Page](../../page)
* namespace [GroupDocs.Viewer.Results](../../../groupdocs.viewer.results)
* assembly [GroupDocs.Viewer](../../../)

---

## Page(int, bool, int, int) {#constructor_2}

Menginisialisasi instance baru dari kelas [`Page`](../../page).

```csharp
public Page(int number, bool visible, int width, int height)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| number | Int32 | Nomor halaman. |
| visible | Boolean | Indikator visibilitas halaman. |
| width | Int32 | Lebar halaman dalam piksel saat ditampilkan sebagai JPG atau PNG. |
| height | Int32 | Tinggi halaman dalam piksel saat ditampilkan sebagai JPG atau PNG. |

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| ArgumentException | Dilempar ketika *number* kurang dari atau sama dengan nol. |
| ArgumentException | Dilempar ketika *width* kurang dari atau sama dengan nol. |
| ArgumentException | Dilempar ketika *height* kurang dari atau sama dengan nol. |

### Lihat Juga

* class [Page](../../page)
* namespace [GroupDocs.Viewer.Results](../../../groupdocs.viewer.results)
* assembly [GroupDocs.Viewer](../../../)

---

## Page(int, string, bool, int, int) {#constructor_5}

Menginisialisasi instance baru dari kelas [`Page`](../../page).

```csharp
public Page(int number, string name, bool visible, int width, int height)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| number | Int32 | Nomor halaman. |
| nama | String | Nama lembar kerja atau halaman. |
| visible | Boolean | Indikator visibilitas halaman. |
| width | Int32 | Lebar halaman dalam piksel saat ditampilkan sebagai JPG atau PNG. |
| height | Int32 | Tinggi halaman dalam piksel saat ditampilkan sebagai JPG atau PNG. |

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| ArgumentException | Dilempar ketika *number* kurang dari atau sama dengan nol. |
| ArgumentException | Dilempar ketika *width* kurang dari atau sama dengan nol. |
| ArgumentException | Dilempar ketika *height* kurang dari atau sama dengan nol. |

### Lihat Juga

* class [Page](../../page)
* namespace [GroupDocs.Viewer.Results](../../../groupdocs.viewer.results)
* assembly [GroupDocs.Viewer](../../../)

---

## Page(int, bool, int, int, List&lt;Line&gt;) {#constructor_3}

Menginisialisasi instance baru dari kelas [`Page`](../../page).

```csharp
public Page(int number, bool visible, int width, int height, List<Line> lines)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| number | Int32 | Nomor halaman. |
| visible | Boolean | Indikator visibilitas halaman. |
| width | Int32 | Lebar halaman dalam piksel saat ditampilkan sebagai JPG atau PNG. |
| height | Int32 | Tinggi halaman dalam piksel saat ditampilkan sebagai JPG atau PNG. |
| lines | List`1 | Baris yang terdapat pada halaman saat ditampilkan sebagai JPG atau PNG dengan Ekstraksi Teks diaktifkan. |

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| ArgumentException | Dilempar ketika *number* kurang dari atau sama dengan nol. |
| ArgumentException | Dilempar ketika *width* kurang dari atau sama dengan nol. |
| ArgumentException | Dilempar ketika *height* kurang dari atau sama dengan nol. |
| ArgumentNullException | Dilempar ketika *lines* bernilai null. |

### Lihat Juga

* class [Line](../../line)
* class [Page](../../page)
* namespace [GroupDocs.Viewer.Results](../../../groupdocs.viewer.results)
* assembly [GroupDocs.Viewer](../../../)

---

## Page(int, string, bool, int, int, List&lt;Line&gt;) {#constructor_6}

Menginisialisasi instance baru dari kelas [`Page`](../../page).

```csharp
public Page(int number, string name, bool visible, int width, int height, List<Line> lines)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| number | Int32 | Nomor halaman. |
| nama | String | Nama lembar kerja atau halaman. |
| visible | Boolean | Indikator visibilitas halaman. |
| width | Int32 | Lebar halaman dalam piksel saat ditampilkan sebagai JPG atau PNG. |
| height | Int32 | Tinggi halaman dalam piksel saat ditampilkan sebagai JPG atau PNG. |
| lines | List`1 | Baris yang terdapat pada halaman saat ditampilkan sebagai JPG atau PNG dengan Ekstraksi Teks diaktifkan. |

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| ArgumentException | Dilempar ketika *number* kurang dari atau sama dengan nol. |
| ArgumentException | Dilempar ketika *width* kurang dari atau sama dengan nol. |
| ArgumentException | Dilempar ketika *height* kurang dari atau sama dengan nol. |
| ArgumentNullException | Dilempar ketika *lines* bernilai null. |

### Lihat Juga

* class [Line](../../line)
* class [Page](../../page)
* namespace [GroupDocs.Viewer.Results](../../../groupdocs.viewer.results)
* assembly [GroupDocs.Viewer](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Viewer.dll -->
