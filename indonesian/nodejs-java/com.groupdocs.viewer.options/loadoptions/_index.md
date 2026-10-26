---
title: "LoadOptions"
second_title: "GroupDocs.Viewer untuk Node.js melalui Java Referensi API"
description: "Menyediakan opsi yang digunakan untuk membuka file."
type: docs
weight: 18
url: /id/nodejs-java/com.groupdocs.viewer.options/loadoptions/
---
**Inheritance:**
java.lang.Object
```
public class LoadOptions
```

Menyediakan opsi yang digunakan untuk membuka file.

Kelas LoadOptions mengenkapsulasi berbagai pengaturan dan parameter yang dapat digunakan untuk menentukan bagaimana sebuah file harus dibuka dan dimuat dalam komponen GroupDocs.Viewer. Untuk detail, lihat [halaman][] dan turunannya.

Contoh penggunaan:

```

 LoadOptions options = new LoadOptions();
 options.setPassword("myPassword");
 options.setFileType(PDF);
 options.setCharset(Charset.forName("UTF-8"));

 try (Viewer viewer = new Viewer(pdfFileInputStream, options)) {
     // Use the viewer object for further operations
 }
 
```


[page]: https://docs.groupdocs.com/viewer/java/loading/
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [LoadOptions()](#LoadOptions--) | Menginisialisasi instance baru dari kelas LoadOptions. |
| [LoadOptions(FileType fileType)](#LoadOptions-com.groupdocs.viewer.FileType-) | Menginisialisasi instance baru dari kelas LoadOptions. |
## Bidang

| Bidang | Deskripsi |
| --- | --- |
| [DEFAULT_URL_CONNECT_TIMEOUT](#DEFAULT-URL-CONNECT-TIMEOUT) |  |
| [DEFAULT_URL_READ_TIMEOUT](#DEFAULT-URL-READ-TIMEOUT) |  |
| [_tryRepair](#-tryRepair) |  |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [isTryRepair()](#isTryRepair--) | Ketika diaktifkan, GroupDocs.Viewer mencoba memperbaiki kerusakan struktural pada dokumen PDF. |
| [setTryRepair(boolean tryRepair)](#setTryRepair-boolean-) | Ketika diaktifkan, GroupDocs.Viewer mencoba memperbaiki kerusakan struktural pada dokumen PDF. |
| [getFileType()](#getFileType--) | Mendapatkan tipe file yang akan dibuka. |
| [setFileType(FileType value)](#setFileType-com.groupdocs.viewer.FileType-) | Mengatur tipe file yang akan dibuka. |
| [getPassword()](#getPassword--) | Mendapatkan kata sandi untuk membuka file terenkripsi. |
| [setPassword(String value)](#setPassword-java.lang.String-) | Mengatur kata sandi untuk membuka file terenkripsi. |
| [getCharset()](#getCharset--) | Set charset yang digunakan saat membuka file berbasis teks atau pesan email seperti [FileType.CSV](../../com.groupdocs.viewer/filetype\#CSV), [FileType.TXT](../../com.groupdocs.viewer/filetype\#TXT), dan [FileType.MSG](../../com.groupdocs.viewer/filetype\#MSG). |
| [setCharset(Charset value)](#setCharset-java.nio.charset.Charset-) | Set charset yang digunakan saat membuka file berbasis teks atau pesan email seperti [FileType.CSV](../../com.groupdocs.viewer/filetype\#CSV), [FileType.TXT](../../com.groupdocs.viewer/filetype\#TXT), dan [FileType.MSG](../../com.groupdocs.viewer/filetype\#MSG). |
| [isDetectCharset()](#isDetectCharset--) | Opsi ini mengaktifkan deteksi charset file [FileType.TXT](../../com.groupdocs.viewer/filetype\#TXT), [FileType.TSV](../../com.groupdocs.viewer/filetype\#TSV), dan [FileType.CSV](../../com.groupdocs.viewer/filetype\#CSV). |
| [setDetectCharset(boolean detectCharset)](#setDetectCharset-boolean-) | Opsi ini mengaktifkan deteksi charset file [FileType.TXT](../../com.groupdocs.viewer/filetype\#TXT), [FileType.TSV](../../com.groupdocs.viewer/filetype\#TSV), dan [FileType.CSV](../../com.groupdocs.viewer/filetype\#CSV). |
| [getResourceLoadingTimeout()](#getResourceLoadingTimeout--) | Mendapatkan batas waktu untuk memuat sumber daya eksternal. |
| [setResourceLoadingTimeout(int resourceLoadingTimeout)](#setResourceLoadingTimeout-int-) | Mengatur batas waktu untuk memuat sumber daya eksternal, seperti grafik. |
| [getUrlConnectTimeout()](#getUrlConnectTimeout--) | Mendapatkan batas waktu koneksi untuk membuat [Viewer](../../com.groupdocs.viewer/viewer) menggunakan java.net.URL untuk memuat dokumen. |
| [setUrlConnectTimeout(int urlConnectTimeout)](#setUrlConnectTimeout-int-) | Mengatur batas waktu koneksi untuk membuat [Viewer](../../com.groupdocs.viewer/viewer) menggunakan java.net.URL untuk memuat dokumen. |
| [getUrlReadTimeout()](#getUrlReadTimeout--) | Mendapatkan batas waktu baca untuk membuat [Viewer](../../com.groupdocs.viewer/viewer) menggunakan java.net.URL untuk memuat dokumen. |
| [setUrlReadTimeout(int urlReadTimeout)](#setUrlReadTimeout-int-) | Mengatur batas waktu baca untuk membuat [Viewer](../../com.groupdocs.viewer/viewer) menggunakan java.net.URL untuk memuat dokumen. |
| [getArchiveSecurityOptions()](#getArchiveSecurityOptions--) | Mendapatkan opsi keamanan untuk mengontrol proses ekstraksi arsip. |
| [setArchiveSecurityOptions(ArchiveSecurityOptions archiveSecurityOptions)](#setArchiveSecurityOptions-com.groupdocs.viewer.options.ArchiveSecurityOptions-) | Mengatur opsi keamanan untuk mengontrol proses mengekstrak arsip. |
| [isSkipExternalResources()](#isSkipExternalResources--) | Saat diatur ke true, semua sumber daya eksternal seperti gambar tidak akan dimuat kecuali \#getWhitelistedResources().getWhitelistedResources(). |
| [setSkipExternalResources(boolean skipExternalResources)](#setSkipExternalResources-boolean-) | Saat diatur ke true, semua sumber daya eksternal seperti gambar tidak akan dimuat kecuali \#getWhitelistedResources().getWhitelistedResources(). |
| [getWhitelistedResources()](#getWhitelistedResources--) | Daftar fragmen URL yang sesuai dengan sumber daya eksternal yang harus dimuat ketika \#isSkipExternalResources().isSkipExternalResources() diatur ke `true`. |
| [setWhitelistedResources(List<String> whitelistedResources)](#setWhitelistedResources-java.util.List-java.lang.String--) | Mengatur daftar fragmen URL yang sesuai dengan sumber daya eksternal yang harus dimuat ketika \#isSkipExternalResources().isSkipExternalResources() diatur ke `true`. |
### LoadOptions() {#LoadOptions--}
```
public LoadOptions()
```


Menginisialisasi instance baru dari kelas LoadOptions.

Untuk contoh kode, lihat [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-file-type-when-loading-a-document/

### LoadOptions(FileType fileType) {#LoadOptions-com.groupdocs.viewer.FileType-}
```
public LoadOptions(FileType fileType)
```


Menginisialisasi instance baru dari kelas LoadOptions.

Untuk contoh kode, lihat [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-file-type-when-loading-a-document/

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.viewer/filetype) | Tipe file yang akan dibuka. |

### DEFAULT_URL_CONNECT_TIMEOUT {#DEFAULT-URL-CONNECT-TIMEOUT}
```
public static final int DEFAULT_URL_CONNECT_TIMEOUT
```


### DEFAULT_URL_READ_TIMEOUT {#DEFAULT-URL-READ-TIMEOUT}
```
public static final int DEFAULT_URL_READ_TIMEOUT
```


### _tryRepair {#-tryRepair}
```
public boolean _tryRepair
```


### isTryRepair() {#isTryRepair--}
```
public boolean isTryRepair()
```


Saat diaktifkan, GroupDocs.Viewer mencoba memperbaiki kerusakan struktural pada dokumen PDF. Nilai default adalah false.

Fitur ini menangani masalah berikut dalam dokumen PDF:

 *  Broken references within the document (incorrect object offsets in the Cross-reference list).
 *  Missing critical elements like root object, page object, or page content.
 *  Circular references (Form X-object referencing itself).

**Returns:**
boolean
### setTryRepair(boolean tryRepair) {#setTryRepair-boolean-}
```
public void setTryRepair(boolean tryRepair)
```


Saat diaktifkan, GroupDocs.Viewer mencoba memperbaiki kerusakan struktural pada dokumen PDF. Nilai default adalah false.

Fitur ini menangani masalah berikut dalam dokumen PDF:

 *  Broken references within the document (incorrect object offsets in the Cross-reference list).
 *  Missing critical elements like root object, page object, or page content.
 *  Circular references (Form X-object referencing itself).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| tryRepair | boolean |  |

### getFileType() {#getFileType--}
```
public final FileType getFileType()
```


Mendapatkan tipe file yang akan dibuka.

Untuk contoh kode, lihat [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-file-type-when-loading-a-document/

**Returns:**
[FileType](../../com.groupdocs.viewer/filetype) - the file type.
### setFileType(FileType value) {#setFileType-com.groupdocs.viewer.FileType-}
```
public final void setFileType(FileType value)
```


Mengatur tipe file yang akan dibuka.

Untuk contoh kode, lihat [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-file-type-when-loading-a-document/

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [FileType](../../com.groupdocs.viewer/filetype) | Tipe file. |

### getPassword() {#getPassword--}
```
public final String getPassword()
```


Mendapatkan kata sandi untuk membuka file terenkripsi.

Untuk contoh kode, lihat [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/load-password-protected-document/

**Returns:**
java.lang.String - kata sandi untuk membuka file.
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Mengatur kata sandi untuk membuka file terenkripsi.

Untuk contoh kode, lihat [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/load-password-protected-document/

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | java.lang.String | Kata sandi untuk membuka file. |

### getCharset() {#getCharset--}
```
public final Charset getCharset()
```


Set charset yang digunakan saat membuka file berbasis teks atau pesan email seperti [FileType.CSV](../../com.groupdocs.viewer/filetype\#CSV), [FileType.TXT](../../com.groupdocs.viewer/filetype\#TXT), dan [FileType.MSG](../../com.groupdocs.viewer/filetype\#MSG).

Nilai default adalah java.nio.charset.StandardCharsets\#UTF\_8.UTF\_8. Untuk contoh kode, lihat [documentation][].

**Learn more**

 *  [Render Excel and Apple Numbers spreadsheets as HTML, PDF, and image files][Render Excel and Apple Numbers spreadsheets as HTML_ PDF_ and image files]
 *  [Render text documents as HTML, PDF, and image files][Render text documents as HTML_ PDF_ and image files]
 *  [Render email messages as HTML, PDF, PNG, and JPEG files][Render email messages as HTML_ PDF_ PNG_ and JPEG files]

**Example:**

```
LoadOptions loadOptions = new LoadOptions();
 loadOptions.setCharset(StandardCharsets.US_ASCII); // Set the charset

 try (Viewer viewer = new Viewer("message.txt", loadOptions)) {
     HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources();

     viewer.view(viewOptions);
 }
```


[documentation]: https://docs.groupdocs.com/viewer/java/specify-encoding-when-loading-documents/
[Render Excel and Apple Numbers spreadsheets as HTML_ PDF_ and image files]: https://docs.groupdocs.com/viewer/java/render-excel-and-apple-numbers-spreadsheets/
[Render text documents as HTML_ PDF_ and image files]: https://docs.groupdocs.com/viewer/java/render-text-files
[Render email messages as HTML_ PDF_ PNG_ and JPEG files]: https://docs.groupdocs.com/viewer/java/render-email-messages/

**Returns:**
java.nio.charset.Charset
### setCharset(Charset value) {#setCharset-java.nio.charset.Charset-}
```
public final void setCharset(Charset value)
```


Set charset yang digunakan saat membuka file berbasis teks atau pesan email seperti [FileType.CSV](../../com.groupdocs.viewer/filetype\#CSV), [FileType.TXT](../../com.groupdocs.viewer/filetype\#TXT), dan [FileType.MSG](../../com.groupdocs.viewer/filetype\#MSG).

Nilai default adalah java.nio.charset.StandardCharsets\#UTF\_8.UTF\_8. Untuk contoh kode, lihat [documentation][].

**Learn more**

 *  [Render Excel and Apple Numbers spreadsheets as HTML, PDF, and image files][Render Excel and Apple Numbers spreadsheets as HTML_ PDF_ and image files]
 *  [Render text documents as HTML, PDF, and image files][Render text documents as HTML_ PDF_ and image files]
 *  [Render email messages as HTML, PDF, PNG, and JPEG files][Render email messages as HTML_ PDF_ PNG_ and JPEG files]

**Example:**

```
LoadOptions loadOptions = new LoadOptions();
 loadOptions.setCharset(StandardCharsets.US_ASCII); // Set the charset

 try (Viewer viewer = new Viewer("message.txt", loadOptions)) {
     HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources();

     viewer.view(viewOptions);
 }
```


[documentation]: https://docs.groupdocs.com/viewer/java/specify-encoding-when-loading-documents/
[Render Excel and Apple Numbers spreadsheets as HTML_ PDF_ and image files]: https://docs.groupdocs.com/viewer/java/render-excel-and-apple-numbers-spreadsheets/
[Render text documents as HTML_ PDF_ and image files]: https://docs.groupdocs.com/viewer/java/render-text-files
[Render email messages as HTML_ PDF_ PNG_ and JPEG files]: https://docs.groupdocs.com/viewer/java/render-email-messages/

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | java.nio.charset.Charset |  |

### isDetectCharset() {#isDetectCharset--}
```
public boolean isDetectCharset()
```


Opsi ini mengaktifkan deteksi charset untuk file [FileType.TXT](../../com.groupdocs.viewer/filetype\#TXT), [FileType.TSV](../../com.groupdocs.viewer/filetype\#TSV), dan [FileType.CSV](../../com.groupdocs.viewer/filetype\#CSV). Jika charset tidak dapat terdeteksi, [getCharset()](../../com.groupdocs.viewer.options/loadoptions\#getCharset--) default akan digunakan.

**Learn more about rendering text and tab/comma delimited files**

 *  [Render text documents as HTML, PDF, and image files][Render text documents as HTML_ PDF_ and image files]
 *  [Render Excel and Apple Numbers spreadsheets as HTML, PDF, and image files][Render Excel and Apple Numbers spreadsheets as HTML_ PDF_ and image files]

Jika encoding tidak dapat terdeteksi, nilai default akan digunakan. Untuk contoh kode, lihat [documentation][].

**Example:**

```
LoadOptions loadOptions = new LoadOptions();
 loadOptions.setDetectCharset(true); // Enable encoding detection

 try (Viewer viewer = new Viewer("employees.csv", loadOptions)) {
     HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources();

     viewer.view(viewOptions);
 }
```


[Render text documents as HTML_ PDF_ and image files]: https://docs.groupdocs.com/viewer/java/render-text-files/
[Render Excel and Apple Numbers spreadsheets as HTML_ PDF_ and image files]: https://docs.groupdocs.com/viewer/java/render-excel-and-apple-numbers-spreadsheets/
[documentation]: https://docs.groupdocs.com/viewer/java/detect-encoding-when-loading-documents/

**Returns:**
boolean
### setDetectCharset(boolean detectCharset) {#setDetectCharset-boolean-}
```
public void setDetectCharset(boolean detectCharset)
```


Opsi ini mengaktifkan deteksi charset untuk file [FileType.TXT](../../com.groupdocs.viewer/filetype\#TXT), [FileType.TSV](../../com.groupdocs.viewer/filetype\#TSV), dan [FileType.CSV](../../com.groupdocs.viewer/filetype\#CSV). Jika charset tidak dapat terdeteksi, [getCharset()](../../com.groupdocs.viewer.options/loadoptions\#getCharset--) default akan digunakan.

**Learn more about rendering text and tab/comma delimited files**

 *  [Render text documents as HTML, PDF, and image files][Render text documents as HTML_ PDF_ and image files]
 *  [Render Excel and Apple Numbers spreadsheets as HTML, PDF, and image files][Render Excel and Apple Numbers spreadsheets as HTML_ PDF_ and image files]

Jika encoding tidak dapat terdeteksi, nilai default akan digunakan. Untuk contoh kode, lihat [documentation][].

**Example:**

```
LoadOptions loadOptions = new LoadOptions();
 loadOptions.setDetectCharset(true); // Enable encoding detection

 try (Viewer viewer = new Viewer("employees.csv", loadOptions)) {
     HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources();

     viewer.view(viewOptions);
 }
```


[Render text documents as HTML_ PDF_ and image files]: https://docs.groupdocs.com/viewer/java/render-text-files/
[Render Excel and Apple Numbers spreadsheets as HTML_ PDF_ and image files]: https://docs.groupdocs.com/viewer/java/render-excel-and-apple-numbers-spreadsheets/
[documentation]: https://docs.groupdocs.com/viewer/java/detect-encoding-when-loading-documents/

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| detectCharset | boolean |  |

### getResourceLoadingTimeout() {#getResourceLoadingTimeout--}
```
public int getResourceLoadingTimeout()
```


Mendapatkan batas waktu untuk memuat sumber daya eksternal.

**Note:** The default value is 10 seconds.

**This option applies to the following file formats:**

 *  [Presentation file formats][]
 *  [Spreadsheet file formats][]
 *  [Web file formats][]
 *  [Word processing file formats][]

**Learn more about options to manage external resources:**

 *  [Set timeout for loading external resources][]

Nilai default adalah 30 detik. Untuk contoh kode, lihat [documentation][].

**Example:**

```
LoadOptions loadOptions = new LoadOptions();
 loadOptions.setResourceLoadingTimeout(5000); // Set resource loading timeout to 5 seconds

 try (Viewer viewer = new Viewer("business-flyer.docx", loadOptions)) {
     HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources();

     viewer.view(viewOptions);
 }
```


[Presentation file formats]: https://docs.groupdocs.com/viewer/java/supported-document-formats/#presentation-file-formats
[Spreadsheet file formats]: https://docs.groupdocs.com/viewer/java/supported-document-formats/#spreadsheet-file-formats
[Web file formats]: https://docs.groupdocs.com/viewer/java/supported-document-formats/#web-file-formats
[Word processing file formats]: https://docs.groupdocs.com/viewer/java/supported-document-formats/#word-processing-file-formats
[Set timeout for loading external resources]: https://docs.groupdocs.com/viewer/java/set-timeout-for-loading-external-resources-contained-by-a-document/
[documentation]: https://docs.groupdocs.com/viewer/java/detect-encoding-when-loading-documents

**Returns:**
int
### setResourceLoadingTimeout(int resourceLoadingTimeout) {#setResourceLoadingTimeout-int-}
```
public void setResourceLoadingTimeout(int resourceLoadingTimeout)
```


Mengatur batas waktu untuk memuat sumber daya eksternal, seperti grafik.

***Note:** The default value is 30 seconds.*

Opsi ini didukung untuk dokumen Pengolah Kata yang berisi sumber daya eksternal. Nilai default adalah 30 detik. Untuk contoh kode, lihat [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/detect-encoding-when-loading-documents

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| resourceLoadingTimeout | int | Batas waktu pemuatan, milidetik. |

### getUrlConnectTimeout() {#getUrlConnectTimeout--}
```
public int getUrlConnectTimeout()
```


Mendapatkan batas waktu koneksi untuk membuat [Viewer](../../com.groupdocs.viewer/viewer) menggunakan java.net.URL untuk memuat dokumen.

***Note:** The default value is 5 seconds.*

**Returns:**
int - batas waktu koneksi.
### setUrlConnectTimeout(int urlConnectTimeout) {#setUrlConnectTimeout-int-}
```
public void setUrlConnectTimeout(int urlConnectTimeout)
```


Mengatur batas waktu koneksi untuk membuat [Viewer](../../com.groupdocs.viewer/viewer) menggunakan java.net.URL untuk memuat dokumen.

***Note:** The default value is 5 seconds.*

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| urlConnectTimeout | int | Batas waktu koneksi. |

### getUrlReadTimeout() {#getUrlReadTimeout--}
```
public int getUrlReadTimeout()
```


Mendapatkan batas waktu baca untuk membuat [Viewer](../../com.groupdocs.viewer/viewer) menggunakan java.net.URL untuk memuat dokumen.

***Note:** The default value is 30 seconds.*

**Returns:**
int - batas waktu baca.
### setUrlReadTimeout(int urlReadTimeout) {#setUrlReadTimeout-int-}
```
public void setUrlReadTimeout(int urlReadTimeout)
```


Mengatur batas waktu baca untuk membuat [Viewer](../../com.groupdocs.viewer/viewer) menggunakan java.net.URL untuk memuat dokumen.

***Note:** The default value is 30 seconds.*

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| urlReadTimeout | int | Batas waktu baca. |

### getArchiveSecurityOptions() {#getArchiveSecurityOptions--}
```
public ArchiveSecurityOptions getArchiveSecurityOptions()
```


Mendapatkan opsi keamanan untuk mengontrol proses ekstraksi arsip.

***Note:** Not each archive type supports all options.*

**Returns:**
com.groupdocs.viewer.options.ArchiveSecurityOptions - objek opsi untuk mengkonfigurasi proses mengekstrak arsip.
### setArchiveSecurityOptions(ArchiveSecurityOptions archiveSecurityOptions) {#setArchiveSecurityOptions-com.groupdocs.viewer.options.ArchiveSecurityOptions-}
```
public void setArchiveSecurityOptions(ArchiveSecurityOptions archiveSecurityOptions)
```


Mengatur opsi keamanan untuk mengontrol proses mengekstrak arsip.

***Note:** Not each archive type supports all options.*

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| archiveSecurityOptions | com.groupdocs.viewer.options.ArchiveSecurityOptions | Objek opsi untuk mengkonfigurasi proses mengekstrak arsip. |

### isSkipExternalResources() {#isSkipExternalResources--}
```
public boolean isSkipExternalResources()
```


Saat diatur ke true, semua sumber daya eksternal seperti gambar tidak akan dimuat kecuali \#getWhitelistedResources().getWhitelistedResources().

**This option applies to the following file formats:**

 *  [Presentation file formats][]
 *  [Spreadsheet file formats][]
 *  [Web file formats][]
 *  [Word processing file formats][]

**Learn more about options to manage external resources:**

 *  [Set timeout for loading external resources][]

**Example:**

```
LoadOptions loadOptions = new LoadOptions();
 loadOptions.setSkipExternalResources(true); // Skip loading of external resources

 try (Viewer viewer = new Viewer("business-flyer.docx", loadOptions)) {
     HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources();

     viewer.view(viewOptions);
 }
```


[Presentation file formats]: https://docs.groupdocs.com/viewer/java/supported-document-formats/#presentation-file-formats
[Spreadsheet file formats]: https://docs.groupdocs.com/viewer/java/supported-document-formats/#spreadsheet-file-formats
[Web file formats]: https://docs.groupdocs.com/viewer/java/supported-document-formats/#web-file-formats
[Word processing file formats]: https://docs.groupdocs.com/viewer/java/supported-document-formats/#word-processing-file-formats
[Set timeout for loading external resources]: https://docs.groupdocs.com/viewer/java/set-timeout-for-loading-external-resources-contained-by-a-document/

**Returns:**
boolean
### setSkipExternalResources(boolean skipExternalResources) {#setSkipExternalResources-boolean-}
```
public void setSkipExternalResources(boolean skipExternalResources)
```


Saat diatur ke true, semua sumber daya eksternal seperti gambar tidak akan dimuat kecuali \#getWhitelistedResources().getWhitelistedResources().

**This option applies to the following file formats:**

 *  [Presentation file formats][]
 *  [Spreadsheet file formats][]
 *  [Web file formats][]
 *  [Word processing file formats][]

**Learn more about options to manage external resources:**

 *  [Set timeout for loading external resources][]

**Example:**

```
LoadOptions loadOptions = new LoadOptions();
 loadOptions.setSkipExternalResources(true); // Skip loading of external resources

 try (Viewer viewer = new Viewer("business-flyer.docx", loadOptions)) {
     HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources();

     viewer.view(viewOptions);
 }
```


[Presentation file formats]: https://docs.groupdocs.com/viewer/java/supported-document-formats/#presentation-file-formats
[Spreadsheet file formats]: https://docs.groupdocs.com/viewer/java/supported-document-formats/#spreadsheet-file-formats
[Web file formats]: https://docs.groupdocs.com/viewer/java/supported-document-formats/#web-file-formats
[Word processing file formats]: https://docs.groupdocs.com/viewer/java/supported-document-formats/#word-processing-file-formats
[Set timeout for loading external resources]: https://docs.groupdocs.com/viewer/java/set-timeout-for-loading-external-resources-contained-by-a-document/

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| skipExternalResources | boolean | Bendera untuk mengaktifkan atau menonaktifkan pemuatan sumber daya eksternal. |

### getWhitelistedResources() {#getWhitelistedResources--}
```
public List<String> getWhitelistedResources()
```


Daftar fragmen URL yang sesuai dengan sumber daya eksternal yang harus dimuat ketika \#isSkipExternalResources().isSkipExternalResources() diatur ke `true`.

**This option applies to the following file formats:**

 *  [Presentation file formats][]
 *  [Spreadsheet file formats][]
 *  [Web file formats][]
 *  [Word processing file formats][]

**Learn more about options to manage external resources:**

 *  [Set timeout for loading external resources][]

**Example:**

```
LoadOptions loadOptions = new LoadOptions();
 loadOptions.setSkipExternalResources(true); // Skip loading of external resources
 loadOptions.getWhitelistedResources().add("avatars.githubusercontent.com"); // Enable loading of external resources that have 'avatars.githubusercontent.com' fragment in resource URL.
 try (Viewer viewer = new Viewer("business-flyer.docx", loadOptions)) {
     HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources();

     viewer.view(viewOptions);
 }
```


[Presentation file formats]: https://docs.groupdocs.com/viewer/java/supported-document-formats/#presentation-file-formats
[Spreadsheet file formats]: https://docs.groupdocs.com/viewer/java/supported-document-formats/#spreadsheet-file-formats
[Web file formats]: https://docs.groupdocs.com/viewer/java/supported-document-formats/#web-file-formats
[Word processing file formats]: https://docs.groupdocs.com/viewer/java/supported-document-formats/#word-processing-file-formats
[Set timeout for loading external resources]: https://docs.groupdocs.com/viewer/java/set-timeout-for-loading-external-resources-contained-by-a-document/

**Returns:**
java.util.List<java.lang.String>
### setWhitelistedResources(List<String> whitelistedResources) {#setWhitelistedResources-java.util.List-java.lang.String--}
```
public void setWhitelistedResources(List<String> whitelistedResources)
```


Mengatur daftar fragmen URL yang sesuai dengan sumber daya eksternal yang harus dimuat ketika \#isSkipExternalResources().isSkipExternalResources() diatur ke `true`.

**This option applies to the following file formats:**

 *  [Presentation file formats][]
 *  [Spreadsheet file formats][]
 *  [Web file formats][]
 *  [Word processing file formats][]

**Learn more about options to manage external resources:**

 *  [Set timeout for loading external resources][]

**Example:**

```
LoadOptions loadOptions = new LoadOptions();
 loadOptions.setSkipExternalResources(true); // Skip loading of external resources
 loadOptions.setWhitelistedResources(Arrays.asList("avatars.githubusercontent.com")); // Enable loading of external resources that have 'avatars.githubusercontent.com' fragment in resource URL.
 try (Viewer viewer = new Viewer("business-flyer.docx", loadOptions)) {
     HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources();

     viewer.view(viewOptions);
 }
```


[Presentation file formats]: https://docs.groupdocs.com/viewer/java/supported-document-formats/#presentation-file-formats
[Spreadsheet file formats]: https://docs.groupdocs.com/viewer/java/supported-document-formats/#spreadsheet-file-formats
[Web file formats]: https://docs.groupdocs.com/viewer/java/supported-document-formats/#web-file-formats
[Word processing file formats]: https://docs.groupdocs.com/viewer/java/supported-document-formats/#word-processing-file-formats
[Set timeout for loading external resources]: https://docs.groupdocs.com/viewer/java/set-timeout-for-loading-external-resources-contained-by-a-document/

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| whitelistedResources | java.util.List<java.lang.String> | Daftar fragmen URL yang sesuai dengan sumber daya eksternal yang harus dimuat. |

