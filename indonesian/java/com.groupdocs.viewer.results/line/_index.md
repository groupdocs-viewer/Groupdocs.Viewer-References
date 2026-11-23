---
title: "Line"
second_title: "Referensi API GroupDocs.Viewer for Java"
description: "Mewakili persegi panjang yang diposisikan relatif yang berisi satu baris."
type: docs
weight: 18
url: /id/java/com.groupdocs.viewer.results/line/
---
**All Implemented Interfaces:**
com.groupdocs.viewer.results.TextElement, java.io.Serializable
```
public interface Line extends TextElement<String>, Serializable
```

Mewakili persegi panjang yang diposisikan relatif yang berisi satu baris.


Antarmuka Line mendefinisikan kontrak untuk mengakses dan memanipulasi sebuah garis yang direpresentasikan oleh persegi panjang
di komponen GroupDocs.Viewer. Ini menyediakan metode untuk mengambil informasi seperti teks baris,
posisi, dan ukuran persegi panjang.


Contoh penggunaan:

````

 try (Viewer viewer = new Viewer("document.pdf")) {
     PdfViewInfo viewInfo = (PdfViewInfo) viewer.getViewInfo(ViewInfoOptions.forHtmlView());
     List lines = viewInfo.getPages().get(0).getLines();
     for (Line line : lines) {
         // Use the line object for further operations
     }
 }
 
````


***Note:** The default implementation of this interface is LineImpl.*

## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [getWords()](#getWords--) | Mengambil kata-kata yang terdapat dalam baris. |
|
|  | [setWords(List<Word> wordList)](#setWords-java.util.List-com.groupdocs.viewer.results.Word--) | Menetapkan kata-kata yang terdapat dalam baris. |
|
### getWords() {#getWords--}
```
public abstract List<Word> getWords()
```


Mengambil kata-kata yang terdapat dalam baris.


**Returns:**
java.util.List<com.groupdocs.viewer.results.Word> - kata-kata yang terdapat dalam baris.

### setWords(List<Word> wordList) {#setWords-java.util.List-com.groupdocs.viewer.results.Word--}
```
public abstract void setWords(List<Word> wordList)
```


Menetapkan kata-kata yang terdapat dalam baris.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | wordList | java.util.List<com.groupdocs.viewer.results.Word> | kata-kata yang terdapat dalam baris. |
|

