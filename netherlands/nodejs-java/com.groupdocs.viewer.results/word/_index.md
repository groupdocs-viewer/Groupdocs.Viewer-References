---
title: "Word"
second_title: "GroupDocs.Viewer voor Node.js via Java API-referentie"
description: "Stelt een relatief gepositioneerde rechthoek voor die één woord bevat."
type: docs
weight: 26
url: /nl/nodejs-java/com.groupdocs.viewer.results/word/
---
**All Implemented Interfaces:**
com.groupdocs.viewer.results.TextElement, java.io.Serializable
```
public interface Word extends TextElement<String>, Serializable
```

Stelt een relatief gepositioneerde rechthoek voor die één woord bevat.

De Word-interface vertegenwoordigt een woord binnen een relatief gepositioneerde rechthoek in de GroupDocs.Viewer-component. Het breidt de TextElement-interface uit en biedt extra methoden om de inhoud van het woord te benaderen en te manipuleren.

Voorbeeldgebruik:

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
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getCharacters()](#getCharacters--) | Haal de tekens op die in het woord staan. |
| [setCharacters(List<Character> characters)](#setCharacters-java.util.List-com.groupdocs.viewer.results.Character--) | Stel de tekens in die bij het woord horen. |
### getCharacters() {#getCharacters--}
```
public abstract List<Character> getCharacters()
```


Haal de tekens op die in het woord staan.

**Returns:**
java.util.List<com.groupdocs.viewer.results.Character> - de lijst met tekens.
### setCharacters(List<Character> characters) {#setCharacters-java.util.List-com.groupdocs.viewer.results.Character--}
```
public abstract void setCharacters(List<Character> characters)
```


Stel de tekens in die bij het woord horen.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| tekens | java.util.List<com.groupdocs.viewer.results.Character> | de lijst met tekens om in te stellen. |

