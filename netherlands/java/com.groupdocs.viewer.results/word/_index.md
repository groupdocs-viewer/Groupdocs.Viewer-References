---
title: "Word"
second_title: "GroupDocs.Viewer for Java API-referentie"
description: "Stelt een relatief gepositioneerde rechthoek voor die één woord bevat."
type: docs
weight: 28
url: /nl/java/com.groupdocs.viewer.results/word/
---
**All Implemented Interfaces:**
com.groupdocs.viewer.results.TextElement, java.io.Serializable
```
public interface Word extends TextElement<String>, Serializable
```

Stelt een relatief gepositioneerde rechthoek voor die één woord bevat.


De Word-interface vertegenwoordigt een woord binnen een relatief gepositioneerde rechthoek in de GroupDocs.Viewer component.
Het breidt de TextElement-interface uit en biedt extra methoden om de woordinhoud te benaderen en te manipuleren.


Voorbeeldgebruik:

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

## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getCharacters()](#getCharacters--) | Haalt de tekens op die in het woord staan. |
|
|  | [setCharacters(List<Character> characters)](#setCharacters-java.util.List-com.groupdocs.viewer.results.Character--) | Stelt de tekens in die in het woord staan. |
|
### getCharacters() {#getCharacters--}
```
public abstract List<Character> getCharacters()
```


Haalt de tekens op die in het woord staan.


**Returns:**
java.util.List<com.groupdocs.viewer.results.Character> - de lijst met tekens.

### setCharacters(List<Character> characters) {#setCharacters-java.util.List-com.groupdocs.viewer.results.Character--}
```
public abstract void setCharacters(List<Character> characters)
```


Stelt de tekens in die in het woord staan.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | tekens | java.util.List<com.groupdocs.viewer.results.Character> | de lijst met tekens om in te stellen. |
|

