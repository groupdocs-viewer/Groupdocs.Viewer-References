---
title: "Character"
second_title: "GroupDocs.Viewer für Node.js über Java API-Referenz"
description: "Stellt ein relativ positioniertes Rechteck dar, das ein einzelnes Zeichen enthält."
type: docs
weight: 14
url: /de/nodejs-java/com.groupdocs.viewer.results/character/
---
**All Implemented Interfaces:**
com.groupdocs.viewer.results.TextElement, java.io.Serializable
```
public interface Character extends TextElement<Character>, Serializable
```

Stellt ein relativ positioniertes Rechteck dar, das ein einzelnes Zeichen enthält.

Das Character-Interface definiert den Vertrag zum Zugreifen und Manipulieren eines Zeichens, das durch ein Rechteck in der GroupDocs.Viewer-Komponente dargestellt wird. Es stellt Methoden bereit, um Informationen wie das Zeichen selbst, die Position und die Größe des Rechtecks abzurufen.

Beispielhafte Verwendung:

```

 try (Viewer viewer = new Viewer("document.pdf")) {
     PdfViewInfo viewInfo = (PdfViewInfo) viewer.getViewInfo(ViewInfoOptions.forHtmlView());
     List characters = viewInfo.getPages().get(0).getLines().get(0).getWords().get(0).getCharacters();
     Character character = characters.get(0);

     // Use the character object for further operations
 }
 
```

***Note:** The default implementation of this interface is CharacterImpl.*
