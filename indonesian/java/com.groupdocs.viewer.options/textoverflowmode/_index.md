---
title: "TextOverflowMode"
second_title: "Referensi API GroupDocs.Viewer for Java"
description: "Mendefinisikan mode overflow teks untuk merender dokumen spreadsheet menjadi HTML."
type: docs
weight: 46
url: /id/java/com.groupdocs.viewer.options/textoverflowmode/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum TextOverflowMode extends Enum<TextOverflowMode>
```

Mendefinisikan mode overflow teks untuk merender dokumen spreadsheet menjadi HTML.


Enum TextOverflowMode mewakili berbagai mode untuk menangani kelebihan teks dalam komponen GroupDocs.Viewer.
Ini menyediakan sekumpulan opsi pra‑definisi yang dapat digunakan untuk mengontrol bagaimana teks ditampilkan ketika melebihi yang tersedia
ruang dalam sel selama proses rendering dokumen spreadsheet ke HTML.
Untuk detail, lihat [documentation](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#control-cell-text-overflow).


Contoh penggunaan:

````

 HtmlViewOptions htmlViewOptions = HtmlViewOptions.forEmbeddedResources();

 htmlViewOptions.setSpreadsheetOptions(SpreadsheetOptions.forOnePagePerSheet());
 htmlViewOptions.getSpreadsheetOptions().setTextOverflowMode(TextOverflowMode.HIDE_TEXT);

 try (Viewer viewer = new Viewer("document.xlsx")) {
     viewer.view(htmlViewOptions);
     // Use the viewer object for further operations
 }
 
````


## Bidang

| Bidang | Deskripsi |
| --- | --- |
|  | [OVERLAY](#OVERLAY) | Lapisi sel berikutnya meskipun tidak kosong. |
|
|  | [OVERLAY_IF_NEXT_IS_EMPTY](#OVERLAY-IF-NEXT-IS-EMPTY) | Lapisi sel berikutnya hanya jika kosong. |
|
|  | [AUTO_FIT_COLUMN](#AUTO-FIT-COLUMN) | Perluas kolom agar sesuai dengan teks. |
|
|  | [HIDE_TEXT](#HIDE-TEXT) | Sembunyikan teks yang meluap. |
|
## Metode

| Metode | Deskripsi |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
### OVERLAY {#OVERLAY}
```
public static final TextOverflowMode OVERLAY
```


Lapisi sel berikutnya meskipun tidak kosong.
Mode ini memungkinkan teks meluap ke sel tetangga, terlepas dari isi sel tersebut.
Untuk detail, lihat [documentation](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#control-cell-text-overflow).


### OVERLAY_IF_NEXT_IS_EMPTY {#OVERLAY-IF-NEXT-IS-EMPTY}
```
public static final TextOverflowMode OVERLAY_IF_NEXT_IS_EMPTY
```


Lapisi sel berikutnya hanya jika kosong.
Mode ini memungkinkan teks meluap ke sel tetangga hanya jika sel tersebut kosong.
Untuk detail, lihat [documentation](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#control-cell-text-overflow).


### AUTO_FIT_COLUMN {#AUTO-FIT-COLUMN}
```
public static final TextOverflowMode AUTO_FIT_COLUMN
```


Perluas kolom agar sesuai dengan teks.
Mode ini secara otomatis menyesuaikan lebar kolom untuk menampung teks yang meluap.
Untuk detail, lihat [documentation](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#control-cell-text-overflow).


### HIDE_TEXT {#HIDE-TEXT}
```
public static final TextOverflowMode HIDE_TEXT
```


Sembunyikan teks yang meluap.
Mode ini menyembunyikan teks yang meluap, mencegahnya ditampilkan.
Untuk detail, lihat [documentation](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#control-cell-text-overflow).


### values() {#values--}
```
public static TextOverflowMode[] values()
```




**Returns:**
com.groupdocs.viewer.options.TextOverflowMode[]
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static TextOverflowMode valueOf(String name)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nama | java.lang.String |  |

**Returns:**
[TextOverflowMode](../../com.groupdocs.viewer.options/textoverflowmode)
