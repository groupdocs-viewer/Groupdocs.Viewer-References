---
title: "Tile"
second_title: "GroupDocs.Viewer untuk Node.js melalui Java Referensi API"
description: "Mewakili wilayah gambar."
type: docs
weight: 33
url: /id/nodejs-java/com.groupdocs.viewer.options/tile/
---
**Inheritance:**
java.lang.Object
```
public class Tile
```

Mewakili wilayah gambar.

Kelas Tile mewakili wilayah gambar dalam komponen GroupDocs.Viewer. Ini digunakan untuk mendefinisikan area atau wilayah spesifik dalam dokumen yang perlu dirender atau diproses secara terpisah. Untuk detail, lihat [documentation][].

Contoh penggunaan:

```

 Tile tile = new Tile(100, 100, 200, 200);

 PngViewOptions pngViewOptions = new PngViewOptions();
 pngViewOptions.getCadOptions().setTiles(Arrays.asList(tile));

 try (Viewer viewer = new Viewer("document.docx")) {
     viewer.view(pngViewOptions);
     // Use the viewer object for further operations
 }
 
```


[documentation]: https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/#split-a-drawing-into-tiles
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [Tile(int startPointX, int startPointY, int width, int height)](#Tile-int-int-int-int-) | Menginisialisasi instance baru dari kelas  Tile  . |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getStartPointX()](#getStartPointX--) | Mendapatkan koordinat X dari titik kiri bawah pada gambar tempat tile dimulai. |
| [getStartPointY()](#getStartPointY--) | Mendapatkan koordinat Y dari titik kiri bawah pada gambar tempat tile dimulai. |
| [getWidth()](#getWidth--) | Mendapatkan lebar tile dalam piksel. |
| [getHeight()](#getHeight--) | Mendapatkan tinggi tile dalam piksel. |
| [getEndPointX()](#getEndPointX--) | Mengembalikan koordinat X dari titik kanan atas pada gambar tempat tile berakhir. |
| [getEndPointY()](#getEndPointY--) | Mengembalikan koordinat Y dari titik kanan atas pada gambar tempat tile berakhir. |
### Tile(int startPointX, int startPointY, int width, int height) {#Tile-int-int-int-int-}
```
public Tile(int startPointX, int startPointY, int width, int height)
```


Menginisialisasi instance baru dari kelas  Tile  .

Konstruktor ini membuat objek tile baru dengan titik awal, lebar, dan tinggi yang ditentukan. Untuk detail, lihat [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/#split-a-drawing-into-tiles

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| startPointX | int | Koordinat X dari titik kiri bawah pada gambar tempat tile dimulai. |
| startPointY | int | Koordinat Y dari titik kiri bawah pada gambar tempat tile dimulai. |
| width | int | Lebar tile dalam piksel. |
| height | int | Tinggi tile dalam piksel. |

### getStartPointX() {#getStartPointX--}
```
public final int getStartPointX()
```


Mendapatkan koordinat X dari titik kiri bawah pada gambar tempat tile dimulai.

Untuk detail, lihat [dokumentasi][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/#split-a-drawing-into-tiles

**Returns:**
int - koordinat X dari titik kiri bawah.
### getStartPointY() {#getStartPointY--}
```
public final int getStartPointY()
```


Mendapatkan koordinat Y dari titik kiri bawah pada gambar tempat tile dimulai.

Untuk detail, lihat [dokumentasi][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/#split-a-drawing-into-tiles

**Returns:**
int - koordinat Y dari titik kiri bawah.
### getWidth() {#getWidth--}
```
public final int getWidth()
```


Mendapatkan lebar tile dalam piksel.

Untuk detail, lihat [dokumentasi][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/#split-a-drawing-into-tiles

**Returns:**
int - lebar tile.
### getHeight() {#getHeight--}
```
public final int getHeight()
```


Mendapatkan tinggi tile dalam piksel.

Untuk detail, lihat [dokumentasi][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/#split-a-drawing-into-tiles

**Returns:**
int - tinggi tile.
### getEndPointX() {#getEndPointX--}
```
public final int getEndPointX()
```


Mengembalikan koordinat X dari titik kanan atas pada gambar tempat tile berakhir.

**Returns:**
int - koordinat X dari titik kanan atas.
### getEndPointY() {#getEndPointY--}
```
public final int getEndPointY()
```


Mengembalikan koordinat Y dari titik kanan atas pada gambar tempat tile berakhir.

**Returns:**
int - koordinat Y dari titik kanan tertinggi.
