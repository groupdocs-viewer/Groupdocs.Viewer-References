---
title: "Metered"
second_title: "GroupDocs.Viewer untuk Node.js melalui Java Referensi API"
description: "Menyediakan metode untuk menerapkan lisensi terukur pada komponen GroupDocs.Viewer."
type: docs
weight: 11
url: /id/nodejs-java/com.groupdocs.viewer/metered/
---
**Inheritance:**
java.lang.Object
```
public class Metered
```

Menyediakan metode untuk menerapkan lisensi terukur pada komponen GroupDocs.Viewer.

Lisensi Metered memungkinkan Anda secara dinamis memantau dan mengontrol penggunaan GroupDocs.Viewer berdasarkan jumlah halaman dokumen yang diproses, bukan lisensi tradisional per-server atau per-developer. Model lisensi yang fleksibel ini cocok untuk skenario di mana kebutuhan pemrosesan dokumen berubah-ubah seiring waktu atau ketika Anda ingin membayar hanya untuk apa yang Anda gunakan.

Contoh penggunaan:

```

 Metered metered = new Metered();
 metered.setMeteredKey(publicKey, privateKey);
 // Perform document processing operations using GroupDocs.Viewer
 // ...
 
```
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [Metered()](#Metered--) |  |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getConsumptionQuantity()](#getConsumptionQuantity--) | Mengambil jumlah megabyte (MB) yang diproses. |
| [getConsumptionCredit()](#getConsumptionCredit--) | Mengambil jumlah kredit yang digunakan. |
| [setMeteredKey(String publicKey, String privateKey)](#setMeteredKey-java.lang.String-java.lang.String-) | Mengaktifkan produk dengan kunci Metered. |
### Metered() {#Metered--}
```
public Metered()
```


### getConsumptionQuantity() {#getConsumptionQuantity--}
```
public static double getConsumptionQuantity()
```


Mengambil jumlah megabyte (MB) yang diproses.

Metode ini mengembalikan total jumlah MB yang diproses oleh komponen.

**Example:**

```

 String publicKey = "Public Key";
 String privateKey = "Private Key";
 Metered metered = new Metered();
 metered.setMeteredKey(publicKey, privateKey);
 double mbProcessed = Metered.getConsumptionQuantity();
 
```

**Returns:**
double - jumlah MB yang diproses.
### getConsumptionCredit() {#getConsumptionCredit--}
```
public static double getConsumptionCredit()
```


Mengambil jumlah kredit yang digunakan.

Metode ini mengembalikan total jumlah kredit yang digunakan oleh komponen.

**Example:**

```

 String publicKey = "Public Key";
 String privateKey = "Private Key";
 Metered metered = new Metered();
 metered.setMeteredKey(publicKey, privateKey);
 double creditsConsumed = Metered.getConsumptionCredit();
 
```

**Returns:**
double - jumlah kredit yang digunakan.
### setMeteredKey(String publicKey, String privateKey) {#setMeteredKey-java.lang.String-java.lang.String-}
```
public final void setMeteredKey(String publicKey, String privateKey)
```


Mengaktifkan produk dengan kunci Metered.

Contoh berikut menunjukkan cara mengaktifkan produk dengan kunci Metered.

**Example:**

```

 String publicKey = "Public Key";
 String privateKey = "Private Key";
 Metered metered = new Metered();
 metered.setMeteredKey(publicKey, privateKey);
 
```

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| publicKey | java.lang.String | Kunci publik. |
| privateKey | java.lang.String | Kunci pribadi. |

