---
title: "Word"
second_title: "GroupDocs.Viewer för Node.js via Java API-referens"
description: "Representerar en relativt placerad rektangel som innehåller ett enda ord."
type: docs
weight: 26
url: /sv/nodejs-java/com.groupdocs.viewer.results/word/
---
**All Implemented Interfaces:**
com.groupdocs.viewer.results.TextElement, java.io.Serializable
```
public interface Word extends TextElement<String>, Serializable
```

Representerar en relativt placerad rektangel som innehåller ett enda ord.

Word‑gränssnittet representerar ett ord inom en relativt placerad rektangel i GroupDocs.Viewer‑komponenten. Det ärver TextElement‑gränssnittet och tillhandahåller ytterligare metoder för att komma åt och manipulera ordets innehåll.

Exempel på användning:

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
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getCharacters()](#getCharacters--) | Hämtar tecknen som finns i ordet. |
| [setCharacters(List<Character> characters)](#setCharacters-java.util.List-com.groupdocs.viewer.results.Character--) | Sätter tecknen som finns i ordet. |
### getCharacters() {#getCharacters--}
```
public abstract List<Character> getCharacters()
```


Hämtar tecknen som finns i ordet.

**Returns:**
java.util.List<com.groupdocs.viewer.results.Character> - listan med tecken.
### setCharacters(List<Character> characters) {#setCharacters-java.util.List-com.groupdocs.viewer.results.Character--}
```
public abstract void setCharacters(List<Character> characters)
```


Sätter tecknen som finns i ordet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| tecken | java.util.List<com.groupdocs.viewer.results.Character> | listan med tecken att ange. |

