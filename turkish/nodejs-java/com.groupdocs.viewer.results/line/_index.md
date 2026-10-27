---
title: "Satır"
second_title: "GroupDocs.Viewer için Node.js üzerinden Java API Referansı"
description: "Tek bir satır içeren göreceli konumlandırılmış bir dikdörtgeni temsil eder."
type: docs
weight: 18
url: /tr/nodejs-java/com.groupdocs.viewer.results/line/
---
**All Implemented Interfaces:**
com.groupdocs.viewer.results.TextElement, java.io.Serializable
```
public interface Line extends TextElement<String>, Serializable
```

Tek bir satır içeren göreceli konumlandırılmış bir dikdörtgeni temsil eder.

Line arayüzü, GroupDocs.Viewer bileşeninde bir dikdörtgen tarafından temsil edilen satıra erişim ve manipülasyon için sözleşmeyi tanımlar. Satır metni, konumu ve dikdörtgenin boyutu gibi bilgileri almak için yöntemler sağlar.

Örnek kullanım:

```

 try (Viewer viewer = new Viewer("document.pdf")) {
     PdfViewInfo viewInfo = (PdfViewInfo) viewer.getViewInfo(ViewInfoOptions.forHtmlView());
     List lines = viewInfo.getPages().get(0).getLines();
     for (Line line : lines) {
         // Use the line object for further operations
     }
 }
 
```

***Note:** The default implementation of this interface is LineImpl.*
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getWords()](#getWords--) | Satırda bulunan kelimeleri alır. |
| [setWords(List<Word> wordList)](#setWords-java.util.List-com.groupdocs.viewer.results.Word--) | Satırda bulunan kelimeleri ayarlar. |
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
| wordList | java.util.List<com.groupdocs.viewer.results.Word> | satırda bulunan kelimeler. |

