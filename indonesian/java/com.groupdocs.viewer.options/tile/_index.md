---
title: "Tile"
second_title: "Referensi API GroupDocs.Viewer for Java"
description: "Mewakili wilayah gambar."
type: docs
weight: 33
url: /id/java/com.groupdocs.viewer.options/tile/
---
**Inheritance:**
java.lang.Object
```
public class Tile
```

Mewakili wilayah gambar.


Kelas Tile mewakili wilayah gambar dalam komponen GroupDocs.Viewer.
Ini digunakan untuk mendefinisikan area atau wilayah spesifik dalam dokumen yang perlu dirender atau diproses secara terpisah.
Untuk detail, lihat [dokumentasi](../https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/#split-a-drawing-into-tiles).


Contoh penggunaan:

````

 Tile tile = new Tile(100, 100, 200, 200);

 PngViewOptions pngViewOptions = new PngViewOptions();
 pngViewOptions.getCadOptions().setTiles(Arrays.asList(tile));

 try (Viewer viewer = new Viewer("document.docx")) {
     viewer.view(pngViewOptions);
     // Use the viewer object for further operations
 }
 
````


## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
|  | [Tile(int startPointX, int startPointY, int width, int height)](#Tile-int-int-int-int-) | Menginisialisasi instance baru dari |
Tile
kelas.
|
## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [getStartPointX()](#getStartPointX--) | Mendapatkan koordinat X dari titik kiri paling bawah pada gambar tempat tile dimulai. |
|
|  | [getStartPointY()](#getStartPointY--) | Mendapatkan koordinat Y dari titik kiri terendah pada gambar tempat ubin dimulai. |
|
|  | [getWidth()](#getWidth--) | Mendapatkan lebar ubin dalam piksel. |
|
|  | [getHeight()](#getHeight--) | Mendapatkan tinggi ubin dalam piksel. |
|
|  | [getEndPointX()](#getEndPointX--) | Mengembalikan koordinat X dari titik kanan paling atas pada gambar tempat ubin berakhir. |
|
|  | [getEndPointY()](#getEndPointY--) | Mengembalikan koordinat Y dari titik kanan paling atas pada gambar tempat ubin berakhir. |
|
### Tile(int startPointX, int startPointY, int width, int height) {#Tile-int-int-int-int-}
```
public Tile(int startPointX, int startPointY, int width, int height)
```


Menginisialisasi instance baru dari
Tile
kelas.


Konstruktor ini membuat objek ubin baru dengan titik awal, lebar, dan tinggi yang ditentukan.
Untuk detail, lihat [dokumentasi](../https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/#split-a-drawing-into-tiles).


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | startPointX | int | Koordinat X dari titik kiri terendah pada gambar tempat ubin dimulai. |
|
|  | startPointY | int | Koordinat Y dari titik kiri terendah pada gambar tempat ubin dimulai. |
|
|  | width | int | Lebar ubin dalam piksel. |
|
|  | tinggi | int | Tinggi ubin dalam piksel. |
|

### getStartPointX() {#getStartPointX--}
```
public final int getStartPointX()
```


Mendapatkan koordinat X dari titik kiri paling bawah pada gambar tempat tile dimulai.
Untuk detail, lihat [dokumentasi](../https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/#split-a-drawing-into-tiles).


**Returns:**
int - koordinat X dari titik kiri terendah.

### getStartPointY() {#getStartPointY--}
```
public final int getStartPointY()
```


Mendapatkan koordinat Y dari titik kiri terendah pada gambar tempat ubin dimulai.
Untuk detail, lihat [dokumentasi](../https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/#split-a-drawing-into-tiles).


**Returns:**
int - koordinat Y dari titik kiri terendah.

### getWidth() {#getWidth--}
```
public final int getWidth()
```


Mendapatkan lebar ubin dalam piksel.
Untuk detail, lihat [dokumentasi](../https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/#split-a-drawing-into-tiles).


**Returns:**
int - lebar ubin.

### getHeight() {#getHeight--}
```
public final int getHeight()
```


Mendapatkan tinggi ubin dalam piksel.
Untuk detail, lihat [dokumentasi](../https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/#split-a-drawing-into-tiles).


**Returns:**
int - tinggi ubin.

### getEndPointX() {#getEndPointX--}
```
public final int getEndPointX()
```


Mengembalikan koordinat X dari titik kanan paling atas pada gambar tempat ubin berakhir.


**Returns:**
int - koordinat X dari titik kanan tertinggi.

### getEndPointY() {#getEndPointY--}
```
public final int getEndPointY()
```


Mengembalikan koordinat Y dari titik kanan paling atas pada gambar tempat ubin berakhir.


**Returns:**
int - koordinat Y dari titik kanan tertinggi.

