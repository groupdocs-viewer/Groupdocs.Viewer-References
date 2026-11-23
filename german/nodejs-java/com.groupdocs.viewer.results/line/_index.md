---
title: "Linie"
second_title: "GroupDocs.Viewer für Node.js über Java API-Referenz"
description: "Stellt ein relativ positioniertes Rechteck dar, das eine einzelne Zeile enthält."
type: docs
weight: 18
url: /de/nodejs-java/com.groupdocs.viewer.results/line/
---
**All Implemented Interfaces:**
com.groupdocs.viewer.results.TextElement, java.io.Serializable
```
public interface Line extends TextElement<String>, Serializable
```

Stellt ein relativ positioniertes Rechteck dar, das eine einzelne Zeile enthält.

Das Line-Interface definiert den Vertrag für den Zugriff auf und die Manipulation einer durch ein Rechteck dargestellten Linie in der GroupDocs.Viewer‑Komponente. Es bietet Methoden zum Abrufen von Informationen wie dem Zeilentext, der Position und der Größe des Rechtecks.

Beispielhafte Verwendung:

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

| Methode | Beschreibung |
| --- | --- |
| [getWords()](#getWords--) | Ruft die in der Zeile enthaltenen Wörter ab. |
| [setWords(List<Word> wordList)](#setWords-java.util.List-com.groupdocs.viewer.results.Word--) | Setzt die in der Zeile enthaltenen Wörter. |
### getWords() {#getWords--}
```
public abstract List<Word> getWords()
```


Ruft die in der Zeile enthaltenen Wörter ab.

**Returns:**
java.util.List<com.groupdocs.viewer.results.Word> - die in der Zeile enthaltenen Wörter.
### setWords(List<Word> wordList) {#setWords-java.util.List-com.groupdocs.viewer.results.Word--}
```
public abstract void setWords(List<Word> wordList)
```


Setzt die in der Zeile enthaltenen Wörter.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| wordList | java.util.List<com.groupdocs.viewer.results.Word> | die in der Zeile enthaltenen Wörter. |

