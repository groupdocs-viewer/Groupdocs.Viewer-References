---
title: "Word"
second_title: "Referensi API GroupDocs.Viewer for Java"
description: "Mewakili persegi panjang yang diposisikan relatif yang berisi satu kata."
type: docs
weight: 28
url: /id/java/com.groupdocs.viewer.results/word/
---
**All Implemented Interfaces:**
com.groupdocs.viewer.results.TextElement, java.io.Serializable
```
public interface Word extends TextElement<String>, Serializable
```

Mewakili persegi panjang yang diposisikan relatif yang berisi satu kata.


Antarmuka Word mewakili sebuah kata dalam persegi panjang yang diposisikan relatif di komponen GroupDocs.Viewer.
Ini memperluas antarmuka TextElement dan menyediakan metode tambahan untuk mengakses dan memanipulasi konten kata.


Contoh penggunaan:

````

 try (Viewer viewer = new Viewer("document.pdf")) {
     PdfViewInfo viewInfo = (PdfViewInfo) viewer.getViewInfo(ViewInfoOptions.forHtmlView());
     List words = viewInfo.getPages().get(0).getLines().get(0).getWords();
     for (Word word : words) {
         // Use the word object for further operations
     }
 }
 
````


***Note:** The default implementation of this interface is WordImpl.*

## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [getCharacters()](#getCharacters--) | Mengambil karakter yang terkandung dalam kata. |
|
|  | [setCharacters(List<Character> characters)](#setCharacters-java.util.List-com.groupdocs.viewer.results.Character--) | Menetapkan karakter yang terkandung dalam kata. |
|
### getCharacters() {#getCharacters--}
```
public abstract List<Character> getCharacters()
```


Mengambil karakter yang terkandung dalam kata.


**Returns:**
java.util.List<com.groupdocs.viewer.results.Character> - daftar karakter.

### setCharacters(List<Character> characters) {#setCharacters-java.util.List-com.groupdocs.viewer.results.Character--}
```
public abstract void setCharacters(List<Character> characters)
```


Menetapkan karakter yang terkandung dalam kata.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | karakter | java.util.List<com.groupdocs.viewer.results.Character> | daftar karakter yang akan ditetapkan. |
|

