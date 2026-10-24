---
title: "Lisensi"
second_title: "Referensi API GroupDocs.Viewer for Java"
description: "Menyediakan metode untuk melisensikan komponen dan membuka semua fungsionalitasnya."
type: docs
weight: 10
url: /id/java/com.groupdocs.viewer/license/
---
**Inheritance:**
java.lang.Object
```
public class License
```

Menyediakan metode untuk melisensikan komponen dan membuka semua fungsionalitasnya.


Kelas License memungkinkan Anda menerapkan lisensi yang valid ke komponen GroupDocs.Viewer, memungkinkan Anda menggunakan semua fitur dan menghapus batasan evaluasi apa pun.


Contoh penggunaan:

````

 License license = new License();
 license.setLicense("path/to/license/file.lic");
 
````


## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [License()](#License--) |  |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [resetLicense()](#resetLicense--) |  |
|  | [setLicense(InputStream licenseStream)](#setLicense-java.io.InputStream-) | Memberi lisensi pada komponen. |
|
|  | [setLicense(Path licensePath)](#setLicense-java.nio.file.Path-) | Memberi lisensi pada komponen. |
|
|  | [setLicense(String licensePath)](#setLicense-java.lang.String-) | Memberi lisensi pada komponen. |
|
|  | [setLicense(URL licenseUri)](#setLicense-java.net.URL-) | Memberi lisensi pada komponen. |
|
| [isLicensed()](#isLicensed--) |  |
### License() {#License--}
```
public License()
```


### resetLicense() {#resetLicense--}
```
public static void resetLicense()
```




### setLicense(InputStream licenseStream) {#setLicense-java.io.InputStream-}
```
public final void setLicense(InputStream licenseStream)
```


Memberi lisensi pada komponen.


Contoh berikut menunjukkan cara mengatur lisensi dengan melewatkan InputStream dari file lisensi.


Untuk informasi lebih lanjut tentang lisensi, silakan merujuk ke
[GroupDocs Licensing FAQ](../https://purchase.groupdocs.com/faqs/licensing).
Anda juga dapat menemukan informasi terperinci tentang lisensi GroupDocs.Viewer di
[Evaluation Limitations and Licensing](../https://docs.groupdocs.com/display/viewernet/Evaluation+Limitations+and+Licensing+of+GroupDocs.Viewer) documentation.

**Example:**

````

 FileInputStream licenseStream = new FileInputStream("LicenseFile.lic");
 License license = new License();
 license.setLicense(licenseStream);
 
````



**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | licenseStream | java.io.InputStream | Aliran lisensi. |
|

### setLicense(Path licensePath) {#setLicense-java.nio.file.Path-}
```
public final void setLicense(Path licensePath)
```


Memberi lisensi pada komponen.


Mengatur lisensi untuk komponen menggunakan jalur lisensi yang ditentukan.


**Note:** This method should be called before using any functionality of the component.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | licensePath | java.nio.file.Path | Jalur lisensi. |
|

### setLicense(String licensePath) {#setLicense-java.lang.String-}
```
public final void setLicense(String licensePath)
```


Memberi lisensi pada komponen.


Metode ini harus dipanggil sebelum menggunakan fungsi apa pun.


Contoh penggunaan:

````

 String licensePath = "GroupDocs.Viewer.lic";
 License license = new License();
 license.setLicense(licensePath);
 
````

<br />



**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | licensePath | java.lang.String | Jalur lisensi atau URL. |
|

### setLicense(URL licenseUri) {#setLicense-java.net.URL-}
```
public void setLicense(URL licenseUri)
```


Memberi lisensi pada komponen.


Metode ini harus dipanggil sebelum menggunakan fungsi apa pun.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | licenseUri | java.net.URL | URI lisensi. |
|

### isLicensed() {#isLicensed--}
```
public final boolean isLicensed()
```




**Returns:**
boolean
