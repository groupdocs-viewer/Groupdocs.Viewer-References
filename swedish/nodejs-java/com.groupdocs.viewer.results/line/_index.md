---
title: "Linje"
second_title: "GroupDocs.Viewer för Node.js via Java API-referens"
description: "Representerar en relativt placerad rektangel som innehåller en enda rad."
type: docs
weight: 18
url: /sv/nodejs-java/com.groupdocs.viewer.results/line/
---
**All Implemented Interfaces:**
com.groupdocs.viewer.results.TextElement, java.io.Serializable
```
public interface Line extends TextElement<String>, Serializable
```

Representerar en relativt placerad rektangel som innehåller en enda rad.

Line-gränssnittet definierar kontraktet för åtkomst och manipulation av en linje som representeras av en rektangel i GroupDocs.Viewer-komponenten. Det tillhandahåller metoder för att hämta information såsom linjetext, position och storlek på rektangeln.

Exempel på användning:

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
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getWords()](#getWords--) | Hämtar orden som finns i linjen. |
| [setWords(List<Word> wordList)](#setWords-java.util.List-com.groupdocs.viewer.results.Word--) | Ställer in orden som finns i linjen. |
### getWords() {#getWords--}
```
public abstract List<Word> getWords()
```


Hämtar orden som finns i linjen.

**Returns:**
java.util.List<com.groupdocs.viewer.results.Word> - orden som finns i linjen.
### setWords(List<Word> wordList) {#setWords-java.util.List-com.groupdocs.viewer.results.Word--}
```
public abstract void setWords(List<Word> wordList)
```


Ställer in orden som finns i linjen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| wordList | java.util.List<com.groupdocs.viewer.results.Word> | orden som finns i linjen. |

