---
title: "Line"
second_title: "GroupDocs.Viewer Java için API Referansı"
description: "Tek bir satır içeren göreceli konumlandırılmış bir dikdörtgeni temsil eder."
type: docs
weight: 18
url: /tr/java/com.groupdocs.viewer.results/line/
---
**All Implemented Interfaces:**
com.groupdocs.viewer.results.TextElement, java.io.Serializable
```
public interface Line extends TextElement<String>, Serializable
```

Tek bir satır içeren göreceli konumlandırılmış bir dikdörtgeni temsil eder.


Line arabirimi, bir dikdörtgen ile temsil edilen bir satıra erişmek ve manipüle etmek için sözleşmeyi tanımlar
GroupDocs.Viewer bileşeninde. Satır metni gibi bilgileri almak için yöntemler sağlar,
konum ve dikdörtgenin boyutu.


Örnek kullanım:

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

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getWords()](#getWords--) | Satırda bulunan kelimeleri alır. |
|
|  | [setWords(List<Word> wordList)](#setWords-java.util.List-com.groupdocs.viewer.results.Word--) | Satırda bulunan kelimeleri ayarlar. |
|
### getWords() {#getWords--}
```
public abstract List<Word> getWords()
```


Satırda bulunan kelimeleri alır.


**Returns:**
java.util.List<com.groupdocs.viewer.results.Word> - satırda bulunan kelimeler.

### setWords(List<Word> wordList) {#setWords-java.util.List-com.groupdocs.viewer.results.Word--}
```
public abstract void setWords(List<Word> wordList)
```


Satırda bulunan kelimeleri ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | wordList | java.util.List<com.groupdocs.viewer.results.Word> | satırda bulunan kelimeler. |
|

