---
title: "CadOptions"
second_title: "GroupDocs.Viewer untuk Node.js melalui Java Referensi API"
description: "Menyediakan opsi untuk merender gambar CAD."
type: docs
weight: 13
url: /id/nodejs-java/com.groupdocs.viewer.options/cadoptions/
---
**Inheritance:**
java.lang.Object
```
public class CadOptions
```

Menyediakan opsi untuk merender gambar CAD.

Kelas CadOptions mengenkapsulasi berbagai pengaturan dan parameter yang dapat digunakan untuk mengontrol rendering gambar CAD dalam komponen GroupDocs.Viewer.

Untuk informasi lebih lanjut dan contoh kode, lihat [Render CAD drawings and models as HTML, PDF, and image files][Render CAD drawings and models as HTML_ PDF_ and image files] dan [Specify rendering options for CAD files][].

Contoh penggunaan:

```

 CadOptions options = CadOptions.forRenderingByWidth(256);
 options.setRenderLayouts(true);
 options.setBackgroundColor(Color.YELLOW);
 options.setLayers(Arrays.asList(
         CacheableFactory.getInstance().newLayer("Layer1"),
         CacheableFactory.getInstance().newLayer("Layer2")
 ));

 try (Viewer viewer = new Viewer("document.dwg")) {
     PdfViewOptions pdfViewOptions = new PdfViewOptions();
     pdfViewOptions.setCadOptions(options);
     viewer.view(pdfViewOptions);
     // Use the viewer object for further operations
 }
 
```


[Render CAD drawings and models as HTML_ PDF_ and image files]: https://docs.groupdocs.com/viewer/java/render-cad-drawings-and-models/
[Specify rendering options for CAD files]: https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/
## Bidang

| Bidang | Deskripsi |
| --- | --- |
| [WIDTH](#WIDTH) |  |
| [HEIGHT](#HEIGHT) |  |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getPc3File()](#getPc3File--) | Mengambil file PC3 (Plotter Configuration) yang terkait dengan plotter. |
| [setPc3File(String pc3File)](#setPc3File-java.lang.String-) | Mengatur file PC3 (Plotter Configuration) yang terkait dengan plotter. |
| [forRenderingByScaleFactor(double scaleFactor)](#forRenderingByScaleFactor-double-) | Menginisialisasi instance baru dari kelas  CadOptions  untuk rendering berdasarkan faktor skala. |
| [forRenderingByWidth(int width)](#forRenderingByWidth-int-) | Menginisialisasi instance baru dari kelas  CadOptions  untuk rendering berdasarkan lebar. |
| [forRenderingByHeight(int height)](#forRenderingByHeight-int-) | Menginisialisasi instance baru dari kelas  CadOptions  untuk rendering berdasarkan tinggi. |
| [forRenderingByWidthAndHeight(int width, int height)](#forRenderingByWidthAndHeight-int-int-) | Menginisialisasi instance baru dari kelas  CadOptions  untuk rendering berdasarkan lebar dan tinggi. |
| [getScaleFactor()](#getScaleFactor--) | Mendapatkan faktor skala untuk rendering. |
| [getWidth()](#getWidth--) | Mendapatkan lebar hasil output dalam piksel. |
| [getHeight()](#getHeight--) | Mendapatkan tinggi hasil output dalam piksel. |
| [getBackgroundColor()](#getBackgroundColor--) | Mendapatkan warna latar belakang gambar. |
| [getBackgroundColorAsHex()](#getBackgroundColorAsHex--) | Mendapatkan warna latar belakang gambar. |
| [setBackgroundColor(Color backgroundColor)](#setBackgroundColor-java.awt.Color-) | Mengatur warna latar belakang gambar. |
| [setBackgroundColor(String colorName)](#setBackgroundColor-java.lang.String-) | Mengatur warna latar belakang gambar. |
| [getTiles()](#getTiles--) | Mendapatkan wilayah gambar untuk dirender. |
| [setTiles(List<Tile> value)](#setTiles-java.util.List-com.groupdocs.viewer.options.Tile--) | Mengatur wilayah gambar untuk dirender. |
| [isRenderLayouts()](#isRenderLayouts--) | Menunjukkan apakah tata letak dari dokumen CAD harus dirender. |
| [setRenderLayouts(boolean value)](#setRenderLayouts-boolean-) | Mengatur apakah tata letak dari dokumen CAD harus dirender. |
| [getLayoutName()](#getLayoutName--) | Mendapatkan nama tata letak spesifik untuk dirender. |
| [setLayoutName(String value)](#setLayoutName-java.lang.String-) | Mengatur nama tata letak spesifik untuk dirender. |
| [getLayers()](#getLayers--) | Mendapatkan lapisan gambar CAD untuk dirender. |
| [setLayers(List<Layer> value)](#setLayers-java.util.List-com.groupdocs.viewer.results.Layer--) | Mendapatkan lapisan gambar CAD untuk dirender. |
| [isEnablePerformanceConversionMode()](#isEnablePerformanceConversionMode--) | Mengatur flag ini ke true mengaktifkan mode konversi khusus yang berorientasi pada kinerja untuk semua format dalam keluarga CAD. |
| [setEnablePerformanceConversionMode(boolean enablePerformanceConversionMode)](#setEnablePerformanceConversionMode-boolean-) | Mengatur flag ini ke true mengaktifkan mode konversi khusus yang berorientasi pada kinerja untuk semua format dalam keluarga CAD. |
| [equals(Object o)](#equals-java.lang.Object-) | Memeriksa apakah objek CadOptions ini sama dengan objek lain. |
| [hashCode()](#hashCode--) | \{@inheritDoc\} |
| [toString()](#toString--) | \{@inheritDoc\} |
| [toString(ToStringStyle style)](#toString-org.apache.commons.lang3.builder.ToStringStyle-) | \{@inheritDoc\} |
### WIDTH {#WIDTH}
```
public static final String WIDTH
```


### HEIGHT {#HEIGHT}
```
public static final String HEIGHT
```


### getPc3File() {#getPc3File--}
```
public String getPc3File()
```


Mengambil file PC3 (Plotter Configuration) yang terkait dengan plotter.

**Returns:**
java.lang.String - jalur file PC3.
### setPc3File(String pc3File) {#setPc3File-java.lang.String-}
```
public void setPc3File(String pc3File)
```


Mengatur file PC3 (Plotter Configuration) yang terkait dengan plotter.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pc3File | java.lang.String | Jalur file PC3. |

### forRenderingByScaleFactor(double scaleFactor) {#forRenderingByScaleFactor-double-}
```
public static CadOptions forRenderingByScaleFactor(double scaleFactor)
```


Menginisialisasi instance baru dari kelas  CadOptions  untuk rendering berdasarkan faktor skala.

Untuk contoh kode, lihat [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/#configure-the-output-image-size

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| scaleFactor | double | Faktor skala untuk rendering. Nilai lebih besar dari 1 akan memperbesar hasil output, sementara nilai antara 0 dan 1 akan membuat hasil output lebih kecil. |

**Returns:**
[CadOptions](../../com.groupdocs.viewer.options/cadoptions) - a new instance of the  CadOptions  class for rendering by scale factor.
### forRenderingByWidth(int width) {#forRenderingByWidth-int-}
```
public static CadOptions forRenderingByWidth(int width)
```


Menginisialisasi instance baru dari kelas  CadOptions  untuk rendering berdasarkan lebar.

Untuk contoh kode, lihat [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/#configure-the-output-image-size

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| width | int | Lebar hasil output dalam piksel. |

**Returns:**
[CadOptions](../../com.groupdocs.viewer.options/cadoptions) - a new instance of the  CadOptions  class for rendering by width.
### forRenderingByHeight(int height) {#forRenderingByHeight-int-}
```
public static CadOptions forRenderingByHeight(int height)
```


Menginisialisasi instance baru dari kelas  CadOptions  untuk rendering berdasarkan tinggi.

Untuk contoh kode, lihat [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/#configure-the-output-image-size

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| height | int | Tinggi hasil output dalam piksel. |

**Returns:**
[CadOptions](../../com.groupdocs.viewer.options/cadoptions) - a new instance of the  CadOptions  class for rendering by height.
### forRenderingByWidthAndHeight(int width, int height) {#forRenderingByWidthAndHeight-int-int-}
```
public static CadOptions forRenderingByWidthAndHeight(int width, int height)
```


Menginisialisasi instance baru dari kelas  CadOptions  untuk rendering berdasarkan lebar dan tinggi.

Untuk contoh kode, lihat [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/#configure-the-output-image-size

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| width | int | Lebar hasil output dalam piksel. |
| height | int | Tinggi hasil output dalam piksel. |

**Returns:**
[CadOptions](../../com.groupdocs.viewer.options/cadoptions) - a new instance of the  CadOptions  class for rendering by width and height.
### getScaleFactor() {#getScaleFactor--}
```
public final double getScaleFactor()
```


Mendapatkan faktor skala untuk rendering. Nilai lebih tinggi dari 1 akan memperbesar hasil output, sementara nilai antara 0 dan 1 akan membuat hasil output lebih kecil.

**Returns:**
double - faktor skala untuk rendering.
### getWidth() {#getWidth--}
```
public final int getWidth()
```


Mendapatkan lebar hasil output dalam piksel.

**Returns:**
int - lebar hasil output.
### getHeight() {#getHeight--}
```
public final int getHeight()
```


Mendapatkan tinggi hasil output dalam piksel.

**Returns:**
int - tinggi hasil output.
### getBackgroundColor() {#getBackgroundColor--}
```
public Color getBackgroundColor()
```


Mendapatkan warna latar belakang gambar.

**Returns:**
java.awt.Color - warna latar belakang gambar.
### getBackgroundColorAsHex() {#getBackgroundColorAsHex--}
```
public String getBackgroundColorAsHex()
```


Mendapatkan warna latar belakang gambar.

**Returns:**
java.lang.String - warna latar belakang gambar dalam format 0xFFFFFF.
### setBackgroundColor(Color backgroundColor) {#setBackgroundColor-java.awt.Color-}
```
public void setBackgroundColor(Color backgroundColor)
```


Mengatur warna latar belakang gambar.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| backgroundColor | java.awt.Color | Warna latar belakang gambar. |

### setBackgroundColor(String colorName) {#setBackgroundColor-java.lang.String-}
```
public void setBackgroundColor(String colorName)
```


Mengatur warna latar belakang gambar.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| colorName | java.lang.String | Nama warna latar belakang gambar. |

### getTiles() {#getTiles--}
```
public final List<Tile> getTiles()
```


Mendapatkan wilayah gambar untuk dirender.

**Note:** This option is supported only for [FileType.DWG](../../com.groupdocs.viewer/filetype\#DWG) and [FileType.DWT](../../com.groupdocs.viewer/filetype\#DWT) file types. The  RenderLayouts  ([isRenderLayouts()](../../com.groupdocs.viewer.options/cadoptions\#isRenderLayouts--)/[setRenderLayouts(boolean)](../../com.groupdocs.viewer.options/cadoptions\#setRenderLayouts-boolean-)) and  LayoutName  ([getLayoutName()](../../com.groupdocs.viewer.options/cadoptions\#getLayoutName--)/[setLayoutName(String)](../../com.groupdocs.viewer.options/cadoptions\#setLayoutName-String-)) options are ignored when rendering by tiles.

**Returns:**
java.util.List<com.groupdocs.viewer.options.Tile> - daftar wilayah gambar yang akan dirender.
### setTiles(List<Tile> value) {#setTiles-java.util.List-com.groupdocs.viewer.options.Tile--}
```
public final void setTiles(List<Tile> value)
```


Mengatur wilayah gambar untuk dirender.

**Note:** This option is supported only for [FileType.DWG](../../com.groupdocs.viewer/filetype\#DWG) and [FileType.DWT](../../com.groupdocs.viewer/filetype\#DWT) file types. The  RenderLayouts  ([isRenderLayouts()](../../com.groupdocs.viewer.options/cadoptions\#isRenderLayouts--)/[setRenderLayouts(boolean)](../../com.groupdocs.viewer.options/cadoptions\#setRenderLayouts-boolean-)) and  LayoutName  ([getLayoutName()](../../com.groupdocs.viewer.options/cadoptions\#getLayoutName--)/[setLayoutName(String)](../../com.groupdocs.viewer.options/cadoptions\#setLayoutName-String-)) options are ignored when rendering by tiles.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | java.util.List<com.groupdocs.viewer.options.Tile> | Daftar wilayah gambar yang akan dirender. |

### isRenderLayouts() {#isRenderLayouts--}
```
public final boolean isRenderLayouts()
```


Menunjukkan apakah tata letak dari dokumen CAD harus dirender.

**Note:** This option applies only to CAD drawings that support layouts, such as [FileType.DXF](../../com.groupdocs.viewer/filetype\#DXF), [FileType.DWG](../../com.groupdocs.viewer/filetype\#DWG), [FileType.DWT](../../com.groupdocs.viewer/filetype\#DWT), [FileType.DWF](../../com.groupdocs.viewer/filetype\#DWF), and [FileType.DWFX](../../com.groupdocs.viewer/filetype\#DWFX). By default, only the Model is rendered.

**Returns:**
boolean -  true  jika tata letak harus dirender,  false  sebaliknya.
### setRenderLayouts(boolean value) {#setRenderLayouts-boolean-}
```
public final void setRenderLayouts(boolean value)
```


Mengatur apakah tata letak dari dokumen CAD harus dirender.

**Note:** This option applies only to CAD drawings that support layouts, such as [FileType.DXF](../../com.groupdocs.viewer/filetype\#DXF), [FileType.DWG](../../com.groupdocs.viewer/filetype\#DWG), [FileType.DWT](../../com.groupdocs.viewer/filetype\#DWT), [FileType.DWF](../../com.groupdocs.viewer/filetype\#DWF), and [FileType.DWFX](../../com.groupdocs.viewer/filetype\#DWFX). By default, only the Model is rendered.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean | true  untuk merender tata letak,  false  sebaliknya. |

### getLayoutName() {#getLayoutName--}
```
public final String getLayoutName()
```


Mendapatkan nama tata letak spesifik yang akan dirender. Nama tata letak bersifat case-sensitive.

**Note:** This option applies only to CAD drawings that support layouts, such as [FileType.DXF](../../com.groupdocs.viewer/filetype\#DXF), [FileType.DWG](../../com.groupdocs.viewer/filetype\#DWG), [FileType.DWT](../../com.groupdocs.viewer/filetype\#DWT), [FileType.DWF](../../com.groupdocs.viewer/filetype\#DWF), and [FileType.DWFX](../../com.groupdocs.viewer/filetype\#DWFX). By default, only the Model is rendered.

**Returns:**
java.lang.String - nama tata letak spesifik yang akan dirender.
### setLayoutName(String value) {#setLayoutName-java.lang.String-}
```
public final void setLayoutName(String value)
```


Mengatur nama tata letak spesifik yang akan dirender. Nama tata letak bersifat case-sensitive.

**Note:** This option applies only to CAD drawings that support layouts, such as [FileType.DXF](../../com.groupdocs.viewer/filetype\#DXF), [FileType.DWG](../../com.groupdocs.viewer/filetype\#DWG), [FileType.DWT](../../com.groupdocs.viewer/filetype\#DWT), [FileType.DWF](../../com.groupdocs.viewer/filetype\#DWF), and [FileType.DWFX](../../com.groupdocs.viewer/filetype\#DWFX). By default, only the Model is rendered.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | java.lang.String | Nama tata letak spesifik yang akan dirender. |

### getLayers() {#getLayers--}
```
public final List<Layer> getLayers()
```


Mendapatkan lapisan gambar CAD untuk dirender.

**Note:** By default, all layers are rendered. Layer names are case-sensitive.

**Returns:**
java.util.List<com.groupdocs.viewer.results.Layer> - lapisan gambar CAD.
### setLayers(List<Layer> value) {#setLayers-java.util.List-com.groupdocs.viewer.results.Layer--}
```
public final void setLayers(List<Layer> value)
```


Mendapatkan lapisan gambar CAD untuk dirender.

**Note:** By default, all layers are rendered. Layer names are case-sensitive.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | java.util.List<com.groupdocs.viewer.results.Layer> | Lapisan gambar CAD. |

### isEnablePerformanceConversionMode() {#isEnablePerformanceConversionMode--}
```
public boolean isEnablePerformanceConversionMode()
```


Mengatur flag ini ke true mengaktifkan mode konversi khusus yang berorientasi pada kinerja untuk semua format dalam keluarga CAD. Dalam mode ini, kecepatan konversi jauh lebih cepat, tetapi kualitas dokumen hasil secara signifikan lebih buruk. Secara default, mode ini dinonaktifkan (false). Kualitas dokumen hasil adalah yang terbaik mungkin dengan mengorbankan kinerja.

**Returns:**
boolean -  true  jika mode konversi berorientasi kinerja diaktifkan,  false  sebaliknya.
### setEnablePerformanceConversionMode(boolean enablePerformanceConversionMode) {#setEnablePerformanceConversionMode-boolean-}
```
public void setEnablePerformanceConversionMode(boolean enablePerformanceConversionMode)
```


Mengatur flag ini ke true mengaktifkan mode konversi khusus yang berorientasi pada kinerja untuk semua format dalam keluarga CAD. Dalam mode ini, kecepatan konversi jauh lebih cepat, tetapi kualitas dokumen hasil secara signifikan lebih buruk. Secara default, mode ini dinonaktifkan (false). Kualitas dokumen hasil adalah yang terbaik mungkin dengan mengorbankan kinerja.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| enablePerformanceConversionMode | boolean | true  untuk mengaktifkan mode konversi berorientasi kinerja,  false  untuk menonaktifkannya. |

### equals(Object o) {#equals-java.lang.Object-}
```
public boolean equals(Object o)
```


Memeriksa apakah objek CadOptions ini sama dengan objek lain.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| o | java.lang.Object | Objek untuk dibandingkan. |

**Returns:**
boolean -  true  jika objek-objek tersebut sama,  false  jika tidak.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Menghitung nilai kode hash untuk objek ini. Kode hash didasarkan pada keadaan internal objek dan digunakan dalam struktur data berbasis hash seperti hash map dan hash set.

**Note:** This method overrides the default implementation of the hashCode() method defined in the Object class.

**Returns:**
int - nilai kode hash untuk objek ini.
### toString() {#toString--}
```
public String toString()
```


Mengembalikan representasi string dari objek ini.

**Note:** This method overrides the default implementation of the toString() method defined in the Object class.

**Returns:**
java.lang.String - representasi string dari objek ini.
### toString(ToStringStyle style) {#toString-org.apache.commons.lang3.builder.ToStringStyle-}
```
public String toString(ToStringStyle style)
```


Mengembalikan representasi string dari objek ini.

**Note:** This method overrides the default implementation of the toString() method defined in the Object class.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| gaya | org.apache.commons.lang3.builder.ToStringStyle | ToStringStyle yang digunakan untuk menghasilkan representasi string. |

**Returns:**
java.lang.String - representasi string dari objek ini menggunakan ToStringStyle yang ditentukan.
