---
title: "Word"
second_title: "GroupDocs.Viewer Java için API Referansı"
description: "Tek bir kelime içeren göreceli konumlandırılmış bir dikdörtgeni temsil eder."
type: docs
weight: 28
url: /tr/java/com.groupdocs.viewer.results/word/
---
**All Implemented Interfaces:**
com.groupdocs.viewer.results.TextElement, java.io.Serializable
```
public interface Word extends TextElement<String>, Serializable
```

Tek bir kelime içeren göreceli konumlandırılmış bir dikdörtgeni temsil eder.


Word arabirimi, GroupDocs.Viewer bileşeninde göreceli konumlandırılmış bir dikdörtgen içinde bir kelimeyi temsil eder.
TextElement arabirimini genişletir ve kelime içeriğine erişmek ve manipüle etmek için ek yöntemler sağlar.


Örnek kullanım:

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

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getCharacters()](#getCharacters--) | Kelime tarafından içerilen karakterleri alır. |
|
|  | [setCharacters(List<Character> characters)](#setCharacters-java.util.List-com.groupdocs.viewer.results.Character--) | Kelime tarafından içerilen karakterleri ayarlar. |
|
### getCharacters() {#getCharacters--}
```
public abstract List<Character> getCharacters()
```


Kelime tarafından içerilen karakterleri alır.


**Returns:**
java.util.List<com.groupdocs.viewer.results.Character> - karakterlerin listesi.

### setCharacters(List<Character> characters) {#setCharacters-java.util.List-com.groupdocs.viewer.results.Character--}
```
public abstract void setCharacters(List<Character> characters)
```


Kelime tarafından içerilen karakterleri ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | characters | java.util.List<com.groupdocs.viewer.results.Character> | ayar yapılacak karakterlerin listesi. |
|

