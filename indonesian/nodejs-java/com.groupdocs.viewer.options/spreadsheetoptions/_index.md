---
title: "SpreadsheetOptions"
second_title: "GroupDocs.Viewer untuk Node.js melalui Java Referensi API"
description: "Menyediakan opsi untuk merender spreadsheet."
type: docs
weight: 31
url: /id/nodejs-java/com.groupdocs.viewer.options/spreadsheetoptions/
---
**Inheritance:**
java.lang.Object
```
public class SpreadsheetOptions
```

Menyediakan opsi untuk merender spreadsheet.

Kelas SpreadsheetOptions mengenkapsulasi berbagai pengaturan dan parameter yang dapat digunakan untuk mengontrol perenderan file spreadsheet (seperti file Excel atau CSV) dalam komponen GroupDocs.Viewer. Untuk detail, lihat anak dari topik [Render spreadsheet files][].

Contoh penggunaan:

```

 PngViewOptions pngViewOptions = new PngViewOptions();
 SpreadsheetOptions spreadsheetOptions = pngViewOptions.getSpreadsheetOptions();
 spreadsheetOptions.setRenderHeadings(true);
 spreadsheetOptions.setCountColumnsPerPage(24);

 try (Viewer viewer = new Viewer("document.docx")) {
     viewer.view(pngViewOptions);
     // Use the viewer object for further operations
 }
 
```


[Render spreadsheet files]: https://docs.groupdocs.com/viewer/java/render-spreadsheets/
## Metode

| Metode | Deskripsi |
| --- | --- |
| [isRenderByPageBreaks()](#isRenderByPageBreaks--) | Menentukan apakah lembar kerja harus dirender berdasarkan pemisah halaman. |
| [setRenderByPageBreaks(boolean renderByPageBreaks)](#setRenderByPageBreaks-boolean-) | Mengatur apakah lembar kerja harus dirender berdasarkan pemisah halaman. |
| [isDetectSeparator()](#isDetectSeparator--) | Mendeteksi pemisah untuk file CSV/TSV. |
| [setDetectSeparator(boolean detectSeparator)](#setDetectSeparator-boolean-) | Mengatur apakah mendeteksi pemisah untuk file CSV/TSV. |
| [forOnePagePerSheet()](#forOnePagePerSheet--) | Membuat instance baru dari kelas SpreadsheetOptions untuk merender satu lembar menjadi satu halaman. |
| [forSplitSheetIntoPages(int countRowsPerPage)](#forSplitSheetIntoPages-int-) | Membuat instance baru dari kelas SpreadsheetOptions untuk merender satu lembar menjadi beberapa halaman. |
| [forSplitSheetIntoPages(int countRowsPerPage, int countColumnsPerPage)](#forSplitSheetIntoPages-int-int-) | Menginisialisasi instance baru dari kelas SpreadsheetOptions untuk merender satu lembar menjadi halaman-halaman. |
| [forRenderingPrintArea()](#forRenderingPrintArea--) | Menginisialisasi instance baru dari kelas SpreadsheetOptions untuk merender hanya area cetak. |
| [isOnePagePerSheet()](#isOnePagePerSheet--) | Menunjukkan apakah satu lembar dirender menjadi satu halaman. |
| [getCountRowsPerPage()](#getCountRowsPerPage--) | Mendapatkan jumlah baris yang dimasukkan ke setiap halaman saat membagi lembar kerja menjadi halaman. |
| [getCountColumnsPerPage()](#getCountColumnsPerPage--) | Mendapatkan jumlah kolom yang dimasukkan ke setiap halaman saat membagi lembar kerja menjadi halaman. |
| [setCountColumnsPerPage(int countColumnsPerPage)](#setCountColumnsPerPage-int-) | Mengatur jumlah kolom yang dimasukkan ke setiap halaman saat membagi lembar kerja menjadi halaman. |
| [isRenderPrintAreaOnly()](#isRenderPrintAreaOnly--) | Menunjukkan apakah hanya area cetak yang dirender. |
| [isRenderingPrintAreaAndPageBreaks()](#isRenderingPrintAreaAndPageBreaks--) | Ketika opsi ini diaktifkan, lembar kerja akan dirender berdasarkan pemisah halaman yang berada dalam area cetak. |
| [setRenderingPrintAreaAndPageBreaks(boolean renderingPrintAreaAndPageBreaks)](#setRenderingPrintAreaAndPageBreaks-boolean-) | Mengatur apakah merender lembar kerja berdasarkan pemisah halaman yang berada dalam area cetak. |
| [isRenderGridLines()](#isRenderGridLines--) | Mengaktifkan perenderan garis kisi. |
| [setRenderGridLines(boolean value)](#setRenderGridLines-boolean-) | Mengaktifkan atau menonaktifkan perenderan garis kisi. |
| [isSkipEmptyRows()](#isSkipEmptyRows--) | Menunjukkan apakah baris kosong harus dilewati selama perenderan. |
| [setSkipEmptyRows(boolean value)](#setSkipEmptyRows-boolean-) | Mengatur apakah baris kosong harus dilewati selama perenderan. |
| [isSkipEmptyColumns()](#isSkipEmptyColumns--) | Menunjukkan apakah kolom kosong harus dilewati selama perenderan. |
| [setSkipEmptyColumns(boolean value)](#setSkipEmptyColumns-boolean-) | Mengatur apakah kolom kosong harus dilewati selama perenderan. |
| [isRenderHiddenRows()](#isRenderHiddenRows--) | Menentukan apakah baris tersembunyi harus dirender. |
| [setRenderHiddenRows(boolean value)](#setRenderHiddenRows-boolean-) | Mengatur apakah baris tersembunyi harus dirender. |
| [isRenderHeadings()](#isRenderHeadings--) | Memeriksa apakah perenderan heading diaktifkan. |
| [setRenderHeadings(boolean renderHeadings)](#setRenderHeadings-boolean-) | Mengaktifkan perenderan heading. |
| [isRenderHiddenColumns()](#isRenderHiddenColumns--) | Mengaktifkan perenderan kolom tersembunyi. |
| [setRenderHiddenColumns(boolean value)](#setRenderHiddenColumns-boolean-) | Mengaktifkan perenderan kolom tersembunyi. |
| [getTextOverflowMode()](#getTextOverflowMode--) | Mengembalikan mode overflow teks untuk merender dokumen spreadsheet ke HTML. |
| [setTextOverflowMode(TextOverflowMode value)](#setTextOverflowMode-com.groupdocs.viewer.options.TextOverflowMode-) | Mengatur mode overflow teks untuk merender dokumen spreadsheet ke HTML. |
| [getLeftMargin()](#getLeftMargin--) | Untuk mengatur margin kiri lembar kerja saat mengonversi ke PDF, jika kurang dari 0 maka nilai konversi default digunakan |
| [setLeftMargin(double leftMargin)](#setLeftMargin-double-) | Untuk mengatur margin kiri lembar kerja saat mengonversi ke PDF, jika kurang dari 0 maka nilai konversi default digunakan |
| [getRightMargin()](#getRightMargin--) | Untuk mengatur margin kanan lembar kerja saat mengonversi ke PDF, jika kurang dari 0 maka nilai konversi default digunakan Jika parameter kurang dari 0, maka nilai default digunakan. |
| [setRightMargin(double rightMargin)](#setRightMargin-double-) | Untuk mengatur margin kanan lembar kerja saat mengonversi ke PDF, jika kurang dari 0 maka nilai konversi default digunakan Jika parameter kurang dari 0, maka nilai default digunakan. |
| [getTopMargin()](#getTopMargin--) | Untuk mengatur margin atas lembar kerja saat mengonversi ke PDF, jika kurang dari 0 maka nilai konversi default digunakan Jika parameter kurang dari 0, maka nilai default digunakan. |
| [setTopMargin(double topMargin)](#setTopMargin-double-) | Untuk mengatur margin atas lembar kerja saat mengonversi ke PDF, jika kurang dari 0 maka nilai konversi default digunakan Jika parameter kurang dari 0, maka nilai default digunakan. |
| [getBottomMargin()](#getBottomMargin--) | Untuk mengatur margin bawah lembar kerja saat mengonversi ke PDF, jika kurang dari 0 maka nilai konversi default digunakan Jika parameter kurang dari 0, maka nilai default digunakan. |
| [setBottomMargin(double bottomMargin)](#setBottomMargin-double-) | Untuk mengatur margin bawah lembar kerja saat mengonversi ke PDF, jika kurang dari 0 maka nilai konversi default digunakan Jika parameter kurang dari 0, maka nilai default digunakan. |
| [forRenderingPrintAreaAndPageBreaks()](#forRenderingPrintAreaAndPageBreaks--) | Menginisialisasi instance baru dari  SpreadsheetOptions  untuk merender area cetak dan pemisah halaman. |
| [forRenderingByPageBreaks()](#forRenderingByPageBreaks--) | Menginisialisasi instance baru dari kelas SpreadsheetOptions untuk merender hanya area cetak. |
### isRenderByPageBreaks() {#isRenderByPageBreaks--}
```
public boolean isRenderByPageBreaks()
```


Menentukan apakah lembar kerja harus dirender berdasarkan pemisah halaman.

***Note:** This option controls the rendering behavior of the worksheet, similar to printing a spreadsheet in Excel.*

**Returns:**
boolean -  true  jika lembar kerja harus dirender berdasarkan pemisah halaman,  false  jika tidak.
### setRenderByPageBreaks(boolean renderByPageBreaks) {#setRenderByPageBreaks-boolean-}
```
public void setRenderByPageBreaks(boolean renderByPageBreaks)
```


Mengatur apakah lembar kerja harus dirender berdasarkan pemisah halaman.

***Note:** This option controls the rendering behavior of the worksheet, similar to printing a spreadsheet in Excel.*

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| renderByPageBreaks | boolean | true  jika lembar kerja harus dirender berdasarkan pemisah halaman,  false  jika tidak. |

### isDetectSeparator() {#isDetectSeparator--}
```
public boolean isDetectSeparator()
```


Mendeteksi pemisah untuk file CSV/TSV.

Untuk detail, lihat [dokumentasi][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-excel-and-apple-numbers-spreadsheets/#detect-a-csvtsv-separator

**Returns:**
boolean -  true  jika pemisah harus terdeteksi secara otomatis,  false  jika tidak.
### setDetectSeparator(boolean detectSeparator) {#setDetectSeparator-boolean-}
```
public void setDetectSeparator(boolean detectSeparator)
```


Mengatur apakah mendeteksi pemisah untuk file CSV/TSV.

Untuk detail, lihat [dokumentasi][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-excel-and-apple-numbers-spreadsheets/#detect-a-csvtsv-separator

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| detectSeparator | boolean | true  untuk mendeteksi pemisah secara otomatis,  false  jika tidak. |

### forOnePagePerSheet() {#forOnePagePerSheet--}
```
public static SpreadsheetOptions forOnePagePerSheet()
```


Membuat instance baru dari kelas SpreadsheetOptions untuk merender satu lembar menjadi satu halaman.

Untuk detail, lihat [dokumentasi][].


[documentation]: https://docs.groupdocs.com/viewer/java/split-worksheet-into-pages/#render-a-worksheet-on-one-page

**Returns:**
[SpreadsheetOptions](../../com.groupdocs.viewer.options/spreadsheetoptions) - a new instance of  SpreadsheetOptions  class for rendering one sheet into one page.
### forSplitSheetIntoPages(int countRowsPerPage) {#forSplitSheetIntoPages-int-}
```
public static SpreadsheetOptions forSplitSheetIntoPages(int countRowsPerPage)
```


Membuat instance baru dari kelas SpreadsheetOptions untuk merender satu lembar menjadi beberapa halaman.

Untuk detail, lihat [dokumentasi][].


[documentation]: https://docs.groupdocs.com/viewer/java/split-worksheet-into-pages/#split-a-worksheet-into-pages-by-rows

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| countRowsPerPage | int | Jumlah baris yang akan dimasukkan dalam setiap halaman. |

**Returns:**
[SpreadsheetOptions](../../com.groupdocs.viewer.options/spreadsheetoptions) - a new instance of  SpreadsheetOptions  for rendering a sheet into pages.
### forSplitSheetIntoPages(int countRowsPerPage, int countColumnsPerPage) {#forSplitSheetIntoPages-int-int-}
```
public static SpreadsheetOptions forSplitSheetIntoPages(int countRowsPerPage, int countColumnsPerPage)
```


Menginisialisasi instance baru dari kelas SpreadsheetOptions untuk merender satu lembar menjadi halaman-halaman.

Untuk detail, lihat [dokumentasi][].


[documentation]: https://docs.groupdocs.com/viewer/java/split-worksheet-into-pages/#split-a-worksheet-into-pages-by-rows

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| countRowsPerPage | int | Jumlah baris yang akan dimasukkan pada setiap halaman. |
| countColumnsPerPage | int | Jumlah kolom yang akan dimasukkan pada setiap halaman. |

**Returns:**
[SpreadsheetOptions](../../com.groupdocs.viewer.options/spreadsheetoptions) - a new instance of the  SpreadsheetOptions  class for rendering a sheet into pages.
### forRenderingPrintArea() {#forRenderingPrintArea--}
```
public static SpreadsheetOptions forRenderingPrintArea()
```


Menginisialisasi instance baru dari kelas SpreadsheetOptions untuk merender hanya area cetak.

Untuk detail, lihat [dokumentasi][].


[documentation]: https://docs.groupdocs.com/viewer/java/split-worksheet-into-pages/#render-a-print-area

**Returns:**
[SpreadsheetOptions](../../com.groupdocs.viewer.options/spreadsheetoptions) - a new instance of the  SpreadsheetOptions  class for rendering print areas only.
### isOnePagePerSheet() {#isOnePagePerSheet--}
```
public final boolean isOnePagePerSheet()
```


Menunjukkan apakah satu lembar dirender menjadi satu halaman.

**Returns:**
boolean -  true  jika satu lembar dirender menjadi satu halaman;  false  jika tidak.
### getCountRowsPerPage() {#getCountRowsPerPage--}
```
public final int getCountRowsPerPage()
```


Mendapatkan jumlah baris yang dimasukkan ke setiap halaman saat membagi lembar kerja menjadi halaman.

Untuk detail, lihat [dokumentasi][].


[documentation]: https://docs.groupdocs.com/viewer/java/split-worksheet-into-pages/#split-a-worksheet-into-pages-by-rows

**Returns:**
int - jumlah baris yang akan dimasukkan ke dalam setiap halaman.
### getCountColumnsPerPage() {#getCountColumnsPerPage--}
```
public int getCountColumnsPerPage()
```


Mendapatkan jumlah kolom yang dimasukkan ke setiap halaman saat membagi lembar kerja menjadi halaman.

Untuk detail, lihat [dokumentasi][].


[documentation]: https://docs.groupdocs.com/viewer/java/split-worksheet-into-pages/#split-a-worksheet-into-pages-by-rows-and-columns

**Returns:**
int - jumlah kolom yang akan dimasukkan ke dalam setiap halaman.
### setCountColumnsPerPage(int countColumnsPerPage) {#setCountColumnsPerPage-int-}
```
public void setCountColumnsPerPage(int countColumnsPerPage)
```


Mengatur jumlah kolom yang dimasukkan ke setiap halaman saat membagi lembar kerja menjadi halaman.

Untuk detail, lihat [dokumentasi][].


[documentation]: https://docs.groupdocs.com/viewer/java/split-worksheet-into-pages/#split-a-worksheet-into-pages-by-rows-and-columns

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| countColumnsPerPage | int | Jumlah kolom yang akan dimasukkan ke dalam setiap halaman. |

### isRenderPrintAreaOnly() {#isRenderPrintAreaOnly--}
```
public final boolean isRenderPrintAreaOnly()
```


Menunjukkan apakah hanya area cetak yang dirender.

**Returns:**
boolean -  true  jika hanya area cetak yang dirender,  false  jika tidak.
### isRenderingPrintAreaAndPageBreaks() {#isRenderingPrintAreaAndPageBreaks--}
```
public boolean isRenderingPrintAreaAndPageBreaks()
```


Ketika opsi ini diaktifkan, lembar kerja akan dirender berdasarkan pemisah halaman yang berada dalam area cetak.

**Returns:**
boolean
### setRenderingPrintAreaAndPageBreaks(boolean renderingPrintAreaAndPageBreaks) {#setRenderingPrintAreaAndPageBreaks-boolean-}
```
public void setRenderingPrintAreaAndPageBreaks(boolean renderingPrintAreaAndPageBreaks)
```


Mengatur apakah merender lembar kerja berdasarkan pemisah halaman yang berada dalam area cetak.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| renderingPrintAreaAndPageBreaks | boolean | Atur ke true untuk mengaktifkan, false untuk menonaktifkan. |

### isRenderGridLines() {#isRenderGridLines--}
```
public final boolean isRenderGridLines()
```


Mengaktifkan perenderan garis kisi.

Untuk detail, lihat [dokumentasi][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#render-worksheet-gridlines

**Returns:**
boolean -  true  jika garis kisi diaktifkan,  false  sebaliknya.
### setRenderGridLines(boolean value) {#setRenderGridLines-boolean-}
```
public final void setRenderGridLines(boolean value)
```


Mengaktifkan atau menonaktifkan perenderan garis kisi.

Untuk detail, lihat [dokumentasi][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#render-worksheet-gridlines

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean | true  untuk mengaktifkan render garis kisi,  false  untuk menonaktifkannya. |

### isSkipEmptyRows() {#isSkipEmptyRows--}
```
public final boolean isSkipEmptyRows()
```


Menunjukkan apakah baris kosong harus dilewati selama perenderan.

Untuk detail, lihat [dokumentasi][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#skip-empty-rows-and-columns

**Returns:**
boolean -  true  jika baris kosong harus dilewati,  false  sebaliknya.
### setSkipEmptyRows(boolean value) {#setSkipEmptyRows-boolean-}
```
public final void setSkipEmptyRows(boolean value)
```


Mengatur apakah baris kosong harus dilewati selama perenderan.

Untuk detail, lihat [dokumentasi][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#skip-empty-rows-and-columns

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean | true  untuk melewatkan baris kosong,  false  sebaliknya. |

### isSkipEmptyColumns() {#isSkipEmptyColumns--}
```
public final boolean isSkipEmptyColumns()
```


Menunjukkan apakah kolom kosong harus dilewati selama perenderan.

Untuk detail, lihat [dokumentasi][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#skip-empty-rows-and-columns

**Returns:**
boolean -  true  jika kolom kosong dilewati,  false  sebaliknya.
### setSkipEmptyColumns(boolean value) {#setSkipEmptyColumns-boolean-}
```
public final void setSkipEmptyColumns(boolean value)
```


Mengatur apakah kolom kosong harus dilewati selama perenderan.

Untuk detail, lihat [dokumentasi][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#skip-empty-rows-and-columns

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean | true  untuk melewatkan kolom kosong,  false  sebaliknya. |

### isRenderHiddenRows() {#isRenderHiddenRows--}
```
public final boolean isRenderHiddenRows()
```


Menentukan apakah baris tersembunyi harus dirender.

Untuk detail, lihat [dokumentasi][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#render-hidden-rows-and-columns

**Returns:**
boolean -  true  jika baris tersembunyi harus dirender,  false  sebaliknya.
### setRenderHiddenRows(boolean value) {#setRenderHiddenRows-boolean-}
```
public final void setRenderHiddenRows(boolean value)
```


Mengatur apakah baris tersembunyi harus dirender.

Untuk detail, lihat [dokumentasi][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#render-hidden-rows-and-columns

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean | true  untuk mengaktifkan render baris tersembunyi,  false  untuk menonaktifkannya. |

### isRenderHeadings() {#isRenderHeadings--}
```
public boolean isRenderHeadings()
```


Memeriksa apakah perenderan heading diaktifkan.

Untuk detail, lihat [dokumentasi][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#render-row-and-column-headings

**Returns:**
boolean -  true  jika render judul diaktifkan,  false  sebaliknya.
### setRenderHeadings(boolean renderHeadings) {#setRenderHeadings-boolean-}
```
public void setRenderHeadings(boolean renderHeadings)
```


Mengaktifkan perenderan heading.

Untuk detail, lihat [dokumentasi][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#render-row-and-column-headings

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| renderHeadings | boolean | true  untuk mengaktifkan render judul,  false  untuk menonaktifkannya. |

### isRenderHiddenColumns() {#isRenderHiddenColumns--}
```
public final boolean isRenderHiddenColumns()
```


Mengaktifkan perenderan kolom tersembunyi.

Untuk detail, lihat [dokumentasi][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#render-hidden-rows-and-columns

**Returns:**
boolean -  true  jika render kolom tersembunyi diaktifkan,  false  sebaliknya.
### setRenderHiddenColumns(boolean value) {#setRenderHiddenColumns-boolean-}
```
public final void setRenderHiddenColumns(boolean value)
```


Mengaktifkan perenderan kolom tersembunyi.

Untuk detail, lihat [dokumentasi][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#render-hidden-rows-and-columns

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean | true  untuk mengaktifkan render kolom tersembunyi,  false  untuk menonaktifkannya. |

### getTextOverflowMode() {#getTextOverflowMode--}
```
public final TextOverflowMode getTextOverflowMode()
```


Mengembalikan mode overflow teks untuk merender dokumen spreadsheet ke HTML.

Untuk detail, lihat [dokumentasi][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#control-cell-text-overflow

**Returns:**
[TextOverflowMode](../../com.groupdocs.viewer.options/textoverflowmode) - the text overflow mode.
### setTextOverflowMode(TextOverflowMode value) {#setTextOverflowMode-com.groupdocs.viewer.options.TextOverflowMode-}
```
public final void setTextOverflowMode(TextOverflowMode value)
```


Mengatur mode overflow teks untuk merender dokumen spreadsheet ke HTML. Untuk detail, lihat [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#control-cell-text-overflow

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [TextOverflowMode](../../com.groupdocs.viewer.options/textoverflowmode) | Mode overflow teks yang akan diatur. |

### getLeftMargin() {#getLeftMargin--}
```
public double getLeftMargin()
```


Untuk mengatur margin kiri lembar kerja saat mengonversi ke PDF, jika kurang dari 0 maka nilai konversi default digunakan

Jika parameter kurang dari 0, maka nilai default digunakan. Untuk detail, lihat [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#set-worksheet-margins-in-the-output-pdf-pages

**Returns:**
double
### setLeftMargin(double leftMargin) {#setLeftMargin-double-}
```
public void setLeftMargin(double leftMargin)
```


Untuk mengatur margin kiri lembar kerja saat mengonversi ke PDF, jika kurang dari 0 maka nilai konversi default digunakan

Jika parameter kurang dari 0, maka nilai default digunakan. Untuk detail, lihat [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#set-worksheet-margins-in-the-output-pdf-pages

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| leftMargin | double |  |

### getRightMargin() {#getRightMargin--}
```
public double getRightMargin()
```


Untuk mengatur margin kanan lembar kerja saat mengonversi ke pdf, jika kurang dari 0 maka nilai konversi default digunakan. Jika parameter kurang dari 0, maka nilai default digunakan. Untuk detail, lihat [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#set-worksheet-margins-in-the-output-pdf-pages

**Returns:**
double
### setRightMargin(double rightMargin) {#setRightMargin-double-}
```
public void setRightMargin(double rightMargin)
```


Untuk mengatur margin kanan lembar kerja saat mengonversi ke pdf, jika kurang dari 0 maka nilai konversi default digunakan. Jika parameter kurang dari 0, maka nilai default digunakan. Untuk detail, lihat [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#set-worksheet-margins-in-the-output-pdf-pages

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| rightMargin | double |  |

### getTopMargin() {#getTopMargin--}
```
public double getTopMargin()
```


Untuk mengatur margin atas lembar kerja saat mengonversi ke pdf, jika kurang dari 0 maka nilai konversi default digunakan. Jika parameter kurang dari 0, maka nilai default digunakan. Untuk detail, lihat [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#set-worksheet-margins-in-the-output-pdf-pages

**Returns:**
double
### setTopMargin(double topMargin) {#setTopMargin-double-}
```
public void setTopMargin(double topMargin)
```


Untuk mengatur margin atas lembar kerja saat mengonversi ke pdf, jika kurang dari 0 maka nilai konversi default digunakan. Jika parameter kurang dari 0, maka nilai default digunakan. Untuk detail, lihat [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#set-worksheet-margins-in-the-output-pdf-pages

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| topMargin | double |  |

### getBottomMargin() {#getBottomMargin--}
```
public double getBottomMargin()
```


Untuk mengatur margin bawah lembar kerja saat mengonversi ke pdf, jika kurang dari 0 maka nilai konversi default digunakan. Jika parameter kurang dari 0, maka nilai default digunakan. Untuk detail, lihat [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#set-worksheet-margins-in-the-output-pdf-pages

**Returns:**
double
### setBottomMargin(double bottomMargin) {#setBottomMargin-double-}
```
public void setBottomMargin(double bottomMargin)
```


Untuk mengatur margin bawah lembar kerja saat mengonversi ke pdf, jika kurang dari 0 maka nilai konversi default digunakan. Jika parameter kurang dari 0, maka nilai default digunakan. Untuk detail, lihat [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#set-worksheet-margins-in-the-output-pdf-pages

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| bottomMargin | double |  |

### forRenderingPrintAreaAndPageBreaks() {#forRenderingPrintAreaAndPageBreaks--}
```
public static SpreadsheetOptions forRenderingPrintAreaAndPageBreaks()
```


Menginisialisasi instance baru dari  SpreadsheetOptions  untuk merender area cetak dan pemisah halaman. Untuk detail, lihat [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/split-worksheet-into-pages/#render-worksheet-by-page-breaks-and-print-area

**Returns:**
[SpreadsheetOptions](../../com.groupdocs.viewer.options/spreadsheetoptions) - New instance of  SpreadsheetOptions  for rendering pages based on page breaks that are included into print area. The behavior is similar to printing in Excel.
### forRenderingByPageBreaks() {#forRenderingByPageBreaks--}
```
public static SpreadsheetOptions forRenderingByPageBreaks()
```


Menginisialisasi instance baru dari kelas  SpreadsheetOptions  untuk merender hanya area cetak. Untuk detail, lihat [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/split-worksheet-into-pages/

**Returns:**
[SpreadsheetOptions](../../com.groupdocs.viewer.options/spreadsheetoptions) - a new instance of  SpreadsheetOptions  for rendering print areas only. The behavior is similar to printing in Excel, where the worksheet is rendered by page breaks.
