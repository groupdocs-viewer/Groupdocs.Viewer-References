---
title: "ForEmbeddedResources"
second_title: "Referensi API GroupDocs.Viewer untuk .NET"
description: "Menginisialisasi sebuah instance dari kelas HtmlViewOptionsgroupdocs.viewer.options/htmlviewoptions untuk merender ke HTML dengan sumber daya tersemat."
type: docs
weight: 10
url: /id/net/groupdocs.viewer.options/htmlviewoptions/forembeddedresources/
---

## ForEmbeddedResources(CreatePageStream) {#forembeddedresources_1}

Menginisialisasi sebuah instance dari kelas [`HtmlViewOptions`](../../htmlviewoptions) untuk merender ke HTML dengan sumber daya tersemat.

```csharp
public static HtmlViewOptions ForEmbeddedResources(CreatePageStream createPageStream)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| createPageStream | CreatePageStream | Metode yang menginstansiasi stream yang digunakan untuk menulis data halaman output. |

### Nilai Kembali

Instance baru dari kelas [`HtmlViewOptions`](../../htmlviewoptions) untuk merender ke HTML dengan sumber daya tersemat.

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| ArgumentNullException | Dilempar ketika *createPageStream* bernilai null. |

### Catatan

Untuk contoh kode, lihat [dokumentasi](https://docs.groupdocs.com/viewer/net/rendering-to-html/#rendering-to-html-with-embedded-resources).

### Lihat Juga

* delegate [CreatePageStream](../../../groupdocs.viewer.interfaces/createpagestream)
* class [HtmlViewOptions](../../htmlviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

---

## ForEmbeddedResources(CreatePageStream, ReleasePageStream) {#forembeddedresources_2}

Menginisialisasi sebuah instance dari kelas [`HtmlViewOptions`](../../htmlviewoptions) untuk merender ke HTML dengan sumber daya tersemat.

```csharp
public static HtmlViewOptions ForEmbeddedResources(CreatePageStream createPageStream, 
    ReleasePageStream releasePageStream)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| createPageStream | CreatePageStream | Metode yang menginstansiasi stream yang digunakan untuk menulis data halaman output. |
| releasePageStream | ReleasePageStream | Metode yang melepaskan aliran yang dibuat oleh metode yang ditetapkan ke delegasi yang diteruskan ke parameter *createPageStream*. |

### Nilai Kembali

Instance baru dari kelas [`HtmlViewOptions`](../../htmlviewoptions) untuk merender ke HTML dengan sumber daya tersemat.

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| ArgumentNullException | Dilempar ketika *createPageStream* bernilai null. |
| ArgumentNullException | Dilempar ketika *releasePageStream* bernilai null. |

### Catatan

Untuk contoh kode, lihat [dokumentasi](https://docs.groupdocs.com/viewer/net/rendering-to-html/#rendering-to-html-with-embedded-resources).

### Lihat Juga

* delegate [CreatePageStream](../../../groupdocs.viewer.interfaces/createpagestream)
* delegate [ReleasePageStream](../../../groupdocs.viewer.interfaces/releasepagestream)
* class [HtmlViewOptions](../../htmlviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

---

## ForEmbeddedResources(IPageStreamFactory) {#forembeddedresources_3}

Menginisialisasi sebuah instance dari kelas [`HtmlViewOptions`](../../htmlviewoptions) untuk merender ke HTML dengan sumber daya tersemat.

```csharp
public static HtmlViewOptions ForEmbeddedResources(IPageStreamFactory pageStreamFactory)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pageStreamFactory | IPageStreamFactory | Fabrik yang mengimplementasikan metode untuk membuat dan melepaskan aliran halaman output. |

### Nilai Kembali

Instance baru dari kelas [`HtmlViewOptions`](../../htmlviewoptions) untuk merender ke HTML dengan sumber daya tersemat.

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| ArgumentNullException | Dilempar ketika *pageStreamFactory* bernilai null. |

### Catatan

Untuk contoh kode, lihat [dokumentasi](https://docs.groupdocs.com/viewer/net/rendering-to-html/#rendering-to-html-with-embedded-resources).

### Lihat Juga

* interface [IPageStreamFactory](../../../groupdocs.viewer.interfaces/ipagestreamfactory)
* class [HtmlViewOptions](../../htmlviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

---

## ForEmbeddedResources() {#forembeddedresources}

Menginisialisasi sebuah instansi dari kelas [`HtmlViewOptions`](../../htmlviewoptions).

```csharp
public static HtmlViewOptions ForEmbeddedResources()
```

### Catatan

Untuk contoh kode, lihat [dokumentasi](https://docs.groupdocs.com/viewer/net/rendering-to-html/#rendering-to-html-with-embedded-resources).

### Lihat Juga

* class [HtmlViewOptions](../../htmlviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

---

## ForEmbeddedResources(string) {#forembeddedresources_4}

Menginisialisasi sebuah instansi dari kelas [`HtmlViewOptions`](../../htmlviewoptions).

```csharp
public static HtmlViewOptions ForEmbeddedResources(string filePathFormat)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| filePathFormat | String | Format jalur file, misalnya 'page_{0}.html'. |

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| ArgumentException | Dilempar ketika *filePathFormat* bernilai null atau kosong. |

### Catatan

Untuk contoh kode, lihat [dokumentasi](https://docs.groupdocs.com/viewer/net/rendering-to-html/#rendering-to-html-with-embedded-resources).

### Lihat Juga

* class [HtmlViewOptions](../../htmlviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Viewer.dll -->
