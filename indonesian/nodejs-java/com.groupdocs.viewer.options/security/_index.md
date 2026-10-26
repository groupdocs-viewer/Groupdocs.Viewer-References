---
title: "Security"
second_title: "GroupDocs.Viewer untuk Node.js melalui Java Referensi API"
description: "Menyediakan opsi keamanan dokumen PDF."
type: docs
weight: 29
url: /id/nodejs-java/com.groupdocs.viewer.options/security/
---
**Inheritance:**
java.lang.Object
```
public class Security
```

Menyediakan opsi keamanan dokumen PDF.

Kelas Security mengenkapsulasi berbagai pengaturan dan opsi yang dapat digunakan untuk menerapkan langkah-langkah keamanan pada dokumen PDF dalam komponen GroupDocs.Viewer. Opsi-opsi ini mencakup perlindungan kata sandi, izin, dan lainnya. Untuk detail, lihat [documentation][].

Contoh penggunaan:

```

 Security security = new Security();
 security.setDocumentOpenPassword("myPassword");
 security.setPermissions(Permissions.DENY_MODIFICATION);

 final PdfViewOptions pdfViewOptions = new PdfViewOptions();
 pdfViewOptions.setSecurity(security);

 try (Viewer viewer = new Viewer("document.pdf")) {
     viewer.view(pdfViewOptions);
     // Use the viewer object for further operations
 }
 
```


[documentation]: https://docs.groupdocs.com/viewer/net/protect-pdf-documents/
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [Security()](#Security--) | Menginisialisasi instance baru dari kelas  Security  . |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getDocumentOpenPassword()](#getDocumentOpenPassword--) | Mendapatkan kata sandi yang diperlukan untuk membuka dokumen PDF. |
| [setDocumentOpenPassword(String value)](#setDocumentOpenPassword-java.lang.String-) | Mengatur kata sandi yang diperlukan untuk membuka dokumen PDF. |
| [getPermissionsPassword()](#getPermissionsPassword--) | Mendapatkan kata sandi yang diperlukan untuk mengubah pengaturan izin. |
| [setPermissionsPassword(String value)](#setPermissionsPassword-java.lang.String-) | Mengatur kata sandi yang diperlukan untuk mengubah pengaturan izin. |
| [getPermissions()](#getPermissions--) | Mendapatkan izin dokumen PDF seperti pencetakan, modifikasi, dan ekstraksi data. |
| [setPermissions(int value)](#setPermissions-int-) | Menetapkan izin dokumen PDF seperti pencetakan, modifikasi, dan ekstraksi data. |
### Security() {#Security--}
```
public Security()
```


Menginisialisasi instance baru dari kelas  Security  .

### getDocumentOpenPassword() {#getDocumentOpenPassword--}
```
public final String getDocumentOpenPassword()
```


Mendapatkan kata sandi yang diperlukan untuk membuka dokumen PDF.

Untuk contoh kode, lihat [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/net/protect-pdf-documents/

**Returns:**
java.lang.String - kata sandi pembukaan dokumen.
### setDocumentOpenPassword(String value) {#setDocumentOpenPassword-java.lang.String-}
```
public final void setDocumentOpenPassword(String value)
```


Mengatur kata sandi yang diperlukan untuk membuka dokumen PDF.

Untuk contoh kode, lihat [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/net/protect-pdf-documents/

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | java.lang.String | Kata sandi pembukaan dokumen. |

### getPermissionsPassword() {#getPermissionsPassword--}
```
public final String getPermissionsPassword()
```


Mendapatkan kata sandi yang diperlukan untuk mengubah pengaturan izin.

Dengan menggunakan kata sandi izin, Anda dapat membatasi pencetakan, modifikasi, dan ekstraksi data. Gunakan kata sandi izin untuk membatasi pencetakan, modifikasi, dan ekstraksi data. Untuk contoh kode, lihat [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/net/protect-pdf-documents/

**Returns:**
java.lang.String - kata sandi izin.
### setPermissionsPassword(String value) {#setPermissionsPassword-java.lang.String-}
```
public final void setPermissionsPassword(String value)
```


Mengatur kata sandi yang diperlukan untuk mengubah pengaturan izin.

Dengan menggunakan kata sandi izin, Anda dapat membatasi pencetakan, modifikasi, dan ekstraksi data. Gunakan kata sandi izin untuk membatasi pencetakan, modifikasi, dan ekstraksi data. Untuk contoh kode, lihat [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/net/protect-pdf-documents/

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | java.lang.String | Kata sandi izin. |

### getPermissions() {#getPermissions--}
```
public final int getPermissions()
```


Mendapatkan izin dokumen PDF seperti pencetakan, modifikasi, dan ekstraksi data.

Untuk contoh kode, lihat [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/net/protect-pdf-documents/

**Returns:**
int - izin dokumen PDF.
### setPermissions(int value) {#setPermissions-int-}
```
public final void setPermissions(int value)
```


Menetapkan izin dokumen PDF seperti pencetakan, modifikasi, dan ekstraksi data.

Untuk contoh kode, lihat [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/net/protect-pdf-documents/

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int | Izin dokumen PDF. |

