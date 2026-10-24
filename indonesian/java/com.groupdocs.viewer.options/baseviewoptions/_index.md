---
title: "BaseViewOptions"
second_title: "Referensi API GroupDocs.Viewer for Java"
description: "Berisi opsi rendering dasar."
type: docs
weight: 12
url: /id/java/com.groupdocs.viewer.options/baseviewoptions/
---
**Inheritance:**
java.lang.Object
```
public abstract class BaseViewOptions
```

Berisi opsi rendering dasar.


The
BaseViewOptions
kelas berfungsi sebagai dasar untuk opsi rendering di GroupDocs.Viewer.
Ini memungkinkan Anda menyesuaikan perilaku rendering dari file HTML, PDF, PNG, dan JPEG output saat merender
format dokumen tertentu.


***Note:** For internal usage.*

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [BaseViewOptions()](#BaseViewOptions--) |  |
## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [getTextOptions()](#getTextOptions--) | Mengambil opsi untuk membagi file teks menjadi halaman. |
|
|  | [setTextOptions(TextOptions textOptions)](#setTextOptions-com.groupdocs.viewer.options.TextOptions-) | Mengatur opsi untuk membagi file teks menjadi halaman. |
|
|  | [isRenderComments()](#isRenderComments--) | Mengaktifkan rendering komentar. |
|
|  | [setRenderComments(boolean value)](#setRenderComments-boolean-) | Mengaktifkan rendering komentar. |
|
|  | [isRemoveComments()](#isRemoveComments--) | Menonaktifkan rendering komentar ketika diatur ke true. |
|
|  | [setRemoveComments(boolean value)](#setRemoveComments-boolean-) | Menonaktifkan rendering komentar ketika diatur ke true. |
|
|  | [isRenderNotes()](#isRenderNotes--) | Mengaktifkan rendering catatan. |
|
|  | [setRenderNotes(boolean value)](#setRenderNotes-boolean-) | Mengaktifkan rendering catatan. |
|
|  | [isRenderHiddenPages()](#isRenderHiddenPages--) | Mengaktifkan rendering halaman tersembunyi. |
|
|  | [setRenderHiddenPages(boolean value)](#setRenderHiddenPages-boolean-) | Mengaktifkan rendering halaman tersembunyi. |
|
|  | [getDefaultFontName()](#getDefaultFontName--) | Font default yang akan digunakan ketika font tertentu yang digunakan dalam dokumen tidak dapat ditemukan. |
|
|  | [setDefaultFontName(String value)](#setDefaultFontName-java.lang.String-) | Font default yang akan digunakan ketika font tertentu yang digunakan dalam dokumen tidak dapat ditemukan. |
|
|  | [getArchiveOptions()](#getArchiveOptions--) | Mengambil opsi tampilan file arsip. |
|
|  | [setArchiveOptions(ArchiveOptions value)](#setArchiveOptions-com.groupdocs.viewer.options.ArchiveOptions-) | Mengatur opsi tampilan file arsip. |
|
|  | [getCadOptions()](#getCadOptions--) | Mengambil opsi tampilan gambar CAD. |
|
|  | [setCadOptions(CadOptions value)](#setCadOptions-com.groupdocs.viewer.options.CadOptions-) | Mengatur opsi tampilan gambar CAD. |
|
| [isCadOptionsInitialized_Internal()](#isCadOptionsInitialized-Internal--) |  |
|  | [getEmailOptions()](#getEmailOptions--) | Mengambil opsi tampilan pesan email. |
|
|  | [setEmailOptions(EmailOptions value)](#setEmailOptions-com.groupdocs.viewer.options.EmailOptions-) | Mengatur opsi tampilan pesan email. |
|
|  | [getOutlookOptions()](#getOutlookOptions--) | Mengambil opsi tampilan file data MS Outlook. |
|
|  | [setOutlookOptions(OutlookOptions value)](#setOutlookOptions-com.groupdocs.viewer.options.OutlookOptions-) | Mengatur opsi tampilan file data MS Outlook. |
|
|  | [getPdfOptions()](#getPdfOptions--) | Mengambil opsi tampilan dokumen PDF. |
|
|  | [setPdfOptions(PdfOptions value)](#setPdfOptions-com.groupdocs.viewer.options.PdfOptions-) | Mengambil opsi tampilan dokumen PDF. |
|
|  | [getMailStorageOptions()](#getMailStorageOptions--) | Mengambil opsi tampilan file data penyimpanan Lotus Notes. |
|
|  | [setMailStorageOptions(MailStorageOptions mailStorageOptions)](#setMailStorageOptions-com.groupdocs.viewer.options.MailStorageOptions-) | Mengatur opsi tampilan file data penyimpanan Lotus Notes. |
|
|  | [getProjectManagementOptions()](#getProjectManagementOptions--) | Mengambil opsi tampilan file manajemen proyek. |
|
|  | [setProjectManagementOptions(ProjectManagementOptions projectManagementOptions)](#setProjectManagementOptions-com.groupdocs.viewer.options.ProjectManagementOptions-) | Mengatur opsi tampilan file manajemen proyek. |
|
|  | [getSpreadsheetOptions()](#getSpreadsheetOptions--) | Mengambil opsi tampilan file spreadsheet. |
|
|  | [setSpreadsheetOptions(SpreadsheetOptions value)](#setSpreadsheetOptions-com.groupdocs.viewer.options.SpreadsheetOptions-) | Mengatur opsi tampilan file spreadsheet. |
|
|  | [getWordProcessingOptions()](#getWordProcessingOptions--) | Opsi tampilan file pengolahan Word. |
|
|  | [setWordProcessingOptions(WordProcessingOptions wordProcessingOptions)](#setWordProcessingOptions-com.groupdocs.viewer.options.WordProcessingOptions-) | Opsi tampilan file pengolahan Word. |
|
|  | [getVisioRenderingOptions()](#getVisioRenderingOptions--) | Mengambil opsi rendering untuk memproses file Visio saat melihat dokumen. |
|
|  | [setVisioRenderingOptions(VisioRenderingOptions visioRenderingOptions)](#setVisioRenderingOptions-com.groupdocs.viewer.options.VisioRenderingOptions-) | Mengatur opsi rendering untuk memproses file Visio saat melihat dokumen. |
|
|  | [getPresentationOptions()](#getPresentationOptions--) | Mengambil opsi tampilan untuk memproses dokumen presentasi. |
|
|  | [setPresentationOptions(PresentationOptions presentationOptions)](#setPresentationOptions-com.groupdocs.viewer.options.PresentationOptions-) | Mengatur opsi tampilan untuk memproses dokumen presentasi. |
|
|  | [getWebDocumentOptions()](#getWebDocumentOptions--) | Mendapatkan opsi rendering yang memungkinkan penyesuaian tampilan output HTML/PDF/PNG/JPEG |
saat merender dokumen Web.
|
|  | [setWebDocumentOptions(WebDocumentOptions webDocumentOptions)](#setWebDocumentOptions-com.groupdocs.viewer.options.WebDocumentOptions-) | Mengatur opsi rendering yang memungkinkan penyesuaian tampilan output HTML/PDF/PNG/JPEG |
saat merender dokumen Web.
|
### BaseViewOptions() {#BaseViewOptions--}
```
public BaseViewOptions()
```


### getTextOptions() {#getTextOptions--}
```
public TextOptions getTextOptions()
```


Mengambil opsi untuk membagi file teks menjadi halaman.


Untuk informasi lebih lanjut dan contoh kode, lihat [dokumentasi](../https://docs.groupdocs.com/viewer/java/render-text-files/).


**Returns:**
[TextOptions](../../com.groupdocs.viewer.options/textoptions) - the text file splitting options.

### setTextOptions(TextOptions textOptions) {#setTextOptions-com.groupdocs.viewer.options.TextOptions-}
```
public void setTextOptions(TextOptions textOptions)
```


Mengatur opsi untuk membagi file teks menjadi halaman.


Untuk informasi lebih lanjut dan contoh kode, lihat [dokumentasi](../https://docs.groupdocs.com/viewer/java/render-text-files/).


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | textOptions | [TextOptions](../../com.groupdocs.viewer.options/textoptions) | Opsi pemisahan file teks. |
|

### isRenderComments() {#isRenderComments--}
```
public final boolean isRenderComments()
```


Mengaktifkan rendering komentar.


Secara default, GroupDocs.Viewer tidak merender komentar. Untuk melakukannya, set properti ini ke true.
Untuk contoh kode, lihat [dokumentasi](../https://docs.groupdocs.com/viewer/java/render-word-documents/#render-comments).


**Returns:**
boolean -  true  jika komentar harus dirender,  false  sebaliknya.

### setRenderComments(boolean value) {#setRenderComments-boolean-}
```
public final void setRenderComments(boolean value)
```


Mengaktifkan rendering komentar.


Secara default, GroupDocs.Viewer tidak merender komentar. Untuk melakukannya, set properti ini ke true.
Untuk contoh kode, lihat [dokumentasi](../https://docs.groupdocs.com/viewer/java/render-word-documents/#render-comments).


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | nilai | boolean | true  jika komentar harus dirender,  false  sebaliknya. |
|

### isRemoveComments() {#isRemoveComments--}
```
public final boolean isRemoveComments()
```


Menonaktifkan rendering komentar ketika diset ke true. Secara default adalah false \\u2014 semua komentar ditampilkan.


Beberapa format dokumen seperti PDF dan WordProcessing mungkin berisi komentar. Secara default GroupDocs.Viewer merendernya. Dengan opsi ini diset ke true, komentar dapat dikecualikan dari dokumen hasil.
Opsi ini menggantikan properti 'RenderComments' yang usang.


**Returns:**
boolean -  true  jika komentar harus dirender,  false  sebaliknya.

### setRemoveComments(boolean value) {#setRemoveComments-boolean-}
```
public final void setRemoveComments(boolean value)
```


Menonaktifkan rendering komentar ketika diset ke true. Secara default adalah false \\u2014 semua komentar ditampilkan.


Beberapa format dokumen seperti PDF dan WordProcessing mungkin berisi komentar. Secara default GroupDocs.Viewer merendernya. Dengan opsi ini diset ke true, komentar dapat dikecualikan dari dokumen hasil.
Opsi ini menggantikan properti 'RenderComments' yang usang.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | nilai | boolean | true  jika komentar harus dirender,  false  sebaliknya. |
|

### isRenderNotes() {#isRenderNotes--}
```
public final boolean isRenderNotes()
```


Mengaktifkan rendering catatan.


Beberapa file, seperti presentasi atau file Microsoft Project, mungkin berisi catatan. Secara default, GroupDocs.Viewer tidak merender catatan. Untuk melakukannya, set properti ini ke true.
Untuk contoh kode, lihat [dokumentasi](../https://docs.groupdocs.com/viewer/java/render-presentations/#render-speaker-notes).


**Returns:**
boolean -  true  jika catatan harus dirender,  false  sebaliknya.

### setRenderNotes(boolean value) {#setRenderNotes-boolean-}
```
public final void setRenderNotes(boolean value)
```


Mengaktifkan rendering catatan.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | nilai | boolean | true  jika catatan harus dirender,  false  sebaliknya. |
|

### isRenderHiddenPages() {#isRenderHiddenPages--}
```
public final boolean isRenderHiddenPages()
```


Mengaktifkan rendering halaman tersembunyi.


Beberapa file, seperti presentasi atau spreadsheet, mungkin berisi halaman tersembunyi. Secara default, GroupDocs.Viewer tidak merender halaman tersebut. Untuk melakukannya, set properti ini ke true.
Untuk contoh kode, lihat [dokumentasi](../https://docs.groupdocs.com/viewer/java/render-presentations/#render-hidden-slides).


**Returns:**
boolean -  true  jika halaman tersembunyi harus dirender,  false  sebaliknya.

### setRenderHiddenPages(boolean value) {#setRenderHiddenPages-boolean-}
```
public final void setRenderHiddenPages(boolean value)
```


Mengaktifkan rendering halaman tersembunyi.


Beberapa file, seperti presentasi atau spreadsheet, mungkin berisi halaman tersembunyi. Secara default, GroupDocs.Viewer tidak merender halaman tersebut. Untuk melakukannya, set properti ini ke true.
Untuk contoh kode, lihat [dokumentasi](../https://docs.groupdocs.com/viewer/java/render-presentations/#render-hidden-slides).


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | nilai | boolean | true  jika halaman tersembunyi harus dirender,  false  sebaliknya. |
|

### getDefaultFontName() {#getDefaultFontName--}
```
public final String getDefaultFontName()
```


Font default yang akan digunakan ketika font tertentu yang digunakan dalam dokumen tidak dapat ditemukan.


Gunakan properti ini untuk mengatur font default untuk sebuah dokumen. GroupDocs.Viewer menggunakan font ini selama proses rendering alih-alih font yang tidak terpasang.
Untuk contoh kode, lihat [documentation](../https://docs.groupdocs.com/viewer/java/replace-missing-font/).


**Returns:**
java.lang.String - nama font default.

### setDefaultFontName(String value) {#setDefaultFontName-java.lang.String-}
```
public final void setDefaultFontName(String value)
```


Font default yang akan digunakan ketika font tertentu yang digunakan dalam dokumen tidak dapat ditemukan.


Gunakan properti ini untuk mengatur font default untuk sebuah dokumen. GroupDocs.Viewer menggunakan font ini selama proses rendering alih-alih font yang tidak terpasang.
Untuk contoh kode, lihat [documentation](../https://docs.groupdocs.com/viewer/java/replace-missing-font/).


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | nilai | java.lang.String | Nama font default. |
|

### getArchiveOptions() {#getArchiveOptions--}
```
public final ArchiveOptions getArchiveOptions()
```


Mengambil opsi tampilan file arsip.


Untuk informasi lebih lanjut dan contoh kode, lihat [documentation](../https://docs.groupdocs.com/viewer/java/render-archive-files/).


**Returns:**
[ArchiveOptions](../../com.groupdocs.viewer.options/archiveoptions) - the archive files view options.

### setArchiveOptions(ArchiveOptions value) {#setArchiveOptions-com.groupdocs.viewer.options.ArchiveOptions-}
```
public final void setArchiveOptions(ArchiveOptions value)
```


Mengatur opsi tampilan file arsip.


Untuk informasi lebih lanjut dan contoh kode, lihat [documentation](../https://docs.groupdocs.com/viewer/java/render-archive-files/).


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | value | [ArchiveOptions](../../com.groupdocs.viewer.options/archiveoptions) | Opsi tampilan file arsip. |
|

### getCadOptions() {#getCadOptions--}
```
public final CadOptions getCadOptions()
```


Mengambil opsi tampilan gambar CAD.


Untuk informasi lebih lanjut dan contoh kode, lihat [Render CAD drawings and models as HTML, PDF, and image files](../https://docs.groupdocs.com/viewer/net/render-cad-drawings-and-models/) dan [Specify rendering options for CAD files](../https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/).


**Returns:**
[CadOptions](../../com.groupdocs.viewer.options/cadoptions) - the CAD drawing view options.

### setCadOptions(CadOptions value) {#setCadOptions-com.groupdocs.viewer.options.CadOptions-}
```
public final void setCadOptions(CadOptions value)
```


Mengatur opsi tampilan gambar CAD.


Untuk informasi lebih lanjut dan contoh kode, lihat [Render CAD drawings and models as HTML, PDF, and image files](../https://docs.groupdocs.com/viewer/net/render-cad-drawings-and-models/) dan [Specify rendering options for CAD files](../https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/).


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | value | [CadOptions](../../com.groupdocs.viewer.options/cadoptions) | Opsi tampilan gambar CAD. |
|

### isCadOptionsInitialized_Internal() {#isCadOptionsInitialized-Internal--}
```
public boolean isCadOptionsInitialized_Internal()
```




**Returns:**
boolean
### getEmailOptions() {#getEmailOptions--}
```
public final EmailOptions getEmailOptions()
```


Mengambil opsi tampilan pesan email.


Untuk informasi lebih lanjut dan contoh kode, lihat [documentation](../https://docs.groupdocs.com/viewer/java/render-email-messages/).


**Returns:**
[EmailOptions](../../com.groupdocs.viewer.options/emailoptions) - Email messages view options.

### setEmailOptions(EmailOptions value) {#setEmailOptions-com.groupdocs.viewer.options.EmailOptions-}
```
public final void setEmailOptions(EmailOptions value)
```


Mengatur opsi tampilan pesan email.


Untuk informasi lebih lanjut dan contoh kode, lihat [documentation](../https://docs.groupdocs.com/viewer/java/render-email-messages/).


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | value | [EmailOptions](../../com.groupdocs.viewer.options/emailoptions) | Opsi tampilan pesan email. |
|

### getOutlookOptions() {#getOutlookOptions--}
```
public final OutlookOptions getOutlookOptions()
```


Mengambil opsi tampilan file data MS Outlook.


Untuk informasi lebih lanjut dan contoh kode, lihat [documentation](../https://docs.groupdocs.com/viewer/java/render-outlook-data-files/).


**Returns:**
[OutlookOptions](../../com.groupdocs.viewer.options/outlookoptions) - MS Outlook data files view options.

### setOutlookOptions(OutlookOptions value) {#setOutlookOptions-com.groupdocs.viewer.options.OutlookOptions-}
```
public final void setOutlookOptions(OutlookOptions value)
```


Mengatur opsi tampilan file data MS Outlook.


Untuk informasi lebih lanjut dan contoh kode, lihat [documentation](../https://docs.groupdocs.com/viewer/java/render-outlook-data-files/).


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | value | [OutlookOptions](../../com.groupdocs.viewer.options/outlookoptions) | Opsi tampilan file data MS Outlook yang akan diatur. |
|

### getPdfOptions() {#getPdfOptions--}
```
public final PdfOptions getPdfOptions()
```


Mengambil opsi tampilan dokumen PDF.


Untuk informasi lebih lanjut dan contoh kode, lihat [documentation](../https://docs.groupdocs.com/viewer/java/render-pdf-documents/).


**Returns:**
[PdfOptions](../../com.groupdocs.viewer.options/pdfoptions) - the PDF documents view options.

### setPdfOptions(PdfOptions value) {#setPdfOptions-com.groupdocs.viewer.options.PdfOptions-}
```
public final void setPdfOptions(PdfOptions value)
```


Mengambil opsi tampilan dokumen PDF.


Untuk informasi lebih lanjut dan contoh kode, lihat [documentation](../https://docs.groupdocs.com/viewer/java/render-pdf-documents/).


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | value | [PdfOptions](../../com.groupdocs.viewer.options/pdfoptions) | Opsi tampilan dokumen PDF. |
|

### getMailStorageOptions() {#getMailStorageOptions--}
```
public MailStorageOptions getMailStorageOptions()
```


Mengambil opsi tampilan file data penyimpanan Lotus Notes.


**Returns:**
[MailStorageOptions](../../com.groupdocs.viewer.options/mailstorageoptions) - the Lotus Notes storage data files view options.

### setMailStorageOptions(MailStorageOptions mailStorageOptions) {#setMailStorageOptions-com.groupdocs.viewer.options.MailStorageOptions-}
```
public void setMailStorageOptions(MailStorageOptions mailStorageOptions)
```


Mengatur opsi tampilan file data penyimpanan Lotus Notes.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | mailStorageOptions | [MailStorageOptions](../../com.groupdocs.viewer.options/mailstorageoptions) | Opsi tampilan file data penyimpanan Lotus Notes. |
|

### getProjectManagementOptions() {#getProjectManagementOptions--}
```
public final ProjectManagementOptions getProjectManagementOptions()
```


Mengambil opsi tampilan file manajemen proyek.


Untuk informasi lebih lanjut dan contoh kode, lihat [documentation](../https://docs.groupdocs.com/viewer/java/render-ms-project-files/).


**Returns:**
[ProjectManagementOptions](../../com.groupdocs.viewer.options/projectmanagementoptions) - the project management files view options.

### setProjectManagementOptions(ProjectManagementOptions projectManagementOptions) {#setProjectManagementOptions-com.groupdocs.viewer.options.ProjectManagementOptions-}
```
public final void setProjectManagementOptions(ProjectManagementOptions projectManagementOptions)
```


Mengatur opsi tampilan file manajemen proyek.


Untuk informasi lebih lanjut dan contoh kode, lihat [documentation](../https://docs.groupdocs.com/viewer/java/render-ms-project-files/).


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | projectManagementOptions | [ProjectManagementOptions](../../com.groupdocs.viewer.options/projectmanagementoptions) | Opsi tampilan file manajemen proyek yang akan diatur. |
|

### getSpreadsheetOptions() {#getSpreadsheetOptions--}
```
public final SpreadsheetOptions getSpreadsheetOptions()
```


Mengambil opsi tampilan file spreadsheet.


Untuk informasi lebih lanjut dan contoh kode, lihat [Render Excel and Apple Numbers spreadsheets as HTML, PDF, and image files](../https://docs.groupdocs.com/viewer/java/render-excel-and-apple-numbers-spreadsheets/), [Split a worksheet into pages](../https://docs.groupdocs.com/viewer/net/split-worksheet-into-pages/), dan [Specify spreadsheet rendering options](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/).


**Returns:**
[SpreadsheetOptions](../../com.groupdocs.viewer.options/spreadsheetoptions) - the spreadsheet files view options.

### setSpreadsheetOptions(SpreadsheetOptions value) {#setSpreadsheetOptions-com.groupdocs.viewer.options.SpreadsheetOptions-}
```
public final void setSpreadsheetOptions(SpreadsheetOptions value)
```


Mengatur opsi tampilan file spreadsheet.


Untuk informasi lebih lanjut dan contoh kode, lihat [Render Excel and Apple Numbers spreadsheets as HTML, PDF, and image files](../https://docs.groupdocs.com/viewer/java/render-excel-and-apple-numbers-spreadsheets/), [Split a worksheet into pages](../https://docs.groupdocs.com/viewer/net/split-worksheet-into-pages/), dan [Specify spreadsheet rendering options](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/).


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | value | [SpreadsheetOptions](../../com.groupdocs.viewer.options/spreadsheetoptions) | Opsi tampilan file spreadsheet. |
|

### getWordProcessingOptions() {#getWordProcessingOptions--}
```
public final WordProcessingOptions getWordProcessingOptions()
```


Opsi tampilan file pengolahan Word.


Untuk informasi lebih lanjut dan contoh kode, lihat [documentation](../https://docs.groupdocs.com/viewer/java/render-word-documents/).


**Returns:**
[WordProcessingOptions](../../com.groupdocs.viewer.options/wordprocessingoptions) - the Word processing options for rendering Word documents.

### setWordProcessingOptions(WordProcessingOptions wordProcessingOptions) {#setWordProcessingOptions-com.groupdocs.viewer.options.WordProcessingOptions-}
```
public final void setWordProcessingOptions(WordProcessingOptions wordProcessingOptions)
```


Opsi tampilan file pengolahan Word.


Untuk informasi lebih lanjut dan contoh kode, lihat [documentation](../https://docs.groupdocs.com/viewer/java/render-word-documents/).


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | wordProcessingOptions | [WordProcessingOptions](../../com.groupdocs.viewer.options/wordprocessingoptions) | Opsi pemrosesan Word untuk merender dokumen Word. |
|

### getVisioRenderingOptions() {#getVisioRenderingOptions--}
```
public VisioRenderingOptions getVisioRenderingOptions()
```


Mengambil opsi rendering untuk memproses file Visio saat melihat dokumen.


Untuk informasi lebih lanjut dan contoh kode, lihat [documentation](../https://docs.groupdocs.com/viewer/java/render-visio-documents/).


**Returns:**
[VisioRenderingOptions](../../com.groupdocs.viewer.options/visiorenderingoptions) - the Visio rendering options for processing Visio files.

### setVisioRenderingOptions(VisioRenderingOptions visioRenderingOptions) {#setVisioRenderingOptions-com.groupdocs.viewer.options.VisioRenderingOptions-}
```
public void setVisioRenderingOptions(VisioRenderingOptions visioRenderingOptions)
```


Mengatur opsi rendering untuk memproses file Visio saat melihat dokumen.


Untuk informasi lebih lanjut dan contoh kode, lihat [documentation](../https://docs.groupdocs.com/viewer/java/render-visio-documents/).


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | visioRenderingOptions | [VisioRenderingOptions](../../com.groupdocs.viewer.options/visiorenderingoptions) | Opsi rendering Visio untuk memproses file Visio. |
|

### getPresentationOptions() {#getPresentationOptions--}
```
public PresentationOptions getPresentationOptions()
```


Mengambil opsi tampilan untuk memproses dokumen presentasi.


Untuk informasi lebih lanjut dan contoh kode, lihat [dokumentasi](../https://docs.groupdocs.com/viewer/java/render-presentations/).


**Returns:**
com.groupdocs.viewer.options.PresentationOptions - opsi tampilan presentasi untuk memproses dokumen presentasi.

### setPresentationOptions(PresentationOptions presentationOptions) {#setPresentationOptions-com.groupdocs.viewer.options.PresentationOptions-}
```
public void setPresentationOptions(PresentationOptions presentationOptions)
```


Mengatur opsi tampilan untuk memproses dokumen presentasi.


Untuk informasi lebih lanjut dan contoh kode, lihat [dokumentasi](../https://docs.groupdocs.com/viewer/java/render-presentations/).


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | presentationOptions | com.groupdocs.viewer.options.PresentationOptions | Opsi tampilan presentasi untuk memproses dokumen presentasi. |
|

### getWebDocumentOptions() {#getWebDocumentOptions--}
```
public WebDocumentOptions getWebDocumentOptions()
```


Mendapatkan opsi rendering yang memungkinkan penyesuaian tampilan output HTML/PDF/PNG/JPEG
saat merender dokumen Web.


Untuk informasi lebih lanjut dan contoh kode, lihat [dokumentasi](../https://docs.groupdocs.com/viewer/java/render-web-documents/).


**Returns:**
com.groupdocs.viewer.options.WebDocumentOptions - objek WebDocumentOptions untuk menyesuaikan opsi rendering.

### setWebDocumentOptions(WebDocumentOptions webDocumentOptions) {#setWebDocumentOptions-com.groupdocs.viewer.options.WebDocumentOptions-}
```
public void setWebDocumentOptions(WebDocumentOptions webDocumentOptions)
```


Mengatur opsi rendering yang memungkinkan penyesuaian tampilan output HTML/PDF/PNG/JPEG
saat merender dokumen Web.


Untuk informasi lebih lanjut dan contoh kode, lihat [dokumentasi](../https://docs.groupdocs.com/viewer/java/render-web-documents/).


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | webDocumentOptions | com.groupdocs.viewer.options.WebDocumentOptions | Objek WebDocumentOptions untuk menyesuaikan opsi rendering. |
|

