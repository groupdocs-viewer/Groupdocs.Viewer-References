---
title: "TextOverflowMode"
second_title: "GroupDocs.Viewer untuk Node.js melalui Java Referensi API"
description: "Mendefinisikan mode overflow teks untuk merender dokumen spreadsheet ke HTML."
type: docs
weight: 46
url: /id/nodejs-java/com.groupdocs.viewer.options/textoverflowmode/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum TextOverflowMode extends Enum<TextOverflowMode>
```

Mendefinisikan mode overflow teks untuk merender dokumen spreadsheet ke HTML.

Enum TextOverflowMode mewakili berbagai mode untuk menangani overflow teks dalam komponen GroupDocs.Viewer. Ini menyediakan sekumpulan opsi pra‑definisi yang dapat digunakan untuk mengontrol bagaimana teks ditampilkan ketika melebihi ruang yang tersedia di sel selama proses rendering dokumen spreadsheet ke HTML. Untuk detail, lihat [documentation][].

Contoh penggunaan:

```

 HtmlViewOptions htmlViewOptions = HtmlViewOptions.forEmbeddedResources();

 htmlViewOptions.setSpreadsheetOptions(SpreadsheetOptions.forOnePagePerSheet());
 htmlViewOptions.getSpreadsheetOptions().setTextOverflowMode(TextOverflowMode.HIDE_TEXT);

 try (Viewer viewer = new Viewer("document.xlsx")) {
     viewer.view(htmlViewOptions);
     // Use the viewer object for further operations
 }
 
```


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#control-cell-text-overflow
## Bidang

| Bidang | Deskripsi |
| --- | --- |
| [OVERLAY](#OVERLAY) | Tumpangi sel berikutnya meskipun tidak kosong. |
| [OVERLAY_IF_NEXT_IS_EMPTY](#OVERLAY-IF-NEXT-IS-EMPTY) | Tumpangi sel berikutnya hanya jika kosong. |
| [AUTO_FIT_COLUMN](#AUTO-FIT-COLUMN) | Perluas kolom agar sesuai dengan teks. |
| [HIDE_TEXT](#HIDE-TEXT) | Sembunyikan teks overflow. |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
### OVERLAY {#OVERLAY}
```
public static final TextOverflowMode OVERLAY
```


Tumpangi sel berikutnya meskipun tidak kosong. Mode ini memungkinkan teks overflow ke sel berdekatan, terlepas dari kontennya.

Untuk detail, lihat [dokumentasi][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#control-cell-text-overflow

### OVERLAY_IF_NEXT_IS_EMPTY {#OVERLAY-IF-NEXT-IS-EMPTY}
```
public static final TextOverflowMode OVERLAY_IF_NEXT_IS_EMPTY
```


Tumpangi sel berikutnya hanya jika kosong. Mode ini memungkinkan teks overflow ke sel berdekatan hanya jika sel tersebut kosong.

Untuk detail, lihat [dokumentasi][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#control-cell-text-overflow

### AUTO_FIT_COLUMN {#AUTO-FIT-COLUMN}
```
public static final TextOverflowMode AUTO_FIT_COLUMN
```


Perluas kolom agar sesuai dengan teks. Mode ini secara otomatis menyesuaikan lebar kolom untuk menampung teks yang overflow.

Untuk detail, lihat [dokumentasi][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#control-cell-text-overflow

### HIDE_TEXT {#HIDE-TEXT}
```
public static final TextOverflowMode HIDE_TEXT
```


Sembunyikan teks overflow. Mode ini menyembunyikan teks yang overflow, mencegahnya ditampilkan.

Untuk detail, lihat [dokumentasi][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#control-cell-text-overflow

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
