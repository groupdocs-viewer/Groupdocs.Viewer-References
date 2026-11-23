---
title: "Word"
second_title: "GroupDocs.Viewer für Node.js über Java API-Referenz"
description: "Stellt ein relativ positioniertes Rechteck dar, das ein einzelnes Wort enthält."
type: docs
weight: 26
url: /de/nodejs-java/com.groupdocs.viewer.results/word/
---
**All Implemented Interfaces:**
com.groupdocs.viewer.results.TextElement, java.io.Serializable
```
public interface Word extends TextElement<String>, Serializable
```

Stellt ein relativ positioniertes Rechteck dar, das ein einzelnes Wort enthält.

Das Word-Interface repräsentiert ein Wort innerhalb eines relativ positionierten Rechtecks in der GroupDocs.Viewer-Komponente. Es erweitert das TextElement-Interface und bietet zusätzliche Methoden zum Zugriff auf und zur Manipulation des Wortinhalts.

Beispielhafte Verwendung:

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

| Methode | Beschreibung |
| --- | --- |
| [getCharacters()](#getCharacters--) | Ruft die im Wort enthaltenen Zeichen ab. |
| [setCharacters(List<Character> characters)](#setCharacters-java.util.List-com.groupdocs.viewer.results.Character--) | Setzt die im Wort enthaltenen Zeichen ab. |
### getCharacters() {#getCharacters--}
```
public abstract List<Character> getCharacters()
```


Ruft die im Wort enthaltenen Zeichen ab.

**Returns:**
java.util.List<com.groupdocs.viewer.results.Character> - die Liste der Zeichen.
### setCharacters(List<Character> characters) {#setCharacters-java.util.List-com.groupdocs.viewer.results.Character--}
```
public abstract void setCharacters(List<Character> characters)
```


Setzt die im Wort enthaltenen Zeichen ab.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Zeichen | java.util.List<com.groupdocs.viewer.results.Character> | die Liste der zu setzenden Zeichen. |

