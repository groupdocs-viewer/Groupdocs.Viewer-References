---
title: ForExternalResources
second_title: GroupDocs.Viewer untuk Referensi .NET API
description: Menginisialisasi instance baruHtmlViewOptionsgroupdocs.viewer.options/htmlviewoptions kelas untuk merender ke dalam HTML dengan sumber daya eksternal.
type: docs
weight: 20
url: /id/net/groupdocs.viewer.options/htmlviewoptions/forexternalresources/
---
## ForExternalResources(CreatePageStream, CreateResourceStream, CreateResourceUrl) {#forexternalresources_1}

Menginisialisasi instance baru[`HtmlViewOptions`](../../htmlviewoptions) kelas untuk merender ke dalam HTML dengan sumber daya eksternal.

```csharp
public static HtmlViewOptions ForExternalResources(CreatePageStream createPageStream, 
    CreateResourceStream createResourceStream, CreateResourceUrl createResourceUrl)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| createPageStream | CreatePageStream | Metode yang menginisiasi aliran yang digunakan untuk menulis data halaman keluaran. |
| createResourceStream | CreateResourceStream | Metode yang melepaskan aliran yang dibuat oleh*createPageStream* metode. |
| createResourceUrl | CreateResourceUrl | Metode yang membuat URL untuk sumber daya HTML. |

### Nilai Pengembalian

Contoh baru dari[`HtmlViewOptions`](../../htmlviewoptions) kelas untuk merender ke dalam HTML dengan sumber daya eksternal.

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| ArgumentNullException | Dilempar kapan*createPageStream* adalah nol. |
| ArgumentNullException | Dilempar kapan*createResourceStream* adalah nol. |
| ArgumentNullException | Dilempar kapan*createResourceUrl* adalah nol. |

### Lihat juga

* delegate [CreatePageStream](../../../groupdocs.viewer.interfaces/createpagestream)
* delegate [CreateResourceStream](../../../groupdocs.viewer.interfaces/createresourcestream)
* delegate [CreateResourceUrl](../../../groupdocs.viewer.interfaces/createresourceurl)
* class [HtmlViewOptions](../../htmlviewoptions)
* ruang nama [GroupDocs.Viewer.Options](../../htmlviewoptions)
* perakitan [GroupDocs.Viewer](../../../)

---

## ForExternalResources(CreatePageStream, CreateResourceStream, CreateResourceUrl, ReleasePageStream, ReleaseResourceStream) {#forexternalresources_2}

Menginisialisasi instance baru[`HtmlViewOptions`](../../htmlviewoptions) kelas untuk merender ke dalam HTML dengan sumber daya eksternal.

```csharp
public static HtmlViewOptions ForExternalResources(CreatePageStream createPageStream, 
    CreateResourceStream createResourceStream, CreateResourceUrl createResourceUrl, 
    ReleasePageStream releasePageStream, ReleaseResourceStream releaseResourceStream)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| createPageStream | CreatePageStream | Metode yang menginisiasi aliran yang digunakan untuk menulis data halaman keluaran. |
| createResourceStream | CreateResourceStream | Metode yang menginstansiasi aliran yang digunakan untuk menulis data sumber daya HTML keluaran. |
| createResourceUrl | CreateResourceUrl | Metode yang membuat URL untuk sumber daya HTML. |
| releasePageStream | ReleasePageStream | Metode yang melepaskan aliran yang dibuat oleh metode yang ditetapkan untuk mendelegasikan yang diteruskan ke*createPageStream* parameter. |
| releaseResourceStream | ReleaseResourceStream | Metode yang melepaskan aliran yang dibuat oleh metode yang ditetapkan untuk mendelegasikan yang diteruskan ke*createResourceStream* parameter. |

### Nilai Pengembalian

Contoh baru dari[`HtmlViewOptions`](../../htmlviewoptions) kelas untuk merender ke dalam HTML dengan sumber daya eksternal.

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| ArgumentNullException | Dilempar kapan*createPageStream* adalah nol. |
| ArgumentNullException | Dilempar kapan*createResourceStream* adalah nol. |
| ArgumentNullException | Dilempar kapan*createResourceUrl* adalah nol. |
| ArgumentNullException | Dilempar kapan*releasePageStream* adalah nol. |
| ArgumentNullException | Dilempar kapan*releaseResourceStream* adalah nol. |

### Lihat juga

* delegate [CreatePageStream](../../../groupdocs.viewer.interfaces/createpagestream)
* delegate [CreateResourceStream](../../../groupdocs.viewer.interfaces/createresourcestream)
* delegate [CreateResourceUrl](../../../groupdocs.viewer.interfaces/createresourceurl)
* delegate [ReleasePageStream](../../../groupdocs.viewer.interfaces/releasepagestream)
* delegate [ReleaseResourceStream](../../../groupdocs.viewer.interfaces/releaseresourcestream)
* class [HtmlViewOptions](../../htmlviewoptions)
* ruang nama [GroupDocs.Viewer.Options](../../htmlviewoptions)
* perakitan [GroupDocs.Viewer](../../../)

---

## ForExternalResources(IPageStreamFactory, IResourceStreamFactory) {#forexternalresources_3}

Menginisialisasi instance baru[`HtmlViewOptions`](../../htmlviewoptions) kelas untuk merender ke dalam HTML dengan sumber daya eksternal.

```csharp
public static HtmlViewOptions ForExternalResources(IPageStreamFactory pageStreamFactory, 
    IResourceStreamFactory resourceStreamFactory)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| pageStreamFactory | IPageStreamFactory | Pabrik yang mengimplementasikan metode untuk membuat dan merilis aliran halaman keluaran. |
| resourceStreamFactory | IResourceStreamFactory | Pabrik yang mengimplementasikan metode yang diperlukan untuk membuat URL sumber daya, membuat instance, dan merilis aliran sumber daya HTML keluaran. |

### Nilai Pengembalian

Contoh baru dari[`HtmlViewOptions`](../../htmlviewoptions) kelas untuk merender ke dalam HTML dengan sumber daya eksternal.

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| ArgumentNullException | Dilempar kapan*pageStreamFactory* adalah nol. |
| ArgumentNullException | Dilempar kapan*resourceStreamFactory* adalah nol. |

### Lihat juga

* interface [IPageStreamFactory](../../../groupdocs.viewer.interfaces/ipagestreamfactory)
* interface [IResourceStreamFactory](../../../groupdocs.viewer.interfaces/iresourcestreamfactory)
* class [HtmlViewOptions](../../htmlviewoptions)
* ruang nama [GroupDocs.Viewer.Options](../../htmlviewoptions)
* perakitan [GroupDocs.Viewer](../../../)

---

## ForExternalResources() {#forexternalresources}

Menginisialisasi instance baru[`HtmlViewOptions`](../../htmlviewoptions) kelas.

```csharp
public static HtmlViewOptions ForExternalResources()
```

### Perkataan

Konstruktor ini menginisialisasi instance baru dari[`HtmlViewOptions`](../../htmlviewoptions) - dengan "p_{0}.html" sebagai format jalur file untuk file HTML keluaran; - dengan "p_{0}_{1}" sebagai format jalur file untuk file sumber daya HTML keluaran; - dengan " p_{0}_{1}" sebagai format URL untuk sumber daya HTML; File keluaran akan ditempatkan ke dalam direktori kerja aplikasi saat ini.

### Lihat juga

* class [HtmlViewOptions](../../htmlviewoptions)
* ruang nama [GroupDocs.Viewer.Options](../../htmlviewoptions)
* perakitan [GroupDocs.Viewer](../../../)

---

## ForExternalResources(string, string, string) {#forexternalresources_4}

Menginisialisasi instance baru[`HtmlViewOptions`](../../htmlviewoptions) kelas.

```csharp
public static HtmlViewOptions ForExternalResources(string filePathFormat, 
    string resourceFilePathFormat, string resourceUrlFormat)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| filePathFormat | String | Format jalur file misalnya 'page_{0}.html'. |
| resourceFilePathFormat | String | Format jalur file sumber daya misalnya 'page_{0}/resource_{1}'. |
| resourceUrlFormat | String | Format URL sumber daya misalnya 'halaman_{0}/sumber daya_{1}'. |

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| ArgumentException | Dilempar kapan*filePathFormat* adalah null atau kosong. |
| ArgumentException | Dilempar kapan*resourceFilePathFormat* adalah null atau kosong. |
| ArgumentException | Dilempar kapan*resourceUrlFormat* adalah null atau kosong. |

### Lihat juga

* class [HtmlViewOptions](../../htmlviewoptions)
* ruang nama [GroupDocs.Viewer.Options](../../htmlviewoptions)
* perakitan [GroupDocs.Viewer](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Viewer.dll -->
