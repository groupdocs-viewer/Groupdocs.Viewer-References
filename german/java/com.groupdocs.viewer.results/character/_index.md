---
title: "Zeichen"
second_title: "GroupDocs.Viewer für Java API-Referenz"
description: "Stellt ein relativ positioniertes Rechteck dar, das ein einzelnes Zeichen enthält."
type: docs
weight: 14
url: /de/java/com.groupdocs.viewer.results/character/
---
**All Implemented Interfaces:**
com.groupdocs.viewer.results.TextElement, java.io.Serializable
```
public interface Character extends TextElement<Character>, Serializable
```

Stellt ein relativ positioniertes Rechteck dar, das ein einzelnes Zeichen enthält.


Das Zeichen-Interface definiert den Vertrag für den Zugriff auf und die Manipulation eines durch ein Rechteck dargestellten Zeichens
im GroupDocs.Viewer‑Komponente. Es bietet Methoden zum Abrufen von Informationen wie das Zeichen selbst,
Position und Größe des Rechtecks.


Beispielverwendung:

````

 try (Viewer viewer = new Viewer("document.pdf")) {
     PdfViewInfo viewInfo = (PdfViewInfo) viewer.getViewInfo(ViewInfoOptions.forHtmlView());
     List characters = viewInfo.getPages().get(0).getLines().get(0).getWords().get(0).getCharacters();
     Character character = characters.get(0);

     // Use the character object for further operations
 }
 
````


***Note:** The default implementation of this interface is CharacterImpl.*

