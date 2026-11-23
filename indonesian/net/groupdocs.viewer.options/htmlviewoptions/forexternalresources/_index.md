---
title: "ForExternalResources"
second_title: "Referensi API GroupDocs.Viewer untuk .NET"
description: "Menginisialisasi instance dari kelas HtmlViewOptionsgroupdocs.viewer.options/htmlviewoptions untuk merender ke HTML dengan sumber daya eksternal."
type: docs
weight: 20
url: /id/net/groupdocs.viewer.options/htmlviewoptions/forexternalresources/
---

## ForExternalResources(CreatePageStream, CreateResourceStream, CreateResourceUrl) {#forexternalresources_1}

Menginisialisasi instance dari kelas [`HtmlViewOptions`](../../htmlviewoptions) untuk merender ke HTML dengan sumber daya eksternal.

```csharp
public static HtmlViewOptions ForExternalResources(CreatePageStream createPageStream, 
    CreateResourceStream createResourceStream, CreateResourceUrl createResourceUrl)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| createPageStream | CreatePageStream | Metode yang menginstansiasi stream yang digunakan untuk menulis data halaman output. |
| createResourceStream | CreateResourceStream | Metode yang melepaskan stream yang dibuat oleh metode *createPageStream*. |
| createResourceUrl | CreateResourceUrl | Metode yang membuat URL untuk sumber daya HTML. |

### Nilai Kembali

Instansi baru dari kelas [`HtmlViewOptions`](../../htmlviewoptions) untuk merender ke HTML dengan sumber daya eksternal.

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| ArgumentNullException | Dilempar ketika *createPageStream* bernilai null. |
| ArgumentNullException | Dilempar ketika *createResourceStream* bernilai null. |
| ArgumentNullException | Dilempar ketika *createResourceUrl* bernilai null. |

### Catatan

Untuk contoh kode, lihat [dokumentasi](https://docs.groupdocs.com/viewer/net/rendering-to-html/#rendering-to-html-with-external-resources).

### Lihat Juga

* delegate [CreatePageStream](../../../groupdocs.viewer.interfaces/createpagestream)
* delegate [CreateResourceStream](../../../groupdocs.viewer.interfaces/createresourcestream)
* delegate [CreateResourceUrl](../../../groupdocs.viewer.interfaces/createresourceurl)
* class [HtmlViewOptions](../../htmlviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

---

## ForExternalResources(CreatePageStream, CreateResourceStream, CreateResourceUrl, ReleasePageStream, ReleaseResourceStream) {#forexternalresources_2}

Menginisialisasi instance dari kelas [`HtmlViewOptions`](../../htmlviewoptions) untuk merender ke HTML dengan sumber daya eksternal.

```csharp
public static HtmlViewOptions ForExternalResources(CreatePageStream createPageStream, 
    CreateResourceStream createResourceStream, CreateResourceUrl createResourceUrl, 
    ReleasePageStream releasePageStream, ReleaseResourceStream releaseResourceStream)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| createPageStream | CreatePageStream | Metode yang menginstansiasi stream yang digunakan untuk menulis data halaman output. |
| createResourceStream | CreateResourceStream | Metode yang menginstansiasi aliran yang digunakan untuk menulis data sumber daya HTML output. |
| createResourceUrl | CreateResourceUrl | Metode yang membuat URL untuk sumber daya HTML. |
| releasePageStream | ReleasePageStream | Metode yang melepaskan aliran yang dibuat oleh metode yang ditetapkan ke delegasi yang diteruskan ke parameter *createPageStream*. |
| releaseResourceStream | ReleaseResourceStream | Metode yang melepaskan aliran yang dibuat oleh metode yang ditetapkan ke delegasi yang diteruskan ke parameter *createResourceStream*. |

### Nilai Kembali

Instansi baru dari kelas [`HtmlViewOptions`](../../htmlviewoptions) untuk merender ke HTML dengan sumber daya eksternal.

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| ArgumentNullException | Dilempar ketika *createPageStream* bernilai null. |
| ArgumentNullException | Dilempar ketika *createResourceStream* bernilai null. |
| ArgumentNullException | Dilempar ketika *createResourceUrl* bernilai null. |
| ArgumentNullException | Dilempar ketika *releasePageStream* bernilai null. |
| ArgumentNullException | Dilempar ketika *releaseResourceStream* bernilai null. |

### Catatan

Untuk contoh kode, lihat [dokumentasi](https://docs.groupdocs.com/viewer/net/rendering-to-html/#rendering-to-html-with-external-resources).

### Lihat Juga

* delegate [CreatePageStream](../../../groupdocs.viewer.interfaces/createpagestream)
* delegate [CreateResourceStream](../../../groupdocs.viewer.interfaces/createresourcestream)
* delegate [CreateResourceUrl](../../../groupdocs.viewer.interfaces/createresourceurl)
* delegate [ReleasePageStream](../../../groupdocs.viewer.interfaces/releasepagestream)
* delegate [ReleaseResourceStream](../../../groupdocs.viewer.interfaces/releaseresourcestream)
* class [HtmlViewOptions](../../htmlviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

---

## ForExternalResources(IPageStreamFactory, IResourceStreamFactory) {#forexternalresources_3}

Menginisialisasi instance dari kelas [`HtmlViewOptions`](../../htmlviewoptions) untuk merender ke HTML dengan sumber daya eksternal.

```csharp
public static HtmlViewOptions ForExternalResources(IPageStreamFactory pageStreamFactory, 
    IResourceStreamFactory resourceStreamFactory)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pageStreamFactory | IPageStreamFactory | Fabrik yang mengimplementasikan metode untuk membuat dan melepaskan aliran halaman output. |
| resourceStreamFactory | IResourceStreamFactory | Fabrik yang mengimplementasikan metode yang diperlukan untuk membuat URL sumber daya, menginstansiasi, dan melepaskan aliran sumber daya HTML output. |

### Nilai Kembali

Instansi baru dari kelas [`HtmlViewOptions`](../../htmlviewoptions) untuk merender ke HTML dengan sumber daya eksternal.

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| ArgumentNullException | Dilempar ketika *pageStreamFactory* bernilai null. |
| ArgumentNullException | Dilempar ketika *resourceStreamFactory* bernilai null. |

### Catatan

Untuk contoh kode, lihat [dokumentasi](https://docs.groupdocs.com/viewer/net/rendering-to-html/#rendering-to-html-with-external-resources).

### Lihat Juga

* interface [IPageStreamFactory](../../../groupdocs.viewer.interfaces/ipagestreamfactory)
* interface [IResourceStreamFactory](../../../groupdocs.viewer.interfaces/iresourcestreamfactory)
* class [HtmlViewOptions](../../htmlviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

---

## ForExternalResources() {#forexternalresources}

Menginisialisasi sebuah instansi dari kelas [`HtmlViewOptions`](../../htmlviewoptions).

```csharp
public static HtmlViewOptions ForExternalResources()
```

### Catatan

Konstruktor ini menginisialisasi sebuah instansi dari [`HtmlViewOptions`](../../htmlviewoptions).

* with "p_{0}.html" as file path format for the output HTML files
* with "p_{0}_{1}" as file path format for the output HTML-resource files
* with "p_{0}_{1}" as URL format for HTML-resources

File output akan ditempatkan ke direktori kerja saat ini dari aplikasi.

Untuk contoh kode, lihat [dokumentasi](https://docs.groupdocs.com/viewer/net/rendering-to-html/#rendering-to-html-with-external-resources).

### Lihat Juga

* class [HtmlViewOptions](../../htmlviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

---

## ForExternalResources(string, string, string) {#forexternalresources_4}

Menginisialisasi sebuah instansi dari kelas [`HtmlViewOptions`](../../htmlviewoptions).

```csharp
public static HtmlViewOptions ForExternalResources(string filePathFormat, 
    string resourceFilePathFormat, string resourceUrlFormat)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| filePathFormat | String | Format jalur file, misalnya 'page_{0}.html'. |
| resourceFilePathFormat | String | Format jalur file sumber daya, misalnya 'page_{0}/resource_{1}'. |
| resourceUrlFormat | String | Format URL sumber daya, misalnya 'page_{0}/resource_{1}'. |

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| ArgumentException | Dilempar ketika *filePathFormat* bernilai null atau kosong. |
| ArgumentException | Dilempar ketika *resourceFilePathFormat* bernilai null atau kosong. |
| ArgumentException | Dilempar ketika *resourceUrlFormat* bernilai null atau kosong. |

### Catatan

Untuk contoh kode, lihat [dokumentasi](https://docs.groupdocs.com/viewer/net/rendering-to-html/#rendering-to-html-with-external-resources).

### Lihat Juga

* class [HtmlViewOptions](../../htmlviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Viewer.dll -->
