---
title: "Word"
second_title: "GroupDocs.Viewer för Java API-referens"
description: "Representerar en relativt placerad rektangel som innehåller ett enskilt ord."
type: docs
weight: 28
url: /sv/java/com.groupdocs.viewer.results/word/
---
**All Implemented Interfaces:**
com.groupdocs.viewer.results.TextElement, java.io.Serializable
```
public interface Word extends TextElement<String>, Serializable
```

Representerar en relativt placerad rektangel som innehåller ett enskilt ord.


Word-gränssnittet representerar ett ord inom en relativt placerad rektangel i GroupDocs.Viewer-komponenten.
Det utökar TextElement-gränssnittet och tillhandahåller ytterligare metoder för att komma åt och manipulera ordets innehåll.


Exempel på användning:

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

## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getCharacters()](#getCharacters--) | Hämtar tecknen som ordet innehåller. |
|
|  | [setCharacters(List<Character> characters)](#setCharacters-java.util.List-com.groupdocs.viewer.results.Character--) | Ställer in tecknen som ordet innehåller. |
|
### getCharacters() {#getCharacters--}
```
public abstract List<Character> getCharacters()
```


Hämtar tecknen som ordet innehåller.


**Returns:**
java.util.List<com.groupdocs.viewer.results.Character> - listan med tecken.

### setCharacters(List<Character> characters) {#setCharacters-java.util.List-com.groupdocs.viewer.results.Character--}
```
public abstract void setCharacters(List<Character> characters)
```


Ställer in tecknen som ordet innehåller.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | tecken | java.util.List<com.groupdocs.viewer.results.Character> | listan med tecken att sätta. |
|

