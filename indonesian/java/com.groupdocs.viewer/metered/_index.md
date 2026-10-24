---
title: "Berbasis meter"
second_title: "Referensi API GroupDocs.Viewer for Java"
description: "Menyediakan metode untuk menerapkan lisensi bermeter ke komponen GroupDocs.Viewer."
type: docs
weight: 11
url: /id/java/com.groupdocs.viewer/metered/
---
**Inheritance:**
java.lang.Object
```
public class Metered
```

Menyediakan metode untuk menerapkan lisensi bermeter ke komponen GroupDocs.Viewer.


Lisensi berbasis meter memungkinkan Anda memantau dan mengontrol penggunaan GroupDocs.Viewer secara dinamis berdasarkan jumlah halaman dokumen yang diproses, bukan lisensi tradisional per-server atau per-pengembang.
Model lisensi fleksibel ini cocok untuk skenario di mana kebutuhan pemrosesan dokumen berubah seiring waktu atau ketika Anda hanya ingin membayar sesuai penggunaan.


Contoh penggunaan:

````

 Metered metered = new Metered();
 metered.setMeteredKey(publicKey, privateKey);
 // Perform document processing operations using GroupDocs.Viewer
 // ...
 
````


## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [Metered()](#Metered--) |  |
## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [getConsumptionQuantity()](#getConsumptionQuantity--) | Mengambil jumlah megabyte (MB) yang diproses. |
|
|  | [getConsumptionCredit()](#getConsumptionCredit--) | Mengambil jumlah kredit yang digunakan. |
|
|  | [setMeteredKey(String publicKey, String privateKey)](#setMeteredKey-java.lang.String-java.lang.String-) | Mengaktifkan produk dengan kunci berbasis meter. |
|
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

````

 String publicKey = "Public Key";
 String privateKey = "Private Key";
 Metered metered = new Metered();
 metered.setMeteredKey(publicKey, privateKey);
 double mbProcessed = Metered.getConsumptionQuantity();
 
````



**Returns:**
double - jumlah MB yang diproses.

### getConsumptionCredit() {#getConsumptionCredit--}
```
public static double getConsumptionCredit()
```


Mengambil jumlah kredit yang digunakan.


Metode ini mengembalikan total jumlah kredit yang digunakan oleh komponen.

**Example:**

````

 String publicKey = "Public Key";
 String privateKey = "Private Key";
 Metered metered = new Metered();
 metered.setMeteredKey(publicKey, privateKey);
 double creditsConsumed = Metered.getConsumptionCredit();
 
````



**Returns:**
double - jumlah kredit yang digunakan.

### setMeteredKey(String publicKey, String privateKey) {#setMeteredKey-java.lang.String-java.lang.String-}
```
public final void setMeteredKey(String publicKey, String privateKey)
```


Mengaktifkan produk dengan kunci berbasis meter.


Contoh berikut menunjukkan cara mengaktifkan produk dengan kunci berbasis meter.

**Example:**

````

 String publicKey = "Public Key";
 String privateKey = "Private Key";
 Metered metered = new Metered();
 metered.setMeteredKey(publicKey, privateKey);
 
````



**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | publicKey | java.lang.String | Kunci publik. |
|
|  | privateKey | java.lang.String | Kunci pribadi. |
|

