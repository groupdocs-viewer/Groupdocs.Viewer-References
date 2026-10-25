---
title: "Tile"
second_title: "GroupDocs.Viewer Java için API Referansı"
description: "Çizim bölgesini temsil eder."
type: docs
weight: 33
url: /tr/java/com.groupdocs.viewer.options/tile/
---
**Inheritance:**
java.lang.Object
```
public class Tile
```

Çizim bölgesini temsil eder.


Tile sınıfı, GroupDocs.Viewer bileşeninde bir çizim bölgesini temsil eder.
Belge içinde ayrı ayrı işlenmesi veya işlenmesi gereken belirli bir alanı veya bölgeyi tanımlamak için kullanılır.
Detaylar için, [belgelere](../https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/#split-a-drawing-into-tiles) bakın.


Örnek kullanım:

````

 Tile tile = new Tile(100, 100, 200, 200);

 PngViewOptions pngViewOptions = new PngViewOptions();
 pngViewOptions.getCadOptions().setTiles(Arrays.asList(tile));

 try (Viewer viewer = new Viewer("document.docx")) {
     viewer.view(pngViewOptions);
     // Use the viewer object for further operations
 }
 
````


## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
|  | [Tile(int startPointX, int startPointY, int width, int height)](#Tile-int-int-int-int-) | Yeni bir örnek başlatır |
Tile
sınıf.
|
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getStartPointX()](#getStartPointX--) | Döşemenin başladığı çizimdeki en alt sol noktanın X koordinatını alır. |
|
|  | [getStartPointY()](#getStartPointY--) | Döşemenin başladığı çizimdeki en alt sol noktanın Y koordinatını alır. |
|
|  | [getWidth()](#getWidth--) | Döşemenin piksel cinsinden genişliğini alır. |
|
|  | [getHeight()](#getHeight--) | Döşemenin piksel cinsinden yüksekliğini alır. |
|
|  | [getEndPointX()](#getEndPointX--) | Döşemenin bittiği çizimdeki en üst sağ noktanın X koordinatını döndürür. |
|
|  | [getEndPointY()](#getEndPointY--) | Döşemenin bittiği çizimdeki en üst sağ noktanın Y koordinatını döndürür. |
|
### Tile(int startPointX, int startPointY, int width, int height) {#Tile-int-int-int-int-}
```
public Tile(int startPointX, int startPointY, int width, int height)
```


Yeni bir örnek başlatır
Tile
sınıf.


Bu yapıcı, belirtilen başlangıç noktası, genişlik ve yükseklik ile yeni bir döşeme nesnesi oluşturur.
Detaylar için, [belgelere](../https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/#split-a-drawing-into-tiles) bakın.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | startPointX | int | Döşemenin başladığı çizimdeki en alt sol noktanın X koordinatı. |
|
|  | startPointY | int | Döşemenin başladığı çizimdeki en alt sol noktanın Y koordinatı. |
|
|  | width | int | Döşemenin piksel cinsinden genişliği. |
|
|  | height | int | Döşemenin piksel cinsinden yüksekliği. |
|

### getStartPointX() {#getStartPointX--}
```
public final int getStartPointX()
```


Döşemenin başladığı çizimdeki en alt sol noktanın X koordinatını alır.
Detaylar için, [belgelere](../https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/#split-a-drawing-into-tiles) bakın.


**Returns:**
int - en alt sol noktanın X koordinatı.

### getStartPointY() {#getStartPointY--}
```
public final int getStartPointY()
```


Döşemenin başladığı çizimdeki en alt sol noktanın Y koordinatını alır.
Detaylar için, [belgelere](../https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/#split-a-drawing-into-tiles) bakın.


**Returns:**
int - en alt sol noktanın Y koordinatı.

### getWidth() {#getWidth--}
```
public final int getWidth()
```


Döşemenin piksel cinsinden genişliğini alır.
Detaylar için, [belgelere](../https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/#split-a-drawing-into-tiles) bakın.


**Returns:**
int - döşemenin genişliği.

### getHeight() {#getHeight--}
```
public final int getHeight()
```


Döşemenin piksel cinsinden yüksekliğini alır.
Detaylar için, [belgelere](../https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/#split-a-drawing-into-tiles) bakın.


**Returns:**
int - döşemenin yüksekliği.

### getEndPointX() {#getEndPointX--}
```
public final int getEndPointX()
```


Döşemenin bittiği çizimdeki en üst sağ noktanın X koordinatını döndürür.


**Returns:**
int - en üst sağ noktanın X koordinatı.

### getEndPointY() {#getEndPointY--}
```
public final int getEndPointY()
```


Döşemenin bittiği çizimdeki en üst sağ noktanın Y koordinatını döndürür.


**Returns:**
int - en üst sağ noktanın Y koordinatı.

