---
title: "Line"
second_title: "GroupDocs.Viewer för Java API-referens"
description: "Representerar en relativt placerad rektangel som innehåller en enskild rad."
type: docs
weight: 18
url: /sv/java/com.groupdocs.viewer.results/line/
---
**All Implemented Interfaces:**
com.groupdocs.viewer.results.TextElement, java.io.Serializable
```
public interface Line extends TextElement<String>, Serializable
```

Representerar en relativt placerad rektangel som innehåller en enskild rad.


Line-gränssnittet definierar kontraktet för att komma åt och manipulera en linje som representeras av en rektangel
i GroupDocs.Viewer-komponenten. Den tillhandahåller metoder för att hämta information såsom radtexten,
position och storlek på rektangeln.


Exempel på användning:

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

## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getWords()](#getWords--) | Hämtar orden som finns i raden. |
|
|  | [setWords(List<Word> wordList)](#setWords-java.util.List-com.groupdocs.viewer.results.Word--) | Ställer in orden som finns i raden. |
|
### getWords() {#getWords--}
```
public abstract List<Word> getWords()
```


Hämtar orden som finns i raden.


**Returns:**
java.util.List<com.groupdocs.viewer.results.Word> - orden som finns i raden.

### setWords(List<Word> wordList) {#setWords-java.util.List-com.groupdocs.viewer.results.Word--}
```
public abstract void setWords(List<Word> wordList)
```


Ställer in orden som finns i raden.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | wordList | java.util.List<com.groupdocs.viewer.results.Word> | orden som finns i raden. |
|

