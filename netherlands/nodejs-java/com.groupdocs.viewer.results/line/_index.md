---
title: "Lijn"
second_title: "GroupDocs.Viewer voor Node.js via Java API-referentie"
description: "Stelt een relatief gepositioneerde rechthoek voor die één regel bevat."
type: docs
weight: 18
url: /nl/nodejs-java/com.groupdocs.viewer.results/line/
---
**All Implemented Interfaces:**
com.groupdocs.viewer.results.TextElement, java.io.Serializable
```
public interface Line extends TextElement<String>, Serializable
```

Stelt een relatief gepositioneerde rechthoek voor die één regel bevat.

De Line-interface definieert het contract voor het benaderen en manipuleren van een lijn die wordt weergegeven door een rechthoek in de GroupDocs.Viewer-component. Het biedt methoden om informatie op te halen, zoals de lijntekst, positie en grootte van de rechthoek.

Voorbeeldgebruik:

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
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getWords()](#getWords--) | Haalt de woorden op die in de lijn staan. |
| [setWords(List<Word> wordList)](#setWords-java.util.List-com.groupdocs.viewer.results.Word--) | Stelt de woorden in die in de lijn staan. |
### getWords() {#getWords--}
```
public abstract List<Word> getWords()
```


Haalt de woorden op die in de lijn staan.

**Returns:**
java.util.List<com.groupdocs.viewer.results.Word> - de woorden die in de lijn staan.
### setWords(List<Word> wordList) {#setWords-java.util.List-com.groupdocs.viewer.results.Word--}
```
public abstract void setWords(List<Word> wordList)
```


Stelt de woorden in die in de lijn staan.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| wordList | java.util.List<com.groupdocs.viewer.results.Word> | de woorden die in de lijn staan. |

