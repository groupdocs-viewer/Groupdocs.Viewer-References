---
title: "Word"
second_title: "GroupDocs.Viewer için Node.js üzerinden Java API Referansı"
description: "Tek bir kelime içeren göreceli konumlandırılmış bir dikdörtgeni temsil eder."
type: docs
weight: 26
url: /tr/nodejs-java/com.groupdocs.viewer.results/word/
---
**All Implemented Interfaces:**
com.groupdocs.viewer.results.TextElement, java.io.Serializable
```
public interface Word extends TextElement<String>, Serializable
```

Tek bir kelime içeren göreceli konumlandırılmış bir dikdörtgeni temsil eder.

Word arayüzü, GroupDocs.Viewer bileşenindeki göreceli konumlandırılmış bir dikdörtgen içinde bir kelimeyi temsil eder. TextElement arayüzünü genişletir ve kelime içeriğine erişim ve manipülasyon için ek yöntemler sağlar.

Örnek kullanım:

```

 try (Viewer viewer = new Viewer("document.pdf")) {
     PdfViewInfo viewInfo = (PdfViewInfo) viewer.getViewInfo(ViewInfoOptions.forHtmlView());
     List words = viewInfo.getPages().get(0).getLines().get(0).getWords();
     for (Word word : words) {
         // Use the word object for further operations
     }
 }
 
```

***Note:** The default implementation of this interface is WordImpl.*
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getCharacters()](#getCharacters--) | Kelimenin içerdiği karakterleri alır. |
| [setCharacters(List<Character> characters)](#setCharacters-java.util.List-com.groupdocs.viewer.results.Character--) | Kelimenin içerdiği karakterleri ayarlar. |
### getCharacters() {#getCharacters--}
```
public abstract List<Character> getCharacters()
```


Kelimenin içerdiği karakterleri alır.

**Returns:**
java.util.List<com.groupdocs.viewer.results.Character> - karakterlerin listesi.
### setCharacters(List<Character> characters) {#setCharacters-java.util.List-com.groupdocs.viewer.results.Character--}
```
public abstract void setCharacters(List<Character> characters)
```


Kelimenin içerdiği karakterleri ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| karakterler | java.util.List<com.groupdocs.viewer.results.Character> | ayar için karakterlerin listesi. |

