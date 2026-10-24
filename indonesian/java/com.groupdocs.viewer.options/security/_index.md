---
title: "Keamanan"
second_title: "Referensi API GroupDocs.Viewer for Java"
description: "Menyediakan opsi keamanan dokumen PDF."
type: docs
weight: 29
url: /id/java/com.groupdocs.viewer.options/security/
---
**Inheritance:**
java.lang.Object
```
public class Security
```

Menyediakan opsi keamanan dokumen PDF.


Kelas Keamanan mengenkapsulasi berbagai pengaturan dan opsi yang dapat digunakan untuk menerapkan langkah-langkah keamanan
pada dokumen PDF dalam komponen GroupDocs.Viewer. Opsi-opsi ini meliputi perlindungan kata sandi,
izin, dan lainnya.
Untuk detail, lihat [dokumentasi](../https://docs.groupdocs.com/viewer/net/protect-pdf-documents/).


Contoh penggunaan:

````

 Security security = new Security();
 security.setDocumentOpenPassword("myPassword");
 security.setPermissions(Permissions.DENY_MODIFICATION);

 final PdfViewOptions pdfViewOptions = new PdfViewOptions();
 pdfViewOptions.setSecurity(security);

 try (Viewer viewer = new Viewer("document.pdf")) {
     viewer.view(pdfViewOptions);
     // Use the viewer object for further operations
 }
 
````


## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
|  | [Security()](#Security--) | Menginisialisasi instance baru dari |
Keamanan
kelas.
|
## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [getDocumentOpenPassword()](#getDocumentOpenPassword--) | Mendapatkan kata sandi yang diperlukan untuk membuka dokumen PDF. |
|
|  | [setDocumentOpenPassword(String value)](#setDocumentOpenPassword-java.lang.String-) | Menetapkan kata sandi yang diperlukan untuk membuka dokumen PDF. |
|
|  | [getPermissionsPassword()](#getPermissionsPassword--) | Mendapatkan kata sandi yang diperlukan untuk mengubah pengaturan izin. |
|
|  | [setPermissionsPassword(String value)](#setPermissionsPassword-java.lang.String-) | Menetapkan kata sandi yang diperlukan untuk mengubah pengaturan izin. |
|
|  | [getPermissions()](#getPermissions--) | Mendapatkan izin dokumen PDF seperti pencetakan, modifikasi, dan ekstraksi data. |
|
|  | [setPermissions(int value)](#setPermissions-int-) | Menetapkan izin dokumen PDF seperti pencetakan, modifikasi, dan ekstraksi data. |
|
### Security() {#Security--}
```
public Security()
```


Menginisialisasi instance baru dari
Keamanan
kelas.


### getDocumentOpenPassword() {#getDocumentOpenPassword--}
```
public final String getDocumentOpenPassword()
```


Mendapatkan kata sandi yang diperlukan untuk membuka dokumen PDF.


Untuk contoh kode, lihat [dokumentasi](../https://docs.groupdocs.com/viewer/net/protect-pdf-documents/).


**Returns:**
java.lang.String - kata sandi pembuka dokumen.

### setDocumentOpenPassword(String value) {#setDocumentOpenPassword-java.lang.String-}
```
public final void setDocumentOpenPassword(String value)
```


Menetapkan kata sandi yang diperlukan untuk membuka dokumen PDF.


Untuk contoh kode, lihat [dokumentasi](../https://docs.groupdocs.com/viewer/net/protect-pdf-documents/).


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | nilai | java.lang.String | Kata sandi pembuka dokumen. |
|

### getPermissionsPassword() {#getPermissionsPassword--}
```
public final String getPermissionsPassword()
```


Mendapatkan kata sandi yang diperlukan untuk mengubah pengaturan izin.


Dengan menggunakan kata sandi izin, Anda dapat membatasi pencetakan, modifikasi, dan ekstraksi data.
Gunakan kata sandi izin untuk membatasi pencetakan, modifikasi, dan ekstraksi data. Untuk contoh kode, lihat [dokumentasi](../https://docs.groupdocs.com/viewer/net/protect-pdf-documents/).


**Returns:**
java.lang.String - kata sandi izin.

### setPermissionsPassword(String value) {#setPermissionsPassword-java.lang.String-}
```
public final void setPermissionsPassword(String value)
```


Menetapkan kata sandi yang diperlukan untuk mengubah pengaturan izin.


Dengan menggunakan kata sandi izin, Anda dapat membatasi pencetakan, modifikasi, dan ekstraksi data.
Gunakan kata sandi izin untuk membatasi pencetakan, modifikasi, dan ekstraksi data. Untuk contoh kode, lihat [dokumentasi](../https://docs.groupdocs.com/viewer/net/protect-pdf-documents/).


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | nilai | java.lang.String | Kata sandi izin. |
|

### getPermissions() {#getPermissions--}
```
public final int getPermissions()
```


Mendapatkan izin dokumen PDF seperti pencetakan, modifikasi, dan ekstraksi data.


Untuk contoh kode, lihat [dokumentasi](../https://docs.groupdocs.com/viewer/net/protect-pdf-documents/).


**Returns:**
int - izin dokumen PDF.

### setPermissions(int value) {#setPermissions-int-}
```
public final void setPermissions(int value)
```


Menetapkan izin dokumen PDF seperti pencetakan, modifikasi, dan ekstraksi data.


Untuk contoh kode, lihat [dokumentasi](../https://docs.groupdocs.com/viewer/net/protect-pdf-documents/).


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | nilai | int | Izin dokumen PDF. |
|

