---
title: "LotusNotesViewInfo"
second_title: "Referensi API GroupDocs.Viewer for Java"
description: "Mewakili informasi tampilan untuk penyimpanan basis data Lotus Notes."
type: docs
weight: 19
url: /id/java/com.groupdocs.viewer.results/lotusnotesviewinfo/
---
**All Implemented Interfaces:**
[com.groupdocs.viewer.results.ViewInfo](../../com.groupdocs.viewer.results/viewinfo)
```
public interface LotusNotesViewInfo extends ViewInfo
```

Mewakili informasi tampilan untuk penyimpanan basis data Lotus Notes.


Antarmuka LotusNotesViewInfo mendefinisikan kontrak untuk mengakses dan memanipulasi informasi tampilan
untuk penyimpanan basis data Lotus Notes dalam komponen GroupDocs.Viewer. Ini menyediakan metode untuk mengambil informasi
seperti jumlah catatan, dan properti lainnya.


Contoh penggunaan:

````

 try (Viewer viewer = new Viewer("document.nsf")) {
     final LotusNotesViewInfo viewInfo = (LotusNotesViewInfo) viewer.getViewInfo(ViewInfoOptions.forHtmlView());
     // Use the viewInfo object for further operations
 }
 
````


***Note:** The default implementation of this interface is LotusNotesViewInfoImpl.*

## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [getNotesCount()](#getNotesCount--) | Mengambil jumlah catatan dalam penyimpanan. |
|
|  | [setNotesCount(int count)](#setNotesCount-int-) | Menetapkan jumlah catatan dalam penyimpanan. |
|
### getNotesCount() {#getNotesCount--}
```
public abstract int getNotesCount()
```


Mengambil jumlah catatan dalam penyimpanan.


**Returns:**
int - jumlah catatan dalam penyimpanan.

### setNotesCount(int count) {#setNotesCount-int-}
```
public abstract void setNotesCount(int count)
```


Menetapkan jumlah catatan dalam penyimpanan.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | jumlah | int | jumlah catatan dalam penyimpanan. |
|

