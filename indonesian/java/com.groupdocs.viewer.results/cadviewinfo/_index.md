---
title: "CadViewInfo"
second_title: "Referensi API GroupDocs.Viewer for Java"
description: "Mewakili informasi tampilan untuk gambar CAD."
type: docs
weight: 13
url: /id/java/com.groupdocs.viewer.results/cadviewinfo/
---
**All Implemented Interfaces:**
[com.groupdocs.viewer.results.ViewInfo](../../com.groupdocs.viewer.results/viewinfo)
```
public interface CadViewInfo extends ViewInfo
```

Mewakili informasi tampilan untuk gambar CAD.


Antarmuka CadViewInfo mendefinisikan kontrak untuk mengambil informasi tampilan khusus pada gambar CAD
dalam komponen GroupDocs.Viewer. Ini menyediakan metode untuk mengakses lapisan gambar CAD.


Contoh penggunaan:

````

 try (Viewer viewer = new Viewer("document.plt")) {
     CadViewInfo viewInfo = (CadViewInfo) viewer.getViewInfo(ViewInfoOptions.forHtmlView());

     // Use the viewInfo object for further operations
 }
 
````


***Note:** The default implementation of this interface is CadViewInfoImpl.*

## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [getLayers()](#getLayers--) | Mengambil daftar lapisan dalam gambar CAD. |
|
|  | [setLayers(List<Layer> layers)](#setLayers-java.util.List-com.groupdocs.viewer.results.Layer--) | Mengatur daftar lapisan dalam gambar CAD. |
|
|  | [getLayouts()](#getLayouts--) | Mengambil daftar tata letak yang terdapat dalam gambar CAD. |
|
|  | [setLayouts(List<Layout> layouts)](#setLayouts-java.util.List-com.groupdocs.viewer.results.Layout--) | Menetapkan daftar tata letak yang terdapat dalam gambar CAD. |
|
### getLayers() {#getLayers--}
```
public abstract List<Layer> getLayers()
```


Mengambil daftar lapisan dalam gambar CAD.


**Returns:**
java.util.List<com.groupdocs.viewer.results.Layer> - lapisan dalam gambar CAD.

### setLayers(List<Layer> layers) {#setLayers-java.util.List-com.groupdocs.viewer.results.Layer--}
```
public abstract void setLayers(List<Layer> layers)
```


Mengatur daftar lapisan dalam gambar CAD.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | layers | java.util.List<com.groupdocs.viewer.results.Layer> | lapisan yang akan ditetapkan untuk gambar CAD. |
|

### getLayouts() {#getLayouts--}
```
public abstract List<Layout> getLayouts()
```


Mengambil daftar tata letak yang terdapat dalam gambar CAD.


**Returns:**
java.util.List<com.groupdocs.viewer.results.Layout> - tata letak dalam gambar CAD.

### setLayouts(List<Layout> layouts) {#setLayouts-java.util.List-com.groupdocs.viewer.results.Layout--}
```
public abstract void setLayouts(List<Layout> layouts)
```


Menetapkan daftar tata letak yang terdapat dalam gambar CAD.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | layouts | java.util.List<com.groupdocs.viewer.results.Layout> | tata letak yang akan ditetapkan untuk gambar CAD. |
|

